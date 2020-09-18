---
layout: single 
title: "Some genetic drift graphs with Mathematica" 
category: story
permalink: /weblog/topics/teaching/mathematica/genetic-drift-simulation-2008.html
tags: [teaching, simulations, Mathematica, genetic drift] 
comments: false 
author: John Hawks 
---

The first thing to come up in my lectures is genetic drift. Pretty much everyone who lectures about drift needs a figure showing the results of simple Monte Carlo simulations of sampling drift in a finite population. You start a population with two alleles, sample it randomly in each generation until one or the other alleles disappears. I tend to start with a "population size" of 1000 gene copies, and an initial allele frequency of 50%. 

We can do this kind of simulation in Mathematica pretty easily. We'll work with three variables: 

<ul>
<li><tt>popSize</tt>, which we'll set equal to 1000;</li>
<li><tt>a</tt>, the number of gene copies with one of the two alleles, initially equal to 500; </li>
<li><tt>frequencyList</tt>, which will hold the value of <tt>a</tt> for each generation. Initially, <tt>frequencyList</tt> holds the first value of <tt>a</tt>, 500.</li>
</ul>

Now, we're ready to code the simulation. We set the three variables, and then set up a <tt>While[]</tt> loop that samples a random binomial deviate in each generation, based on the previous generation's allele frequency (<tt>a/popSize</tt>):

<div class="code">
a = N[500];
popSize = 1000;
frequencyList = {a};
While[a < popSize && a > 0, 
   a = N[RandomInteger[BinomialDistribution[popSize, a/popSize]]];
   AppendTo[frequencyList, a]]
</div>
 
The last line appends the value <tt>a</tt> to the list. Nesting <tt>BinomialDistribution[]</tt> inside <tt>RandomInteger[]</tt> gives us a binomial deviate, based on <tt>popSize</tt> trials and frequency <tt>a/popSize</tt>. The loop executes until <tt>a</tt> reaches either zero or 1000, at which point the simulation stops. 
 
 OK, that gives us a list, <tt>frequencyList</tt>, which contains the number of gene copies with one of the two alleles over time. Now, we want to plot that list. We can try: 
 
<div class="code">
ListPlot[
   frequencyList,
   PlotJoined -> True]
</div>
 
...which gives us:
 
<div class="middle-picture">
<img src="/graphics/drift-monte-carlo-first-figure-2008.png" width="360" height="214" alt="Monte Carlo simulation of genetic drift" /> 
</div>

That's servicable, but a bit simple. And it's confusing where the axis cuts across. It would be better to have the plot bounded at 0 and 1000, the min and max possible. Also, we need a better font than Times. 

Let's try:

<div class="code">
ListPlot[
   {frequencyList},
   PlotJoined -> True,
   Frame -> True,
   AxesOrigin -> {0, 0},
   PlotStyle -> Thick,
   FrameLabel -> {"Time (generations)", Frequency},
   TextStyle -> {FontFamily -> "Myriad Pro", FontSize -> 12},
   Filling -> 500]
</div>


<div class="middle-picture">
<img src="/graphics/drift-monte-carlo-simulation-one-population-2008.png" width="360" height="230" alt="Monte Carlo simulation of genetic drift" /> 
</div>

That's a bit more like it. The <tt>Filling -> 500</tt> gives us shading everywhere between our frequency line and the 500 mark, a nice cue reminding us where the simulation started. 

Now, we can add a second run in the same plot:

<div class="middle-picture">
<img src="/graphics/drift-monte-carlo-simulation-two-populations-2008.png" width="360" height="230" alt="Monte Carlo simulation of genetic drift, two populations" /> 
</div>

Oh, well that shifted the <i>x</i>-axis. No harm, though. And we continue...

<div class="middle-picture">
<img src="/graphics/drift-monte-carlo-simulation-four-populations-2008.png" width="360" height="230" alt="Monte Carlo simulation of genetic drift, two populations" /> 
</div>

Not a bad representation of the process, with fixation times ranging from very short to quite long, and one going to fixation at zero. The different color shading tends to confuse the picture a bit, and doing it in a larger size for the projector will take some tweaks, but so far it's much more attractive than the Excel version. 

We could run a few more simulations to substitute, just in case one made the overall picture more clear (for example, by moving the lines apart in the early phase). But here we have the benefit of honesty --- these are the first four sims I ran.

UPDATE (2009-09-13): I'm revisiting this post as I work on a Mathematica Demonstration of genetic drift. It's much simpler to implement the central drift algorithm with a <tt>NestList</tt> or a <tt>NestWhileList</tt>. For example: 

<div class="code">
NestList[RandomInteger[BinomialDistribution[1000, #/1000]] &, 500, 4000]
</div>

gives you the trajectory over 4000 generations. This: 

<div class="code">
NestWhileList[
 RandomInteger[
   BinomialDistribution[1000, #/1000]] &, 500, # < 1000 && # > 0 &]
</div>

replicates the output above. 

