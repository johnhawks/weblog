---
layout: single 
title: "Spatial dispersal, parallel adaptation, and the &quot;Stooge effect&quot; " 
category: story
permalink: /weblog/topics/evolution/selection/spatial-dynamics/ralph-coop-tesselations-wave-advance-2010.html
tags: [population structure, recent selection, diffusion, adaptation, R. A. Fisher, Holocene, acceleration, malaria, spatial dynamics] 
comments: false 
author: John Hawks 
---

Peter Ralph and Graham Coop have an interesting paper in the current <i>Genetics</i>, titled, "Parallel Adaptation: One or Many Waves of Advance of an Advantageous Allele?" <bib>Ralph:Coop:2010</bib> 

Fisher <bib>Fisher:1937</bib> famously considered the case in which an advantageous allele is dispersing through a spatially dispersed population, showing that the dispersal forms a "wave of advance". This work was the foundation for a lot of progress in understanding spatial dynamics of organisms. 

As I discussed in 2008 (<a href="http://johnhawks.net/weblog/topics/evolution/selection/acceleration/pickrell-hgdp-selection-2009.html">"Overstating the obvious"</a>), one of the consequences of the Fisher wave model for human evolution is that advantageous alleles will spread very slowly through the population. During the course of the Holocene, a strongly selected mutation might move only across a radius of a thousand or so kilometers. That provides one explanation for why new advantageous alleles haven't spread very far beyond their points of origin -- they just haven't had time yet. 

Another reason why an allele might not have spread widely is interference from other alleles with similar effects. I mentioned this process last year (<a href="http://johnhawks.net/weblog/topics/evolution/selection/acceleration/coop-2009-geography-recent-selection.html">"Spatial variation and near-fixed selected alleles"</a>): 

<blockquote>Greg Cochran and I have been discussing this idea for some time. We call it the "Stooge effect". Think of the Three Stooges all trying to run through a door at the same time and getting stuck in the middle. That's what these genes are doing -- all of them are competing to respond to selection, but each is slowed by the presence of the others.</blockquote>

Ralph and Coop have cleverly combined the "Stooge effect" phenomenon with spatial dispersal. They suppose a case in which two separate advantageous mutations arise in different geographic locations, each affecting the same trait. Each begins to spread independently as a Fisher wave of advance. What happens when they meet? 

As they show, the dynamics in this case give rise to a static equilibrium -- once the "waves of advance" meet, they stop moving, forming a stable boundary. A new favorable mutation makes headway only so long as it has no equally favorable mutation to compete against. 

I like the way they used both analytical approaches and simulations to come to this outcome. The appearance of stable boundaries in a reaction-diffusion system has long been known (demonstrated first by Alan Turing, actually!). But to my knowledge, no one has considered this specific case from an analytical perspective. 

The Fisher equation is not all that simple for most students to work with. If you become familiar with the equation, you will notice the key aspect is that it has two separate components -- a logistic (or reaction) component representing the increase in frequency at a single point in space, and a diffusion component representing the dispersal across space. 

The muscle of the dispersal process comes from the logistic component. Without the intrinsic growth of the selected allele, the dispersal of individuals along the boundary would not carry many copies of the selected allele into new geographic areas. If the local selective advantage dies, the wave of advance rapidly stalls. A static equilibrium arises, with the frequency of the selected allele forming a cline that correlates with the local selection pressure. 

Ralph and Coop's model approximates this case, in a dynamical sense. Each new selected mutation forms an increasing zone in which the selective advantage of <i>other</i> mutations is zero. When those other mutations encounter this zone, they form a stable cline. The cline is stable in the short term, but the diffusion component still disperses copies of an allele; they just lack the muscle to continue their deterministic expansion. 

The most interesting simulations by Ralph and Coop show the two-dimensional case, in which the stable boundaries emerge in a "tesselation" pattern. 

<div class="middle-picture">
<img src="/graphics/ralph-coop-tesselations-2010.png" width="440" height="288" alt="Tesselations" />
<p class="caption">Figure 6 from Ralph and Coop (2010), showing "tesselations" in 2-d simulations of waves of advance.</p>
</div>

The lower three panes in the figure show the stability of the boundaries between the selected alleles. They proceed to fixation locally, but their dispersal stops where they come into contact with other adaptive alleles. Over the very long term, the population will mix -- the diffusion process will slowly carry all these alleles throughout the species' range. Look at the process after a million generations and the entire zone will be gray. But this dispersal occurs at the neutral rate, where the diffusion term is the only factor driving the dispersal. 

<h4>What about humans?</h4>


My graduate student Zach Throckmorton and I have been working in this area for a while now. One of the things that impresses us is the way that much more interesting dynamics can emerge when you alter the assumptions. I learned some of this stuff by talking to Frank Livingstone, who gave a lot of thought to these issues of spatial dispersal and selection as applied to malaria resistance alleles. 

In particular, Frank thought about the case where one allele has a slightly larger advantage than another. In some contexts, this allows the "better" allele to overtake and swamp the expansion of the "weaker" (but nonetheless adaptive) one. In others, the two come to a near standstill, one displacing the other only very gradually. Much depends on the timing of the two mutations and the local conditions controlling their initial dispersal. 

Ralph and Coop briefly consider this case in their paper, noting that the difference in fitness advantage of two alleles will allow one to advance into the range of the other, albeit at a slower rate. In humans, we may be seeing a smaller subset of cases, where one or more of the alleles have not yet established a wavefront. In these cases, the arrival of another wave can disrupt the spatial pattern of the rarer allele. The diploid case gives rise to the possibility of more complex epistases. Well-defined boundaries between selected alleles are rare, and where they occur (as may be the case with HbC and HbS in Africa), many have focused on negative epistasis as an explanation. 

Also, alleles are unlikely to substitute perfectly for each other. In many cases, they may work synergistically -- individuals carrying two selected alleles that affect the same function may outperform those carrying only one such allele. At some point, new selected mutations may start to have diminishing returns, even on a trait like skin pigmentation where dozens of alleles may have been selected in widespread human populations. So the current distribution may to some extent be "frozen", but by a more complicated dynamic than the simple intersection of waves of advance. 

As Coop and colleagues showed last year <bib>Coop:2009</bib>, and we discussed in 2007 <bib>accel</bib>, there are really only few genes that have approached local fixation in recent human evolution. The current spatial pattern of recently selected alleles doesn't look like a tesselation with many alleles near local fixation.  Over most of the Old World, it looks like populations have a very large number of very new alleles, far from fixation, and few up over 70 percent in frequency. 

So the specific scenario in this paper <i>by itself</i> probably does not explain the overall empirical pattern in humans. But if we consider the current pattern as a transient, approximating the early stages of dispersal for many selected alleles, we may not be terribly far off the mark. 


<h4>Mutation-limited evolution</h4>

This is a long dense paper and there's a lot in it. One further aspect of the paper that I think is essential is the way that Ralph and Coop reiterate the basic point that more people means more mutations. In their case, they focus on population density over space (population number, when you multiply them) as a constraint on the number of possible adaptive mutations. They apply this idea as a hypothesis to account for parallel adaptations that may have emerged in recent human evolution. 

<blockquote>Multiple mutational origins are likely if the characteristic length is shorter than the physical dimensions of the region. Eurasia measures &gt;8000 km across, and so Table 1 suggests that multiple origins at a single base pair are very unlikely at the lower population density. On the other hand, if the mutational target is large, then multiple origins are likely at low densities, while at high densities independent origins are ubiquitous. The complementary cases of (rho = 2,  = 10<sup>8</sup>) and (rho = 0.002,  = 10<sup>5</sup>) give identical characteristic lengths of 3000 km, although the timescale on which the mutations spread differs. Thus for these two parameter combinations we can expect a few mutations to dominate within continents and for multiple mutations to be common in a population spread across an area the size of Eurasia. Obviously these calculations are very crude, as population densities vary through space and time, and dispersal across continents is not simply a function of geographic distance and individual dispersal. Nevertheless, these calculations suggest that it is plausible that for adaptive traits with reasonable mutational targets (e.g., a change anywhere within a gene or pathway) even low population densities can lead to parallel adaptation across an area the size of Eurasia, and higher densities almost certainly will.</blockquote>

<blockquote>We note that as human population densities have increased dramatically over time, so too has the probability of parallel adaptation. It is interesting therefore to note that a number of recent human adaptations (e.g., sickle cell alleles) involve repeated changes at very small mutational targets in relatively small geographic areas, while older adaptations from single changes (e.g., skin pigmentation) are more broadly spread.</blockquote>

They are describing a scenario in which small human populations would have been <i>mutation-limited</i> -- that is, the number of new mutations is small, making it unlikely that adaptive mutations will happen in any given generation. In such populations, the rate of adaptation is limited by the availability of new mutations. In an extreme -- in the very small effective sizes of Pleistocene human populations -- the rate of adaptation may be extremely slow and regional populations may come to differ at many weakly selected loci, which spread very slowly. 

As the population grows, strongly adaptive mutations become more and more likely to happen <i>somewhere</i> in the species' range. Yet they are still relatively rare -- meaning that they have an opportunity to spread fairly far before encountering another equally strongly selected mutation affecting the same trait. 

This process can give rise to very large differences on a continental scale, even when the selection pressures in different regions do not differ. In humans, the dispersal of selected alleles across space may have been significantly accelerated by actual dispersals of populations. It is not a mere coincidence that very widespread alleles in Eurasia also tend to be much older than 20,000 years old -- long-distance dispersals prior to that time had a higher chance of leaving a lasting influence on subsequent populations.

But as the population gets bigger and bigger, parallel mutations are more and more likely to happen. As Ralph and Coop point out, at the extreme of large population size and likely mutations, you shouldn't see any new mutations emerging and spreading over very large areas. Any of these mutations would be very likely to encounter other new mutations that do the same thing. 

Is this likely in humans? Clearly some mutations have happened recurrently. Making a broken gene is easy -- there's a large mutational target, since a large fraction of nonsynonymous substitutions might do the job. So if there's a net selective advantage to breaking a gene, we ought to see that happen recurrently in human populations. 

In contrast, if the mutational target is very small, then mutations will still be rare even in a very large population. If only one base change can have an adaptive effect, that precise change will happen less than once in 10<sup>9</sup> births (remember that not just <i>any</i> mutation at a site, but some <i>particular</i> mutation is what we may need). If a rare duplication or gene conversion is the necessary change, then it may be much rarer. 

Looking across the last few million years, when human population numbers were much smaller than the Holocene, we can be pretty sure that some aspects of our evolution were mutation-limited. The changes that took hold in our ancestors were the ones that happened, and that survived the winnowing of genetic drift. Many changes that <i>would have been adaptive</i> didn't happen in our ancestors. They just weren't lucky enough. 

But some of those changes would <i>still</i> be adaptive now, if we could get them. And we have had much larger numbers in the last 10,000 years. <i>Homo erectus</i> needed these mutations, but we only now are seeing them selected in the human population. 

<h4>Malaria adaptation</h4>

Hemoglobinopathies are among the cases of easy mutations -- where breaking a gene is adaptive. It's not just <i>any</i> broken version of alpha- or beta-globin that does the job, though. The hemoglobin needs to be impaired in certain ways to impede the parasites while maintaining blood function. This provides many of the classic cases of human adaptation, and Ralph and Coop turn to this system for examples of parallel adaptation: 


<blockquote>The sickle cell allele HbS at the ?-globin gene in humans provides a particularly interesting case of putative parallel adaptation. The HbS allele (?6 Glu-Val) has been driven to intermediate frequencies by selection within the past 10,000 years due to increased resistance to malaria of heterozygotes for the allele (HALDANE 1949; ALLISON 1954; CURRAT et al. 2002; KWIATKOWSKI 2005). The HbS allele is present on at least four major distinct haplotypes in Africa, each at intermediate frequency within a different geographic region; the haplotypes are named after the population sample where they were first discovered (Central African Republic, Senegal, Benin, and Cameroon). This is consistent with multiple origins of this single-base-pair change. Note that a distinct, malaria resistance allele, HbC (?6 Glu-Lys), has also arisen in Africa at the same codon as the HbS allele (TRABUCHET et al. 1991; AGARWAL et al. 2000; WOOD et al. 2005a), increasing our confidence that the mutational input was high enough to allow multiple types to arise. However, FLINT et al. (1998) thought the hypothesis of multiple new mutations arising at a single base pair was extremely unlikely and proposed that it was more likely that gene conversion had spread a single mutation across multiple haplotypes.</blockquote>


<blockquote>The theory we have developed can be used to assess the plausibility of the multiple mutational origins of the sickle cell allele, by exhibiting parameter combinations that yield characteristic lengths consistent with the separation of the sample locations. [Recall that the wave of advance, and thus also our model, works in the case of heterozygote advantage (ARONSON and WEINBERGER 1975).] The different HbS haplotypes co-occur within a few thousand kilometers of each other (see Table 5 of FLINT et al. 1998) (noting that these locations are unlikely to reflect the geographic mutational origins, and mutations will have been spread by large population movements). As the HbS changes occur at a single base pair, the mutation rate would have been 10<sup>8</sup>, and we take an s = 0.05 (as in CURRAT et al. 2002). If human dispersal at that time was well approximated by a Gaussian kernel with sigma = 100 km, then a characteristic length of 1000 km would require an effective density of individuals of rho = 25 km<sup>2</sup>, while if sigma = 10 km, then we would require only rho = 2.5 km<sup>2</sup>. This latter set of parameters does not seem unrealistic, considering our knowledge of population density and dispersal parameters, so our model suggests that the hypothesis of multiple origins is not unreasonable.</blockquote>


I think they've got the basic idea correct here, but there are some additional details to consider. The distribution of HbE is not quite so easy to understand if parallel mutations are really so likely, and of course there is the negative epistasis of different alleles (and the thalassemias) which impacts their dispersal ability when they become moderately common. The dynamic may be of similar form to the one described here, but boundaries between alleles may be reinforced by the fitness costs of carrying multiple ones. 

This situation raises the issue of path dependence. Some mutations have "first mover" advantages. Once they are common, other adaptive mutations may still occur -- even mutations that are <i>better</i> from the standpoint of fitness -- but be lost or grow very slowly because their net fitness advantage over the common mutant is slight. Where HbE is common, new HbS alleles are unlikely to invade quickly. Where HbS is common, new HbE mutants are similarly unlikely to invade -- even though HbE has a higher fitness. 

Network effects among genes may also dominate the spatial dynamics. HbS spread most widely in the context of populations that were already Duffy null, and in which G6PD deficiency was rapidly increasing. The first conditioned the parasite environment -- <i>P. vivax</i> had a strong disadvantage in Duffy null populations, <i>P. falciparum</i> made up most of the parasite load. G6PD deficiency should have impacted the relative advantage of HbS, more and more as it became more common. Those are two loci among many that alter malaria dynamics in Africa compared to South and Southeast Asia. 

<h4>Conclusions</h4>

There is much more to say about this paper -- it's 22 journal pages. But I think I've given an impression of what's there and how the ideas may impact our interpretation of recent human evolution. Many of the central concepts were presaged by earlier work in 2007 and 2008, as reviewed here on the blog. The new analytical and simulation work, I really like. 

Hopefully we can get out some shorter papers that will focus on aspects of these problems as applied to humans. A message that comes across very clearly in our work and this new paper is that different time periods in our evolutionary history must have had very different selection dynamics. Pleistocene humans were not only in a different ecology than us, they experienced a radically lower potential for adaptation. 

