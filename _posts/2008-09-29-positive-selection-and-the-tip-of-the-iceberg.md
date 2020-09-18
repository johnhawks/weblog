---
layout: single 
title: "Positive selection and the tip of the iceberg" 
category: story
permalink: /weblog/topics/evolution/selection/johansson-gyllensten-2008-detecting-selection.html
tags: [Fst, HapMap, natural selection] 
comments: false 
author: John Hawks 
---


Razib <a href="http://scienceblogs.com/gnxp/2008/09/selectives_sweeps_and_the_alle.php">points to a new paper by Johansson and Gyllensten</a>, in which they develop a comparison of <i>F</i><sub>ST</sub> and haplotype block length as a test of positive selection. The <a href="http://dx.doi.org/10.1111/j.2008.0018-0661.02054.x">paper</a> is interesting enough (and open access) -- they give a list of a few variants that are likely selected in different populations. 

What I wanted to point to was this figure:


<div class="middle-picture">
<img src="/graphics/johansson-gyllensten-selection-plot.png" width="500" height="462" alt="Selection versus drift, Johansson and Gyllensten 2008" />
</div>

That pretty much encapsulates the problem of detecting recent positive selection, with current methods. The distribution of selected alleles looks significantly different from the distribution of neutral alleles, but there is a tremendous overlap. Particularly when it comes to choosing an arbitrary cutoff between the two distributions. 

Imagine if you had a sample of men and women, and you chose an arbitrary cutoff of stature to distinguish them. Say, everyone over 5 foot 7 is a man. Well, that will do better than chance, but you've included a lot of women in your sample of men, and vice versa. Now, suppose you thought that men were <i>inherently rare</i> compared to women. Say, 100 women for every man. A cutoff of 5 foot 7 inches is going to include many more false positives (i.e., tall women) than genuine men. So you choose a very conservative cutoff, one that is not likely to include very many women. Maybe 6 foot 5. The people you see who are over 6 foot 5 are extremely likely to be men -- not certainly, you still will catch some very tall women -- but quite likely men. But you've excluded 95 percent of the men to do this. 

That's the situation we are in with respect to detecting selection. There is an enormous set of false <i>negatives</i> -- truly selected alleles that are indistinguishable <b>by means of an arbitrary cutoff</b> from neutral alleles. In the figure above, Johansson and Gyllensten suppose that each ascertained variant (at <i>s</i>=0.01) represents almost 5 in the population. So far, few have made much of the point that a small number of selected alleles under a very stringent cutoff must correspond to a large number that don't make the cutoff. (our 2007 paper being an exception). The issue is not only ascertainment; it is the shape of the non-ascertained distribution. 

Still, one may hope to do better at identifying selected alleles. So far, people have been hacking at these statistical distributions with a hatchet. We need a scalpel. 



<h4>References:</h4>

<p class="cite">Johansson A, Gyllensten U. 2008. Identification of local selective sweeps in human popluations since the exodus from Africa. Hereditas 145:126-137. <a href="http://dx.doi.org/10.1111/j.2008.0018-0661.02054.x">doi:10.1111/j.2008.0018-0661.02054.x</a></p>

