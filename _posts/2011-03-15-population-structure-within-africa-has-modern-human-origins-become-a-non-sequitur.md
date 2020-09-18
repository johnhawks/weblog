---
layout: single 
title: "Population structure within Africa: has &quot;modern human origins&quot; become a non sequitur?" 
category: story
permalink: /weblog/reviews/genomics/modern/henn-southern-africa-origins-2011.html
tags: [Africa, Hadza, hunter-gatherers, Middle Stone Age, population structure, Neandertal DNA, Bantu, Bushmen, Middle Pleistocene, admixture] 
comments: false 
author: John Hawks 
---

When I wrote about the Denisova genome late last year, I claimed that "A large-scale reorganization of the science of human origins is upon us." 

I'm glad I had the sense to write that. A lot of people have pointed back to that quote over the last few months. Still, I know that the full implications of the Denisova and Neandertal genomes haven't really sunk in. "Large-scale reorganization" takes time. 

A new paper by Brenna Henn and colleagues in <i>PNAS</i> <bib>Henn:2011</bib> shows how the shifting landscape has caught many geneticists off their footing. Submitted before the Denisova genome, but long after the Neandertal, the paper is titled, "Hunter-gatherer genomic diversity suggests a southern African origin for modern humans". In today's landscape, with only one instance of the word "Neanderthal" in the paper, the conclusions are obviously incomplete. 

The "southern African origins" conclusion of the paper comes out of a simple analysis that assumes that the best-fit maximum for genetic diversity (as assessed by linkage) is the most likely point of origin of the population. That would be true if the African population emerged by a series of founder effects from a single small ancestral population -- the "serial founder effect" model that I have criticized here before. But of course in 2011, we know that model is false, because it is predicated on a lack of ancient mixture with Neandertals or other populations. If the serial founder model can't work <i>outside</i> Africa, it certainly can't work <i>inside</i> Africa, where populations were larger and regionally diversified during by the beginning of the Late Pleistocene. Without that false assumption, the "southern African origin" evaporates. The primary observation, a cline of linkage disequilibrium within sub-Saharan Africa, can be explained with reference to mixture of populations without assuming an origin and expansion from one geographic location. 

I don't want to criticize overmuch. Many ongoing research projects are casualties of our new knowledge of ancient genomics, and we'll see more papers like this before the fallout has settled. Simplistic founder models, acceptable only a year ago when these projects were conceived, are now unquestionably false. Ancient population mixture is the order of the day, and we don't have any simple, plug-in-the-data models to apply to data like these.

Instead, I want to consider the power of the data in this article to answer some fundamental questions about African population history. Henn and colleagues report on SNP genotyping of several Bushman groups from southern Africa and Sandawe and Hadza people from eastern Africa. These data are on the 550k SNP platform that was used by 23andMe before the recent increase to 1M SNPs. That means the data are comparable to many other studies. They are not entirely comparable with other samples of African genetic variation, and the authors cut the total number of SNPs down to the 55,000 that overlap among all the genotyping platforms used in their analysis. For this reason, the paper presents a genome-wide set of 55,000 SNPs across many African populations. 

It's far from the perfect sample. I expect we'll be able to do much more with the full 550k dataset from the hunter-gatherer populations. The data have been made publicly available for download, and here we're already starting to investigate them. 

Within the current paper there is a very useful analysis of the broader dataset using the ADMIXTURE software. ADMIXTURE assumes that the current samples represent a mixture of ancient populations that were more distinct than today's. I went through this algorithm with my students in class Wednesday and Friday, which I'm sure was an intimidating process to most of them. The math is not too conceptually daunting; it's just hard to conceptualize how all the possible interactions relate to gene frequencies when you are assuming more than a few putative ancestral populations. Razib Khan gives <a href="http://blogs.discovermagazine.com/gnxp/2011/03/analyzing-ancestry-with-admixture-step-by-step/">an impressive step-by-step guide to performing an ADMIXTURE analysis</a>, including some of these samples. 


I'm not in love with this analytical method -- there's no reality check on its assumptions. But its output can be informative about many aspects of population structure. Here are some first approximations: 

<b>1. The genetic diversification of African populations was once much greater than today.</b> <a href="http://blogs.discovermagazine.com/gnxp/2011/03/where-in-the-world-did-anatomically-modern-humans-come-from/">Razib Khan points out</a> the homogenizing effect that agricultural populations have had on the African continent, particularly during and after the Bantu expansion. I think the current data suggest that earlier processes involving LSA hunter-gatherers also tended to homogenize populations. 

For example, when eight initial clusters are assumed, the ADMIXTURE analysis constructs them in a way that most of the ancestors of today's Bushmen were in a population with a high degree of genetic divergence from the other seven ancestral populations. The <i>F</i><sub>ST</sub> between the Bushman ancestral population and others ranges from 0.1 (for forest pygmies) to a high of 0.25 (from Europeans). That estimate is nearly double the equivalent statistic in today's populations. 

Again, we don't have to believe the assumptions underlying the ADMIXTURE algorithm, but it does highlight the basic partitioning of diversity in the African population. Today there is high diversity within African population samples, and some of that diversity can be traced back to populations of 100,000 years ago or more. Some of the diversity that once existed among these populations has now been spread within them instead. The populations got genetically closer over time.  

A model of successive population expansions, bringing ancient populations genetically closer and closer together, is also what we may see in other places. As we have learned more about the mtDNA of ancient Europeans, it has become clear that successive expansions and migrations of people into Europe have radically reshaped the gene pool. 


<b>2. Click languages have no genealogical unity.</b> Over the years, many linguists and anthropologists have proposed that Hadza, Sandawe, and Bushmen are closely related to each other, despite their geographic distance, because they all speak languages that use click sounds. No historical linguist has ever successfully demonstrated a system of sound changes or detailed correspondences among these languages, but people promoting the hypothesis seem immune to these kinds of facts. 

The genetics show a very clear and ancient differentiation of these hunter-gatherer peoples. In the ADMIXTURE analysis, some of the largest genetic distances are among these peoples. By itself, that may not be surprising; these are the populations that have most evaded the homogenization that followed the spread of farming. The Hadza themselves are strikingly distinctive, and their genetics may reflect a history of small population size during the last several hundred years. The potential for genetic drift in this population was very high. Still, the genetic relations are just the opposite that would be expected if speakers of these click languages had shared a common origin. 

Seems to me that this could have been the lede of the paper, if it had been written differently. A bit more exploration of the hunter-gatherer data (probably incorporating some haplotype-level analysis to give a better estimate of the ages of events) would demonstrate this point very well. 


<b>3. By the time we find "modern" humans in West Asia, the African population had long since diversified into regional populations.</b> This is not news; the mtDNA evidence has suggested for several years that southern Africa and the remainder of sub-Saharan Africa were already regionally differentiated before 120,000 years ago. There have also been hints of this diversification from whole-genome evidence (including the supplement of the Neandertal genome paper last year). Here we have a clear indication that the regionality extends to every African hunter-gatherer population. 


<b>4. Hunter-gatherers have relatively little evidence for recent positive selection.</b> The supplementary data of the current paper includes a short discussion of selection and a list of candidate loci in the hunter-gatherer samples. There is relatively little overlap in candidate regions for selection among these samples. Different genes have been selected in different populations, and not all that many of them. This is not surprising if the selection is relatively new -- the last 20,000 years or maybe more, given the distances and amount of historical population structure estimated for the data. It's also consistent with the demography of these populations. It will be interesting to check, but I would speculate that the signature of selection will on average appear older in these samples than in populations that have historically been agriculturalists. 

<b>5. Where's the Aterian?</b> North Africa is relatively depauperate in variation in the large combined dataset. That may stem mostly from Holocene events, including the spread of West Asian populations across North Africa. But the low variation there doesn't readily fit the idea that an out-of-Africa dispersal of genes came from a North African source. I don't think the observations in the paper (centered around linkage disequilibrium with a very low SNP count) are enough to settle anything about this question, but I'd be nervous if I were busy trying to make the Aterian seem important to the modern human origins issue. 

<h4>Bottom line</h4>

As interesting as these assertions look, I don't think that a lot of African prehistory is about to be rewritten. Obviously, geneticists need to get serious about reading some African archaeology. We already know that African regional populations were large and diverse during the Middle Stone Age, and that's a very good fit to the kind of genetic diversity we are seeing in these samples. 

The barrier is Holocene population history. Agricultural populations grew, spread, mixed with and absorbed hunter-gatherers, and what we left are the shattered remnants of ancient African population structure. Linkage may be the most powerful way we have to consider historical hypotheses using these SNP data, but if we're going to rely on it we have to control for recent demography and selection. 

And of course, it will be interesting to see a model that can integrate both Neandertal-African and within-African population histories. I don't really have a bang-up finish for this post, because there is immediately more work to be done with these data. 









