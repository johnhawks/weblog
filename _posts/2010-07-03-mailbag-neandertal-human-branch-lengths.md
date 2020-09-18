---
layout: single 
title: "Mailbag: Neandertal-human branch lengths" 
category: mailbag
permalink: /weblog/mailbag/neandertal-branch-lengths-substitutions-2010.html
tags: [Neandertal DNA] 
comments: false 
author: John Hawks 
---

<blockquote>In their recent paper (1, p.13) Prfer et al. are quite explicit about how they estimate the average divergence age for the human/Neanderthal lineages; assuming no differences in substitution rate, they use:
 
  Age = Hs/(Hs+Cs) D
 
where:
 
  Hs = human lineage specific changes, i.e. changes that are only seen in human (Neandertal and chimpanzee being equal)
  Cs = chimpanzee specific changes, i.e. changes that are only seen in chimpanzee (human and Neandertal being equal)
  D  = 2  average divergence between human and chimpanzee in million years
 
It seems to me that because of the implied sister group relationship between human and Neanderthal, another relatively independent estimate for the same split age could be obtained as:
 
  Age = Ns/(Ns+Cs) D
 
where:
 
  Ns = Neanderthal lineage specific changes, i.e. changes that are only seen in Neanderthal (human and chimpanzee being equal)
 
I don't see any mention of this possibility in the paper.
If this alternative estimate is valid, the disagreement between the two age estimates might provide some measure of the uncertainty due to the underlying assumption about equal substitution rates.
Apologies about wasting your time if these are just the faulty reflections of an amateur!</blockquote>

You're correct, this is mathematically equivalent and would work in theory. The practical problem is the large amount of DNA damage and base misincorporations in the Neandertal sequence. At present, roughly 9/10 of the Neandertal-specific changes are actually false positives. This means that the N branch would look artificially long according to the equation you give, because the C-(HN) branch is not similarly affected. 

The advantage of looking at the H-specific branch is that any given site has only a 1% chance of a false positive on the N branch. That's an acceptable error rate for estimation of the branch lengths.  

In the end, this will be fixed by multiplex coverage. At present, I'm going through the N genome draft to look specifically at areas with multiple reads to find genuine N changes. It's only a small fraction of the genome that we can trust them at present, I'm afraid. 

