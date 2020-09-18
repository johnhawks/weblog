---
layout: single
title: "Neandertal similarity in the HapMap samples"
description: "In this post (from 2012), I examine the pattern of Neandertal ancestry in India and East Africa."
category: story
permalink: /weblog/reviews/neandertals/neandertal_dna/hapmap-introgression-neandertals-2012.html
tags: [India, Neandertal DNA, my research, HapMap, East Africa, introgression, population structure]
comments: false
author: John Hawks
---

*This post is from 2012 and the results here are no longer current. Readers can find more current information about Neandertal introgression in later posts.*

In my last installment on Neandertal introgression in present-day human samples, I covered whole genome data from the 1000 Genomes Project (<a href="http://johnhawks.net/weblog/reviews/neandertals/neandertal_dna/1000-genomes-introgression-among-populations-2012.html">"Which population in the 1000 Genomes Project samples has the most Neandertal similarity?"</a>. For the next few weeks I'll be releasing more of these comparisons, made with the help of my Ph.D. student, Aaron Sams.

Just to remind about our methods for comparing genomes, what we have done is to examine every base reported as a single nucleotide polymorphism by the 1000 Genomes Project. If the sequencing data had no errors, then this would be an account of every point mutation in the human genome. However, the data are imperfect in various ways, as I'll note below. Likewise, the Neandertal sequence data are imperfect in various ways.

Here's one of the 1000 Genomes Project comparisons, showing the histogram for pooled European, African, and Chinese samples. In this chart, the number of shared Neandertal derived SNP alleles is the <em>x</em>-axis, divided into bins of around 500. The <em>y</em>-axis is the number of individual genomes in the sample found in each bin. So on this chart, the largest number of European genomes (nearly 120) share very approximately 645,000 derived SNP alleles with the Vindija 33.16 genome.

<div class="middle-picture">
<img src="/graphics/introgression-europe-china-africans-vi3316-nox.png" alt="Comparison of shared Neandertal derived variants in African, Chinese and European samples" />
</div>

I find it necessary to be very explicit about these charts, because after showing them to many people I know how easily they can be misinterpreted. It's natural to assume that they are bar charts, where higher <em>y</em> values mean more Neandertal. But with more than 2000 genomes to compare, a bar chart is really just noise. These histograms are much like bell curves, in which the shape of the distribution on the <em>y</em>-axis indicates the dispersion within the population of Neandertal shared alleles.

<h4>Percentages</h4>

Everyone is excited to find out what percentage of Neandertal ancestry people have. I'm hesitant to report percentages, because I think they are misleading on these data. There is some filtering hiding beneath the data. In particular SNP alleles that are found only in one individual ("singletons") are likely to be undersampled by the project's sequence analysis. Because gene variants that have introgressed from Neandertal populations tend to be rare in present-day samples, when we miss some rare alleles, this tends to reduce our estimate of Neandertal similarity. This bias in resequencing data should affect populations roughly in proportion to their Neandertal ancestry. Our comparisons of different populations are therefore likely to give the right <em>order</em> of Neandertal ancestry (e.g., Europeans more than Asians) but may underestimate the total <em>fraction</em> of ancestry by some amount. We are counting human SNP variants and not every base pair in the Neandertal genome data, so the effect of sequencing error in the Neandertals will be minimal, but nevertheless present in a small fraction of comparisons. These errors should be randomly distributed with respect to human population differences, but they also add noise that should decrease the accuracy of percentage estimates.

For another thing, we don't know where the zero point may be. Europeans have around 3 percent more than Yoruba; Yoruba (as I showed in the last post) have around a half percent more Neandertal similarity than Luhya in the 1000 Genomes Project sample. The Luhya are almost certainly not minimal for living people, in fact I would put some money against it. Since some Neandertal alleles have proceeded right up to high frequencies outside Africa, there has been ample opportunity during the last 30,000 years or more for other alleles to have spread into Africa.

Our conservative approach is to rely on comparisons of large samples of people, ideally hundreds, and to trust a comparison only when it achieves statistical significance in these samples. That still allows us to detect very slight excesses of Neandertal ancestry in some populations, because the data from hundreds of individuals is very strong evidence. But the overlap among populations is sometimes very extensive even if their means differ significantly.

Incomplete lineage sorting (ILS) is one pattern by which living people share alleles with Neandertals. ILS should be equally distributed among populations today, under the assumption that Neandertals and ancestral Africans stem from a single unstructured population. Obviously, Europeans and Asians share more derived SNP alleles with Neandertals than do Africans today, so we can strongly reject the hypothesis of isolation between African and Neandertal populations.

Given that, three patterns of evolution could have caused some populations to share more derived alleles with Neandertals than others.

1. Population structure in the ancestors of Africans and Neandertals may have caused some populations to share more ILS with Neandertals than others.

2. Continued gene flow between Neandertals and Africans could have spread Neandertal alleles into Africa and vice-versa.

3. Recent introgression from Neandertal populations into the ancestors of today's populations may have transferred new Neandertal alleles into recent humans.

These three processes actually overlap with each other. Very likely all three of them happened -- although to date, the descriptions of Neandertal genome data have accentuated the last and argued that the first two are relatively less important <bib>Green:draft:2010</bib> <bib>Yang:ancient:2012</bib>. A "new" allele in a Neandertal may actually have originated from a mutation more than a half million years ago, have been lost within ancient Africans, and transferred into today's Europeans when they encountered and mixed with Neandertals. We cannot tell these processes apart from the standpoint of any single SNP allele. Only by comparing many SNP alleles across many populations can we sort out their relative importance.

To this end, we have been comparing populations with each other and ancient Neandertals in many different ways. The 1000 Genomes Project has continued to sample and resequence many of the same samples that were initially amassed for the International HapMap Project. The HapMap was a project based on genotyping individuals with microarray technology. Genotypes are just as informative in many cases as whole-genome sequences. If you already know which genetic variations you want to examine, a microarray can save a substantial amount of wasted effort.

With Neandertal comparisons, we don't start out knowing in advance which genotypes will be useful. For this reason, genotyping data yields a potential bias when comparing to Neandertal or other human genomes. The microarray was designed to include genotypes that were already known to vary in some human population. With the HapMap, this bias tends to overrepresent the genetic variations in the initial HapMap samples -- generally, Utah residents of northern European descent, ethnic Yoruba people from Nigeria, ethnic Han Chinese from Beijing, and Japanese people from Tokyo. If these samples share some common derived SNP alleles with Neandertals, they will very likely be represented in the genotyping array. But very rare alleles won't be represented. And alleles that are uniquely in <em>other</em> populations -- such as East Africans or South Asians -- may not be represented, either. The bias is called "ascertainment bias" because it comes from the "ascertainment" of SNPs, or their initial discovery in some populations but not others.

It is possible now to find sets of SNP markers that have been statistically chosen to minimize ascertainment biases. The filters used in such comparisons are complex, and in some cases actually rely on the Neandertal genotype, so I haven't used them here. For our first paper we have focused on the whole-genome sequence comparisons, but here I'll give the same comparisons on some HapMap samples to show approximately where they fit. I will focus here on raw comparisons instead of standardizing them in terms of the predictive ability of informative SNPs on whole genome data. Finding the most informative SNPs is part of the process of sorting introgression from earlier population structure, and is rather more complex; I prefer to start with something very simple and visually easy to interpret.

<h4>South Asia</h4>

One interesting place is India. The HapMap includes a sample of Indian-Americans with origins in Gujarat, in western India. Here's a plot comparing the Gujarat ancestry (GIH) sample with the CEU and LWK samples:

<div class="middle-picture">
<img src="/graphics/ceu-lwk-gih-vi3316-nox.png" alt="Comparison of shared Neandertal derived variants in CEU, LWK and GIH samples" />
</div>


The GIH sample has substantially fewer shared Neandertal derived SNP alleles than the CEU sample. What may be more curious is that the GIH sample also has fewer than East Asians on average. The JPT+CHB samples, for example, exceed the GIH mean by around 100 derived SNPs.

<div class="middle-picture">
<img src="/graphics/jptchb-lwk-gih-vi3316-nox.png" alt="Comparison of shared Neandertal derived variants in JPT+CHB, LWK and GIH samples" />
</div>

On a mean of more than 43,000, 100 is around a fourth of a percent, so it's not much -- and it may fall within the amount expected from ascertainment bias. It will be much more enlightening to have GIH whole genome data. In the meantime, we can probably confirm the picture from sequence data that indicates Europeans today have the highest degree of Neandertal ancestry.

<h4>East Africa</h4>

The situation within Africa is potentially very complex also. From sequence data, we were able to show that Yoruba (YRI) and Luhya (LWK) population samples have different numbers of shared derived Neandertal SNP alleles. The YRI sample in West Africa has significantly more Neandertal similarity than the LWK sample in East Africa. We speculate that this relation may reflect trans-Saharan gene flow, which has continued throughout history and prehistory.

Is this a question of east versus west in Africa? That might seem unlikely considering the extent of population movements into northeastern Africa and continued trade along the East African coast throughout historic time.

The HapMap includes a sample of ethnic Maasai people from Kenya, which allows us to provide another perspective on African variation. Here is the chart, compared to LWK and CEU:

<div class="middle-picture">
<img src="/graphics/ceu-lwk-mkk-vi3316-nox.png" alt="Comparison of shared Neandertal derived variants in CEU, LWK and MKK samples" />
</div>

The Maasai have substantially more Neandertal similarity than Luhya, despite their present geographic proximity. In fact, the mean amount of Neandertal similarity in the Maasai is approximately the same as that in the ASW sample, which is composed of African-American ancestry people in the Southwest U.S.:

<div class="middle-picture">
<img src="/graphics/ceu-lwk-asw-vi3316-nox.png" alt="Comparison of shared Neandertal derived variants in CEU, LWK and ASW samples" />
</div>

You see immediately more dispersion in the African-American ancestry sample, because the mixture between African and European ancestors is more variable and much more recent than the events that gave rise to the Neandertal ancestry of Maasai people.

We speculate that there may have been a substantial amount of interaction in northeast Africa. Obviously this has been true in historic times, but the Maasai suggest that it may go back long before the origins of the present ethnic groups and their movements into this area. The present heterogeneity of Neandertal similarity in these populations suggests a really complex population history. Some of the present Neandertal similarity may derive from ILS within the ancient African population.

<h4>Probing assumptions</h4>

Of course my lab is not the only one presently engaged in comparing the archaic human genomes with recent populations. One of the reasons why we're pursuing a more open science strategy in our reporting is that different groups using different methodologies ought to converge on the same population history. Where we see different results, it's often an indication that the alternative approaches involve substantially different assumptions about the way ancient humans interacted. As we've probed more deeply into the data, we have confronted the reality that long-term population mixture between Neandertal and African ancestral populations is extremely difficult to rule out. Assuming that long-term interactions were impossible because Neandertals and Africans were completely isolated will probably lead to erroneous results. That makes it harder for us to clearly identify gene variants that came from Neandertals within the last hundred thousand years, as opposed to those shared with Neandertals via more ancient gene flow.

What makes long-term interactions seem more likely is that some of the Neandertal genomes seem to be more closely related to living people than others. More on that in my next installment.




