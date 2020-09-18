---
layout: single 
title: "The problem with HapMap: a parable of potholes" 
category: story
permalink: /weblog/reviews/genomics/selection/hapmap_mcvean_2005.html
tags: [genomics, natural selection] 
comments: false 
author: John Hawks 
---

<p>
I've been sifting through some HapMap-related stuff. It's a tremendous resource for looking at human variation, but it also presents some tremendous problems. <a href="http://genetics.plosjournals.org/perlserv/?request=get-document&doi=10.1371/journal.pgen.0010054">An interesting review</a> of some of the information coming out of HapMap by Gil McVean and colleagues is running in PLoS Genetics. 
</p>

<p>
These guys are statisticians working to analyze some of the data, and they put into words very well some of the issues I've been butting against. 
</p>

<blockquote>There is great heterogeneity across the genome in terms of patterns of genetic variation. Some of this heterogeneity is due to variation in factors such as mutation rate and recombination rate. Some of this heterogeneity arises because of the stochastic properties of mutation and genealogical history. But there are also other forces such as natural selection and genomic features such as inversions that may influence local patterns of variation. How can we look for the effects of such factors? There are two approaches. Either we can try to predict what we would expect to observe under models with and without such effects [23,24], or we can simply look at the empirical distribution of statistics of genetic variation and take as candidate regions those showing extreme or unusual patterns. The difficulty of the first approach is that <b>accurately modelling human variation (and SNP ascertainment) is probably impossible</b>. The difficulty of the latter approach is that there is no guarantee that empirically unusual patterns point to biologically interesting features (McVean et al. 2005:e54, emphasis added).</blockquote>

<p>
I would add that there is an additional difficulty with the second approach -- namely, that it assumes that selection or other factors cause <i>heterogeneity</i>. More about that later. 
</p>

<p>
This point about ascertainment and demography is an important one. Predictions about the effects of evolution (including drift) upon genetic variation are simplest under random sampling. Since the beginning of human genetics, almost no one has attempted to sample people at random. Some nonrandomness may be desirable -- for example, recent demographic changes make a random sample of today's humans very different in composition from a random sample of humans in 1491, or 6000 B.C., or almost any time in the past. Which of these "random" samples would represent the population whose history we care about? If we are interested in prehistoric events, we may find it desirable to represent peoples in proportion to their prehistoric distributions. This has precisely been the approach of some genetic surveys. 
</p>

<p>
But even from this simple example, the problems with human demography are clear. We can try to shift samples to represent prehistoric "distributions" of populations, but geography is not the only aspect of demography that has changed. There have been massive population mixtures that would never have had the opportunity to occur in prehistoric times. There have been diseases and demographic crashes that we know about, and probably many that we don't know about. 
</p>

<p>
The question is whether it is possible to arrive at a "rough draft" of human demographic history that would be precise enough to generate theoretical distributions of human variation. As it happens, that is precisely the goal of <a href="http://www.genome.org/cgi/content/full/15/11/1576">this paper by Stephen Schaffner and colleagues</a> in <i>Genome Research</i>. From the abstract: 
</p>

<blockquote>With the advent of large empirical data sets, it is now possible to calibrate population genetic models with genome-wide data, permitting for the first time the generation of data that are consistent with empirical data across a wide range of characteristics. We present here the first such calibrated model and show that, while still arbitrary, it successfully generates simulated data (for three populations) that closely resemble empirical data in allele frequency, linkage disequilibrium, and population differentiation. <b>No assertion is made about the accuracy of the proposed historical and recombination model</b>, but its ability to generate realistic data meets a long-standing need among geneticists (Schaffner et al. 2005:1576, emphasis added). </blockquote>

<p>
The problem with the approach is precisely in the boldface sentence. It is possible to <i>use</i> empirical data to <i>calibrate</i> a model that generates <i>simulated</i> data that is similar to the <i>empirical</i> data. The point of using such a calibrated model is to be able to show how strange certain regions are if they <i>don't</i> fit the simulated distribution, which is based on the empirical distribution. 
</p>

<p>
But it's all circular.
</p>

<p>
Suppose we wanted to use a detailed topographic survey of a road to find the potholes. But for everyday roads, there is a problem -- there are lots of bumps and grooves that <I>aren't</i> potholes. And different parts of the road are more or less bumpy. It would help a lot if we could use the empirical distribution of bumps to simulate a section of road -- then we could figure out whether anomalies in the real road were likely to be potholes or not. 
</p>

<p>
Now suppose that the road isn't just pocked with the occasional pothole -- it has a pothole every three or four feet. Remember why we're using simulations -- not only do we not know where the potholes are, we don't know how common they are. So our simulations based on the pothole-rich road will find that pothole-sized bumps are normal. If pothole-sized bumps are not unusual, then our simulation can have only one result: <i>a pothole is not a pothole</i>. 
</p>

<p>
Consider <a href="http://biology.plosjournals.org/perlserv/?request=get-document&doi=10.1371/journal.pbio.0030378">this current paper on the <i>CCR5&#916;32</i> allele</a>, generally thought to be recently selected in Europeans as a disease defense against smallpox (<a href="http://johnhawks.net/weblog/reviews/genetics/disease/delta_ccr5_novembre_2005.html">my earlier entry</a>). Sabeti et al. (2005) revise the date of the mutation from only around 700 years ago to around 5000. But more important, they deny that the allele was necessarily selected. Why? <i>Because its pattern of linkage disequilibrium is relatively common across the genome.</i>

<blockquote>Our reanalysis of CCR5 shows that CCR5-&#916;32 does not clearly stand out from the rest of the genome in terms of allele frequency distribution, population differentiation, or long-range LD (Figure S8). The high population differentiation and long-range LD found for CCR5-&#916;32 are, in fact, far more common in the genome than previously believed, and therefore do not provide support for the hypothesis of strong selection for CCR5-&#916;32. Using methods described both in the previous study [8] and in the current study, and by examining currently available data, there is no detectable evidence for recent selection for CCR5-&#916;32 (Sabeti et al. 2005:e378). </blockquote>

<i>Ceci n'est pas un pothole</i>. 
</p>

<p>
Why is it that simulations like these are not attempts to make accurate historical models? Quite simply, because they can't. After years of attempts at reconstruction human evolution based on "neutral" genetic loci, the HapMap at last has thrown out the possibility entirely. If we want to use the broadest source of information, we have to take with it some significant lumps. And one of the biggest is that we simply don't know the selective dynamics of most of the genome. 
</p>

<p>
For the anthropologist interested in history, it is not critical that we be able to develop a model of demographic history accurate enough to serve as a theoretical distribution for testing selection. Our goals are often much less ambitious, and there is much information about demographic history to be had from the HapMap and like projects. But neither should we minimize the problems. Attempting to use simulations to match the variation of the genome as a whole simply isn't going to work, if any substantial proportion of the genome has been under recent selection. And as we move to higher parameter models of demography (Schaffner et al. 2005 attempt a 21-parameter model) selection on relatively few sites becomes more and more capable of distorting demographic estimates. 
</p>

<p>
By far the worse problem is finding selection. 
</p>

<p>
For example, McVean et al. (2005) embark upon an examination of the "tails" of the genome -- the parts that show highly unusual patterns of variation compared to most regions. The idea is that if these very unusual loci had areas of biological interest (i.e., particular genes), their very strangeness might lead to a hypothesis of historical change (such as selection). 
</p>

<p>
But they run into problems: 
</p>

<blockquote>Of the 19 genes with previous evidence for historical selection, 12 show an unusual pattern of genetic variation in at least one population (defined as having a value lying in either the bottom 5% or top 5% of empirical values). Superficially, this result suggests that statistical tests based on rejecting a simple population genetics model are effective at detecting genes of interest. However, for 114 tests, we might expect 11 to lie in either the top or bottom 5% of observations, compared to the 17 observed. Another concern is that genes of known functional and selective importance, such as Duffy and CD40 ligand, do not fall in the tails of the empirical distribution of Tajima's D and Fay and Wu's H statistics and others, such as MMP3, hemochromatosis (HFE), and aldehyde dehydrogenase 2 (ALDH2) show patterns that are unusual, but not indicative of the action of recent selective sweeps.</blockquote>

<p>
Multiple comparisons are pretty tricky across the entire genome and in multiple populations. Considering this, we might see the HapMap and similar surveys as hotbeds of type II error: if we go looking for strange things, we are going to miss the forest for the trees. 
</p>

<blockquote>There are two main conclusions from these analyses. First, that biologically interesting loci often do have unusual patterns of genetic variation, but that there is no single way of measuring "unusual" that is uniformly powerful for detecting the action of natural selection. Second, that rejection of neutral evolutionary models is no guarantee that the locus is unusual when compared to the rest of the genome (McVean et al. 2005:e54). </blockquote>

<p>
"Unusual compared to the rest of the genome" is a phrase you should expect to hear a lot of in the next few years. 
</p>

<h4>References:</h4>

<p class="cite">McVean G, Spencer CCA, Chaix R. 2005. Perspectives on human genetic variation from the HapMap project. PLoS Genetics 1:e54. <a href="http://genetics.plosjournals.org/perlserv/?request=get-document&doi=10.1371/journal.pgen.0010054">Full text (free)</a></p>

<p class="cite">Sabeti PC et al. 2005. The case for selection at <i>CCR5-&#916;32.</i> PLoS Biol 3:e378. <a href="http://biology.plosjournals.org/perlserv/?request=get-document&doi=10.1371/journal.pbio.0030378">Full text (free)</a></p>

<p class="cite">Schaffner SF, Foo C, Gabriel S, Reich D, Daly MJ, Altshuler D. 2005. Calibrating a coalescent simulation of human genome sequence variation. Genome Res 15:1576--1583. <a href="http://www.genome.org/cgi/content/full/15/11/1576">Full text (free)</a></p>

