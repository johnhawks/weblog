---
layout: single 
title: "R. A. Fisher&#39;s model of adaptation" 
category: story
permalink: /weblog/topics/evolution/fisher/fisher-adaptation-geometric-model-2009.html
tags: [history of genetics, population genetics, R. A. Fisher, selection, evolutionary theory] 
comments: false 
author: John Hawks 
---

Chapter 2 of R. A. Fisher's <i>Genetical Theory of Natural Selection</i> is remarkable for many reasons. In it, he presents a model of selection in an age-structured population, the concept of reproductive value, and the Fundamental Theorem. Toward the end of the chapter, he discusses "The Nature of Adaptation," presenting a geometric model to justify the assertion that the probability of favorable genetic changes declines as the effect size of those changes increases.
<!--break-->
<blockquote>In order to consider in outline the consequences to the organic world of the progressive increase of fitness of each species of organism, it is necessary to consider the abstract nature of the relationship which we term 'adaptation.' This is the more necessary since any <i>simple</i> example of adaptation, such as the lengthened neck and legs of the giraffe as an adaptation to browsing on high levels of foliage, or the conformity in average tint of an animal to its natural background, lose, by the very simplicity of statement, a great part of the meaning which the world really conveys. <b>For the more complex the adaptation, the more numerous the different features of conformity, the more essentially adaptive the situation is recognized to be</b>. An organism is regarded as adapted to a particular situation, or to the totality of situations which constitute its environment, only in so far as we can imagine an assemblage of slightly different situations, or environments, to which the animal would on the whole be less well adapted; and equally only in so far as we can imagine an assemblage of slightly different organic forms, which would be less well adapted to that environment (38).</blockquote>

I've highlighted that last sentence, which is saying that organisms fit their environments in possibly many different ways, so that their <i>fitness</i> is not actually tied in any single feature, such as "tint," but is instead an optimum of many features, with respect to any single factor the organism may be more or less well adapted. The rest of that paragraph continues on to make the same point. 

Then: 

<blockquote>The statistical requirements of the situation, in which one thing [the organism] is made to conform to another [the environment] in a large number of different respects, may be illustrated geometrically. The degree of conformity may be represented by the closeness with which a point <i>A</i> approaches a fixed point <i>O</i>. In space of three dimensions we can only represent conformity in three different respects, but even with only these the general character of the situation may be represented. The possible positions representing adaptations superior to that represented by <i>A</i> will be enclosed by a sphere passing through <i>A</i> and centered at <i>O</i>. </blockquote>

This is really very simple, and the geometric model reveals an interesting switch. Suppose that we imagine an organism as a set of <i>a</i> traits, each of which lies at some distance <i>d</i><sub>1</sub>, <i>d</i><sub>2</sub>, <i>d</i><sub>3</sub>, ..., <i>d</i><sub>a</sub> from the optimum value for that trait, <i>O</i>. We could imagine adaptation as a stepwise process, in which a any one of the <i>a</i> traits may change, and only those changes that reduce <i>d</i><sub>a</sub> will potentially be selected. 

But there's no reason at all why we should consider every trait as an independent entity. Suppose that a single genetic change could improve <i>two</i> traits, or <i>three</i>, or even <i>all</I> the traits at the same time. 

Or, more interesting, a change might greatly improve trait 1, while making all the rest of the traits marginally worse. Without a word, Fisher has removed the issue of adaptation from the fit of many separate variables, to a single distance in multidimensional space -- a change from cartesian to polar coordinates, as it were. 

<blockquote>If <i>A</i> is shifted through a fixed distance, <i>r</i>, in any direction its translation will improve the adaptation if it is carried to a point within this sphere, but will impair it if the new position is outside.</blockquote> 


The geometric model really assumes very little. It tells us nothing at all about the relationship between fitness and any particular phenotype, aside from assuming that (1) the relation is continuous within the sphere centered on <i>O</i> with radius <i>A</i>, and (2) there are no "holes" of low fitness within that sphere. This is not a fitness landscape. Fisher's view, as will become clear, was that species are well-adapted in nature. He assumes that the distance between <i>A</i> and <i>O</i> is always rather small in comparison to the kinds of phenotypic effects that mutations might cause. So in assuming that the fitness function is continuous, and that the area is small, he more or less automatically arrived at the assumption that there's only one peak at <i>O</i>. 

The next part is the famous one that people remember: 


If <i>r</i> is very small it may be perceived that the chances of these two events are approximately equal, and the chance of an improvement tends to the limit 1/2 as <i>r</i> tends to zero; but if <i>r</i> is as great as the diameter of the sphere or greater, there is no longer any chance whatever of improvement, for all points within the sphere are less than this distance from <i>A</i>.</blockquote>

In this model, small changes are roughly 50-50 beneficial versus deleterious, but since their effect is very small, it hardly matters. Big changes are much less likely to be beneficial -- and if they exceed twice the distance from <i>A</i> to <i>O</i>, they can never be beneficial. 


After this quote, he gives an exact expression for the probability that a given change <i>r</i> is beneficial ((1/2)(1-(r/diameter))), but this is limited to the three-dimensional model. Then, there's another interesting one-sentence switch: 

<blockquote>The chance of improvement thus decreases steadily from its limiting value 1/2 when <i>r</i> is near zero, to zero when <i>r</i> equals <i>d</i>. <b>Since <i>A</i> in our representation may signify either the organism or its environment</b>, we should conclude that a change on either side has, when this change is extremely minute, an almost equal chance of effective improvement or the reverse; while for greater changes the chance of improvement diminishes progressively, becoming zero, or at least negligible, for changes of a sufficiently pronounced character.</blockquote>

Remember that <i>A</i> represents the current "degree of conformity" of the organism to its "particular situation." This degree of conformity might be changed either by changing the organism or its environment -- the implication fo the last confusing sentence from the first paragraph, above. 

The point <i>O</i> is not an objective location (as it would be if we assumed it <i>is</i> the optimum <i>within the current environment</i>). Instead, it is a geometric abstraction that exists only in so far as it bears a relation to <i>A</i> in the present multidimensional space of "adaptation". We may change the distance from <i>A</i> to <i>O</i> either by changing the organism or by changing its environment. Fisher refers explicitly to this "assemblage of slightly different situations" with respect to both -- and again, the concept of "slightly different" underlies the assumption that the fitness function within the sphere is continuous. 

It seems to me that the idea of "niche construction" falls very easily within Fisher's model. An organism that systematically alters its environment may thereby change its level of adaptation. So even though mutation is an obvious candidate for a process described by the model, I've continued to refer to "change" as a nonspecific term for the unit of adaptation. 

<blockquote>The representation in three dimensions is evidently inadequate; for even a single organ, in cases in which we know enough to appreciate the relation between structure and function, as is, broadly speaking the case with the eye in vertebrates, often shows this conformity in many more than three respects. It is of interest therefore, that if in our geometrical problem the number of dimensions be increased, the form of the relationship between the magnitude of the change <i>r</i>. and the probability of improvement, tends to a limit which is represented in Fig. 3. The primary facts of the three dimensional problem are conserved in that the chance of improvement, for very small displacements tends to the limiting value 1/2, while it falls off rapidly for increasing displacements, attaining exceedingly small values, however, when the number of dimesnions is large, even while <i>r</i> is still small compared to <i>d</i>. </blockquote>

Here we see the problem of universal pleiotropy emerging. As the number of dimensions of adaptability increases, the probability that one change will be a net increase in fitness, considering all dimensions, must decrease. This probability remains larger when the distance between <i>A</i> and <i>O</i> is larger, but declines as the number of dimensions increases. 

However, what we would call "universal pleiotropy" is intrinsic to Fisher's assumption that the <i>direction</i> of changes in this multidimensional space is random. If changes may occur in any direction, this is the same as asserting that a mutation may induce correlated changes between any set of phenotypes. With thousands of genes, and therefore thousands of dimensions of genetic "adaptedness", we might guess that the dimensionality is <i>high enough</i> to make this assumption useful. 

If on the other hand, the direction of changes is <i>constrained</i> in some way, then the dimensionality of the space accordingly is smaller by some degree. This is the rough equivalent of <i>modularity</i> in Fisher's model: if we say that some genetic correlations cannot be changed, we are saying that the phenotypic structure of the organism is modularized. 

The remainder of the section discusses the general case in spaces with higher than three dimensions. The basic point is that the probability that a change of a given size will be adaptive increases with the distance from <i>A</i> to <i>O</i>, decreases with the effect size <i>r</i>, and also decreases with the number of dimensions. 

Fisher finishes with a paragraph that, had he begun the section with it, might have made everything much clearer: 

<blockquote>The conformity of these statistical requirements with common experience will be perceived by comparison with the mechanical adaptation of an instrument, such as the microscope, when adjusted for distinct vision. If we imagine a derangement of the system by moving a little each of the lenses, either longitudinally or transversely, or by twisting through an angle, by altering the refractive index and transparency of the different components, or the curvature, or the polish of the interfaces, it is sufficiently obvious that any large derangement will have a very small probability of improving the adjustment, while in the case of alterations much less than the smallest of those intentionally effected by the maker or the operator, the chance of improvement should be almost exactly half. </blockquote>

But there is an obvious objection: if you twist a knob on a microscope, it may move one of the lenses, but it isn't going to polish it. It's not possible to effect <i>simultaneous</i> changes on distinct elements of the microscope, because a microscope is in fact modular in its construction and controls. That doesn't disprove Fisher's model, but at least in the microscope case, the possible changes are not random in direction, but are constrained to "Cartesian"-like independent axes. 

 


Fisher's general idea is different from the fitness landscape, in the sense used by Sewall Wright. Fisher assumes a single adaptive optimum; Wright espoused the possibility of a "rugged" landscape in which large genetic changes might diverge from the nearest local optimum yet place the population near an alternate (possibly higher) local optimum. But the geometric model shares many properties with the fitness landscape, including its assumptions about hill-climbing toward the local optimum. 

I <a href="http://johnhawks.net/weblog/topics/evolution/selection/gavrilets-fitness-landscape-metaphor-2009.html">pointed to Sergey Gavrilets work</a> a couple of weeks ago. Fisher's geometric model is most similar to the second meaning of fitness landscape, which pertains to the mean fitness of a population given a discrete genotype -- or in this case, a discrete phenotype-environment combination. Fisher's model is entirely about the relationship of two equilibria: the population mean fitness before and after a given change. It does not deal with the dynamics of the transition from one state to another. 

<h4>References:</h4>

<p class="cite">Fisher RA. 1930. The Genetical Theory of Natural Selection. Clarendon Press, Oxford. </p>

