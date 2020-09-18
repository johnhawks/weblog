---
layout: single 
title: "Sergey Gavrilets on the two fitness landscapes" 
category: story
permalink: /weblog/topics/evolution/selection/gavrilets-fitness-landscape-metaphor-2009.html
tags: [Sewall Wright, population genetics, R. A. Fisher, fitness] 
comments: false 
author: John Hawks 
---

Sewall Wright's metaphor of the "fitness landscape" is fundamental in the way many biologists think about adaptation. The idea of a population "climbing" toward "adaptive peaks" is a visually compelling image for the increase in mean fitness that results from selection on many genes. 

However, the correspondence between this metaphor and the mathematics of population genetics leaves several ambiguities that tend to confuse people. One of the main sources of ambiguity concerns the meaning of the spatial dimensions in the fitness landscape. Do the dimensions represent the frequencies of alleles in the population? Or do they represent particular genotypes that individuals may have? Wright used mathematics that implied both approaches in different places. For purposes of metaphorical visualization, the difference between these perspectives may not matter. But if we want to guide our thinking about the evolutionary process, it's helpful to know where real-life cases are supposed to fit. 


Sergey Gavrilets' book, <a href="http://www.amazon.com/gp/product/069111983X?ie=UTF8&tag=johnhawksanth-20&linkCode=as2&camp=1789&creative=390957&creativeASIN=069111983X"><i>Fitness Landscapes and the Origin of Species</i></a> takes on this problem in chapter 2. This post comes from my notes about the book, which I read some time ago. So although I've brushed them up, many holes remain -- think of it as a synopsis of points I found worth noting. What I don't have is a thesis -- in case you're wondering why you should care. 

For me (and many others), the most important aspect of Gavrilets' work is the demonstration that a "rugged" landscape does not exist if we consider a sufficiently high number of interacting genotypes. The genomes of organisms, from <i>E. coli</i> to humans, don't have that many genes, but the number of combinations among only 1000 biallelic genes is so large that Wright's "rugged landscape" analogy may never apply to them. Never mind our 20,000 multiallelic genes. I'll return to that issue another time, because this question of genomic searches has shaped my thinking about mutation-limited evolution and recent selection.
<!--break-->
In the meantime, back to the fitness landscape metaphor. 

Gavrilets describes two competing mathematical versions of fitness landscape: (1) Fitness landscape as relationship between genotypes and fitness of individuals, and (2) fitness landscape as relationship between genotype frequencies and the mean fitness of the population. In the first, the space is defined by the genotypes, and is therefore discrete. Two neighboring genotypes may have very different fitnesses -- even extremely so, since a single mutation might be lethal. In the second, the space is defined by the possible states of the population, and is (for sufficiently large populations) approximately continuous. Two nearby combinations of frequencies are likely to have nearly the same mean fitnesses. 

After the descriptions, he comes to the issue of whether the two versions are consistent or commensurable with each other. He comes to several very powerful arguments why the mean fitness version of the landscape is not useful for considering evolution across many loci (pp. 31-33): 

<blockquote>I note that [the mean fitness] version of fitness landscapes is often defined as a relationship between the allele (or gene) frequencies in a population and its mean fitness (e.g., Coyne et al. 1997; Fear and Price 1988; Arnold et al. 2001). Because allele frequencies in general are not sufficient for specifying the mean fitness of populations (unless fitness is additive or selection is very weak relative to recombination, so that linkage disequilibrium can be completely neglected), this definition is, strictly speaking, meaningless in multilocus systems. </blockquote>

To take a concrete case, recent human evolution has involved selection on many genes which interact both with each other and with environments. In the set of genes that have responded to this selection, dominance and overdominance effects are likely. For example, new adaptive mutations are much more likely to escape drift if they are dominant in effect. Also, in this context, the number of genes and strength of selection are large enough that we probably cannot neglect linkage. The probability that a <i>allele</i> would have become more common in this population depends on the fitness of the <i>genotypes</i> that include it, and the correlation between these and other genotypes.

<blockquote>Another common misconception is that the two versions of fitness landscapes are "wholly incompatible" (e.g., Provine 1986 [this is Provine's history of population genetics]). Yet, it is straightforward to find mathematically the average fitness of the population ... if one knows the individual fitnesses. That is, the first version can be transformed into the second version in a straightforward manner. However, knowing [the mean fitness] indeed does not allow one to find individual fitnesses.</blockquote>

So the first version appears useful because you can find the mean fitness if you want for any possible frequencies of genotypes. The second version loses information because you can't work back from the population mean to the individual fitnesses of genotypes.

<blockquote>Evolutionary dynamics of populations on fitness landscapes is a very complex process. In general, all relevant evolutionary factors (e.g., natural and sexual selection, random genetic drift, mutation, spatial structure and migration, environmental variability) and their interactions are expected to play important roles. Excluding some special cases (e.g., one-locus models of viability selection), the feature and patterns of evolutionary dynamics cannot be captured or predicted on the basis of any single characteristic such as the mean fitness. Indeed, it is well known that the mean fitness of the population does not necessarily increase and there are no general multilocus analogs of Wright's equations [predicting changes in frequency for a single locus] that do not rely on rather strong approximations [citations omitted]. Therefore, this second version of fitness landscapes is not particularly useful in a multilocus context and for modeling speciation. </blockquote>

That's Gavrilets' aim in the book, so it makes sense for him to lay out that reason for avoiding the second version of fitness landscapes. 

But, does that criticism have more general force? I find the next sentences more persuasive: 

<blockquote>The dimensionality of fitness landscapes in this version is very high and increases exponentially rather than linearly with the number of loci. Moreover, even with a relatively small number of loci, the number of possible genotypes is much larger than any reasonable population size. This implies that most genotype frequencies will be equal to zero. In this case, describing populations by listing genotype frequencies becomes equivalent to listing all genotypes present, which is exactly what is done in the first version of fitness landscapes.</blockquote>

Keep in mind that "genotype frequencies" here refers to the frequencies of multilocus genotypes, across very large sets of loci. A large number of genotypes at different loci can be combined in an extremely large number of ways -- many more than the number of individuals in natural populations. This is the principle behind DNA fingerprinting -- it only takes a couple of dozen multiallelic loci before the probability of two different individuals sharing genotypes converges on zero. 

These are persuasive arguments why the mean fitness interpretation of a fitness landscape doesn't help very much in considering evolution in a multilocus sense. Multilocus genotypes tend to be absent from the population, and probably even more important, independent assortment means that they don't reproduce themselves.

But if we interpret the fitness landscape as representing the fitness of genotypes, then we can discuss the movement of a <i>population</i> on the landscape only under very constrained circumstances. The "strong selection, weak mutation" model of change (first explicitly discussed by Gillespie) predicts that a population can explore only very small parts of the fitness space from any given location. In that model, the entire population will move to a nearby combination of genotypes, wait for a while until a better mutation can occur, and then move again. Evolution in this model proceeds stepwise through a clear sequence of genotypes, and is mutation-limited not only as regards any single trait, but in fact across all traits. 

By contrast, if selection is weak and mutation is strong, then <i>individuals</i> in the population may occupy far-off locations in the fitness space, and the entire population is smeared across a large region of that space. On the surface, it might seem that evolution in such a population would be more deterministic, because the waiting time to beneficial mutations is much lower. But with many beneficial genotypes available to the population at any given time, the rate and direction of evolution are still affected strongly by stochasticity/ 


<h4>Metaphors</h4>

Next, Gavrilets describes the <i>metaphor</i> of a fitness landscape as a different issue from the <i>mathematical description</i> of a fitness landscape. The metaphorical version of a fitness landscape is the conventional textbook illustration: one fitness axis varies continuously against a two-dimensional genotype space. Neither the units nor the identities of the genotype dimensions are specified. The metaphor functions as an aid to imagination: Mean fitness changes as a hill-climbing function, without implying any specific idea of <i>how much</i> fitness should change as genotypes change. If you wanted some predictive qualities, you would need to specify the dimensions mathematically. 

Two issues arise with the metaphorical use of fitness landscapes. First, is the metaphor useful at all? 

Gavrilets implies that this distinction doesn't really matter -- that it is an error to try to interpret the metaphor of a fitness landscape in terms of mathematics, when the purpose of the metaphor is to illustrate broad potentialities instead of specific predictions. 

I don't really agree. I think that people familiar with the metaphor are consistently misdirected toward the mean fitness/allele frequency version (that is, Gavrilets' second mathematical version) of the fitness landscape. There are two qualities of the metaphor that lead to this natural conclusion. First, the "genotype dimensions" of the metaphor are continuous, and delimited on both ends. Second, the fitness function, whether drawn as rugged or smooth, is always continuous. Nearby locations on the spatial axes always have nearby fitnesses, without apparent discontinuities. <b>An array of genotypes would not have this quality</b>. Many lethal sequences differ by only one mutation from highly fit ones. In general, there's no reason to expect neighboring genotypes to have nearby fitnesses unless some kind of rank ordering were presupposed. Besides that, if we were considering an indefinitely large number of genotypes, we wouldn't use two spatial axes. It may be a mistake to judge the metaphor in mathematical terms, but if so, I suggest that the metaphor generates more confusion than the math. 

From Gavrilets' discussion of the "rugged fitness landscape", I think he agrees that the metaphor misleads in just this way.

<blockquote>The value of Wright's metaphor is that it attempts to explain something very complex (multidimensional fitness landscapes and evolutionary dynamics) using something that everybody has a close knowledge of -- geographic landscapes. The view of rugged landscapes explicitly emphasizes the existence of different alternative solutions (alternative fitness peaks) to the problem of survival. In most three-dimensional fitness landscapes, peaks are isolated and there is no way to get from one peak to another without first descending to some valley. The metaphor of rugged fitness landscapes imposes a belief that the same is true in multidimensional fitness landscapes (36).</blockquote>


But the rest of Gavrilets' work is a demonstration that highly multidimensional fitness landscapes <i>don't</i> have this intuitive three-dimensional shape. It's not obvious to me that the genotype fitness metaphor informs us either, because the strong selection/weak mutation model does not apply to most populations with sufficient fidelity to make evolution look like a simple directed walk through a series of genotypes. Understanding the dynamics requires us to consider how the population's mean fitness evolves, yet Fisher and Wright both had recourse to extreme simplifying assumptions about the relationship of mean fitness and the fitnesses of genotypes. 

Problems, problems...



<h4>References:</h4>

<p class="cite">Gavrilets S. 2004. Fitness landscapes and the origin of species. Princeton University Press, Princeton NJ. <a href="http://www.amazon.com/gp/product/069111983X?ie=UTF8&tag=johnhawksanth-20&linkCode=as2&camp=1789&creative=390957&creativeASIN=069111983X">Amazon</a></p>.

