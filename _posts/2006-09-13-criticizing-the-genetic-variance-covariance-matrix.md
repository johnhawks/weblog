---
layout: single 
title: "Criticizing the genetic variance-covariance matrix" 
category: story
permalink: /weblog/reviews/evolution/constraints/pigliucci_2006_genetic_variance-covariance.html
tags: [constraints, evo-devo, Sewall Wright] 
comments: false 
author: John Hawks 
---


<p>
A subset of evolutionary theorists are specifically concerned with how the evolution of multiple characters of organisms are linked to each other by genetic correlations. A handful of those theorists actually think about human evolution. There is a little bit of matrix algebra involved; maybe that explains why the number is so small -- I don't know. 
</p>

<p>
But the problem is of fundamental importance to quantitative evolution, because the power of selection to change a feature is constrained by the genetic relationships of that feature to other features of the organism. 
</p>

<p>
For example -- want to make the brain bigger? Then you have to deal with the fact that some of the same genes that make brains bigger also make bodies bigger. Want to make the neocortex bigger in particular? It will be hard to do it without increasing the size of the brain, the size of the body, the size of the teeth, and so on. All these sizes are genetically correlated to some extent, the actual extent being described by the genetic variance-covariance matrix (often called <b>G</b>). Each of these characters has its own pattern of (often stabilizing) selection, so if you push on one very much, others will pull against you. 
</p>

<p>
Massimo Pigliucci (2006) knows a lot of quantitative genetics. He even has <a href="http://www.amazon.com/exec/obidos/redirect?link_code=as2&path=ASIN/0195160436&tag=johnhawksanth-20&camp=1789&creative=9325">a textbook about it</a>. He also has <a href="http://dx.doi.org/10.1007/s10539-005-0399-z">a paper</a> in <i>Biology and Philosophy</i>, titled "Genetic variance-covariance matrices: a critique of the evolutionary quantitative genetics research program." So this attracted my interest -- what is a well-known quantitative geneticist doing critiquing the research project of quantitative genetics?
</p>

<p>
It has a pretty provocative abstract: 
</p>

<blockquote>This paper outlines a critique of the use of the genetic variance-covariance matrix (<b>G</b>), one of the central concepts in the modern study of natural selection and evolution. Specifically, I argue that for both conceptual and empirical reasons, studies of <b>G</b> cannot be used to elucidate so-called constraints on natural selection, nor can they be employed to detect or to measure past selection in natural populations - contrary to what assumed by most practicing biologists. I suggest that the search for a general solution to the difficult problem of identifying causal structures given observed correlation's has led evolutionary quantitative geneticists to substitute statistical modeling for the more difficult, but much more valuable, job of teasing apart the many possible causes underlying the action of natural selection. Hence, the entire evolutionary quantitative genetics research program may be in need of a fundamental reconsideration of its goals and how they correspond to the array of mathematical and experimental techniques normally employed by its practitioners (Pigliucci 2006:1).</blockquote>

<p>
That's some big talking -- "fundamental reconsideration of its goals". Do his specific critiques of the application of the genetic variance-covariance matrix support this conclusion? 
</p>

<p>
His first point is that the theoretical work on "the" <b>G</b> matrix leaves very open the structure of <i>particular</i> <b>G</b> matrices that one might study in one or another organism. Some covariances among characters are stable at high taxonomic levels, like the family level, and other covariances may be very different from one population of a species to another. He writes: 
</p>

<blockquote>The upshot of this is that quantitative geneticists who focus on stamens in Brassicaceae are likely to reach completely different conclusions about the stability of the genetic variance-covariance matrix from their colleagues who instead study leaf evolution in semi-aquatic plants. Indeed, research by Waldmann and Andersson (2000) in populations of <i>Scabiosa columbaria</i> and <i>S. canescens</i> found, among other patterns, that 'the magnitude of (co)variances was more variable among characters than among populations,' i.e., the results of a given study of <b>G</b> depend more strongly on which traits the investigators choose to focus on then it does on the species selected! Again, this ought to be obvious, but much of the literature is written in a way that implies that the evolution of <b>G</b> is a single kind of thing, and that it makes sense to think of <b>G</b> itself, somewhat independently of the particular traits used to calculate it (Pigliucci 2006:8). </blockquote>

<p>
I think that does pose a theoretical problem (i.e., what is the relationship of theory to empirical results-on-the-ground), but it doesn't pose any particular problem for people studying <i>specific</i> traits in a <i>specific</i> group of organisms -- for instance, cranial form in the hominids. At that level, we don't care about <b>G</b> matrices <i>in general</i>, or even the total genetic variance-covariance matrix for the human body, as long as we can estimate the variances and covariances of the characters we are studying. So the global problem may not affect the specific implementations. 
</p>

<p>
Pigliucci's second point carries more force, and to my mind is really a concatenation of two separate issues. First, we have some practical means that we may use to estimate genetic variances and covariances -- such as half-sib breeding designs. But we have no justification for the further assumption that the variances and covariances obtained from such experiments actually apply to any natural populations. The second, and related, issue is that the "true" <b>G</b> matrix in a natural population depends on its breeding structure. 
</p>

<p>
If anything, these points have more force applied to the specific example of human evolution than to the general case. For one thing, for most characteristics we don't even have any studies of the genetic variance and covariance with other characters. A lot of studies just substitute the <i>phenotypic</i> variance-covariance matrix, assuming that it is "more or less" like the genetic matrix. 
</p>

<p>
And there is <i>an awful lot</i> of simply using phenotypic variances and covariances <i>without mentioning genetics at all!</i> As in, "population X and Y cluster phenotypically near each other, <i>therefore</i> they are genetically close to each other." 
</p>

<p>
The second part is something to consider more closely. Have hominids changed their breeding structure in ways that would make difference to the genetic correlations among traits? Hard to say. Seems like changes in group size and within-group relatedness would make a difference, but I'm not sure about the scale. 
</p>

<p>
Pigliucci's third point concerns the use of <b>G</b>, which is always a <i>local</i> estimate, to examine long-term patterns of evolution: 
</p>

<blockquote>As with <i>h<sup>2</sup></i>, if the available genes or the gene frequencies in the population change, so too might <b>G</b>; similarly, in a different range of environments (or if the population becomes differently distributed among the environments encountered), <b>G</b> might well change. Given this, if one wants to make use of <b>G</b> in simulations of long-term evolution (e.g., Via 1987), one must assume that the matrix stays constant (or at least proportional) to the ancestral state over the time period one is investigating (generally thousands of generations). But several authors (e.g., Turelli 1988; Pigliucci and Schlichting 1997) have pointed out that this is highly unlikely on first principles, because evolution de facto changes gene frequencies, and therefore G itself; nor is it unreasonable to suppose that over such time periods the environment encountered by the population may change as well. Therefore, while it is sensible to assume near-constancy of <b>G</b> for short-term applications (e.g., crop or animal breeding, artificial selection experiments, or perhaps even evolution in wild populations over few generations), the hypothesis of approximate constancy becomes less and less likely the more widely separated the relevant populations are in time and/or space (Pigliucci 2006:10-11). </blockquote>

<p>
He notes that the same argument applies to variation in environments, as does to time. 
</p>

<p>
I would personally say that this is the most serious problem. If the genetic variance-covariance matrix evolves, <i>as it must for phenotypic evolution to occur</i>, then it cannot be assumed constant. I have many times heard the argument that we can estimate variances and covariances for fossil humans by using large samples of living humans -- because living humans are more or less similar in their variances and covariances to ancient humans. (These are, of course, phenotypic variances and covariances, since the idea of genetics rarely enters!) But this idea is simple nonsense, particularly since it is usually made in an effort to show <i>just how different</i> some fossil sample is from living people!
</p>

<p>
Pigliucci's fourth point is best described in his own words: 
</p>

<blockquote>More philosophically interesting are problems concerning G that cut to the core of why biologists use the concept to begin with. Let us start with the notion that the predictability of future phenotypic evolution is predicated on <b>G</b> revealing 'constraints' on evolutionary change imposed by the 'genetic architecture' underlying complex phenotypes. The idea is that trade-offs between traits to which an organism can allocate available resources (for example, between survival and reproduction) should manifest themselves as observable (negative) genetic covariances between the traits in question. If this were true, studies of <b>G</b> matrices could reveal features of the underlying trade-offs that influence the direction of phenotypic evolution, a major goal of evolutionary biology. Unfortunately, work by Houle (1991) and Gromko (1995) has dealt what should have been devastating blows to these uses of G in evolutionary theory; oddly, despite these key papers being published in Evolution, the premier journal in the field, their arguments have scarcely made a dent in the literature (Pigliucci 2006:12). </blockquote>

<p>
He goes on to describe the results. Houle demonstrated mathematically that trade-offs do not always give rise to negative genetic covariances, because the genetic covariances depend on the genetic variances and the number of genes involved. Large variances at many genes may outweigh even strong negative covariances at few genes. Gromko demonstrated many different pleiotropic mechanisms might generate the same <b>G</b> matrix, and that the pattern of covariances cannot distinguish between different possible evolutionary outcomes. In particular, covariances near zero might occur for systems that nevertheless are highly constrained in their coevolution. 
</p>

<p>
More than other problems, this one would seem to reveal a conflict between evolutionary developmental (evo-devo) approaches and standard quantitative genetic approaches. Where standard approaches might view the genetic variance-covariance matrix as the genetic structure, evo-devo looks for the mechanisms that give rise to the stucture. Since different functional relationships among genes might give rise to the same covariances, this gives some reason for caution in applying the covariances to predict long-term evolution. 
</p>

<p>
Pigliucci's fifth point is that <b>G</b> matrices don't provide much help in distinguishing the effects of selection from those of genetic drift. This is an important theoretical problem in biology and one that has been applied to evolutionary transitions in human evolution (e.g., the cranial form of early <i>Homo</i>). Pigliucci gives a review of the predictions of standard theory (viz., selection should affect different sets of characters differently, drift should affect the entire matrix in a proportional way), and then describes <i>Drosophila</i> experimental work that raises problems for the theory: 
</p>

<blockquote> When these authors [Phillips et al., 2001] considered the <i>average</i> G across populations (a statistically useful, but biologically meaningless, construct), this did indeed follow Roff's expectations: the populations that had undergone drift had an average <b>G</b> that was proportional to that of the founding population, as predicted by the theory <i>for a set of replicated populations</i> (i.e., when one actually knows the historical path of evolution). If these results had held for the individual populations that underwent drift, rather than for the statistical construct created by averaging them, this would have been good news indeed. But alas, when Phillips and collaborators examined the <b>G</b>s of individual populations that had undergone drift, they found that most were not proportional to their control at all: i.e., these matrices appeared to have been produced by selection, not drift, even though there was no significant selection going on! (Pigliucci 2006:16, emphasis in original). </blockquote>

<p>
In other words, instances of the evolutionary process don't look like averages over many instances. This is a problem with inferring selection as opposed to drift (i.e., drift in a single population may look like selection), but I would guess there is a corresponding problem inferring drift (i.e., selection in a small sample may look like drift, due to the inaccuracies in estimating covariances). The problem of sample size and covariances is one I may take up again later. 
</p>

<p>
Pigliucci's sixth and final point is that biologists often confuse individual-level versus population-level processes when they talk about "selection on" <b>G</b> matrices. I can see this point, as he describes it: 
</p>

<blockquote>When considering natural selection, it is clear that physical interactions at the individual level may result in predictable statistical patterns at the population level, and yet this does not imply that the reverse move (from population to individual) is just as straightforward. The point has been made more generally by Shipley (2000), who - in the context of discussing the relationship between causation and correlation in biology - concluded that biologists can test hypothesized causal models by comparing them with their predicted statistical 'shadows,' but cannot reasonably go from the latter to the former. Alas, that is exactly what a great part of the research project in evolutionary quantitative genetics is all about! To put it into another fashion, we can calculate the statistics, but what sort of biological questions are they answering, if any?  (Pigliucci 2006:17). </blockquote>

<p>
But I'm having trouble thinking of a concrete example that shows why it is a problem, beyond being a conceptual problem. 
</p>

<p>
In any event, that summarizes the critique. It is hard for me to imagine the multivariate study of fossil hominids that answers all these points convincingly. There is maybe some feeling that studies of fossil hominids are imperfect, but will get better if the samples increase in numbers, etc., etc. But Pigliucci has some nice turns of phrase that I like as answers to this idea. For example: 
</p>

<blockquote>[B]y now it should be clear that quantitative evolutionary biologists ought not to think of these statistical constructs as 'first approximations' to be refined by further research; the difficulty with these constructs is not that they are imprecise (and, therefore, amenable to 'refinement'), but that they do not answer the questions we wish answered (Pigliucci 2006:19).</blockquote>

<p>
After his critique, Pigliucci tries to outline ways that might advance our understanding and avoid these conceptual problems. I can't say he has much success at it, since ultimately somebody is going to have to invent new methods to answer the problems. 
</p>

<p>
Additionally, I would say that the problems studying hominid evolution go a lot deeper. Many studies uncritically apply multivariate techniques to samples of five or ten individuals. Keep in mind that these samples are insufficient for estimating <i>variances</i> with reasonable error. Now consider that people are using them to estimate <i>covariances</i> among <i>twenty or more characters</i>. That's a different scale of problem from the ones Pigliucci is describing, but it borders and grades into them. 
</p>

<p>
I do want to quote one part of the conclusion of the paper, because it will be interesting to students of the Fisher-Wright controversy: 
</p>

<blockquote>The conceptual reason [for commitment to multivariate regression], of more philosophical interest, can be traced back to the rationale that went into the publication of Lande and Arnold's (1983) paper: the main goal there was to provide not just a way to statistically quantify natural selection in action, but to do so while obtaining coefficients of selection that could be directly plugged into the standard quantitative genetics equations for the prediction (or post-diction) of phenotypic evolution. It turns out that, until now, nobody has figured out a way to use path coefficients for the same purpose (but see Scheiner et al. 2000 for the beginning of such an attempt). This implies that a theoretical goal has been for all effective purposes overriding serious conceptual and methodological limitations of the techniques used. What makes this a possible dead end for the entire field is that there are good reasons to believe that the theoretical goal in question - the long-term prediction of evolutionary trajectories - is simply not achievable because of the problems of locality and liability of G discussed above (Pigliucci 2006:20). </blockquote>

<p>
That's interesting because, of course, the usual multivariate techniques owe their origin to Fisher, while path analysis was Sewall Wright's solution to some of these genetic problems. Personally, I would say that path analysis is more logical in many ways, but yet it is pretty difficult to implement. A connection between evo-devo genetics and path analysis would be pretty interesting to see. 
</p>

<h4>References:</h4>

<p class="cite">Pigliucci M. 2006. Genetic variance-covariance matrices: a critique of the evolutionary quantitative genetics research program. Biology and Philosophy 21:1-23. <a href="http://dx.doi.org/10.1007/s10539-005-0399-z">DOI link</a>

