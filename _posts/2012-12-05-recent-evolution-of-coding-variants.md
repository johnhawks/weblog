---
layout: single 
title: "Recent evolution of coding variants" 
description: "Probing the pattern of noncoding rare variation in whole exome data." 
category: story
permalink: /weblog/reviews/genomics/selection/fu-2012-mutation-ages-europeans-africans.html
tags: [Europe, Africa, recent evolution, Holocene, acceleration, fitness effects, mutation] 
comments: false 
author: John Hawks 
---

How did I get myself quoted in a story as the <em>skeptic</em> about recent human evolution? (<a href="http://www.wired.com/wiredscience/2012/11/recent-human-evolution-2/">"Human Evolution Enters an Exciting New Phase"</a>). After all, I've been a huge advocate of the idea that recent human evolution was a lot faster and more interesting than anthropologists used to think (<a href="http://johnhawks.net/weblog/topics/evolution/selection/acceleration/accel_story_2007.html">"Why human evolution accelerated"</a>). 

The story, by Brandom Keim, is a good account of a new paper in <em>Nature</em> by Wenqing Fu and colleagues, "Analysis of 6,515 exomes reveals the recent origin of most human protein-coding variants" <bib>Fu:exomes:2012</bib>. It's a pretty cool study, which has identified protein-coding alleles in large samples of European-American and African-American individuals. 

Fu and colleagues compared all the coding variants they found in large samples of European-Americans and African-Americans, and discovered that the European-ancestry people have a higher fraction of rare coding variants. They propose that the rate of new coding variants entering and persisting within the population actually accelerated in the ancestral European population. Why would this happen? In their view, demography is the most likely explanation. As European populations expanded during the Neolithic and later time periods, the rate by which new mutations are lost by genetic drift began to decline. These new mutations have pooled up within the European population, giving them a glut of new changes to protein-coding sequences. Many of these mutations may be deleterious, just not bad enough for natural selection to have weeded them out in the growing ancient population. 

I think in large part this explanation is correct. In some ways it is incomplete. 

The effect of population history on our evolution was the theme of our 2007 paper on positive selection in recent humans <bib>accel</bib>. We relied on exactly the same mathematical relations used in this new paper: More people means more different mutations entering the population. In our case, the increase in the total number of mutations meant that we could expect more potential adaptive mutations to be selected within a growing population. In this case, the increase in the total number of mutations means more mutations remain to be picked up by resequencing rare neutral or deleterious variations in present samples. 

One of the senior authors of the study, Joshua Akey, commented: 

<blockquote>Most of the mutations that we found arose in the last 200 generations or so. There hasnt been much time for random change or deterministic change through natural selection. We have a repository of all this new variation for humanity to use as a substrate. In a way, were more evolvable now than at any time in our history.</blockquote>

(this is quoted by <a href="http://wp.stockton.edu/gfb1/2012/12/01/humans-are-more-evolvable-now-than-at-any-time-in-history/">Punnett Square</a>, not sure about the original source)

That's a cool concept. These rare protein-coding variations may be mostly unimportant to fitness today, and many are slightly deleterious. Still they provide a store of variability that increases the potential range of responses to future adaptive challenges. Or, they give us room to examine the effects of small differences, which will help us to understand better how genes work. For the past few thousand years, a small proportion of those have come under positive selection, the part that we have been studying in my lab since 2007. 

The current study has some drawbacks. For one, it isn't evident from the results how these new coding mutations are distributed among individuals. Under population growth alone, we should expect that the number of these new coding variants carried by any one individual should be approximately the same as any other individual, regardless of the population size. Where a big population differs from a small population is in the variety of mutations carried by different individuals, with the average number per individual being equal. That may be true in this study, but it isn't possible to tell from the results presented. 

To the extent that some of these mutations are deleterious, their distribution matters. In Europeans, there may be a greater number of deleterious mutations that are on average more rare; all things being equal, this pattern should make it harder to find statistical evidence for association of these rare variants with complex disorders. By contrast, in Africans, the higher average frequencies of such variants should make them easier to tie to phenotypic variation. All this can be concluded from frequencies alone, without a need to relate frequency to age.

Probably the biggest shortcoming of the paper is in its estimation of ages for these rare mutational variants. Estimating the ages of mutations in human populations has been a real problem for those of us working with genotyping or sequencing data from small samples. When we depend on the linkage between a rare allele and nearby genetic loci, we run into a sampling problem: Estimating the proportion of recombinants in a population fundamentally has a lot of error when you are working with a sample of 10 copies of the rare allele. 

Estimating dates by LD is bad enough, but this paper doesn't even go that far. Instead, it estimates the ages of alleles from their frequency. 

Frequency estimation of age is OK if the genome sequences have come from a Wright-Fisher population (that is, a random-mating, constant size population). More common alleles tend to be older, new alleles tend to be very rare. This isn't a very accurate means of dating any particular mutation, because the relationship of age and frequency under genetic drift has a tremendous variance. But when pooling large sets of alleles into frequency classes, the age-by-frequency approach gives a rough idea of whether mutations have accelerated or stayed at a constant rate over time. 

But there's one obvious thing missing from the model that may have a large effect on the frequencies of rare coding variants: Introgression from Neandertals! If we want to know why Europeans have a large store of rare coding variants relative to Africans, their ancient mixture of a small fraction of a very divergent human population is one obvious reason. None of the Neandertal alleles in Europeans today are new, they are all old. But a method that estimates their ages by allele frequency alone will always conclude that these rare Neandertal alleles are very young. 

In the current paper, the relation of frequency and age is derived from simulations that are based on a model of human population history. Like all recent papers that apply a model of human population history, this one is both overcomplicated (lots of parameters to which we have no good estimates) and oversimplified (too few events to accommodate known historical phenomena). Here's the population model used to derive allele ages in the paper: 

<div class="middle-picture">
<img src="/graphics/fu-2012-population-model.png" alt="Population model from Fu et al. 2012" />
<p class="caption">Population model from Figure S5 in the supplementary information from Fu et al. 2012</p>
</div>

The parameters for population divergence times and ancient population sizes are estimated from genetic data, so any systematic error will propagate through to the estimation of allele ages. The exclusion of Neandertal introgression in the model really does bias the allele age estimates badly, as Neandertal genes today are mostly rare, and mostly very old. This year's shift in our assumptions about mutation rates (to a much slower rate than previously assumed) will also affect the estimates of the demographic parameters in the model. An older coalescence time for most genes means a larger ancestral effective size for these populations, and much older allele ages when frequency is the estimator. 

Our lab is working very hard on allele ages, and I hope to be able to share some of that work soon. 

This study is not alone in demonstrating the real importance of rare coding variation in human populations. This line of research has substantial value, as it helps to show why so much of the additive genetic variation underlying variation in human phenotypes has not yet been assigned to genes. We know that many traits are heritable by comparing genetic relatives with each other. Finding the genetic loci that explain similarity among relatives is relatively easy when the genes involved are common, because the same gene variants will be shared across many families. But pooling many families doesn't help us find very rare mutations, as these are likely carried only by a few pedigrees even in a very large sample. By showing the large store of rare coding variation, these studies help to establish that much of the genetic variation underlying disease may be there for us to discover, if we change our discovery approach. 



