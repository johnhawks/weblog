---
layout: single 
title: "Neandertal introgression, 1000 Genomes style" 
description: "We&#39;re quantifying the amount of Neandertal ancestry in whole genome data from living people." 
category: story
permalink: /weblog/reviews/neandertals/pigmentation/neandertal-introgression-1000-genomes-style-2011.html
tags: [Europe, Asia, China, Africa, introgression, Neandertals, African Americans, Puerto Rico, Neandertal DNA] 
comments: false 
author: John Hawks 
---

For our project to understand pigmentation genetics in archaic humans, we had to find a good comparative sample of sequence data from recent humans. The original publication on the draft Neandertal genomes compared them to five low-coverage genomes from different Old World populations, along with the publicly available genomes from Craig Venter and others <bib>Green:draft:2010</bib>. The first publication on the Denisova genome added an additional handful of genomes to these comparisons <bib>Reich:Denisova:2010</bib>. 

Some of these handful of genomes from living people are more similar to the Neandertal and Denisova genomes than others. That simple fact is the proof that some living people have Neandertal and Denisovan ancestors. 

But until now, the comparison has been limited to a very small number of human genomes. That became a focus for critics of the Neandertal and Denisovan results. How could three or four genome sequences possibly provide an adequate representation of human variability? We could imagine scenarios in which the similarities between Neandertal and humans could be explained by some unsampled population, for example, northeast Africans <bib>Hodgson:2010</bib>. Denisova does not present the same problem, because African population structure cannot possibly explain its resemblance to populations in Wallacea, Australia, and Oceania <bib>Reich:Denisova:2010</bib> <bib>Reich:Denisova:2011</bib>. But to compare either of these genomes, we should seek a broader sampling of genomes from living people. 

As I wrote yesterday, my students and I have been working to understand pigmentation genetics of the archaic human genomes (<a href="http://johnhawks.net/weblog/reviews/neandertals/pigmentation/pigmentation-project-intro-2011.html">"Pigmentation of archaic humans: introduction"</a>). I've emphasized the need to break the analysis into small steps. For this question, we need to examine whether the pattern of introgression around pigmentation genes is characteristic of the genome as a whole. If genes involved in pigmentation have systematically higher or lower levels of Neandertal ancestry, that will tell us a lot about the evolutionary history of pigmentation in recent and archaic humans. For this, we need a good comparative sample, and the 1000 Genomes Project provides the best sample available. 

The first step in assessing the pattern of introgression for pigmentation genes is to characterize the pattern of introgression across the whole genome. 

Yes, a whole-genome introgression analysis sounds awfully big for my "small steps" concept. But actually this is simpler than it might sound. Here's a teaser: 


<div class="middle-picture">
<img src="/graphics/introgression-vi3316-af-eu-as-2011.png" />
</div>

The figures in this post are not from a whole-genome analysis; they include data from eight chromosomes that we prioritized because of our pigmentation analysis. I am licensing all of them under a <a href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons ShareAlike license</a> so that anyone can use them anywhere. 

UPDATE (2011-12-10): I finished the whole genome analysis and am updating this post and figures accordingly. The results are the same throughout, with the exception of the Europe-East Asia comparison, which now shows these populations to be significantly different across the genome as a whole. I have partially updated the figures and will finish these later today.


<h4>The value of sequences</h4>

The 1000 Genomes Project data have been updated several times in the last year, as both sequencing and analysis of the genomes have progressed (<a href="http://www.1000genomes.org/">more information on 1000 Genomes Project website</a>). We downloaded a release of SNP genotype calls from 1094 individuals, based on the low-coverage (average 4x) sequencing that has been carried out on the sample. 

A SNP (single nucleotide polymorphism) is a nucleotide site with at least two alleles present in the global human sample. These sites represent only one kind of genetic variation in today's populations. Many of the differences between people's genes are caused by insertions, duplications, deletions, transpositions, or inversions. But those kinds of polymorphisms can be challenging to study in low-coverage genomes, and we already understand quite a lot about SNPs in human populations from the earlier HapMap project <bib>HapMap:2005</bib> <bib>McVean:HapMap:2005</bib>. The HapMap provided the data underlying our 2007 paper on the acceleration of recent human evolution (<a href="http://johnhawks.net/weblog/topics/evolution/selection/acceleration/accel_story_2007.html">"Why human evolution accelerated"</a>) <bib>accel</bib>. 

The drawback of earlier SNP variation projects is that they examined only a subset of SNP variation in a sample of people. To design a microchip that could provide a million or more SNP genotypes from a saliva sample, somebody first had to discover where in the genome SNPs could be found. So they took small samples of people, sometimes only a single person's two copies of the genome, and sequenced. Adding together SNPs found by several methods, they could get a representation of SNP variation across the whole genome in a population. But this process introduced a bias: the SNPs were <em>ascertained</em> in a sample that inevitably could not represent humans in other samples with the same accuracy. Initially, SNP samples were heavily biased toward people of European ancestry (upon whom most genetic work was originally done), and the HapMap project went to great efforts to increase the representation of other populations. But even with the best possible ascertainment, interpreting SNP variation requires us to jump through some theoretical hoops. 

Sequence data make life much easier for the population geneticist. Seriously, working on this stuff on the whiteboard is <em>fun</em> instead of a constant nightmare of sampling biases and spaces between markers. I have a bias myself, in that I find recombination hard to deal with. I love reticulation among populations, but I'd rather work with genealogies that look like proper trees instead of a liana-strewn mess. So looking at sequence data over short intervals makes me happy. Not as happy as beer aged in bourbon barrels, but happy. 

The 1000 Genomes Project SNP files represent every SNP mutation observed in the sample. In other words, these <em>are</em> sequence data, just with all the fixed (and therefore redundant) sites removed. Even so, these sequence data are not perfect. Low coverage means that some rare mutations in the sampled individuals will go unreported. We aren't typically interested in singleton mutations in the sample, except that missing them will introduce a bias upon our estimates of the time that common ancestors lived. Next-gen sequence reads are usually fairly riddled with errors. High coverage allows these errors to be removed with some confidence, but low-coverage genomes risk throwing out real SNPs along with the spurious ones. The publicly available files represent some analytical steps that we do not here control, so we have to work with the understanding that the data are not perfect. 

The 1000 Genomes SNP files have had a phasing algorithm applied to them, which attempts to assign genotypes to chromosomes. In essence, phasing tries to figure out whether adjacent SNP alleles belong to the same copy or to different copies of the same chromosome. The details of this phasing are not yet apparent, and for many reasons I am cautious about using phased data. The inference is often inaccurate for rare mutations, and the whole process tends to sneak assumptions about population history into the resulting dataset. I <em>hate</em> being forced to live with someone else's assumptions about human population history, and I typically try to avoid needing phased data. In this case, it looks like the data over short intervals are as accurate as they can be, given the limitations on coverage and sampling. We have moved forward by applying methods that make a bare minimum of assumptions. 


<h4>Counting derived SNP alleles</h4>

David Reich and colleagues came up with an appealingly simple test of introgression, which they applied to both the Neandertal and Denisovan genomes. Eric Durand, Reich, Nick Patterson and Monty Slatkin described the method formally this year <bib>Durand:2011</bib>, which they call the D-statistic. Informally, this has become known as the ABBA-BABA test, after their labels for the discordant genealogies that the test compares. By and large, across the genome, humans living today share many more new mutations with each other than they do with an archaic human like a Neandertal. But sometimes two genomes are different from each other, and one of them shares a new mutation with the Neandertal. 

A human might share a mutation with a Neandertal because it actually isn't very new, and both inherited the mutation from some much more ancient population of humans. This scenario is called "incomplete lineage sorting", because humans today have multiple gene lineages that existed within some very ancient population, instead of these having been "sorted" cleanly into the different human and Neandertal populations. Incomplete lineage sorting does happen a lot between humans, Neandertals, and Denisovans. ILS is the normal mode of variation among recent human populations, who trace their genealogical histories back much further than the earliest "modern" humans. So if one human has a Neandertal allele, and another human has a different allele, it's probably no big deal. They both just inherited gene variants that already existed in our distant common ancestors. 

You can probably see already that if we had a way to estimate the <em>age</em> of an allele, we could tell whether incomplete lineage sorting is a credible explanation for any particular site. <strong>I'll leave that point for another post.</strong> 

In the meantime, if we pretend that we know nothing at all about the ages of alleles, we must find some other way to tell whether incomplete lineage sorting can explain Neandertal similarities. Reich and colleagues recognized that incomplete lineage sorting from ancient pre-Neandertal ancestors <strong>ought to be distributed equally among living people</strong>. If we look at every site in the genome where we have data from Neandertals, we should find that one living human genome should look like the Neandertal <em>just as often</em> as another. 

This insight led to their test. Take a pair of humans, count the number of times sequence A is like the Neandertal and sequence B is like a chimpanzee, and then do the inverse &mdash; B then A. ABBA-BABA. 

Why a chimpanzee? In most cases the chimpanzee allele will represent the ancestral state for humans. Living people can inherit ancestral alleles from Neandertals as well as derived ones, but the derived ones tend to be rarer and younger within human populations. If one living genome shares an ancestral allele with the Neandertal genome, we don't need incomplete lineage sorting <em>or</em> introgression to explain the pattern. For all we know, such a mutation originated after Neandertals were already gone. So we need to pay attention to the <em>derived</em> mutations, ones that are present in Neandertals but not in chimpanzees. Do a count of these across the genome, and if you find a living genome with significantly more than another, you've found evidence for introgression. 

Ed Green, David Reich and colleagues <bib>Green:draft:2010</bib> <bib>Reich:Denisova:2010</bib> did a comparison of every possible pair of genomes in their modern human sample. These sequence data were gappy, so that sequence A might share different coverage with B than with sequence C. So it was necessary to consider each pair separately, counting all the sites where both human sequence and the Neandertal and chimpanzee sequences had data. 

The 1000 Genomes Project sample reports genotypes for every SNP for every sampled individual. So in principle, every pair of sequences should have data for every one of these sites. Again, we have to be cautious about the nature of the sequencing, attending to the possibility of systematic biases due to low coverage. But we really don't have to take the time-consuming step of comparing every possible pair of the 2188 resulting haploid genomes. We can just find the derived SNP alleles that are present in Neandertals and count how many of them are in each of the human sequences. If one sequence has significantly more Neandertal derived alleles than another, it had to get them somehow. 


<h4>That magic three percent</h4>

The figure at the top of the post represents that count. Every individual in the 1000 Genomes Project dataset has two copies of the autosomal genome. Separating these two copies of the genome (basically arbitrarily) and counting up the shared derived features between each of those copies and the genome of Vindija 33.16, we obtain the histogram. Here it is again: 

<div class="middle-picture">
<img src="/graphics/introgression-vi3316-af-eu-as-2011.png" />
</div>

The African genomes in the 1000 Genomes sample include Yoruba from Nigeria and Luhya from Kenya. The Asian populations sampled are Japanese and Chinese, including people of Han Chinese ethnicity in Beijing and southern China. The European ancestry samples include the CEU sample from Utah, as well as British, Tuscan, Spanish and Finn samples. 

The histogram shows that Asian and European genomes have significantly more Neandertal derived SNP alleles than do the African genomes. The averages for the Asian and European samples are around 3% higher than the average for the African samples. Whatever gave Africans some degree of similarity to Neandertals, non-Africans seem to have gotten around 3% <em>more</em> of it. 

Green and colleagues <bib>Green:draft:2010</bib> assumed conservatively that Africans share derived SNP alleles with Neandertals only because of incomplete lineage sorting from the human-Neandertal ancestral population. This fraction should be the same in all human populations, under the assumption that Africans were mostly isolated from Neandertals for some period of time. The 3% Neandertal bonus outside Africa should then represent introgression from Neandertals into recent populations outside Africa. 

Both previous studies noted that genomes outside Africa are not significantly different in the fraction of derived SNP alleles shared with Neandertals. A genome from China and a genome from France carried the same fraction of shared derived SNP alleles with Neandertals. Here, we've confirmed that basic identity in the level of introgression in these populations. 

I have told several people now that I find the distributions in China and Europe <b>spookily similar</b>. On parts of the genome, the two distributions have means that are not significantly different. Indeed, I worked for a week with an analysis of eight chromosomes, in which the East Asian and European means were fewer than 100 SNP alleles apart. Even across the whole genome, Europeans average only 700 derived SNP alleles more than the East Asian sample. This small difference a bit more than a tenth of a percent) is strongly significant on these sample sizes. A t-test yields a <em>p</em>-value of 1.1 times 10<sup>-26</sup> on the difference in means. Even so, the distributions of these two populations overlap across most of their ranges. 

<div class="middle-picture">
<img src="/graphics/introgression-vi3316-eu-as-2011.png" />
</div>

Seeing these hundreds of genomes arrayed on a histogram provides much more information than we had from a handful of genomes. It is remarkable how much dispersion there is among genomes from a single population. Although the means of these two samples are nearly the same, you can see that each of them has a large range of variation in the shared derived SNP alleles with Neandertals. This variation means that people within a single population have very different proportions of Neandertal ancestry. 

This is not a graph of people, but a separation of the two copies of SNP alleles carried by these people. That separation is phased at short scales but arbitrary on the scale of a whole chromosome, so the histogram likely understates the variance among single genomes while it overestimates to some extent the variation among people with their diploid genomes. Still, it looks likely from these comparisons that some people in Europe carry more than a percent higher Neandertal ancestry than the average, and some carry a percent less. We can use statistical methods to test this hypothesis directly as applied to individuals in the sample. 


<h4>Neandertal genes in recently admixed populations</h4>

A sample of hundreds of people allows us to demonstrate significant differences among the genomes of different populations. Some of the 1000 Genomes Project samples are from populations that represent historically recent admixture of people who trace their ancestry to different parts of the world. 

For example, the "ASW" population sample includes African-American people who live in the Southwest United States. We know from many other genetic studies that African-Americans vary in the fraction of ancestry they derive from Europeans and from Africans. The average amount of African and European ancestry varies among African-Americans who live in different parts of the U.S., as low as 3% and as high as 20% or more in some parts of the country. The proportion among individuals varies even more. So when we consider the ASW sample, we should expect to see a lot of variation in the number of shared derived SNP alleles with Neandertals, with a mean higher than African populations. 

Which is exactly what we do see: 

<div class="middle-picture">
<img src="/graphics/introgression-vi3316-asw-yri-ceu-2011.png" />
</div>

The ASW sample overlaps substantially with the Yoruba sample from West Africa (Nigeria) and slightly with the CEU sample, which includes people of European ancestry in Utah. The total in the ASW genomes is more variable than either the Yoruba or CEU population samples. If the higher mean in the ASW genomes reflects European ancestry from a population like CEU, the proportion of European ancestry would be around 17% for that sample of people. It would be hard to tell from these numbers alone how much of the variation in ASW is attributable to variation in ancestry fraction, and how much is expected within a population of homogeneous ancestry. As we'll see in some other populations, there are some appreciable differences among populations within a given region, and ancestry differences may add to the variation among individuals within populations. 

We see a similar pattern when we look at the Puerto Rican sample. Individuals in this sample have some ancestry from European, Native American and African ancestors. The comparisons by Reich and colleagues <bib>Reich:Denisova:2010</bib> and Green and colleagues <bib>Green:draft:2010</bib> suggested that Native American populations have the same fraction of Neandertal ancestry as other people outside Africa. In the comparison with YRI and CEU samples, Puerto Rican (PUR) genomes are intermediate, with a mean suggesting around 15% ancestry from the West African population. 

<div class="middle-picture">
<img src="/graphics/introgression-vi3316-pur-yri-ceu-2011.png" />
</div>

The two outlier points in the Puerto Rican sample are the two genome copies from one individual, who we would hypothesize had much higher African ancestry than the average in the sample. 

<h4>Next...</h4>

This post has taken me much longer than I expected to get to the point of talking about variation among samples within continental regions. It turns out that, despite the similarity of European and East Asian samples in their averages, there are substantial differences between samples within each of these regions. 

For example, here's a comparison of north and south Chinese samples: 

<div class="middle-picture">
<img src="/graphics/introgression-vi3316-chb-chs-2011.png" />
</div>

People of Han Chinese ethnicity sampled in Beijing appear to have on average a half percent more Neandertal ancestry than people of the same ethnicity sampled in southern China. I found these kinds of differences almost everywhere I looked within regions. More later...

