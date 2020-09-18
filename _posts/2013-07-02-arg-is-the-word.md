---
layout: single 
title: "ARG is the word" 
category: quickbit
permalink: /weblog/topics/theory/population-genetics/siepel-ancestral recombination graph-2013.html
tags: [population structure, genomics, theory, population genetics] 
comments: false 
author: John Hawks 
---

Adam Siepel has written a very useful explainer about a new preprint he has posted with Matthew Rasmussen on the arXiv preprint server: <a href="http://haldanessieve.org/2013/07/02/our-paper-genome-wide-inference-of-ancestral-recombination-graphs/">"Our Paper: Genome-wide inference of ancestral recombination graphs"</a>. The paper and the post cover the obscure topic of ancestral recombination graphs (ARGs), the genome-wide equivalent of a phylogenetic tree. Siepel explains why the concept of the ARG is useful to biologists, and illustrates the difficult of actually inferring ARGs from genome-wide data. 

<blockquote>Viewing population genetics in terms of the ARG can clarify ones thinking about many problems of interest.  For instance, the ARG makes it clear that divergence times for genetically isolated populations can be estimated by looking across the ARG for the most recent coalescences that cross population boundaries.  Similarly, given an estimated divergence time, the rate of gene flow or migration between populations can be estimated, in a fairly straightforward manner, in terms of the rates of inter-population coalescence events across the ARG.  Ancestral effective population sizes can be estimated from the density of coalescence events in the ARG over time. Signatures of natural selection, including hitchhiking and background selection, can be detected by various kinds of local distortion of the ARG.  In general, the ARG provides a unifying framework for the field, and many challenging statistical problems in population genetics can properly be seen as problems of revealing relevant features of the ARG.</blockquote>

It's the best introduction to this subject that I have seen, explaining clearly why many population geneticists are forced to work with lower-order abstractions of data such as principal components, because of the conceptual and computational difficulty of the ARG.

