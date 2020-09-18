---
layout: single 
title: "Were ancient Africans divided into small, isolated bands?" 
description: "Revisiting a paper that claims an African bottleneck, I examine the subject of population structure" 
category: story
permalink: /weblog/reviews/genetics/mtdna_migrations/behar-mtdna-population-structure-2008.html
tags: [migrations, Africa, out-of-Africa, population structure, demography, mtDNA, effective population size] 
comments: false 
author: John Hawks 
---

<p>
Last week when <a href="http://johnhawks.net/weblog/reviews/genetics/mtdna_migrations/sub-saharan-africa-population-size-behar-2008.html">I wrote about the study of African mtDNA variation</a> by Behar and colleagues, I focused on the issue of population size. To me, that must be the first parameter that we try to estimate, because the simplest relevant model of population history -- the Wright-Fisher model -- is described by that single parameter: the number of individuals. If we are going to evaluate evidence for population structure, we first must deal with the question of size. 
</p>

<p>
The claim <a href="http://www.eurekalert.org/pub_releases/2008-04/ngs-dom042308.php">in the press release</a> is that the African population was divided into separate populations:
</p>

<blockquote>Doron Behar, Rambam Medical Center, Haifa, said: "We see strong evidence of ancient population splits beginning as early as 150,000 years ago, probably giving rise to separate populations localized to Eastern and Southern Africa. It was only around 40,000 years ago that they became part of a single pan-African population, reunited after as much as 100,000 years apart."</blockquote>

<p>
Is it true? Certainly that describes the model tested in the paper. But is it the right model? Is there evidence to justify that model as opposed to simpler alternatives?
</p>

<p>
A real population may be structured in many ways -- by age, by caste or class, by space. If we have samples that are taken from different geographic locations, as in this study, it is natural to test hypotheses about structuring across geography. That's what Behar and colleagues did: they tested a hypothesis of panmixia, or random mating across space. 
</p>

<p>
Panmixia is the simplest model -- the null hypothesis -- about population structure. If everyone mates randomly, then there is no geographic structure. The population would be a single, unstructured gene pool. The paper refutes this model, demonstrating that people did not mate randomly across the geography of Africa during a certain period of time. 
</p>

<p>
But the question is: which model do we adopt once we have refuted panmixia? 
</p>

<p>
I rather like isolation-by-distance as a model for human population history. Isolation-by-distance (IBD) assumes that people travel some distance before they reproduce. It's a simple model -- the distance traveled may vary among individuals, but the variance in this value is the only parameter necessary to predict the structure of the population. IBD can explain quite a lot -- why people look like their neighbors, why intermediate populations on the map tend to look intermediate in allele frequencies, and why selected alleles take some time to disperse across space. It is generally consistent with what we know about hunter-gatherer demography. People tend to stay where they are, but a fairly large fraction move to marry into neighboring groups, and a smaller fraction go beyond the neighboring groups to marry further away. So I think this is the null hypothesis once panmixia is refuted. IBD is not a hypothesis of small, isolated bands -- it is a hypothesis of a geographically dispersed population with gene flow. 
</p>

<p>
The Genographic Project has done more than any other single project to extend the sampling of human populations. The paper by Behar and colleagues is a testament to that -- they are able to work with a broader and deeper sampling of mitochondrial variation in Africa than has yet been available. This is a credit both to the ambitious goals of the project and to today's genetic technology, which has made it possible to sequence more whole mitochondrial genomes on the project's budget. It is a great example of how spending money can circumvent some theoretical problems. 
</p>

<p>
Still, the Project likely wanted to maximize the effectiveness of its money, so it focused on sequencing only those variants that were underrepresented or rare in previous studies. From the Methods:
</p>

<blockquote>Samples were chosen to include the widest possible range of Hg L(xM,N) internal variation on the basis of the previously available sequence analysis of the mtDNA control region and are, therefore, biased toward rare variants. In addition, we attempted to focus on branches (e.g., L0d, L0k), populations (e.g., Khoisan), and geographic regions (e.g., Chad) for which the current data were scant. Last, we preferred to sequence variants that the current literature suggested to be rare or anecdotal in any given geographic region (e.g., L0k in the Near East). </blockquote>

<p>
Ummm... wait a minute. This is definitely <i>not</i> what you want to do if you're going to test hypotheses of population history. They have deliberately narrowed their sample in a way that distinguishes Khoisan from other peoples, and have excluded some proportion of variants already known to be common. We can predict, based on the sampling scheme alone, that Khoisan and other people ought to be more distinct that would be expected under a random sampling of each population, and certainly more so than expected under a random sampling of the African continent. This means that if the data were to reject IBD, we would have to examine whether that was because of the population history, or instead because of the sampling scheme. 
</p>

<p>
Do the data reject IBD? Well, we don't actually know from the paper. The study employs an island model, in which Khoisan and all others are assumed to represent either one panmictic population or two isolated ones. They devised a test based on permuting the number of lineages that they inferred to have existed during past time intervals. An island model with isolation of two populations predicts that each will share some gene lineages lacking in the other -- so-called "private" haplotypes. In contrast, two samples taken from a single panmictic population would each have a small proportion of "private" haplotypes, as well as some number of common haplotypes shared by both samples. 
</p>

<p>
So, the study (reasonably) tests the null hypothesis that the African mtDNA samples derive from a single panmictic population going back to the mtDNA coalescent. They estimate the date of this coalescent (based on their mutation rate model) as around 200,000 years ago, so this is a test of panmixia in Africa across this time period. They use a permutation test to evaluate the likelihood that some number of closely related lineages would all be private to the Khoisan population, under the hypothesis that they are randomly drawn from the African population as a whole. The lineages they examine are the ones they infer to have been present in the Khoisan population at various time intervals in the past -- again, based on their model of mutation rate. They can disprove panmixia across times after 100,000 years and before 80,000 years. Before this time, too few coalescent lineages are inferred to have existed to obtain a significant refutation of the test of panmixia. After 40,000 years, there are obvious shared lineages between Khoisan and other samples that could only have been shared by gene flow. 
</p>

<p>
I worry that there is a bias in this test. The authors applied it only to a period of time earlier than the coalescence times of <i>recent</i> shared lineages, but after the diversification of the <i>ancient</i> lineages that are not shared. In other words, there <i>appeared</i> to be a gap in the coalescence times of shared haplogroups. Usually, you would correct the test for multiple comparisons not only across haplogroups, but also across time periods. Given that we are considering a range of 150,000 years, across which there is evidence for gene flow both early and late in that history, what is the significance of the fact that we see few shared lineages at intermediate times? That will be less significant than the values reported in the paper, but how much less it is difficult to predict. 
</p>

<p>
In the end, what do the observations in the paper mean? In the simplest interpretation, either Africans were not random-mating after 100,000 years ago or regional selection differentiated southern and other African mtDNA pools. 
</p>

<p>
Did ancient Africans live in two isolated groups? I wouldn't say that: the authors didn't test that hypothesis. 
</p>

<p>
Did ancient Africans live in small bands scattered across the continent? Well, <i>all</i> ancient humans lived in small bands. The question of whether they were scattered is a question about the population size -- and as <a href="http://johnhawks.net/weblog/reviews/genetics/mtdna_migrations/sub-saharan-africa-population-size-behar-2008.html">I showed last week</a>, the population size during this period of time was not small. So we can imagine a population structure like recent historic hunter-gatherers -- with Africa possibly having something like the population size and structure of indigenous Australians. 
</p>

<p>
What's the bottom line? The results are consistent with isolation-by-distance in ancient Africans. That model, followed by a subsequent global expansion, has been around for a long time. In 1993, Henry Harpending and colleagues called it the "Weak Garden of Eden" model: a geographically structured African population that underwent an expansion and dispersal to other regions. Certainly for the mitochondrial DNA, this seems to be the model that presently best fits the data. 
</p>

<p>
What remains in question is how much of the subsequent spread of mtDNA was also reflected by spread of nuclear DNA haplotypes, and how much was induced by natural selection on mtDNA haplogroups. As I continue to write about population histories, we will meet this issue again. 
</p>

<h4>References:</h4>

<p class="cite">Behar DM, 14 others, and The Genographic Consortium (consortium again? Whoa). 2008. The dawn of human matrilineal diversity. Am J Hum Genet 82:1-11. <a href="http://dx.doi.org/10.1016/j.ajhg.2008.04.002">doi:10.1016/j.ajhg.2008.04.002</a></p>


