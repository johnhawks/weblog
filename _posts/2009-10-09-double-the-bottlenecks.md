---
layout: single 
title: "Double the bottlenecks" 
category: story
permalink: /weblog/reviews/genetics/mtdna_migrations/amos-hoffman-two-bottlenecks-str-2009.html
tags: [demography, STRs, bottlenecks] 
comments: false 
author: John Hawks 
---


Amos and Hoffman (2009) describe a study of microsatellite (STR) data taken from 53 populations -- the HGDP dataset. They suggest that the worldwide diversity of STR loci is consistent with a double-bottleneck population history: An initial bottleneck accompanying a dispersal of humans from Africa some 50,000 years ago, followed by a second bottleneck as people moved into Beringia much later. Despite the cline of diversity across Eurasia leading to lower diversity farther from Africa, they do not see any evidence for successive (sequential) bottlenecks across this region. 

In general, I think that people are going farther than the data on this question of human migrations. Even considering only 53 population samples, there are thousands of ways that they might have been connected to each other over time. Rarely does anybody test simple null hypotheses, like isolation by distance. Often they mix two or more distinct scenarios in an attempt to find a closer fit to data. The problem is that two or more distinct scenarios will <i>inevitably</i> provide a closer fit, merely by virtue of adding parameters. The question is whether the fit is <i>significantly</i> better. 

I find some things to like in this paper. They treat STR data in a better way than many other studies, and I think they've done the right thing in examining the question of heterozygosity versus allele number. That statistic is worth more consideration. 

From their introduction: 

<blockquote>The question of how many bottlenecks account for the distribution of modern human diversity has been relatively little studied (Rogers & Harpending 1992) and yields conflicting results. First, simulations indicate that the observed pattern is consistent with a linear stepping-stone model featuring a long series of founder events (Ramachandran et al. 2005; Liu et al. 2006). However, this does not preclude equally good fits based on other models. Equally, at the other extreme, large steps in single nucleotide polymorphism diversity between adjacent populations have been used to argue for two dominant bottlenecks, one out of Africa and one around the Bering land bridge where humans crossed into the Americas (Hellenthal et al. 2008). The latter event is supported by both mitochondrial data (Wallace et al. 1985; Fagundes et al. 2008) and data from a few nuclear markers (Hey 2005). However, mitochondrial sequences only inform on female lineages, while the adjacent population approach is least reliable in regions like the Bering Strait where population samples are extremely sparse.</blockquote>

They make a good point here: that "other models" may produce "equally good fits." That is a routine problem in "modern human origins" research -- alternative models are rarely evaluated, and people almost never take a null hypothesis testing approach. 

I've always been hesitant to give much credence to demographic studies based on microsatellites. The evidence for mutation-drift disequilibrium in a stepwise mutation model is an unusual pattern of variance among the individual length variances of STR loci. That's a complicated statistic, and it responds poorly to deviations from the pure stepwise mutation model. In particular, any constraints on allele length will eliminate outliers in allele length variance, making the population look like it went through a bottleneck of some kind. 

The current study looks for disequilibrium in the relation of heterozygosity to allele number -- the logic being that a population crash will eliminate rare alleles but not common ones, leaving heterozygosity nearly the same but cutting allele number substantially. They also are explicit about the problems of the stepwise mutation model: 

<blockquote>One problem with the Bottleneck test is that microsatellites do not follow a strict SMM. Known deviations include mutation biases favouring expansion or contraction (Xu et al. 2000), interruption mutations within the repeat tract that slow the rate of slippage (Jin et al. 1996; Kruglyak et al. 1998), occasional larger jump mutations of several repeat units (Di Rienzo et al. 1994; Schltterer et al. 1998) and some form of upper length boundary that prevents indefinite expansion (Amos & Clarke 2008).</blockquote>

They go on to argue that their test is less susceptible to deviations in the mutation model. That claim deserves further evaluation. The information they provide about the pattern of variation of different classes of STR loci is useful, as it points to ways that the mutation model may have influenced the appearance of a bottleneck. But since they find "strong and consistent evidence of a bottleneck at the lowest variability loci." Given a correlation between diversity and strength of evidence of a bottleneck, and remembering that the signature of a bottleneck in their test is <i>high</i> diversity per allele, I would want to look for some mechanical explanation for the correlation. 

A (possibly additional) problem: The number of rare alleles within any single subpopulation is rapidly increased by migration from other subpopulations. All you need is a single migrant to bring in a new allele from somewhere else, and you've got another allele. Now, obviously this allele may not be sampled in any given dataset, so you have to account for sampling. But the point remains: it doesn't take much migration to increase allele numbers. 

Migration after any bottlenecks should, then, hide the evidence for them. It's not hard to imagine scenarios equally consistent with the data. For example, if every different population underwent a single bottleneck simultaneously, they would be unlikely to lose the same rare alleles, but would retain nearly the same heterozygosity. As migration resumed between them after the bottleneck, the rare alleles would be replenished in a way the reflects the subsequent migration rate and population size (the same number of migrants has a faster effect on allele frequencies in a smaller population). 

Or, if there were any interaction between a single bottlenecked ("founder") population and other <i>pre-existing</i> populations, it would tend to reduce the sign of a bottleneck. It seems plausible that the data in this paper might be explained by such interactions in South or East Asia, providing them with a store of rare alleles that didn't make it to the Near East. 

This is why it's useful to start simple. The simplest model in this case would include migration and expansion (which we know from non-genetic evidence happened) and no bottlenecks. Plumb these parameters to see if any acceptable fits turn up. They do with the question of the heterozygosity cline alone -- a simple trend of directionally biased migration is sufficient for that. Looking at the allele number together with the heterozygosity may reject that model, in which case you'd want to pick out the next simplest. In that sense, mtDNA may actually be giving more information than the hundreds of STR loci, because with mtDNA clades there is a way to estimate haplotype ages -- meaning that the demographic hypothesis must give rise to those haplotype ages in addition to the geographic dispersion of haplotypes and within-subpopulation diversity. 

<h4>References:</h4>

<p class="cite">Amos W, Hoffman JI. 2009. Evidence that two main bottleneck events shaped modern human genetic diversity. Proc R Soc Lond B (online) <a href="http://dx.doi.org/10.1098/rspb.2009.1473">doi:10.1098/rspb.2009.1473</a></p>



