---
layout: single 
title: "When genetic drift reduces entropy" 
category: story
permalink: /weblog/topics/information/theory/genetic-drift-reduces-entropy-2009.html
tags: [genetic drift, recent selection, genomics, HapMap, recombination, information theory, effective population size] 
comments: false 
author: John Hawks 
---

<div class="quote">      <p class="noindent" ><i>This  is  the  third  in  a  series  on  information  theory  and  tests      for recent selection. The first post, <a  href="http://johnhawks.net/weblog/topics/information/theory/information-theory-intro-2008.html" >&#8220;Information theory: a short      introduction&#8221;</a>, covered some of the basics of entropy. The second      post, <a  href="http://johnhawks.net/weblog/topics/information/theory/chi-square-mutual-information-2008.html" >&#8220;Information theory and mutual information between genetic      loci&#8221;</a>, showed that mutual information between independent sites      will be distributed as a <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup></i>.</div> 

<p class="noindent" >We tend to think of genetic drift as a random process. Random processes operating repeatedly over time are called &#8220;stochastic,&#8221; and changes in gene frequency under genetic drift are certainly that. <p class="indent" >   Since entropy is a measure of <span  class="cmti-10">uncertainty</span>, it might seem natural to think that stochastic changes in gene frequency would increase the entropy in a population. After all, the gene frequency in a population under genetic drift will be more and more uncertain over time. So, considering the frequency of a single allele as the system, genetic drift appears to increase entropy over time. 

<p class="indent" >   But even this simple system isn&#8217;t quite so simple as it might appear. Sure if you start out <span  class="cmti-10">knowing </span>the allele frequency, then genetic drift will increase your uncertainty over time. You will become less and less able to say that it lies in any given interval. But what if you don&#8217;t start out knowing? What if all you know is that the locus has been subjected to <span  class="cmmi-10">t </span>generations of genetic drift? 

<p class="indent" >   As <span  class="cmmi-10">t </span>increases, the probability of fixation of the locus also increases. The net effect is to reduce the entropy in the system &#8211; going from uncertainty about the allele frequency to more and more certainty that it will be either one or zero. The only thing that will stop this process is some other evolutionary force &#8211; mutation, migration from other populations, balancing selection. Each of these will have its own distinctive effects on the entropy of the single-locus system.
<!--break-->
<a   id="section*.2"></a>    

<h3 class="sectionHead"><a   id="x1-2000"></a>Drift and recombination</h3> <p class="noindent" >We are going to consider a system of two partially linked loci. That means that the two are near enough to each other on a single chromosome that they are usually inherited together, but that a small fraction of individuals will have recombination between the two loci in each generation.                                                                                                                                      <p class="indent" >   If the two loci were unlinked, the evolution of allele frequencies at one would have no effect on the other. The mutual information between the two loci would accord with the description in <a  href="http://johnhawks.net/weblog/topics/information/theory/chi-square-mutual-information-2008.html" >the last post in the series</a>. As described there, the distribution of mutual information estimates taken from different samples of such populations would approximate a chi-square distribution. <p class="indent" >   But our two loci will be linked. Genetic drift tends to affect the allele frequencies at the two loci in the same way. Haplotypes consisting of one allele from each locus will increase or decrease under drift. Over time, haplotype frequencies will tend to diverge, some becoming rare, others common. Because the alleles of the two loci are evolving in tandem, the joint entropy of the two-locus system will be lower than expected from the sum of the individual entropies of the two loci. Mutual information will be greater than expected under the hypothesis of independence. <p class="indent" >   How much? That depends on the amount of recombination between the two loci and the power of genetic drift. Recombination introduces random noise, by breaking up pairs of alleles and shuffling them. That tends to increase the joint entropy of the two-allele system. The more recombination, the less we can predict the allelic state of one locus from what we observe at the other. <p class="indent" >   Genetic drift is more powerful in small populations; less so in large populations. It can also be enhanced by population structure, or diminished by migration. 

<p class="indent" >   So in principle, the reduction in joint entropy from genetic drift opposes the increase in joint entropy from recombination. As the physical distance between the two loci increases, the power of recombination will increase. As the population size increases, the power of genetic drift will decrease. That means we need to know something about local recombination patterns, and something about ancient human demography to get a good estimate of the effects of these processes on human genes. 

<p class="indent" >   But given some knowledge about these things, we should be able to get a pretty accurate idea of the distribution of mutual information that would result from drift alone in ancient human populations. 

<a   id="section*.3"></a>    

<h4 class="subsectionHead"><a   id="x1-3000"></a>Simulating some samples</h4> 

<p class="noindent" >These days, the person who wants to investigate the effects of genetic drift on samples of genes has many options. Several well-documented computer programs allow simulations of genetic drift allowing the user to choose parameters like effective population size, recombination rate, marker type and density. Some of these programs use a forward-time approach &#8211; that is, starting with a randomized sample and propagating it forward through time. Others use a coalescent approach, which &#8220;starts&#8221; with a sample of genes taken from the present and propagates their ancestry backward in time. There&#8217;s a good diversity to choose from, unlike the old days (10 years ago) when you more or less had to write your                                                                                                                                      own. 

<p class="indent" >   For this series, I&#8217;m going to use a package called CoaSim. The package was written by Thomas Mailund and colleagues, and is <a  href="http://www.daimi.au.dk/~mailund/CoaSim/" >available under a free software license</a>, including documentation. This software employs a coalescent approach to generate an &#8220;ancestral recombination graph&#8221; (ARG) among a sample of genes, under a specified model of demographic history. The ARG is a tree of genealogical relationships among the sampled genes, factoring in a history of recombination between them. From the ARG, the software can add markers (such as SNPs or microsatellites), resulting in simulated datasets of sequences that <span  class="cmti-10">could have </span>evolved under the specified demographic history. 

<p class="indent" >   Similar functionality is available in some other packages. I&#8217;m using CoaSim in this case because it includes Python bindings. I use Python for a number of other analytical methods, so this cuts my development time. That&#8217;s a faster path from investigation to results. 

<p class="indent" >   So, let&#8217;s consider some samples that might result from a long history of genetic drift in a single population. First, I&#8217;ll assume that the effective size of my population is 10,000 diploid individuals. I&#8217;m going to simulate 10000 samples from populations matching this description. Each sample consists of two SNP markers drawn from 120 gametes &#8211; in other words, two copies from each of 60 individuals, with current sample frequencies random between 0.1 and 0.9. If you&#8217;ll recall from the <a  href="http://johnhawks.net/weblog/topics/information/theory/chi-square-mutual-information-2008.html" >last post in the series</a>, we need a decent number of individuals representing each bin for our mutual information estimate to be reasonable. Excluding rare SNPs helps to make sure we have that. 

<p class="indent" >   The mutual information between these SNPs will depend on the rate of recombination between them. To begin with, I&#8217;ll assume that the two markers are 50 kilobases apart, and that the rate of recombination is 1cM/Mb, or around 10<sup><span  class="cmsy-7">-</span><span  class="cmr-7">8</span></sup> per base. 

<div class="middle-picture"> 
<img  src="/graphics/drift_only_N_10000_rho_400_markers_50kb.png" alt="PIC"   /> 
</div>

<p class="indent" >   The red line represents a chi-square distribution with 1 degree of freedom. That would be the expectation if these two loci were independent, and the histogram is clearly biased to the right compared to that expectation. That means that the mutual information between two linked loci is higher, on average, than that between two unlinked loci. This is a simulation under drift alone, not an empirical distribution. Drift reduces the joint entropy of two linked loci more than it reduces the individual entropy of each locus. <p class="indent" >   How much mutual information are we talking about? From the <a  href="http://johnhawks.net/weblog/topics/information/theory/chi-square-mutual-information-2008.html" >last post</a>, we know that twice the sample mutual information, measured in nats, is approximated by a chi-square. Here on the high end, we have a value of 50, which corresponds to 25 nats per sample. In our sample of 120 gametes, that is around 0.2 nats per gamete, or around 0.3 bits per gamete. That&#8217;s not a remarkable amount &#8211; it&#8217;s about the entropy of a single biallelic locus with allele frequencies of 0.95 and 0.05. 

<p class="indent" >   Now, what happens if we keep recombination the same, but reduce the strength of genetic drift? The following chart shows what happens if I assume an effective size                                                                                                                                      of 100,000, with the rest of the parameters kept the same &#8211; 50 kb, 120 chromosomes, frequencies between 0.1 and 0.9. 

<div class="middle-picture">
<img  src="/graphics/drift_only_N_100000_rho_400_markers_50kb.png" alt="PIC"   /> 
</div>

<p class="indent" >   Here, the histogram is much closer to the expected chi-square distribution under independence. There&#8217;s still a slight bias upward, and out of 10,000 samples, a few that have rather high mutual information values. But the effect of genetic drift in this scenario is very slight compared to the case where <span  class="cmmi-10">N </span>= 10000. 

<p class="indent" >   As it turns out, the effect of a tenfold larger population is precisely the same as if I kept population size the same and moved the loci ten times further apart. The mutual information scales with the <span  class="cmti-10">product </span>of recombination and effective population size. So two loci 500 kb apart in an effective population of 10,000 would on expectation have the same mutual information as two loci 50 kb apart in an effective population of 100,000. Another way of putting it: By reducing the coalescent probability tenfold, recombination has ten times the opportunity to scramble associations between the two loci. 

<a   id="section*.4"></a>    

<h4 class="subsectionHead"><a   id="x1-4000"></a>When population size expands</h4> 

<p class="noindent" >Human populations have grown by more than a thousand-fold during the last 40,000 years. Compared to the population of 40,000 years ago, today&#8217;s human population should have markedly less mutual information between linked genetic loci. If we want to find out how much, we&#8217;ll have to have a model of the recent human demography. 

<p class="indent" >   Here, I&#8217;ve done some simulations with changing population size. First, let&#8217;s assume that we have two loci 50 kb apart. I&#8217;m going to start with a very simplistic model of human demographic history. This model has three stages, or &#8220;epochs:&#8221;      

<ol  class="enumerate1" >      
<li    class="enumerate" id="x1-4002x1">For the last 400 generations, the effective size is 1,000,000 individuals.      </li>      
<li    class="enumerate" id="x1-4004x2">Before  that,  up  to  800  generations  ago,  the  effective  size  is  100,000      individuals.      </li>      
<li    class="enumerate" id="x1-4006x3">Before 800 generations ago, the effective size is 10,000 individuals.</li></ol> 

<p class="indent" >   This is both simplistic and conservative. It&#8217;s basically assigning a size of a million to the post-agriculture population, and 100,000 to the population after the Last Glacial Maximum. We know that those early values are way too small for the African population, which did not markedly contract during the LGM and has had an effective size up over 30,000 for at least the last 100,000 years. And obviously, the effective population for the past 10,000 years has been much higher than a million. The European population may have had more of a bottleneck at the LGM, but today&#8217;s Europeans have substantial ancestry in West Asia, so 10,000 is conservative there as well. The point is not that these values are realistic; it is that they are almost certainly too small. 

<p class="indent" >   I&#8217;ve picked the simple scenario to make it a little more transparent what is going on with the results. Here they are: 

<div class="middle-picture">
<img  src="/graphics/drift_only_N_simple_growth_rho_4000_markers_50kb.png" alt="PIC"   > 
</div>

<p class="indent" >   With this population history, two loci 50 kb apart have nearly the same distribution of mutual information as two independent loci. There&#8217;s a slight bias toward higher values, but very little. Out at the tail, it looks like there are around twice as many loci as predicted by the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> approximation, and this is still a very small number. <p class="indent" >   I thought it might be useful to consider what the mutual information would be under the same population history for two loci that are closer together. Here&#8217;s the same scenario, except the loci are 5 kb apart: 

<div class="middle-picture">
<img  src="/graphics/drift_only_N_simple_growth_rho_4000_markers_5kb.png" alt="PIC"   >
</div>

<p class="indent" >   With the markers ten times closer here, there is only a tenth as much recombination between them. That makes the result a lot more like the first case above, where the markers were 50 kb apart and the effective size was 10,000 back to infinity. Markers 5 kb apart should have a good chance of sharing significant mutual information under drift alone in a human-like population history. However, as in the first case above, the mutual information generated by drift is still fairly slight. 

<a   id="section*.5"></a>    

<h4 class="subsectionHead"><a   id="x1-5000"></a>Growth and recombination</h4> 

<p class="noindent" >Let&#8217;s step back and consider what&#8217;s going on with these examples. Mutual information is determined by the balance between recombination and coalescence. Increase the effective size, and you reduce the probability of coalescence between lineages. That gives recombination more of a chance to scramble the loci, eliminating mutual information between them. <p class="indent" >   A human-like population history has a very large effective size within the last several thousand years. The large effective size reduces the probability of coalescence down to almost zero across that time period. So the ancestry of almost every gene copy has more than 400&#8212;and often up to 1000&#8212;generations all to itself. If recombination is ticking along at 1cM/Mb, then physical distances out to around 50 kb start to saturate for recombinants across the last 20,000 years. 

<p class="indent" >   Consider: two lineages that coalesce 400 generations in the past are separated by 800 generations of time. The two lineages were initially identical. Our two markers are 50 kb apart, given them a per-generation probability of recombination of 0.0005. The probability that neither undergoes recombination during those 400 generations is:    

<div class="middle-picture">
<img  src="/graphics/genetic-drift-reduces-entropy0x.png" alt="(1- 0.0005)800 = 0.67 " class="math-display" >
</div>

<p class="indent" >   Two thirds remain the same; one third of pairs will have recombined with other lineages. Half of pairs that coalesce 700 generations ago will have recombined. In contrast, after 700 generations, only seven percent of pairs separated by 5 kb will have recombined. Pairs that remain identical carry mutual information; each pair that recombines loses this mutual information. 

<p class="indent" >   Under drift alone, the mutual information builds slowly. From the first chart we know that the mutual information at this physical distance in a small population will be significant, but not very high. Most of this information is still retained in the samples represented by the last chart, where they are separated by only 5 kb. But over longer distance this mutual information dissipates rapidly in a growing population. 

<p class="indent" >   So if we observe substantial mutual information between loci in today&#8217;s populations, we need some explanation other than genetic drift. Selection is one possible explanation&#8212;but to consider that more closely, we will want to consider other information theoretic features of gene samples. 

<p class="indent" >   <span  class="cmbx-10"><a href="http://johnhawks.net/weblog/topics/information/theory/strings-of-loci-multiinformation.html">Next: Extending to strings of loci</a></span>

