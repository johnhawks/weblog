---
layout: single 
title: "Information theory and mutual information between genetic loci" 
category: story
permalink: /weblog/topics/information/theory/chi-square-mutual-information-2008.html
tags: [information, HapMap, recent selection, natural selection, information theory] 
comments: false 
author: John Hawks 
---

<blockquote><i>This is the second in a series on information theory and tests for recent selection. The first entry, <a href="http://johnhawks.net/weblog/topics/information/theory/information-theory-intro-2008.html">"Information theory: a short introduction"</a> reviewed the basic concepts of information measures and their background.</i></blockquote>

<p class="noindent" >The <a  href="http://www.hapmap.org" >International HapMap</a> is a massive project to determine the genotypes for up to 3 million single nucleotide polymorphisms (SNPs) in samples of people from 11 population samples around the world. The current data release (<a  href="http://www.sanger.ac.uk/humgen/hapmap3/" >Phase 3</a>) includes genotypes for a subset of over 1.5 million SNPs in 1,115 people. The 11 population samples include people of African ancestry from the US Southwest, Utah residents of Northern and Western European ancestry, Han Chinese from Beijing, people of Chinese ancestry from Denver, people in the Houston Gujarati Indian community, Japanese people from Tokyo, Luhya and Maasai people from Kenya, people of Mexican ancestry from Los Angeles, Italians in Tuscany, and Yoruba from Ibadan, Nigeria. </p>

<p class="indent" >  As impressive as this effort is, we may wonder why exactly SNP genotyping of so many people is a valuable enterprise in itself. The project&#8217;s homepage includes this short statement:      <div class="quote">      <p class="noindent" >The goal of the International HapMap Project is to compare the      genetic sequences of different individuals to identify chromosomal      regions  where  genetic  variants  are  shared.  By  making  this      information  freely  available,  the  Project  will  help  biomedical      researchers  find  genes  involved  in  disease  and  responses  to      therapeutic drugs.</div> <p class="indent" >   There are theoretical and practical objections to this simple explanation (as <a  href="http://johnhawks.net/weblog/topics/profiles/david-goldstein-wade-profile-2008.html" >I discussed here last month</a>). However, what no one involved with the project seems to have expected is the extent to which the data would demonstrate the importance of recent adaptive evolution in human populations. <p class="indent" >   Here, I am describing some of the ways that we can test hypotheses about natural selection by using the SNP genotypes from the HapMap. This is a theory-centric description, with some digression into practical aspects of handling the genotype data. First, I consider how we might use information theoretic concepts to test the hypothesis of independence between two genetic loci.
<!--break-->
<a   id="section*.2"></a>    <h3 class="sectionHead"><a   id="x1-2000"></a>Entropy and genotypes</h3> <p class="noindent" >The data from the HapMap consist of an array of biallelic genotypes for each population. The size of this array is different for each population; we may consider it to have <span  class="cmmi-10">m </span>rows, each row corresponding to a single SNP locus, and <span  class="cmmi-10">n </span>columns, each corresponding to a person. The entries are genotypes: <span  class="cmmi-10">AA</span>, <span  class="cmmi-10">AT</span>, <span  class="cmmi-10">CG</span>, and so on. Each SNP is biallelic, so it hardly matters what we call the two alleles&#8212;we can arbitrarily                                                                                                                                      label them <span  class="cmmi-10">a </span>and <span  class="cmmi-10">b</span>. Thus, the three possible genotypes may be labeled <span  class="cmmi-10">aa</span>, <span  class="cmmi-10">ab </span>and <span  class="cmmi-10">bb</span>. <p class="indent" >   Of course, from a sample of genotypes, we can readily estimate the frequencies of the two alleles in the population. The sample allele frequency <img  src="/graphics/chi-square-mutual-information0x.png" alt="&#x02C6;p"  class="circ" > (<span  class="cmmi-10">a</span>) = <img  src="/graphics/chi-square-mutual-information1x.png" alt="&#x02C6;p"  class="circ" > (<span  class="cmmi-10">aa</span>) + <img  src="/graphics/chi-square-mutual-information2x.png" alt="12"  class="frac" align="middle"><img  src="/graphics/chi-square-mutual-information3x.png" alt="&#x02C6;p"  class="circ" > (<span  class="cmmi-10">ab</span>), where the estimate <img  src="/graphics/chi-square-mutual-information4x.png" alt="&#x02C6;p"  class="circ" > (<span  class="cmmi-10">aa</span>) is the number of <span  class="cmmi-10">aa </span>individuals in the sample divided by the sample size <span  class="cmmi-10">n</span>. It is worth expressing some statistical caution about estimates. Although the HapMap SNPs are biased toward common alleles, nevertheless some of them are rare indeed. And as we stretch down the chromosome to consider multilocus haplotypes, many may be vanishingly rare or even singular in the population, even though they happen to occur in the sample. <p class="indent" >   Now, how shall we estimate the entropy of a single locus? It seems there are several ways we might look at the question.      <ol  class="enumerate1" >      <li    class="enumerate" id="x1-2002x1"><span  class="cmbx-10">Allelic entropy </span>We might use the entire sample of genotypes at the      locus to estimate the allele frequencies. In that case, the entropy of the      SNP locus would be estimated by      <table  class="equation"><tr><td>      <center class="math-display" >      <img  src="/graphics/chi-square-mutual-information5x.png" alt="H&#x02C6;(SNP ) = - [&#x02C6;p(a)log &#x02C6;p(a)+ &#x02C6;p(b)log &#x02C6;p(b)]      " class="math-display" ><a   id="x1-2003r1"></a></center></td><td class="equation-label">(1)</td></tr></table>      <p class="nopar" >      <p class="noindent" >For a SNP locus with empirical genotype frequencies <span  class="cmmi-10">p</span>(<span  class="cmmi-10">aa</span>) = 0<span  class="cmmi-10">.</span>16,      <span  class="cmmi-10">p</span>(<span  class="cmmi-10">ab</span>) = 0<span  class="cmmi-10">.</span>48 and <span  class="cmmi-10">p</span>(<span  class="cmmi-10">bb</span>) = 0<span  class="cmmi-10">.</span>36, this estimate of allelic entropy would be 0.97      bits.      </li>      <li    class="enumerate" id="x1-2005x2"><span  class="cmbx-10">Genotypic entropy </span>Or, we might consider the <span  class="cmti-10">genotype frequencies </span>as the      essential elements of the system. In this case, the entropy would be estimated      by      <table  class="equation"><tr><td>                                                                                                                                           <center class="math-display" >      <img  src="/graphics/chi-square-mutual-information6x.png" alt="H&#x02C6;(SNP) = - [&#x02C6;p(aa) log &#x02C6;p(aa)+ &#x02C6;p(ab)logp&#x02C6;(ab)+ &#x02C6;p(bb)log &#x02C6;p(bb)]      " class="math-display" ><a   id="x1-2006r2"></a></center></td><td class="equation-label">(2)</td></tr></table>      <p class="nopar" >      <p class="noindent" >For the same genotype frequencies listed above, this genotypic entropy would      be estimated as 1.46 bits.      </li>      <li    class="enumerate" id="x1-2008x3"><span  class="cmbx-10">Sample entropy </span>Or, we might consider the sample of genotypes as a series of      <span  class="cmmi-10">n </span>repeated trials. That would make the sample entropy in the example 1<span  class="cmmi-10">.</span>46<span  class="cmmi-10">n</span>      bits. We might also calculate a sample entropy considering the gametes      instead of the genotypes&#8212;but this would work out to be the <span  class="cmti-10">same</span>, as      long as we don&#8217;t know which gametes came from which parents of      heterozygotes.      </li></ol> <p class="indent" >   To understand this last point, imagine that the sample is a deck of shuffled cards. Each card may be red with probability <span  class="cmmi-10">p</span>(<span  class="cmmi-10">a</span>) or black with probability <span  class="cmmi-10">p</span>(<span  class="cmmi-10">b</span>). If we drew cards one at a time, we could record a sequence (red, red, black,&#x2026;) of 2<span  class="cmmi-10">n</span> cards. Each card drawn thereby has an exact position in the sequence. If <span  class="cmmi-10">p</span>(<span  class="cmmi-10">a</span>) = 0<span  class="cmmi-10">.</span>4 and <span  class="cmmi-10">p</span>(<span  class="cmmi-10">b</span>) = 0<span  class="cmmi-10">.</span>6 as above, then this entropy will be 1<span  class="cmmi-10">.</span>94<span  class="cmmi-10">n </span>bits. Now, imagine instead that we draw the cards two at a time, and record only these pairs (homozygote red, homozygote black, heterozygote,&#x2026;). We will have a sequence half as long, and this sequence does not include the exact position of the red and black cards, only their position as part of a pair. The entropy of this sequence of <span  class="cmmi-10">n</span> genotypes is only 1<span  class="cmmi-10">.</span>46<span  class="cmmi-10">n </span>bits. This gives some insight into the nature of the sample entropy as defined above: It is the entropy of a <span  class="cmti-10">sequence </span>of genotypes. <p class="indent" >   By contrast, the allelic entropy is the uncertainty associated with drawing a single copy of the SNP at random from the sample. The genotypic entropy is the uncertainty associated with drawing a genotype (two SNP copies) from the sample. Again, these are empirical estimates derived from the sample; they represent the underlying population just to the extent the sample does. <p class="indent" >   Which of these estimates will be useful to us? The sample entropy tells us how many bits of hard drive space we need to store the HapMap data under an efficient coding scheme. That&#8217;s interesting, but not necessarily what we have in mind. The other two are sample estimates of an underlying population characteristic&#8212;either                                                                                                                                      allele or genotype frequencies. In what follows, we will be interested in quantifying how much our uncertainty about one individual&#8217;s SNP genotype is <span  class="cmti-10">reduced </span>by knowing that same individual&#8217;s genotype for some <span  class="cmti-10">other </span>SNP. It would seem that the appropriate measure for this problem will be the genotypic entropy. <a   id="section*.3"></a>    <h3 class="sectionHead"><a   id="x1-3000"></a>Mutual information between SNPs</h3> <p class="noindent" >The joint entropy represented by two SNP loci may be less than the sum of their individual entropies. That is to say, there may be mutual information between the two loci. Mutual information can arise between SNPs for several reasons. Most obviously, if the sample of individuals actually consists of members of <span  class="cmti-10">two distinct</span> <span  class="cmti-10">populations </span>with different allele frequencies, then two distinct SNPs may have mutual information because of this <span  class="cmbx-10">hidden population structure</span>. This source of mutual information is exploited by <span  class="cmbx-10">admixture mapping</span>&#8212;a process that involves taking people with recent ancestry from two or more populations and finding genomic regions that are linked by virtue of the fact that little recombination has yet had time to reshuffle haplotypes that may be locally common but globally rare. Or two loci may share mutual information because they are physically linked. 

<p class="indent" >   As an example of mutual information estimation, consider two sets of genotypes (the rows of the following table):   </p>

<div class="middle-picture">
<table><tr>
<td><span  class="cmmi-10">A </span>=    0    1    0    2    0    1    1    0    1    0    1    0    2    1    0    0    1    0    1    0   </td></tr>
<tr><td><span  class="cmmi-10">B </span>=    2    2    2    0    1    1    2    2    0    2    1    1    0    1    2    1    2    2    1    2 </td>
</tr>
</table>
</div>

<p class="noindent" >Each SNP locus has three genotypes; twenty people are represented in the sample, each column represents the genotypes of a single individual. The empirical estimate of genotypic entropy from the first SNP locus (<span  class="cmmi-10">&#x0124;</span>(<span  class="cmmi-10">A</span>)), based on 10 zeros, 8 ones and 2 twos, is 1.36 bits per individual. The same estimate for the second SNP locus (<span  class="cmmi-10">&#x0124;</span>(<span  class="cmmi-10">B</span>)), based on 3 zeros, 7 ones, and 10 twos, is 1.44 bits per individual. The <span  class="cmbx-10">sum of the individual entropies</span> for the two SNP loci is 2.8 bits. But the <span  class="cmbx-10">joint entropy </span>of the two loci (<span  class="cmmi-10">&#x0124;</span>(<span  class="cmmi-10">A,B</span>)), based on three (0,1), seven (0,2), one (1,0), four (1,1), three (1,2), and two (2,0) joint genotypes, is only 2.36 bits. Hence, the two SNP loci share an estimated 0.44 bits of mutual information (e.g., <span  class="cmmi-10"></span>(<span  class="cmmi-10">A</span>;<span  class="cmmi-10">B</span>) = 0<span  class="cmmi-10">.</span>44 bits). <p class="indent" >   What does this mean? Consider the following contingency table, based on the genotypes above:   

<div class="middle-picture">
<table border="1" align="center">
<tr border="1px"><th width="20px"></td><th width="20px">0 </th><th width="20px">   1  </th><th width="20px">  2 </th></tr> 
<tr><th border="1px"> 0 </th><td></td><td>3  </td><td>  7 </td></tr> 
<tr><th border="1px"> 1  </th><td>  1  </td><td>  4  </td><td>  3  </td></tr>
<tr><th border="1px"> 2 </th><td>   2  </td><td>  </td><td> </td> </tr>
</table>
</div>                                                                                                                                      

<p class="indent" >   None of the sampled individuals have the joint genotype (0,0) and none have (2,1) or (2,2). But even more important, a full seven have (0,2) even though only 2.5 would be expected if the two SNPs were independent. <p class="indent" >   The contingency table is a clue (for the statistically-minded). The mutual information is telling us something like Pearson&#8217;s <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> test of association. If we know the genotype for SNP <span  class="cmmi-10">A</span>, we can do better than chance predicting the genotype for SNP <span  class="cmmi-10">B</span>. <a   id="section*.4"></a>    <h3 class="sectionHead"><a   id="x1-4000"></a>Significance testing for mutual information</h3> <p class="noindent" >The comparison with Pearson&#8217;s <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> test raises another obvious question: How do we test whether a given amount of mutual information is statistically significant? In the example above, we have estimated 0.44 bits of mutual information between SNP <span  class="cmmi-10">A</span> and SNP <span  class="cmmi-10">B</span>. Is this a lot? How much mutual information should we expect between two <span  class="cmti-10">random </span>samples of data? <p class="indent" >   Let&#8217;s take an even simpler contingency table &#8212; the relation between two coin flips. Each flip may have a 50-50 chance of producing &#8220;heads&#8221; or &#8220;tails&#8221;. On average, we expect to see one fourth (H, H), one fourth (T, T), one fourth (H, T) and one fourth (T, H) in our results. But if we perform this experiment (2 coin flips) a finite number of times, we will almost always see some slight divergence from these proportions. Ten sets of coin flips <span  class="cmti-10">absolutely can&#8217;t </span>give us one fourth of each result, because <span  class="cmbx-10">ten doesn&#8217;t divide by four evenly</span>. On top of that problem, we might get six or seven (H, H) by chance, even if we only expect 2.5. Any of these cases will give us a positive non-zero <span  class="cmti-10">estimate </span>of mutual information, even if there is no causal connection between the coin flips. <p class="indent" >   Another way of stating this observation is that the <span  class="cmti-10">estimate </span>of mutual information, <span  class="cmmi-10"></span>(<span  class="cmmi-10">A</span>;<span  class="cmmi-10">B</span>) is <span  class="cmbx-10">biased</span>. We should expect the estimate from a small sample to be <span  class="cmti-10">larger than </span>the true mutual information in the population at large. <p class="indent" >   The analogy between mutual information and the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> test is more apt than it might appear. In fact, over many trials, the distribution of sample estimates of mutual information will approximate a <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> distribution, multiplied by a factor 2<span  class="cmmi-10">n</span>log 2, where <span  class="cmmi-10">n </span>is the number of cases in the sample. Our sample of genotypes of <span  class="cmmi-10">A </span>and <span  class="cmmi-10">B </span>above has 20 individuals and 3 possible genotypes, so 40(log 2)<span  class="cmmi-10"></span>(<span  class="cmmi-10">A</span>;<span  class="cmmi-10">B</span>) should be distributed as a <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> with 4 degrees of freedom. <p class="indent" >   Reflecting on the three ways we might estimate the entropy of a locus, above, this is twice the mutual information calculated from the <span  class="cmti-10">sample</span> <span  class="cmti-10">entropy</span>, measured in <span  class="cmti-10">nats </span>instead of bits. Even though we are interested in estimating the population characteristic, the <span  class="cmti-10">genotypic entropy</span>, the significance of our estimate can only be evaluated by considering the entropy of the sample. <p class="indent" >   And indeed, we can perform a randomization of the two sets of genotypes and                                                                                                                                      show the correspondence. Here, I&#8217;ve done ten thousand permutations of the genotypes in <span  class="cmmi-10">A </span>with respect to those in <span  class="cmmi-10">B</span>: <p class="indent" >   

<div class="middle-picture">
<img  src="/graphics/chi-square-mutual-information.png" width="400"  alt="Simulation outcome"   >

</div>

 <p class="indent" >   The bars are the histogram representing the 10,000 permuted samples, the curve is the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> density function with 4 degrees of freedom. You can see that the permutations show significant clumpiness. With only 20 sampled individuals, some fractional combinations come up quite often while others are impossible. Also, the permutations are <span  class="cmti-10">more biased </span>than the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> would predict&#8212;there are too few small values for <span  class="cmmi-10"></span>(<span  class="cmmi-10">A</span>;<span  class="cmmi-10">B</span>). This is another small sample effect. Generally, the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> approximation fails when there are fewer than 5 observations in a cell, and shouldn&#8217;t really be trusted with fewer than 10. Here, we have nine cells and only 20 <span  class="cmti-10">total </span>observations. But our value of 0.44 bits&#8212;equal to a sample mutual information of 12.2 nats on the scale of the figure&#8212;is significant according to the (uncorrected) <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> approximation with <span  class="cmmi-10">p </span>= 0<span  class="cmmi-10">.</span>016, and according to the permutation test with <span  class="cmmi-10">p </span>= 0<span  class="cmmi-10">.</span>014. If we are very concerned about the deviation from the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> distribution, we might decide to use Fisher&#8217;s Exact Test on the underlying contingency table. <p class="indent" >   With more observations, data do tend to converge to a <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> distribution. For example, here I have run 10,000 permutations of a sample of 10,000 individuals, for two loci, each locus with 10 alleles at equal frequencies. The curve is a <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> distribution with 81 degrees of freedom: <p class="indent" >  

<div class="middle-picture">
<img  src="/graphics/chi-square-mutual-information-massive.png" width="400" alt="Simulation outcome"   > 
</div>

<p class="indent" >   Very nice. <p class="indent" >   This comparison suggests a couple of things. First, we can always do a permutation test of the hypothesis of independence. Take a sample of paired genotypes, shuffle up one of them, and see if the observed pairs share higher mutual information than a large fraction (say, 95%) of the permuted sets. (Naturally, if at this point you are already thinking of a genome-wide survey, you will need to consider ways to correct for multiple comparisons&#x2026;.) <p class="indent" >   Second, we can get approximate results for mutual information using a <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> test. All we do is multiply the mutual information estimate <span  class="cmmi-10"></span>(<span  class="cmmi-10">A</span>;<span  class="cmmi-10">B</span>) by 2<span  class="cmmi-10">n</span>log 2 and compare it to the appropriate significance level of the <span  class="cmmi-10">&#x03C7;</span><sup><span  class="cmr-7">2</span></sup> distribution with the appropriate number of degrees of freedom. This approximation will be poor for small samples, including the HapMap samples. Again, if we were testing the hypothesis of independence in those cases, we would likely want to use Fisher&#8217;s Exact Test instead. <p class="indent" >   But in what follows, we will generally not be testing the hypothesis that two loci are <span  class="cmti-10">independent</span>; we will be testing the hypothesis that they are linked under neutrality. In that context, these statistical tests of independence will be useful for quickly weeding out genetic regions where linkage is negligible. Then, we can employ different tests for regions where linkage appears to be more substantial, tests that make more effective use of the properties of mutual information. <p class="indent" >   <span  class="cmbx-10">Next: Genetic drift reduces mutual information</span>
