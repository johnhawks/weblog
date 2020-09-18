---
layout: single
title: "Are parsimony analyses better than Bayesian methods for phylogenetics?"
description: "Old-school parsimony seems better when the criterion is generating trees consistent with the stratigraphic order of fossils."
category: story
permalink: /weblog/topics/systematics/sansom-bayesian-parsimony-stratigraphy-2019.html
tags: [phylogenetics, systematics]
comments: false
modified: 2019-07-07
author: John Hawks
---


During the past few years, Bayesian approaches to phylogeny reconstruction have become more and more widespread, including analyses of fossil hominins. Among hominins, Bayesian approaches sometimes lead to very different results from parsimony, even when applied to exactly the same datasets.

That's a problem. As a field, we can put much more effort into building morphological datasets of fossils. The best existing datasets still have enormous holes and gaps---they are highly biased toward cranial and dental traits, and even these traits are underrepresented in published datasets compared to fossils that preserve the traits. Researchers who have tried to include some specimens in their analyses have actually been denied permission to study them, meaning that they must rely on published studies only, which exclude many traits. So there's much room to better document the fossil record that already exists.

Last year Robert Sansom and coworkers carried out a study to examine what difference it makes to use Bayesian methods versus parsimony upon the same datasets. Their conclusion is stated in their title: <a href="https://doi.org/10.1098/rsbl.2018.0263">"Parsimony, not Bayesian analysis, recovers more stratigraphically congruent phylogenetic trees"</a>.

Other scientists have looked at how these methods perform in generating phylogenetic trees for simulated data. In that artificial context, Bayesian methods do better than parsimony. But what about real data? Sansom and colleagues considered it possible that some aspects of real datasets make them different from the usual simulated datasets.

That's tough to test, because we don't know the <em>real phylogeny</em> in real datasets. But Sansom and coworkers looked at how the different methods perform with relation to the stratigraphic position of fossils --- testing for <em> stratigraphic consistency</em>. They found that Bayesian algorithms don't do so well:

<blockquote>Bayesian analyses yielded trees that were significantly less congruent with stratigraphic data. Given that the 167 empirical datasets were from a wide range of authors, clades, time periods and taxonomic levels, we can place confidence in the small but significant differences observed. Taking stratigraphic range data as a benchmark independent of morphology, therefore, indicates that parsimony should be preferred over Bayesian analyses, but these empirical results differ from simulation studies. We explore a few possible explanations for this discrepancy.</blockquote>

To be honest, the difference in performance between the two methods in this study is pretty slight. Both methods do badly in generating trees that are stratigraphically consistent. Parsimony was better in a statistical sense but the difference was not large. To me, the bottom line is that some real datasets have features that make Bayesian methods work badly, and others probably have features that make parsimony work badly (and many probably are unsuitable for both).

One thing that the study discusses is whether published trees and methods have already been biased by researchers who were <em>aiming for a particular solution</em>:

<blockquote>Cycles of revision and re-analysis of morphological data matrices during construction could lead practitioners to prioritize phylogenetic solutions that fit some preconceived ideas for final publication (either consciously or subconsciously), including stratigraphic fit. Under such circumstances, parsimony trees might exhibit artificially elevated stratigraphic congruence because parsimony is the historic default method used to evaluate morphological data. </blockquote>

From my experience with hominins, this kind of bias is a real possibility. Until the last few years, paleoanthropologists seemed to aim at a particular kind of phylogenetic hypothesis: one in which successive species in stratigraphic order are progressively more closely related to living humans. That's an intrinsically unlikely order for relationships to occur. Even though scientists <em>profess</em> to accept that human evolution was a tree, they still tend to arrange them as if they were a straight line.


<blockquote>In conclusion, our analyses demonstrate a clear result: Bayesian searches yield trees that have significantly lower stratigraphic congruence compared with trees from parsimony searches. We find little difference between parsimony using equal and implied character weighting—they are roughly comparable with respect to stratigraphic congruence. If stratigraphic congruence is taken as a benchmark for phylogenetic accuracy, then, maximum parsimony is the preferred method of choice for analysis of morphological data.</blockquote>

I'm not sure that stratigraphic congruence is anything that we should be aiming at. With hominins, it has become clear that relationships between lineages may have little to do with the age of the fossils.  I'm also dubious that any change in algorithm is going to bring us closer to the "real" phylogeny. As long as we have substantial missing data from specimens that have already been found, the algorithms are garbage-in-garbage-out.
