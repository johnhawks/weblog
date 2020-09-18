---
layout: single 
title: "Surfing and recent selection" 
category: story
permalink: /weblog/reviews/genetics/spatial/hofer-2008-surfing-population-differences.html
tags: [genomics, acceleration, population structure, spatial dynamics, recent selection, genetic drift, demography] 
comments: false 
author: John Hawks 
---

<a href="http://scienceblogs.com/geneticfuture/2009/01/genetic_differences_between_hu.php">Genetic Future</a> and <a href="http://www.gnxp.com/blog/2009/01/selection-or-demography-in-differences.php">Gene Expression</a> have commented today on the relative roles of selection and demography in shaping the genetic differences between populations. They are reacting to a paper by Hofer and colleagues (2009) that examined the differences in frequency among human populations for a number of genetic markers, including STR (microsatellite), SNP and insertion-deletion mutations. 

That paper's abstract: 

<blockquote>Several studies have found strikingly different allele frequencies between continents. This has been mainly interpreted as being due to local adaptation. However, demographic factors can generate similar patterns. Namely, allelic surfing during a population range expansion may increase the frequency of alleles in newly colonised areas. In this study, we examined 772 STRs, 210 diallelic indels, and 2834 SNPs typed in 53 human populations worldwide under the HGDP-CEPH Diversity Panel to determine to which extent allele frequency differs among four regions (Africa, Eurasia, East Asia, and America). We find that large allele frequency differences between continents are surprisingly common, and that Africa and America show the largest number of loci with extreme frequency differences. Moreover, more STR alleles have increased rather than decreased in frequency outside Africa, as expected under allelic surfing. Finally, there is no relationship between the extent of allele frequency differences and proximity to genes, as would be expected under selection. We therefore conclude that most of the observed large allele frequency differences between continents result from demography rather than from positive selection.</blockquote>

OK, so that abstract concludes that demography (including population bottlenecks and geographic dispersals) is a better explanation for the genome-wide pattern of interpopulation frequency differences than selection. 

I agree completely. 

When I teach Anthropology 105, our introduction to biological anthropology, I always force my students to learn how to calculate Wright's <i>F</i><sub>ST</sub>. They really don't like it. They think it's <b>cruel and unusual punishment</b> to have to do math in an anthropology course. 

Well, if they're going to take <b>my</b> courses, they'll have to get used to it. Because with me, it's all about the math. 

So, let's consider <i>F</i><sub>ST</sub>. The statistic represents the reduction in heterozygosity in subpopulations due to isolation, compared to the expectation under panmixia. The expression is: 

<div class="middle-picture">
<img src="/graphics/fst-equation-h.png" width="220" height="74" alt="Fst equation" /> 
</div>

Where <i>H<sub>S</sub></i> is the average heterozygosity of subpopulations, and <i>H<sub>T</sub></i> is the expected heterogosity of the total population, given the allele frequencies. 

I always use a two-allele locus as an example in class, and I always choose a case in which the frequency of an allele in <i>one</i> subpopulation is 70 percent, and the frequency of the <i>same</i> allele in the <i>other</i> subpopulation is 30 percent. Big difference in frequencies -- the frequency is 40 percent higher in one population than in the other. In fact, that frequency difference is well within the range considered "extreme" in the current paper by Hofer and colleagues. 

Well, if the subpopulations are the same size, the average allele frequency is 50 percent. So the expected heterozygosity of the total population is 0.5. (that's 2<i>pq</i>, where <i>p</i> and <i>q</i> are the frequencies of the two alleles). And the average heterozygosity of the two subpopulations is 0.42. So applying the formula above, we come to an <i>F</i><sub>ST</sub> of 0.16. 

Now, the average <i>F</i><sub>ST</sub> among human continental populations is between 0.1 and 0.15. A value of 0.16 for a single gene should not be in the least bit unusual. Under neutrality, there ought to be lots and lots of gene loci that show allele frequency differences this great or greater. And indeed, Hofer and colleagues find a large set of such loci -- something like one out of 10, which actually seems a bit low to me. 

Other surveys that have tried to test the neutral hypothesis have considered a much smaller range of frequencies -- essentially, genes in which an allele is 80 percent or higher in one population and rare or absent in others. This study included much smaller allele frequency differences as part of their "extreme" and thereby found that a very high fraction of sites had such differences. 

For the broader meaning of "extreme" used in this paper, which under neutrality would include one out of every 10 loci, it is no surprise that most would look, well, <i>neutral</i>. There are so many neutral loci fitting these characteristics that they completely swamp out any statistical expectation of  selection. There might be a handful of selected sites among the high-<i>F</i><sub>ST</sub> loci in the paper (and the authors identify a few candidates from other studies), but most must be neutral. The study tests the adequacy of neutral hypothesis to explain low <i>F</i><sub>ST</sub> genes, and finds that population differences at that level have not been driven primarily by selection. 

I'm not sure why the authors didn't include the prosaic mathematical prediction of neutrality in their paper. It seems to me that the results were foreordained by theory. 

Still, several of the observations in the paper are interesting. In particular, the excess of STR alleles outside of Africa that have increased in frequency is a sign of a long-term demographic bias toward population growth outside of Africa. I have heard that observation from other research groups in other contexts, but this is the first paper I can think of that reported it clearly. The "allele surfing" explanation is a very credible explanation for that observation -- essentially, geographically-dispersed founder effect. 

The end of the discussion includes a statement about positive selection:

<blockquote>While we find that positive selection is unlikely to have shaped the allele frequency spectrum at most loci, it may certainly have acted on fewer genes than previously believed, and our current results do not allow us to discriminate between the effects of demography and selection for an individual locus. Loci which are candidates for being under positive selection should therefore be more carefully scrutinized to find links between potentially selected alleles and a phenotypic effect (see e.g. Sabeti et al. 2007).</blockquote>

I find nothing to disagree with here. Any individual instance of positive selection should be tested with reference to phenotypic effects, and collectively, most of the genome's diversity was not shaped by positive selection. Our own research on positive selection (<a href="http://johnhawks.net/weblog/topics/evolution/selection/acceleration/accel_story_2007.html">discussed in this post from last year</a>) addresses a relatively small subset of <i>haplotypes</i> across the genome. Even though the number of affected genes is quite large (on the order of several thousand), it did not strongly influence the genome-wide diversity parameters assessed by Hofer and colleagues. 

The limited genome-wide effect of selection, in the face of a large apparent number of selected alleles, is one of the strongest arguments that the rate of positive selection has recently accelerated. If the rate had been high throughout human evolution, we would find a much stronger effect on the genome-wide variation than we in fact observe. The demographic changes proposed by Hofer and colleagues in fact bolster the case for a recent acceleration -- the very demographic changes that might create "allelic surfing" would also tend to generate more positively selected mutations. 



<h4>References:</h4>

<p class="cite">Hofer T, Ray N, Wegmann D, Excoffier L. 2009. Large allele frequency differences between human continental groups are more likely to have  occurred by drift during range expansions than by selection. Ann Hum Genet 73:95-108. <a href="http://dx.doi.org/10.1111/j.1469-1809.2008.00489.x">doi:10.1111/j.1469-1809.2008.00489.x</a></p>

