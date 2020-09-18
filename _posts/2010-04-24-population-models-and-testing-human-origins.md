---
layout: single 
title: "Population models and testing human origins" 
category: story
permalink: /weblog/reviews/genomics/modern/laval-modern-human-origins-2010.html
tags: [multiregional, early modern, Neandertal DNA, out-of-Africa] 
comments: false 
author: John Hawks 
---

Earlier in the week, I pointed to a news story about upcoming research that substantiates some amount of gene flow among Pleistocene groups, persisting into living populations (<a href="http://johnhawks.net/weblog/reviews/evolution/introgression/joyce-dalton-interbreeding-2010.html">"Multiregional evolution lives!"</a>). That scenario made a bit of a splash in the news, but the result is not unprecedented. 

Last year around this time, I noted a study by Wall, Lohmueller and Plagnol that came to a similar result -- estimating that around 5 percent of the gene pool of today's people outside Africa derived from ancestral non-Africans. That followed on earlier work by Plagnol and Wall from 2006 with essentially the same result. 


Looking back at the blog, this has been a recurring topic since the beginning. For example, back in 2005 when I was still doing a meetings update, I posted about several conference presentations on the topic (<a href="http://johnhawks.net/weblog/reviews/genetics/genetics_mre_aapa_2005.html">"Genetics and multiregional evolution, meetings 2005"</a>). At that time the new results were from Alan Rogers, Jody Hey, and Mike Hammer's lab, all suggesting that ancestral diversity either suggested some ancestral population structure outside Africa, or at least didn't reject it. A key finding was published by Garrigan and colleagues (2005), who found a pseudogene on the X chromosome with an unusually deep gene tree in East Asia (<a href="http://johnhawks.net/weblog/reviews/genetics/garrigan_2005.html">"Modern human origins: X marks the spot?"</a>). 

But there's a lot of literature out there that contradicts this line of research. Some of it is still being published. A case in point is the paper released in <i>PLoS ONE</i> this week by <a href="http://dx.doi.org/10.1371/journal.pone.0010284">Guillaume Laval and colleagues (2010)</a>. The key part of the abstract: 

<blockquote>Our results support a model in which modern humans left Africa through a single major dispersal event occurring ~60,000 years ago, corresponding to a drastic reduction of ~5 times the effective population size of the ancestral African population of ~13,800 individuals. Subsequently, the ancestors of modern Europeans and East Asians diverged much later, ~22,500 years ago, from the population of ancestral migrants. This late diversification of Eurasians after the African exodus points to the occurrence of a long maturation phase in which the ancestral Eurasian population was not yet diversified.</blockquote>


That seems to directly contradict all the research suggesting some component of intermixture among pre-modern populations outside Africa. So what's the deal? 

I have a good idea what's going on now with these apparent contradictions, thanks to a recent paper by Alan Templeton (2010). I'll discuss that paper in detail later this week, as I'm covering these issues now in my graduate seminar. 

In the meantime, I want to give a little thought to the new paper by Laval and colleagues. Following through their simulation methods may give us some ideas about how we can resolve the discrepancies among these tests of human population history. I also want to explore some of the ways that paleontology and paleogenomics may help to inform our tests about these issues. 

Here's a nice paragraph from the results section of the paper that outlines many of the simulation methods. I'd like to have seen some issues laid out more clearly, as some of the parameter combinations are hidden in the supplements and not clearly explained there. It means that as I discuss these, I may not quite have understood everything correctly. 



<blockquote>First, we determined the evolutionary scenario that took place in the ancestral lineage that culminated in the emergence of modern humans (for a complete list of parameter symbols used along the manuscript, see Tables 2 and S4). We tested different evolutionary models [2], [5], [19], [22], [51][56] that allow different levels of introgression of archaic hominids to modern human populations. We assumed an early diffusion of archaic hominids (Homo erectus) out of Africa ~1.25 and ~2.25 million years ago [57], various ancestral migration rate intensities (m<sub>0</sub>, ancestral migration rate is the proportion of migrants before the Out-of-Africa exodus) and an African exodus of modern humans between ~40,000100,000 years ago [38]. By tuning the replacement rate ?, we then simulated scenarios that consider different levels of replacement of archaic hominids by modern humans (i.e. different levels of introgression of archaic material into the modern gene pool), including the most extreme cases of complete (? = 1) and no replacement (? = 0) as well as several scenarios with varying intermediate levels of replacement (Figures 3A and S2, Table S4). The summary statistics were calculated by merging all population samples (except for global F<sub>ST</sub>) in order to minimize the effects of recent demographic events related to the continental populations. We thus considered in all models a constant size for the three modern human populations. The model with residual ancestral migration rate (m<sub>0</sub>~10<sup>?10</sup>) and full replacement (? = 1) clearly better fitted our data than any other model (Figure 3A, highest ?1, the ?1 of this model is significantly higher after correction for multiple testing when compared with the other ?1 values, P<0.01). However, we could not discern between a complete (? = 1) and an almost-complete (??0.99) replacement of archaic hominids (difference between ?1 is not significant for this pairwise comparison), indicating that a small contribution of archaic humans to our present-day genome cannot be completely ruled out [58][61].</blockquote>



For a long time, I've been bothered in the back of my mind about the outcomes of these analyses based on simulations and "approximate Bayesian computation" (ABC). I learned a long time ago never to argue statistics with a Bayesian. It's not that the approach is infallible, it's just that if someone is clever enough to use Bayesian statistics, it's going to turn into a long argument. 

By my count the model has 18 parameters, and we could reshuffle them in lots of ways. Can it really be that no combination of the parameters provides a better fit than zero admixture? Intuitively, it seems wrong -- because it would mean that one combination of the other 17 parameters gave a near-perfect fit to the data. Perfect fits don't happen, not with genetic data as messy as in humans. 


The conceptual scheme of the paper is an island model with migration, growth, and replacement as possibilities, between the three populations -- Africa, Europe and East Asia. Since any of the parameters could in concept vary from zero to infinity, each specific model ought to be a proper subset of the general island model, and they ought to grade continuously into each other. In other words, an out-of-Africa replacement is just one extreme of the general multiregional/admixture/introgression model. 

That has some predictable consequences. A nonzero migration rate <i>before</i> a complete replacement ought to behave very much like a structured population <i>within</i> Africa before a replacement. An analysis that prefers the second really shouldn't be distinguishable from the first. Likewise, a very small population outside Africa before a slight replacement should look very much like a larger population with a more complete replacement. These options aren't identical, but they ought to grade continuously into each other. 

But in the paper, the authors bounded the parameters in ways that make these different specific models discontinuous. For example, consider the parameter that defines the time of the initial population spread out of Africa: 

<blockquote> We assumed an early diffusion of archaic hominids (Homo erectus) out of Africa ~1.25 and ~2.25 million years ago </blockquote>

If the time of founding of these populations could vary down toward the time of possible replacement (in the last 100,000 years), the continuity and replacement models would grade continuously. This would be the logical connection implied by the island model, but by limiting the range of times, the authors have generated an artificial difference between the models. 

In principle, we could have a good reason for separating the models in this way. For example, we know that Europe and Asia were occupied by hominids before 1.25 million years ago, and we might specifically be interested in those people. 

But in reality, we know that a 1.25-million-year old split between European and African populations is in conflict with paleogenomics. The Neandertal genome shows that we shared a small common ancestral population with Neandertal ancestors at most around 300,000 years ago, and possibly much more recently. If the human-Neandertal ancestral population was dispersed across Eurasia and Africa at that time, it must have had relatively high gene flow, enough so to behave as a single population with a small effective size. 

So this is a possible problem. None of the "admixture" models included in the paper have a feature which the paleogenomic evidence says is necessary. My point is that the authors have generated a "rugged landscape" of models by eliminating the continuity between them. It may not be surprising that one choice of parameters fits the data much more strongly than alternatives, because the intermediates have not been examined. 

There are other parameters for which uncertainty might be substantially reduced by using other evidence. For example, the authors consider a range of migration rates varying over three orders of magnitude between recent (modern) populations on different continents. The actual value of this rate has a large effect on the appearance of admixture, because it determines the likelihood that ancestral African variation has recently dispersed out of Africa into Eurasia. But we can probably obtain a good estimate of this rate of recent gene flow from other data, since we have large datasets of genome-wide SNP and microsatellite polymorphisms from these regions. These data could also provide a better test of the proposed Europe-Asia "split". Why are these aspects important? Because recent events will disturb or cover up the evidence for earlier dispersals and interactions. If we can constrain the recent events using other evidence, we can increase our power to test hypotheses about earlier events. 

Although many possible intermediate models are excluded in the study, the authors in the end find an overlap in results between two apparently very different parameter combinations: 

<blockquote>Among the 24 models tested, the model assuming a complete replacement rate of archaic hominids (? = 1) and a residual ancestral migration (m<sub>0</sub>~10<sup>?10</sup>) exhibited the significantly highest ?1 except when compared with the model assuming an almost complete replacement rate of archaic hominids (??0.99).</blockquote>

That result might seem paradoxical. At face value, it means that ancestral humans outside Africa <i>did</i> contribute genes to living populations, but only by means of very rare gene flow from Eurasia <i>back into</i> Africa before a subsequent replacement. In other words, the first modern humans in Africa would have been descendants of Africans and of Eurasian people. It's not surprising that the outcome is <i>close</i> to a model with very slight survival of Eurasian populations. 

As we think of ways to improve these tests, I think we need to introduce independent tests of each parameter. This won't always be possible, and there will be cases where changing one parameter will impose a trade-off with one or more others. But that's the nature of these models -- each parameter is a dial, and twisting one of them may be corrected by turning others. The important point is that we can already falsify many of the conceivable possibilities. Until we have a model in which paleontology, archaeology, paleogenomics and the genetics of living people all form a single consistent picture, our work isn't done. 

(see also, <a href="http://blogs.discovermagazine.com/gnxp/2010/04/nearly-100-out-of-africa-in-the-past-100000-years/">Gene Expression</a>)


<h4>References:</h4>

<p class="cite">Garrigan D, Kingan SB. 2006. Archaic human admixture: A view from the genome. Curr Anthropol 48:895-902. <a href="http://dx.doi.org/10.1086/523014">doi:10.1086/523014</a></p>


<p class="cite">Garrigan, D., Mobasher, Z., Severson, T., Wilder, J. A., Hammer, M. F. 2005. Evidence for archaic Asian ancestry on the human X chromosome. Mol. Biol. Evol. 22:189-192. <a href="http://dx.doi.org/10.1093/molbev/msi013">doi:10.1093/molbev/msi013</a> </p>

<p class="cite">Hawks J, Cochran G. 2006. Dynamics of adaptive introgression from archaic to modern humans. PaleoAnthropology 2006:101-115. <a href="http://www.paleoanthro.org/journal/content/PA20060101.pdf">Open access</a></p>

<p class="cite">Hawks J, Cochran G, Harpending HC, Lahn BT. 2007. A genetic legacy from archaic <i>Homo</i>. Trends Genet <a href="http://dx.doi.org/10.1016/j.tig.2007.10.003">doi:10.1016/j.tig.2007.10.003</a></p>

<p class="cite">Laval G, Patin E, Barreiro LB, Quintana-Murci L (2010) Formulating a Historical and Demographic Model of Recent Human Evolution Based on Resequencing Data from Noncoding Regions. PLoS ONE 5(4): e10284. <a href="http://dx.doi.org/10.1371/journal.pone.0010284">doi:10.1371/journal.pone.0010284</a></p>

<p class="cite">Plagnol, V., Wall, J. D. 2006. Possible ancestral structure in human populations. PLoS Genet. 2:e105. <a href="http://dx.doi.org/10.1371/journal.pgen.0020105">doi:10.1371/journal.pgen.0020105</a></p>

<p class="cite">Templeton AR. 2010. Coherent and incoherent inference in phylogeography and human evolution. Proc Nat Acad Sci USA 107:6376-6381. <a href="http://dx.doi.org/www.pnas.org/cgi/doi/10.1073/pnas.0910647107">doi:www.pnas.org/cgi/doi/10.1073/pnas.0910647107</a></p>

<p class="cite">Wall JD, Lohmueller KE, Plagnol V. 2009. Detecting ancient admixture and estimating demographic parameters in multiple human populations. Mol Biol Evol (early online) <a href="http://dx.doi.org/10.1093/molbev/msp096">doi:10.1093/molbev/msp096</a></p>


