---
layout: single 
title: "One model, hold the extra parameters" 
category: story
permalink: /weblog/reviews/genetics/ray_2005_modern_human_origins.html
tags: [Late Pleistocene, multiregional] 
comments: false 
author: John Hawks 
---


<p>
Ray et al. (2005) (<a href="http://www.genome.org/cgi/content/full/15/8/1161">full text from Genome Research</a>) compare two classes of models of modern human origins to observed data from human microsatellites. They first perform simulations to confirm that the data can distinguish the different models from each other ("multiregional evolution" vs. "unique origin" models). This they apparently should be able to do -- using only 20 markers, the simulations attained 99 percent classification accuracy. 
</p>

<p>
On the other hand, none of the models explained the observed data very well. Out of the models, an origin in northern Africa fit the model best, but there was no significance test showing that the fit to their "unique" African origin was significantly better than their "multiregional" models. 
</p>

<h4>The "models"</h4>

<p>
Why the scare quotes? Because these models are weird. Let's look at the clearest description of the "multiregional evolution" model (from the caption of <a href="http://www.genome.org/cgi/content-nw/full/15/8/1161/FIG2">figure 2</a>): 
</p>

<blockquote>(B) Multiregional evolution (ME) model. As in A, a small population went through a speciation event and instantaneously colonized the three continents 30,000 generations ago. For 26,000 generations the continents harbored relatively large populations and exchanged occasional migrants (see Table 1 for continent population sizes and migration rates under different scenarios). Then, 4000 generations ago, three range expansions were initiated from the three different origins shown in C.</blockquote>

<p>
Although the idea of populations connected by gene flow is consistent with multiregional evolution, this idea of geographic range expansion from three locations is batty. Who thinks that happened?
</p>

<p>
In practice, it appears that they used three separate range expansions because that is what they had the software for. And that raises another issue: these range expansions begin with an extreme bottleneck: a founding population of only 50 individuals. 
</p>

<p>
Now if I ever write an article saying "Humans originated by multiregional evolution with small levels of gene flow, and in the Late Pleistocene there was a worldwide catastrophe limiting people to three far-flung populations of 50 people," I think people would call me crazy. 
</p>

<p>
The weirdness of the model is confirmed by their results. Here's how the paper describes its "multiregional" model results: 
</p>

<blockquote>Among the ME scenarios, it is worth noting that the best fit to the data is found for scenarios 26 and 29, which corresponds to cases in which the Pleistocene migration rates between continents are very limited (Nm = 0.1, or one migrant gene exchanged every 10 generations). This very limited amount of gene flow between continents makes it difficult to understand how humans could have evolved simultaneously toward modernity, as advocated by the supporters of the multiregional evolution hypothesis (Hawks et al. 2000; Wolpoff et al. 2000). It is also interesting to note that the best supported ME scenario (no. 26) assumes equal continental sizes, whereas previous studies (Takahata et al. 2001; Satta and Takahata 2004) had found a better support for ME scenarios in which the African continent would have had a much larger population size than other continents. It supports the view that the pattern of genetic differentiation between human populations is more affected by the geography (migration corridors, contours) of the continents than by their population densities.</blockquote>

<p>
This is beyond weird. The paper is saying that <i>unlike all other data</i>, their microsatellite distances support the idea that human populations were strongly isolated in the past, and that Africa had no more people than any other region. I say it is beyond weird because the data even more strongly support their "unique origin" model, in which the ancestral population was panmictic. Which is it? Panmictic or highly structured? 
</p>

<p>
Now look at the description of a "unique origin" (i.e. replacement) model:
</p>

<blockquote>(A) Unique origin (UO) model. In this model, 30,000 generations ago, a small population (N = 100 genes) went through a demographic expansion after a first speciation event. Then, 4000 generations ago, a range expansion followed a bottleneck of 10 generations to mimic a second speciation event. The large population preceding the speciation and range expansion can be considered to be a large subdivided population. </blockquote>

<p>
OK, so we have one large subdivided population, which undergoes a short bottleneck and then expands around the world. Here's the problem: if this earlier population <i>actually were</i> subdivided, then this model would be multiregional evolution (!). But the model <i>doesn't</i> have a "large subdivided population", it actually has a single small panmictic population. 
</p>

<p>
And again, there's the strange bottleneck. I just don't understand why they include it, unless it's an artifact of their simulation method. They don't report any reason for the bottleneck, other than that it "simulates a speciation". But it doesn't look like any speciation I ever heard of. 
</p>

<p>
And what about Zhivotovsky et al. (2003)? That paper used exactly the same set of microsatellite data to infer the demographic history of humans. It concluded that different continental populations of humans underwent a population expansion from an initial size of between 1000 and 3000 individuals at times ranging from 4000 to 36000 years ago. These values bear little relationship to the values used by Ray et al. (2005) --- expansion from an initial size of 20000 (with a short bottleneck of 100) some 120,000 years ago. Should we believe the demographic model? Or should we believe the geographic model? Ray et al. (2005) don't cite Zhivotovsky et al. (2003), so maybe they didn't consider that the two estimates should, maybe, match? 
</p>

<h4>What's going on here?</h4>

<p>
Here is my completely uninformed line of speculation about these results. It begins from these premises: 
</p>

<p>
1. The test statistic is a goodness-of-fit between the observed matrix of distances between populations (<i>R<sub>ST</sub></i>) and the simulated matrix. 
</p>

<p>
2. None of the simulated matrices fits the observed data very well; simulated data fit their predictions much better. 
</p>

<p>
3. This means that the simulated scenarios are not generating data that look like the observed pattern of genetic distances between populations. 
</p>

<p>
4. <i>But the observed pattern of genetic distances between populations is a very good fit to isolation-by-distance!</i> This shouldn't be a hard distribution for a simulation to match. 
</p>

<p>
5. Hence, there is something very weird about the models. 
</p>

<p>
Now, what explains the weird results? Here are some ideas: 
</p>

<p>
6. Consider the "multiregional" model here: three initially divergent populations in the corners of the Old World begin to expand. As they expand, their allele frequencies drift in random directions. At some point, these geographic expansions <i>meet</i>, but mix only slightly before the simulation ends. Result: strong differences in allele frequencies along very narrow geographic corridors where the populations met -- a distribution that looks nothing like the observed pattern. Bad fit from a bad model. 
</p>

<p>
7. Under this scenario, the "unique" origin models <i>ought</i> to do better. But here the puzzle is different: why do the South Asian and Southern African "unique" origins do so much worse? Neither of these regions is all that far from the North African locations that do so well. An origin in either location seems like it ought to be more likely than an <i>Australian</i> origin. Considering the obvious problems with the "multiregional" models, they ought to outperform them as well. But they don't. 
</p>

<p>
8. Here's my guess: migration. The geographic model appears to include migration among all populated demes -- even the ones that have been populated a long time. That is a <I>good</I> thing about the model; it is markedly more realistic than models that assume <I>no</i> migration. But it creates a problem, since their test statistic is Fst. If the only factor creating <i>differences</i> among demes is a founder effect at their establishment, and migration is constantly making them more similar, then it follows that the demes closest to the origin should be the <i>least</i> different from each other. (Populations far from the origin may also be very similar to each other, because very little variation gets to them at all, but that's a separate point.) 
</p>

<p>
9. Ooops...that's a problem. The empirical data have fairly large interpopulation differences in Africa. 
</p>

<p>
10. Southern Africa therefore won't work as an origin with this model. The simulations control the rate of migration though the assumption of a parameter called "friction", which is supposed to represent the difficulty of moving to a particular kind of environment. It is easy to move to a nice place, and hard to move to a bad place. The paper doesn't report the "friction" parameters (there are over 9000 of them, after all), but Southern Africa ought to be relatively nice, and the demes have few neighbors so they should mix easily. In the model, a Southern Africa origin would make those populations too much like each other. 
</p>

<p>
11. Northern Africa evades this problem, because it is a <i>desert</i>. If the authors recognized this by assigning high "friction" to these demes, then these demes would sustain more genetic differences. These would be more similar to the observed data (although still not very much like it in many respects). 
</p>

<p>
So I don't think the article advances the issue of modern human origins. 
</p>

<h4>Parameters</h4>

<p>
The problem is not that the models are unrealistic. A simple but unrealistic model can still advance the problem by suggesting ways that it is deficient. New studies can build on a failed simple model by adding parameters to better approximate observed data. 
</p>

<p>
But this paper doesn't have any simple models. The models here each have more than 18000 parameters. The models are drowning in complexity. 
</p>

<p>
Let me point out that it is possible to completely fit an Rst matrix with a migration matrix that has the same number of cells (effectively one fewer, since all the others can be expressed in terms of one of them). This model would simply be a multiregional model, in which the migration between each pair of demes was the only cause of their present level of difference. Here, the number of parameters is always equal to the number of degrees of freedom, which both depend on the number of populations being compared. 
</p>

<p>
Now, if you have a simple model that fits the data perfectly, why would you want to go to a more complicated model? Why in particular would you go to a model with over 18000 extra parameters? 
</p>

<p>
This is not to say that the simple migration matrix is the <I>true</I> model; it is just an observation that adding more parameters should not result in a <i>lower</i> fit to the data. The data should be overfit 18000 ways. If your fit to the data <i>gets worse</i> then you should definitely abandon your model!
</p>

<p>
I have some thoughts on this, but I'm holding on to them for a bit. They are shaping up to be a nice paper. 
</p>

<p>
In the meantime let me say: if you intend to add 18000 extra parameters, please try to make sure that any case you test is at least <i>reducible</i> to the perfect-fit model. In this case, we know that we can construct a multiregional model that fits the observed Rst matrix. Why should we pay attention to the weird models that fit the data worse? 
</p>

<h4>References:</h4>

<p class="cite">Ray N, Currat M, Berthier P, Excoffier L. 2005. Recovering the geographic origin of early modern humans by realistic and spatially explicit simulations. Genome Res 15:1161-1167. <a href="http://www.genome.org/cgi/content/full/15/8/1161">Full text (free)</a></p>

<p class="cite">Zhivotovsky LA, Rosenberg NA, Feldman MW. 2003. Features of evolution and expansion of modern humans, inferred from genomewide microsatellite markers. Am J Hum Genet 72:1171-1186.</p>

