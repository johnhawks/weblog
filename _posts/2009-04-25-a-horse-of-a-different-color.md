---
layout: single 
title: "A horse of a different color" 
category: story
permalink: /node/1966
tags: [horses, paleogenomics, genomics, pigmentation, domestication, MC1R] 
comments: false 
author: John Hawks 
---

I feel like I've been transported into the future to see what science will be like fifteen years from now: 

<blockquote>We successfully typed eight mutations in six genes (6) responsible for coat color variation for 89 [out of 152 tested; tables S1 to S5 (6)] ancient samples. To assess coat color variation of predomestic horses, we analyzed the bones of wild horses from the Late Pleistocene and Early Holocene found in Siberia, East and Central Europe, and the Iberian Peninsula. We found no variation in the Siberian and European Pleistocene horses, suggesting that these horses were bay or bay-dun in color.</blockquote>

<blockquote>...</blockquote>

<blockquote>In contrast, a rapid and substantial increase in the number of coat colorations is found in both Siberia and East Europe beginning in the fifth millennium B.P. (Fig. 1 and figs. S1 and S2). Although the earliest chestnut allele (MC1R gene) was identified in a Romanian sample from the late seventh millennium B.P., chestnut horses were first observed in Siberia (fifth millenium B.P.). Their prevalence increased rapidly, reaching 28% during the Bronze Age.</blockquote>

The whole paper is only a page long. Like, "Oh yeah, we just genotyped 89 horse skeletons from the Neolithic up to the Bronze Age, and here's how the process of selection on color patterns worked out." 

Couple of things -- 

1. The pigment-altering mutations at these genes do not all show statistical signs of selection in contemporary samples of horses. But they aren't there in the ancient horses. That's the best evidence of selection you could possibly have. Message: tests of selection on contemporary samples are weak, particularly for loci with rare alleles or more than two alleles. 

2. The study shows how much you can learn with a moderate number of samples. The advantages working in this case: the genes responsible for pigmentation phenotypes are well-characterized, the number of loci is well-matched by the sample size; the study focuses on recovering SNPs instead of sequencing. 

UPDATE (2009-04-25): I looked at the statistical test of selection used in the paper with a little more detail. It comes from a paper by Jonathan Bollback, Thomas York and Rasmus Nielsen, published last year in <i>Genetics</i>. It's a very clever test. Assume a sample of genes taken from a population at some discrete set of times, <i>t</i><sub>1</sub>, <i>t</i><sub>2</sub>, <i>t</i><sub>3</sub>, and so on. Under genetic drift, this series of frequencies approximates a random walk, with the size of deviations depending on the effective population size. Under constant directional selection, the random walk will be biased in a way that can be approximated by a diffusion model of selection. 

So if you have a big enough sample, you can estimate the relative contribution of stochastic (drift) effects and deterministic (directional selection) effects on the frequencies over time. 

In the current case, two alleles have sample sizes that are large enough, frequency changes that are large enough and constant enough in direction to show that drift is minor and selection is strong. For example, the chestnut variant goes from zero in the Neolithic to 65 percent in the Medieval time period, with every change a between time increments an increase. That's an allele with 44 copies (by my quick count) in all samples. 

Four alleles do not have such large changes (they are initially absent, but present in only four or fewer individuals in the later time intervals). There's only one copy of the <i>SILV9</i> color variant mutation in the entire sample of archaeological horses. With a very small sample, the sampling variance will be larger than the stochastic effects of drift. So even if those few copies are exclusively in the latest time increments, the time series won't look unusual compared to drift. 

But what the test doesn't consider is the current frequency. Since this is known with much less sampling variance, we can compare the present frequency with the frequency summed across the older time intervals to get a more powerful test of neutrality. Also, the test assumes that selection is constant -- if selection had a stochastic element, varying over time, that would have the same impact on the sample as drift or sampling variance. That's why the absence of an allele in an ancient sample can be stronger evidence of selection than the fine-scaled record of change over time. 

Complicating matters is population structure. The coat color variants are not distributed evenly across the modern horse population; they are distributed into different breeds. The strong association of some color variants with breeds is, of course, evidence of its own that the color variants have been correlated with fitness under domestication. Now, whether this fitness association is a deliberate result of people liking colors (because they differentiate breeds, or look pretty, or whatever) or whether they arise incidentally (by linkage with other traits) isn't tested by these data. These <i>functional</i> aspects of selection provide another possible test of neutrality -- for example, in this case all the non-bay-black alleles increased over time, a bias that isn't consistent with chance. 



<h4>References:</h4>

<p class="cite">Bollback JP, York TL, Nielsen R. 2008. Estimation of 2<i>N</i><sub>e</sub><i>s</i> from temporal allele frequency data. Genetics 179:497-502. <a href="http://dx.doi.org/10.1534/genetics.107.085019">doi:10.1534/genetics.107.085019</a></p>

<p class="cite">Ludwig A, Pruvost M, Reissmann M, Benecke N, Brockmann GA, Casta&ntilde;os P, Cieslak M, Lippold S, Llorente L, Malaspinas A-S, Slatkin M, Hofreiter M. 2009. Coat color variation at the beginning of horse domestication. Science 324:485. <a href="http://dx.doi.org/10.1126/science.1172750">doi:10.1126/science.1172750</a></p>

