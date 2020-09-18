---
layout: single 
title: "Genetic drift eliminated rare mtDNA haplotypes from Iceland" 
category: story
permalink: /weblog/reviews/genetics/mtdna_migrations/iceland-genetic-drift-mtdna-ancient-helgason-2009.html
tags: [genetic drift, mtDNA, Iceland, founder effect] 
comments: false 
author: John Hawks 
---

How powerful has genetic drift been in recent human evolution? That's the question <a href="http://johnhawks.net/weblog/reviews/genetics/disease/mybpc3-cardiomyopathy-dhandapany-2009-india.html">I raised the other day</a> with reference to the claim that a heart disease risk-inducing allele had become common by drift in India during the last 30,000 years. 

Another paper released earlier this week in <i>PLoS Genetics</i> claims that mtDNA haplotypes have been recently lost from the Icelandic population by strong genetic drift. The evidence for such changes in haplotypes comes from sequencing the mtDNA of thousand-year-old skeletons unearthed in Iceland during the last 150 years. These ancient remains have haplotypes that are found elsewhere in Europe today, but not in Iceland. The conclusion is that the modern-day descendants of these early Iceland settlers have experienced genetic drift within the last 1000 years, relieving them of of a load of rare mtDNA haplotypes. 


Could genetic drift have accomplished this loss of haplotypes? Although the paper does not present any analysis of this question, a quick consideration of some theory will show that genetic drift could easily have caused the observed results. It also shows a contrast between this case and others where genetic drift has been described as "strong". Even in this case, on an island with a limited human population, genetic drift is only "strong" in the sense of eliminating alleles that are already quite rare in the population.
<!--break-->
Today, Iceland is a large population of more than 300,000 individuals. As in many countries, the current size is a result of twentieth-century population growth. From <a href="http://en.wikipedia.org/wiki/Iceland#History">Wikipedia</a>: 

<blockquote>The population of the island is believed to have varied from 40,000 to 60,000 in the period from initial settlement until the mid-19th century. During that time, cold winters, ashfall from volcanic eruptions, and bubonic plagues adversely affected the population several times. The first census was carried out in 1703 and revealed that the population was then 50,358. After the destructive volcanic eruptions of the Laki volcano during 17831784 the population reached a low of about 40,000. Improving living conditions have triggered a rapid increase in population since the mid-19th century - from about 60,000 in 1850 to 320,000 in 2008.</blockquote>

Forty thousand is a large population, in evolutionary terms. But not all these 40,000 people would have counted toward the variance in reproduction of gene lineages (See my discussion of the Wright-Fisher model). If we took a census of the medieval Iceland population, we would find that a large fraction of individuals, maybe half, were children. A rather small fraction would be postreproductive adults. So at most half the population, and probably less, were of reproductive age at any given time. At a first approximation, this population of 40,000 individuals would reproduce like a Wright-Fisher population of less than 20,000. Around half that number will be females -- although probably a bit more than half, since reproductive variance is usually higher among men. So less than 10,000 mating females per generation. Other factors, such as within-family fitness correlations, may limit the effective number even further. I'll assume a value of 5000 effective women, which is certainly an underestimate for the last 300 years, but may not be too much of an underestimate for earlier times.  

We should keep in the back of our minds that the population did not grow instantaneously to this value -- it would have taken a couple hundred years to reach its ultimate medieval size. So genetic drift might have been substantially stronger when these skeletons were being buried than it would have been 300 or 400 years later. 

Helgason et al. (2009) applied an unusual test to demonstrate the genetic difference between early and current Icelanders. They don't consider the <i>frequencies</i> of haplotypes. Nor do they use a measure that would ultimately be influenced by frequencies, like <i>F</i><sub>ST</sub>. Instead, they consider the number of shared haplotypes between the two samples as a measure of similarity. 

The statistical question is whether the modern and ancient samples share significantly fewer haplotypes than expected if the ancient and modern samples had been randomly drawn from a single population. The authors tested this hypothesis with a randomization test: they repeatedly drew random samples of the same sizes as the ancient and modern samples, from a distribution including both samples. It's a clever technique. 

It doesn't yield an easy answer to the question of <i>how strong</i> genetic drift needs to be to explain the data. But we can address this question by considering the data and nature of the comparison. 

Here, we're talking about the <I>presence or absence</i> of haplotypes that each have a very low frequency. For example, the modern Scandinavian sample in the paper includes 337 distinct haplotypes. The modern Icelandic sample, with a slightly larger same sample size (947 versus 898 individuals), has many fewer haplotypes -- only 172. That's a substantial deficit in the Icelandic sample. 

Now, let's consider the ancient sample, with 73 individuals and 58 haplotypes. Obviously, nearly all the haplotypes were present in only a single sampled individual. This implies that many haplotypes existed in that population that were not sampled in these 73 individuals. It also implies that the average frequency of a unique mtDNA haplotype in that population was less than 1.4 percent (less, in other words, than 1/73). 

We don't know that these alleles were lost in Iceland; what we know is that they weren't sampled today. So a real answer to this question would include some considerations of sampling theory. 

We can do a quick calculation to figure out the chances that an allele of 1.5 percent would be eliminated by drift in less than 1000 years (around 40 generations). Here's a small piece of Mathematica code that begins with an allele at 0.015 frequency, a population of 5000 effective individuals, runs it under drift for 40 generations: 

<div class="code">
drift := Module[{popSize, a, result, count, b},
  count = 0;
  For[i = 1, i <= 10000, i++,
   popSize = 5000;
   a = N[RandomInteger[BinomialDistribution[popSize, 0.015]]];
   For[j = 1, j <= 40, j++,
    a = N[RandomInteger[BinomialDistribution[popSize, a/popSize]]]];
   If[a == 0, count++]];
  count]

</div>

The variable <tt>count</tt> returns the number of trials out of 10,000 that the allele disappeared. For an initial frequency of 1.5 percent, roughly 3 percent of trials (308 out of 10000) end in loss of the allele. That's not a very high proportion of loss by drift. 

Still, we're not interested in loss from the population; we're interested in why haplotypes might not show up in the present-day <i>sample</i>. That might happen for two reasons: 

1. The alleles weren't so common to begin with -- many haplotypes were present in the early population that weren't in the skeletal sample. We can use the simulation to see what happens to rarer haplotypes. For example, if the initial frequency was only half a percent (0.005), then they are lost from the population after 40 generations nearly a third of the time (3142 out of 10000). 

2. The alleles are still in the Icelandic population, but rare enough they didn't get sampled. A sample of 900 people will miss roughly half of haplotypes with frequencies of 0.005 or less. Altering the simulation again, we find that drift achieves this result in roughly 5 percent (526 out of 10000) of cases, beginning at an initial frequency of 0.015. 

So altogether, the observed result is not at all unlikely. Genetic drift in Iceland had the power to eliminate rare alleles, even <i>after</i> the population was founded and grew to its medieval size. 

Still, this "strength" of genetic drift is manifested in its ability to eliminate initially rare alleles. If we ask what effect it would have on a <i>common</i> allele, we see a somewhat different dynamic. For mtDNA, the variance of allele frequency after one generation of drift is <i>p</i>(1-<i>p</i>)/(<i>N</i>), where <i>N</i> is the female effective population size (for autosomal genes with two copies, this expression would include 2<i>N</i> instead of <i>N</i>). After 40 generations, we expect a variance of 40<i>p</i>(1-<i>p</i>)/(<i>N</i>). What that means is that in 95 percent of cases, an allele that begins at 20 percent frequency will be between 13 and 27 percent after 40 generations. 

In other words, even in the small population of medieval Iceland, genetic drift is not strong enough to cause large increases or losses of common mtDNA haplotypes. And the effect of drift is four times greater for mtDNA than for autosomal genes. 

As a result of the loss of rare haplotypes, the medieval Iceland sample shares more alleles with <b>Eastern Europe</b>, <b>Russia</b>, and <b>Spain and Portugal</b> than with today's Icelanders. But if we look at a measure like <i>F</i><sub>ST</sub>, which is dominated by <i>common</i> alleles, the differences between these populations are very slight. 

I've gone through the example to point out that <i>some</i> kinds of observations are explained well by drift, and others aren't. Genetic drift has been an important cause of some evolutionary changes, even in recent human populations. But in any given case it is a hypothesis. We test this hypothesis by applying our knowledge of demographic history, mathematical models, and other genes. The hypothesis of drift might well be useful to explain one kind of observation (loss of rare alleles), while it is useless to explain others (elevation of one rare allele to a high frequency). 




<h4>References:</h4>

<p class="cite">Helgason A, Nicholson G, Stef&aacute;nsson K, Donnelly P. 2003. A reassessment of genetic diversity in Icelanders: Strong evidence from multiple loci for relative homozygosity caused by genetic drift. Ann Hum Genet 67:281-297. <a href="http://dx.doi.org/10.1046/j.1469-1809.2003.00046.x">doi:10.1046/j.1469-1809.2003.00046.x</a></p>


<p class="cite">Helgason A, Lalueza-Fox C, Ghosh S, Sigurardttir S, Sampietro ML, Gigli E, Baker A, Bertranpetit J, Arnadottir L, &THORN;orsteinsdotter U, Stef&aacute;nsson K. 2009. Sequences From First Settlers Reveal Rapid Evolution in Icelandic mtDNA Pool. PLoS Genet 5(1): e1000343. <a href="http://dx.doi.org/10.1371/journal.pgen.1000343">doi:10.1371/journal.pgen.1000343</a></p>

