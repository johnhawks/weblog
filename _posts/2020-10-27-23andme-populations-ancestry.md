---
layout: single
title: "An update to the 23andMe ancestry algorithm, how populations are constructed"
description: "Looking at the invention of races from the point of view of genotypes."
category: story
permalink: /weblog/topics/biotech/testing/23andme-ancestry-algorithm-boxcars-2020.html
tags: [23andMe, ancestry, genomics, testing, race]
comments: false
author: John Hawks
---


The genomics testing company 23andMe has come out with a new algorithm for ancestry assignment from their SNP panel. They describe the new procedure in a blog post: <a href="https://blog.23andme.com/ancestry-reports/algorithm-gets-an-upgrade/">"The 23andMe Ancestry Algorithm Gets an Upgrade"</a>. 

I find that the blog post is a helpful short explanation for how ancestry assignment algorithms work. The authors use the analogy of the genome as a train, and small segments of the genome as "boxcars". To give the method in brief, the genome is divided up into around 2000 segments, and then a matching algorithm examines whether an individual's genotypes in each segment match the comparison set of 45 population samples from different parts of the world. The algorithm then does a second pass in which neighboring segments that differ are re-evaluated to see if they may work together to make a stronger fit than they do when considered separately. 

This is all straightforward. What struck me upon reading the post is how this procedure boils down to an invention of races. 

For instance, when neighboring segments match different comparative samples that are geographically near each other, the algorithm assigns the segments to a higher-level in a population hierarchy: a regional population. 

<blockquote>Or, say there’s a stretch of boxcars that don’t match either Ethiopian or Sudanese with high confidence. Here, the smoother can “zoom out” to a broader population called “Northern East African,” at which point it will be highly confident in that assignment.</blockquote>

There's an irony in being "highly confident" in cases where the data do not match any of the comparative samples well enough to make an assignment. The regional populations actually don't exist in the comparative sample; they are constructed statistically to account for certain kinds of mismatches in the data. 

All of this is true of both the new and old algorithms. The authors describe the difference between new and old algorithms in terms of the training set. Some of the regional population assignments made by the old algorithm came from being trained on a set of test genomes. The idea was that examining identity mismatches between neighboring segments in many real genomes would generate likelihoods of similar kinds of mismatches in a target genome. The new algorithm does away with this training on other people's genomes and instead considers the pattern of ancestry matches and mismatches within the target genome as a training set for improving assignment of segments. As a result, according to the blog post, the new algorithm will less often assign segments to a regional population and will more often match it to the specific samples in the comparative set. 

For my own data, I don't think there is much difference when looking at the results from the new algorithm. One thing I notice consistently is that the chromosome ideogram display of my ancestry information portrays much greater uniformity across stretches of chromosome than probably exists in my genome. For instance, I'm estimated to be roughly 40% British/Irish and 34% French/German, which is close to what genealogical data would indicate for me. But the ideogram displays a full copy of chromosome 2 as British/Irish, and a full copy as French/German, which is very unlikely from my genealogical data. The boxcars here seem to have been oversimplified. 

Some oversimplification is good. Chromosome 2 is around 242 million base pairs long, which makes it around 8 percent of the genome. It should have around 160 of the 2000 "boxcars" of the genome. The noise of genetic variation within any one population is likely to make some of those segments look like better fits to other populations, even if my ancestry was entirely from a single population. But this approach is going to make medium-range genealogy look more homogeneous than it really is, and obscure some of the deeper-range mixture of populations. 





