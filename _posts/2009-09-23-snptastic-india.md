---
layout: single 
title: "SNPtastic India" 
category: story
permalink: /weblog/reviews/genomics/variation/reich-2009-india-population-genetics.html
tags: [population growth, genomics, population history, HapMap, admixture, India] 
comments: false 
author: John Hawks 
---

The cover story in <i>Nature</i> this week is a paper about the population history of India, from David Reich's lab. It's an important contribution to our knowledge of human genetic variation, and provides a very interesting set of data for further investigation of modern human origins, the dispersal of agriculture into the subcontinent, and the history of more recent Indian populations. 

Here's the abstract: 

<blockquote>India has been underrepresented in genome-wide surveys of human variation. We analyse 25 diverse groups in India to provide strong evidence for two ancient populations, genetically divergent, that are ancestral to most Indians today. One, the 'Ancestral North Indians' (ANI), is genetically close to Middle Easterners, Central Asians, and Europeans, whereas the other, the 'Ancestral South Indians' (ASI), is as distinct from ANI and East Asians as they are from each other. By introducing methods that can estimate ancestry without accurate ancestral populations, we show that ANI ancestry ranges from 3971% in most Indian groups, and is higher in traditionally upper caste and Indo-European speakers. Groups with only ASI ancestry may no longer exist in mainland India. However, the indigenous Andaman Islanders are unique in being ASI-related groups without ANI ancestry. Allele frequency differences between groups in India are larger than in Europe, reflecting strong founder effects whose signatures have been maintained for thousands of years owing to endogamy. We therefore predict that there will be an excess of recessive diseases in India, which should be possible to screen and map genetically.</blockquote>

The number of individuals is not huge for the purposes of population genetic analysis -- only 132 people from 25 groups -- but it is very significant in terms of recent samples. By comparison, it is around double the number of effective individuals in any of the HapMap v.1 populations, genotyped at more than 560,000 SNPs. 

The results of the study are basic population genetic issues, including the degree of endogamy, the pattern of regional differentiation, the likelihood of discovering new recessive genetic disorders by additional sampling. Some notes: 


<b>Population mixture</b>. The authors propose that today's groups descend in varying proportions from two ancient (and no longer existing) populations, which they call "ancestral North Indian" and "ancestral South Indian". 

I'm always skeptical of mixture models, especially when the putative source populations no longer exist. There are just too many ways that structured migration or dispersal can lead to the appearance of mixture. People once thought of "Alpines" as a mixture of pure Nordic and Mediterranean elements, after all-- and that was just because their heads were mesocephalic. 

Still, with a half-million SNPs, it's possible to do a better job testing the hypothesis of mixture versus structured migration. The authors in this paper didn't -- they applied a simplified "3 Population Test" that compares the empirical allele frequencies to proportions expected under only two scenarios: simple mixture or complete isolation. It seems to me that the null should be simple isolation by distance, which would give the same result as "mixture" according to their test. If you really want to look for population mixture, you need to involve the dimension of time, for example, by demonstrating the antiquity of haplotypes that have mixed together. 

So I don't accept this ancestral division, certainly not at face value. It does seem plausible that West Asian (and thereby European-related) genes have introgressed into India over time, perhaps in association with the growth of high-density agricultural populations. Maybe some of this gene flow occurred under the influence of positive selection, but processes of elite dominance and differential growth may have been sufficient. 


<b>Regional differences</b>. The results show a greater degree of regional genetic differentiation in India than has been found for continental Europe. Still, with an <i>F</i><sub>ST</sub> of only 0.01, we're not talking about major population splits here. With that number, the subcontinent is closer to panmixia than one might expect for a region its size. The authors suggest that founder effects explain the regional differentiation: 

<blockquote>We propose that the high FST among Indian groups could be explained if many groups were founded by a few individuals, followed by limited gene flow. This hypothesis predicts that within groups, pairs of individuals will tend to have substantial stretches of the genome in which they share at least one allele at each SNP. We find signals of excess allele sharing in many groups (Supplementary Fig. 2), which as expected tend to occur in the groups that have the highest FST values from all others (P = 0.002 for a correlation). To estimate the age of founder events, we measured the genetic distance scale over which allele-sharing decays, and verified the robustness of our procedure by simulation (Supplementary Fig. 3). Six Indo-European- and Dravidian-speaking groups have evidence of founder events dating to more than 30 generations ago (Supplementary Fig. 2), including the Vysya at more than 100 generations ago (Fig. 2). Strong endogamy must have applied since then (average gene flow less than 1 in 30 per generation) to prevent the genetic signatures of founder events from being erased by gene flow. </blockquote>

I don't think that explanation works. With those times in generations, we're talking about events within the last 600-2000 years. Since all these calculations are done on the whole dataset assuming complete neutrality, I think we should look more closely at the distribution of LD across loci. It seems likely that some of the high-LD loci that appear to point to founder effects will actually be found to be selected. 

<b>Relationships of Indian to non-Indian populations</b>. One of the real problems of assuming a tree with no migration is that it leads to statements like this: 

<blockquote>[T]he ANI [ancestral North Indian] and CEU [HapMap European sample] form a clade, and further analysis shows that the Adygei, a Caucasian group, are an outgroup (Supplementary Note 4). Many Indian and European groups speak Indo-European languages, whereas the Adygei speak a Northwest Caucasian language. It is tempting to assume that the population ancestral to ANI and CEU spoke 'Proto-Indo-European', which has been reconstructed as ancestral to both Sanskrit and European languages, although we cannot be certain without a date for ANIASI mixture.</blockquote>

<i>Some</i> of the common ancestors of <i>some</i> living Europeans and <i>some</i> Indians were probably speakers of proto-Indo-European speakers. But we can easily refute the hypothesis that <i>all</i> of the common ancestors did so -- some of those common ancestors lived more than 40,000 years ago, as is well-known from the mtDNA chronology. The tree model with complete isolation does not explain the data. So as simple as it is -- and as well-used by Cavalli-Sforza and others -- it would be better to use a more accurate model. 

UPDATE (2009-09-24): Gene Expression has <a href="http://scienceblogs.com/gnxp/2009/09/south_asians_as_a_hybrid_popul.php">a full review of the paper</a>.

UPDATE (2009-09-27): Very interesting angle by Suvrat Kher at <a href="http://suvratk.blogspot.com/2009/09/genetic-ancestry-of-indians-new-paper.html">Reporting on a Revolution</a>: 

<blockquote>The Indian Press has made a hash of the finding....</blockquote>

<blockquote>But I can't blame the press entirely. The scientists who gave interviews to the press didn't mention this. They wimped out on reporting this potential inflammatory and politically incorrect finding. This is just poor and irresponsible science outreach on part of the scientists. How can you ignore a finding that is staring out at you from the very paper you are talking about? The press may be guilty of not digging in but it was just reporting what the scientists told them.</blockquote>

<h4>References:</h4>

<p class="cite">Reich D, Thangaraj K, Patterson N, Price AL, Singh L. 2009. Reconstructing Indian population history. Nature 461:489-494. <a href="http://dx.doi.org/10.1038/nature08365">doi:10.1038/nature08365</a></p>





