---
layout: single 
title: "Did humans face extinction 70,000 years ago?" 
description: "A study of mtDNA variation gets hyped as evidence of a bottleneck, but actually shows the opposite." 
category: story
permalink: /weblog/reviews/genetics/mtdna_migrations/sub-saharan-africa-population-size-behar-2008.html
tags: [migrations, MSA, Late Pleistocene] 
comments: false 
author: John Hawks 
---

<p>
That was the headline of many of last week's stories about the paper by Behar and colleagues, drawing upon the Genographic Project African mitochondrial DNA (mtDNA) data. Here's a quote from <a href="http://www.eurekalert.org/pub_releases/2008-04/ngs-dom042308.php">the National Geographic Society's press release</a>: 
</p>

<blockquote>Previous studies have shown that while human populations had been quite small prior to the Late Stone Age, perhaps numbering fewer than 2,000 around 70,000 years ago, the expansion after this time led to the occupation of many previously uninhabited areas, including the world beyond Africa.</blockquote>

<p>
And here's project director Spencer Wells' quote in the same release:
</p>

<blockquote>Dr. Spencer Wells, National Geographic Explorer-in-Residence and Director of the Genographic Project, said: "This new study released today illustrates the extraordinary power of genetics to reveal insights into some of the key events in our species' history. Tiny bands of early humans, forced apart by harsh environmental conditions, coming back from the brink to reunite and populate the world. Truly an epic drama, written in our DNA."</blockquote>

<p>
Well, that certainly sounds dramatic. But is it true? 
</p>
<!--break-->
<p>
The paper itself does not provide any tests of the number of ancient humans indicated by the mtDNA phylogeny. The press release mentions "previous studies" that fix a small initial founding population for Africans, so I went looking through the paper to see which studies they had cited. 
</p>

<p>
I found this passage, which seems relevant: 
</p>

<blockquote>Different approaches were taken in the attempt to estimate the sub-Saharan <i>Homo sapiens</i> population size in different time frames.<sup>7</sup></blockquote>

<p>
OK, that seems like what I want -- estimates of population size in different time frames in sub-Saharan Africa. So I looked up reference 7, and found this: 
</p>

<blockquote>Hawks,J., Wang,E.T., Cochran,G.M., Harpending,H.C., and Moyzis,R.K. (2007). Recent acceleration of human adaptive evolution. Proc. Natl. Acad. Sci. USA 104, 20753-20758.</blockquote>

<p>
D'oh! 
</p>

<p>
Now on the one hand, it is very gratifying to be recognized as an expert on the genetic demography of sub-Saharan Africa. I mean, we did work hard on that paper. But on the other hand, it seems like we might do a little better than that paper as an examination of the demographic history of sub-Saharan Africa. 
</p>

<p>
And the current paper by Behar and colleagues provides <i>exactly</i> the right kind of information to get that more detailed demographic history. So I've put together some notes here on how we can discover whether there was a population bottleneck 70,000 years ago in Africa, using the mtDNA evidence. I'm setting aside for the moment the question of population structure -- the "isolation" story that was also made in the press release for the paper. Population structure and size are not independent of each other, and we will have to consider how they interacted in African prehistory. But the first issue should be size, because our interpretation of size is based on relatively simple aspects of genetic variation (at its simplest, the first moment), while testing hypotheses about population structure requires higher-order comparisons. 
</p>

<!-- more -->

<h4>Assumptions</h4>

<p>
Any estimate of ancient population sizes requires a number of assumptions. I'm about to be more explicit about these assumptions than any other analysis of ancient population sizes you're likely to have seen. 
</p>

<p>
<b>Major assumption: Effective population size is relevant to the actual population size.</b>

<p>
I wanted to put that up front, to be perfectly clear that we are going to be dealing with an estimate of the rate of inbreeding, and not a direct signature of the number of individuals. The two may be related to each other, given other assumptions. But human genetics has what you might call a Vizzini problem: that word they keep saying, "effective population size," it does not mean what they think it means. The "effective population size" is often confused uncritically for the true number of individuals in a present-day or ancient population. 
</p>

<p>
The interpretation of a bottleneck (e.g., of the 2000-individual variety noted above) is based on the inference that a population in the past had a much higher rate of inbreeding than was true more recently. Inbreeding, as we will see below, has characteristic effects on the rate of coalescence of gene lineages. The rate can be converted to an estimate of the effective population size, given other assumptions. 
</p>

<p>
I'll have a much longer discussion of effective population size in a separate post. But for the time being, please note that our "population size" estimates are actually estimates of "effective population size," which for ancient humans must certainly have been smaller than the actual number of people, and may have been smaller than the actual number of people by an order of magnitude or more. 
</p>

<p>
So what other assumptions should we keep in mind? 
</p>

<p>
<b>1. Mutation model and rate</b>

<p>
In this discussion, I will assume the mutation model and rates assumed in the paper by Behar and colleagues (2008). Those may be in error, and the errors will necessarily affect my estimates. But I don't have any particular reason to think the errors are in one direction or another -- in fact, I think that the dates given for lineages in the study look reasonable given the evidence from other sources, and are consistent with other recent studies. 
</p>

<p>
<b>2. Panmixia</b>

<p>
We'll assume random mating. This assumption is certainly false for this sample of mtDNA, as demonstrated by Behar et al. But we will leave it for additional tests to see how much a more accurate hypothesis of population structure will affect our estimate of effective size. 
</p>

<p>
<b>3. No selection</b>

<p>
That's an odd thing for you to see me write. It is actually very likely that some of the relevant mtDNA lineages have been selected during their history. We ignore that at our peril, since natural selection (which causes inbreeding) would invalidate the relationship between effective size (a measure of inbreeding) and the actual population size. 
</p>

<h4>The coalescent</h4>

<p>
The coalescent is a statistical description of the genealogical relationships among a sample of genes taken from a population. As I will describe it here, the coalescent applies to a Wright-Fisher population model, a random-mating, discrete-generation population model described by a single parameter, <i>N</i>, the number of individuals. The concept of "effective population size" (<i>N</i><sub>e</sub>) relates the level of inbreeding in an actual population to that expected in a Wright-Fisher population of <i>N</i><sub>e</sub> individuals. Often we consider a diploid population with 2<i>N</i> gene copies (chromosomes), but because we will be considering mitochondria here, I will use the haploid formulation with <i>N</i> gene copies. 
</p>

<p>
In a Wright-Fisher population, the probability that two randomly chosen gene copies actually descend from a single gene copy in the previous generation is simply 1/<i>N</i>. Looking at the genealogy of the genes in a retrospective point of view, this is the probability that the two lineages will <i>coalesce</i> into a single ancestral lineage, and we can call this a <i>coalescent event</i>. 
</p>

<p>
Now, let's consider a sample if <i>n</i> gene copies. Any random pair of these copies might share a parent in the preceding generation, with probability 1/<i>N</i>. Collectively, if we ignore the chance that two or more coalescent events occur in the same generation, the probability of that <i>n</i> gene copies have only <i>n-1</i> ancestors in the previous generation is:
</p>

<div style="text-align:center;">
<img src="/graphics/equations/coalescent_n_probability.png" />
</div>

<p>
Conversely, the probability that the <i>n</i> copies have <i>n</i> distinct ancestors is 1&nbsp;-&nbsp;Pr[<i>n</i>&rarr;<i>n</i>&nbsp;-&nbsp;1]. 
</p>

<p>
Now we can ask, what is the mean number of generations between coalescent events? The probability of a coalescent event among <i>n</i> copies in generation <i>t</i> -- but not before generation <i>t</i> -- is: 
</p>

<div style="text-align:center;">
<img src="/graphics/equations/coalescent_in_generation_t.png" />
</div>

<p>
This probability declines as <i>t</i> increases, and is distributed as a geometric decay, so that the expected time that the genealogy has exactly <i>n</i> ancestral lineages is:
</p>

<div style="text-align:center;">
<img src="/graphics/equations/coalescent_mean_from_n.png" />
</div>

<p>
The mean time from <i>n</i> to <i>n</i>-2 is the sum of the means from <i>n</i> to <i>n</i>-1 and from <i>n</i>-1 to <i>n</i>-2, and the total time to the coalescent of the entire sample is expected to be:
</p>

<div style="text-align:center;">
<img src="/graphics/equations/coalescent_time_haploid.png" />
</div>

<p>
This expression converges toward 2<i>N</i> as <i>n</i> increases to be very large. Because of this relation, the coalescence time of the sample serves as an estimator of the size of the Wright-Fisher population with similar genetic variation as the sampled population. The estimate of <i>N</i> thus derived is called the inbreeding effective population size -- "inbreeding" because it depends on the identity-by-descent among the sampled gene copies. 
</p>

<p>
This estimate is a kind of average effective population size, covering the time all the way back to the coalescent of the sample. It is therefore not very informative about the way that population has changed over time. If we want to know about the size of the African population between 70,000 and 100,000 years ago, say, we are going to have to find a way to estimate more precisely. 
</p>

<h4>Applied to African mtDNA</h4>

<p>
If we know that the present-day sample of African mtDNA coalesced to <i>n</i> ancestral lineages 80,000 years ago, and further to <i>n-x</i> ancestral lineages 90,000 years ago, then we can arrive at an estimate of effective population size applying just to that time period. 
</p>

<p>
The mitochondrial equivalent of the Wright-Fisher population size <i>N</i> is the inbreeding effective number of females, <i>N</i><sub>e(f)</sub>. Assuming this number was constant across the interval from <i>t<sub>n</sub></i> to <i>t<sub>n-x</sub></i>, then the female effective size is given by the equation:
</p>

<div style="text-align:center;">
<img src="/graphics/equations/coalescent_female_ne.png" />
</div>

<p>
Helpfully, Behar et al. (2008) provide the number of ancestral lineages remaining at the beginning of various time periods, from 80,000 to 144,000 years ago, in their Table 1. They estimated dates using their model of mutations in the genealogy, so the numbers may be imprecise. But they make it very easy to derive estimates of the effective number of females in the ancient African population. Note that these estimate will have an error factor due to the fact that the coalescent events do not match up exactly with the time intervals given in Table 1. A substitution of the true estimates for the coalescent dates would eliminate this source of error; for this post I am sticking with the dates given in Table 1 instead of the supplementary table, just because the numbers of lineages in these intervals have been pre-tabulated and are simpler for readers to cross-check. 
</p>

<p>
At 80,000 years ago, the African sample includes 24 ancestral lineages; by 90,000 years ago it includes only 22. That means 2 coalescent events in this 500 generation span, yielding an estimate of female <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;66,000. 
</p>

<p>
That's a high estimate, certainly very high compared to the notion that the human population was restricted to fewer than 2000 individuals at that time! 
</p>

<p>
But in a very small population of 2000 individuals, we would expect a very large fraction of the sampled ancestral lineages to have coalesced in a 500-generation span. We would expect 24 ancestral lineages to coalesce into only three or four across that time period. Instead, we find that the African sample had a low rate of lineage coalescence across that span: low inbreeding, and therefore a high effective population size. 
</p>

<p>
I picked the 80,000-90,000 year span first because it has relatively few coalescent events. Earlier and later spans have more coalescent events, and therefore the estimate of effective population size should be smaller. 
</p>

<p>
For example, the period from 90,000 to 100,000 years ago includes 8 coalescent events, from 22 to 14 ancestral lineages, leading to an estimate of <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;9600. The period between 70,000 and 80,000 (less accurate because I have to read off Figure 1 instead of a table) appears to have 7 coalescent events (counting the multifurcation at the base of L3 as 6 separate events). That leads to an estimate of <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;27,000. 
</p>

<p>
Which of these estimates is more accurate? We have to consider: 
</p>

<p>
1. More coalescent events in an interval should lead to a more accurate estimate, because the major component of error comes from the large variance in the distribution of coalescence times. Counting several events tends to average out extreme values. Likewise, the boundaries of these time slices are arbitrary dates in years, not coincident with coalescent events. Each slice includes some amount of time before and after the included coalescent events, causing more inaccuracy for small numbers of events. So the interval including only 2 events should result in a much less reliable estimate of effective size. 
</p>

<p>
2. On the other hand, the population could really have changed in size. If so, there's nothing impossible about <i>all</i> the estimates being accurate. The estimates provide a testable hypothesis of population history. 
</p>

<p>
I tend to think that these estimates by themselves are insufficient to document the fluctuation of the population across this span -- we would want additional evidence from other genes, preferably corroborated by archaeology. Also, we have to remember that population structure is affecting the inbreeding in a way that we haven't tested yet. So all in all, I would prefer to assume a constant size, and put the most reliable estimate together. 
</p>

<p>
We can do this by combining the span represented in the paper. Across the time period from 70,000 to 144,000 years ago, the African sample coalesces from 31 to 7 ancestral lineages, a total of 24 coalescent events. If the female effective population size were constant across that time span, this would lead to an estimate of <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;17,000. Taking only the span from 70,000 to 100,000 years ago as a subsample yields an estimate of <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;19,000 -- in other words, barely larger. The effective sizes seem consistent across the span from 70,000 to 144,000 years. There was no narrow bottleneck at that time, nothing associated with those "megadroughts," nothing associated with the Toba volcanic eruption. 
</p>

<h4>What does the large African effective size mean?</h4>

<p>
Since those estimates are for the <i>female</i> effective size, we can double them to estimate the total inbreeding effective population size for Africa across this time period -- approximately 34,000 individuals. 
</p>

<p>
This is substantially larger than the long-term effective size as estimated from most autosomal genes. Autosomal genes have a much longer total coalescence time than the mtDNA -- in the Wright-Fisher model, they would have a coalescence time 4 times longer. And they do tend to preserve ancient diversity from much earlier than 200,000 years ago -- an average around 800,000 to 1 million years, and some much longer. These times correspond to an estimate of the long term effective size of <i>N</i><sub>e</sub>&nbsp;=&nbsp;10,000. 
</p>

<p>
If the mtDNA is showing a larger effective size -- around three or more times larger than the long-term value for autosomal genes -- then I would hypothesize that the expansion of the African population had already commenced during this time period. This corresponds to the late Middle Stone Age, a time of exceptional flourishing of regional technological variation in Africa as well as the innovation of new tool types, hunting techniques (projectile weapons) and artistic expression. It makes sense for the African population to have been expanding at this time, not contracting or undergoing a severe bottleneck. 
</p>

<p>
I am currently working on testing this hypothesis with new SNP data from African populations. But from the mtDNA alone we have a partial indication that the expansion had begun by 144,000 years ago. If we look back to the earliest part of the tree, back to the inferred coalescent of the entire mtDNA sample -- a date this study places at 200,000 years ago -- we can estimate female effective size using the same method as above. 
</p>

<p>
The earliest branches of a gene genealogy should be the oldest, because we should wait much longer for a coalescent event among a few sampled lineages than among many. In fact, in a Wright-Fisher population, half the total time depth of a gene genealogy is expected to be taken up by the final coalescent -- the time span during which only two ancestral lineages remain. In the tree presented by Behar et al. (2008), the tree coalesces from three lineages to two at 180,000 years ago. All things being neutral and constant, we would expect the final coalescent to take another 180,000 years -- for a total time depth of 360,000 years. We can observe that that date would accord very well with a female effective size of 18,000 as estimated for later dates in the tree. 
</p>

<p>
But in <i>this</i> tree, the final coalescent takes only 20,000 years. In fact, the final few coalescent events seem to take substantially less time than would be expected under neutrality. 
</p>

<p>
We can quantify this: taking the population from 7 ancestral lineages at 144,000 years ago back to only 1 ancestral lineage at 200,000 years ago, we estimate <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;1600. This looks like a small ancestral size for the sample -- but not at 70,000 years ago, but instead well over 140,000 years ago. If we consider the effective size estimate back to the next-to-last coalescent, 180,000 years ago, we obtain an estimate of <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;2500 -- almost as small, but not quite. This indicates that the apparent increase in inbreeding characterizes not only the final coalescent but the final few. Pending further investigation, I would say this is probably a real increase in inbreeding. 
</p>

<p>
Is this a bottleneck? I think the null hypothesis is that this small effective size represents the same population size as estimated for the long-term autosomal value. A population effective size of 5000 for the mtDNA is probably not statistically different from a size of 10,000 for the autosomes -- given the small number of coalescent events we are including. 
</p>

<p>
But maybe this early high level of inbreeding does represent a bottleneck, or possibly the rapid differentiation of a mtDNA variant under selection in Africa after 200,000 years ago. 
</p>

<h4>How many people would this mean in the African late MSA?</h4>

<p>
I'm going to post on effective population size in the next few days, because it is a complicated story. But if you happen to miss those posts, I can give a quick indication of what these numbers mean for the African population. The inbreeding effective size in ancient humans was likely somewhere between a third of the actual number of individuals anywhere down to a tenth or less. 
</p>

<p>
This means that an estimate of the effective size of 34,000 would likely indicate a true population size of 100,000 up to 300,000 individuals. This population may have occupied all the parts of Africa for which late MSA assemblages exist. The evidence for some population structure presented by Behar et al. (2008) (as well as earlier work by Gonder et al. 2007 and others) supports that model: A large and widely dispersed African population, exchanging genes and ideas. 
</p>

<p>
Other phenomena may cause much more inbreeding than expected in a Wright-Fisher population. Genetic draft, or pseudohitchhiking, is one; repeated colonization and extinction of small groups is another. If these factors were important in human evolution, they may have reduced the inbreeding effective size to much less than a tenth of the census population size. As yet, we have no good estimate of such factors, but they should have become less important as populations grew during the Late Pleistocene. So a total population size of 500,000-1 million is not out of the realm of possibility for the late MSA, especially if some currents within this population made more of a contribution to later populations than others. 
</p>

<p>
The late Acheulean/early MSA population appears likely to have been much smaller, only a third or less the size of that during the later MSA. Human occupation was widespread across Africa during that earlier time, so the expansion may represent either an increase in the density across the same range or the displacement of some populations (or genetic lineages) by others. 
</p>

<p>
I can't finish without noting that many of the key archaeological innovations of the late MSA are also found outside of Africa, in the European and Levantine Middle Paleolithic. The mtDNA evidence is necessarily telling us about African populations of this period, because the Eurasian mtDNA gene pool is much more recently derived. But the demographic changes occurring in Africa must have influenced neighboring regions as well, both through gene flow and cultural diffusion. 
</p>

<p>
The most interesting genes are the selected ones. This improved picture of demographic history in Africa greatly aids our ability to evaluate selection in recent African populations. As indicated by these data, there was no severe bottleneck in Africa within the last 100,000 years. The population was quite large (in evolutionary terms) across that entire span. This is reflected by the low level of linkage disequilibrium evident in the Yoruba HapMap and other African population samples. It means that long LD regions in these samples certainly do not derive from recent bottlenecks. 
</p>

<h4>How could this be wrong?</h4>

<p>
Looking back to the underlying assumptions, there are several possible weaknesses in the analysis as it applies to the real prehistoric African population as opposed to an ideal Wright-Fisher population. 
</p>

<p>
1. Nonrandom sampling strategy. The research article has very selectively drawn mtDNA samples for further analysis by whole-genome sequencing. In particular, the study attempted to increase our knowledge of the diversity within the ancient L1 and L0 lineages. But ideally for this kind of demographic inference we would want a random sample of genes, not a highly selected sample. 
</p>

<p>
Still, I don't think that presents a significant bias in this case. The entire sample includes several hundred mtDNA copies, so these ancient lineages should have shown up regardless. Sampling diversity in this way would certainly alter our interpretations of recent divergences (by underestimating the true inbreeding rate) but this should have little effect on the ancient parts of the genealogy. 
</p>

<p>
2. Population structure. Behar et al. (2008) conclude that their Khoisan and other African samples could not have belonged to a single random-mating population across the span from 80,000 to 100,000 years ago, and possibly more recently. 
</p>

<p>
Generally speaking, population structure tends to increase genetic variation. But when we consider the rate of coalescent events, the story is more complicated. Partial isolation would affect the times of coalescent events in the sample across this span: Coalescent events within each sample would be somewhat more likely, while coalescent events including lineages from both samples would be much less likely. 
</p>

<p>
We can test the effect of population structure on our estimate of effective size, by considering each sample separately. The Khoisan sample includes very few lineages across the entire span (at most 4), so an estimate of female effective size from this sample will not be very reliable. Based on the reduction from 4 to 2 ancestral lineages from 80,000 to 144,000 years ago, we can estimate <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;6400. The non-Khoisan African sample includes many more ancestral lineages across this range: from 20 to 5. This yields an estimate of <i>N</i><sub>e(f)</sub>&nbsp;=&nbsp;11,000. The sum of these is hardly different than would be estimated from the whole sample under the assumption of random mating, so <i>this</i> aspect of population structure has relatively little influence on the estimate across this span. It remains possible that other aspects of population structure (such as finer geographic structuring) might be inflating the estimate. 
</p>

<p>
3. Selection. I am less concerned with selection in this portion of the African mtDNA history than I am in later times. Clearly, many mtDNA lineages have recently been increased or reduced in frequency by selection. We see rather large transitions in frequency between ancient and modern samples in some regions, we see health and other phenotypic consequences of mtDNA lineages in living humans, and we see a clear signature of rapid growth for some lineages indicative of selection. 
</p>

<p>
But across the span from 70,000 to 144,000 years ago, there is no sign of large-scale frequency changes among the sampled lineages. It is possible that some diversifying selection may be maintaining different lineages, but this seems sort of unlikely over 60,000 years or more, also considering the relatively steady rate of coalescent events across the span. 
</p>

<p>
However, the initial period of the genealogy, between 200,000 and 144,000 years ago, may have seen positive selection on a new mtDNA variant. That hypothesis may be tested by further comparisons with autosomal variability. 
</p>

<p>
Weak purifying selection on coding sites would tend to reduce the length of early branches compared to later branches, as these later branches would include some weakly selected mutations that would not be expected to survive over the long term. This phenomenon would depress our estimates of effective size early in the tree. This could be tested by comparing the synonymous/nonsynonymous mutation ratio for earlier and later branches. 
</p>

<p>
4. Mutation model. The estimates here depend on the mutation model employed by Behar et al. That model could be wrong. 
</p>

<p>
This is by far the largest potential source of error in the estimate, not only because adjustments to the rate of mutations would cause a linear response in the estimates of female effective size, but also because the evident changes in the genealogy over time will change in date as a result. If we increased the mutation rate estimated for coding mtDNA mutations by double, we would be looking at a bottleneck around 2000 individuals ending around 70,000 years ago -- pretty much what the press release had claimed. (It is interesting that you have to double the mutation rate to get to that value!)
</p>

<p>
Now, the mutation model used in this paper does agree with results from other recent whole-genome analyses of mtDNA. And doubling the mutation rate would have other untenable consequences -- for instance, it would move the South Asian appearance of the modern human mtDNA variability down to less than 30,000 years ago, and the population expansion into the New World down to around 7000 years ago. Still, we might maintain that the later branches have lower effective mutation rates than the early branches. 
</p>

<p>
We should also keep in mind the possibility of error in the other direction, as well. If our estimate of mutation rate is too high, then effective size estimates are systematically too low. That would point to an earlier population expansion in Africa. 
</p>

<h4>Conclusion</h4>

<p>
As you can see, these data allow a direct test of the hypothesis of a 70,000-year-old bottleneck in Africa, and they refute the hypothesis. The new data allow a powerful model of ancient African population size to be built, one that comes together with archaeological data to give us a really interesting picture of the early evolution of "modern" humans. The model can be tested with new, massive sets of information from single nucleotide polymorphisms, as well as a more detailed chronology of late MSA sites. 
</p>

<h4>References:</h4>

<p class="cite">Behar DM, 14 others, and The Genographic Consortium (consortium again? Whoa). 2008. The dawn of human matrilineal diversity. Am J Hum Genet 82:1-11. <a href="http://dx.doi.org/10.1016/j.ajhg.2008.04.002">doi:10.1016/j.ajhg.2008.04.002</a></p>

