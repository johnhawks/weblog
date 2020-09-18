---
layout: single 
title: "Now for anthropological genomics" 
category: story
permalink: /weblog/reviews/genomics/variation/1000-genomes-2010.html
tags: [sequencing, population structure, recent selection, 1000 Genomes Project] 
comments: false 
author: John Hawks 
---

The first of the papers describing results from the 1000 Genomes project has been released today in <i>Nature</i> <bib>1000Genomes:Nature:2010</bib>. 

This is "big project" genomics news. Like many announcements of this kind, it represents more of a public relations milestone than actual scientific advance. Some of the project data have been publicly available for a while -- the 1000 Genomes and HapMap projects have to their great benefit been based on the strategy of immediate data release. The new paper and its supplements include many summary statistics and report on new genetic variants that have been found -- there's a lot of information here. But most of the interesting science is just getting started. A paper like this really represents the opening of a race to use the new data for innovative research.

Here in my lab, we are exploring the ways that whole genome sequencing can change our study of human population history. A large part of this is our work on recent selection, of course (<a href="http://johnhawks.net/weblog/topics/evolution/selection/acceleration/accel_story_2007.html">"Why human evolution accelerated"</a>). Whole-genome sequencing is not essential to finding many recently selected regions of the genome, but it will help enormously in narrowing down the actual functional changes that affected fitness in past populations. 

Whole-genome sequencing will rapidly improve our ability to resolve the population history of Pleistocene humans. For older events -- going back to the origins of <i>Homo</i> -- whole-genome sequencing will give us samples of genealogies from across the genome. We will be able to resolve some very ancient episodes of population mixture, and we have a chance of testing what kinds of events accompanied the rise of our genus. Even for events of the Late Pleistocene and Holocene, for which haplotypes of SNP markers can be useful without resequencing, whole-genome sequencing can be tremendously valuable. Reconstructing haplotypes from diploid genotypes requires us to make some assumptions about the demography of the population, which may be exactly what we are trying to discover. A sample of genomes sequenced at high read coverage will free us from some of those assumptions. It's really exciting stuff for an anthropologist. 

All those are reasons why the data will be useful for us in the long term. But at the moment, the data are not nearly so rich. The current paper reports: 

1. Whole-genome sequencing at 42x coverage of six individuals, one three-person family trio from Utah, and one family trio from Nigeria. 

2. Low-coverage (2x-6x) sequencing of 59 Yoruba, 60 Utah residents, 30 Chinese and 30 Japanese individuals. These are a subsample of the original HapMap samples. 

3. Sequencing at 50x coverage of 8140 exons in 697 individuals. These are a subset of the HapMap v.3 population samples, including Yoruba, Luhya, Utah, Tuscan, Japanese and Chinese samples. These exons come from 906 genes targeted "randomly". 

It's pretty far from a thousand genomes, and even farther from the stated goal of 2400 genomes. The low-coverage genomes are not sufficient to call genotypes across most of the genome. This is a persistent problem with "whole-genome" sequencing projects so far. A person's whole genome is mostly <i>diploid</i> -- two copies of most everything. Recently, we've seen several "whole-genome" sequences where each base is given a consensus value. SNP variants may be called against <i>other</i> people's genomes, but rarely is there sufficient coverage to call SNPs <i>within</i> the individual. There are exceptions -- a handful of public whole genomes are at high coverage. The exon sequencing here should be enough to call SNPs in these functional regions with great confidence. The family trios also should have enough to call SNPs. So some of these will be our first chance to do actual population genetics on diploid genome-wide sequence data. 

One important piece of analysis in the paper is the confirmation of a low rate of <i>de novo</i> mutations in the children of the family trios. I discussed a result last spring that came to a very low rate of per-site mutation (<a href="http://johnhawks.net/weblog/reviews/genetics/divergence/roach-family-quartet-mutation-rate-2010.html">"A low human mutation rate may throw everything out of whack"</a>). The rate in that paper was 1.1 x 10<sup>-8</sup> per site per generation. The current paper comes to a rate between 1.0 and 1.2 x 10<sup>-8</sup>. I have some more written on this issue and I'll integrate the new finding and post it later in the week. This aspect of the study is pretty important to our understanding of human evolution. 


The paper makes an interesting distinction between "accessible" and "inaccessible" portions of the genome -- accessibility meaning ease of mapping and aligning sequence reads: 

<blockquote>Accurate identification of genetic variation depends on alignment of the sequence data to the correct genomic location. We restricted most variant calling to the accessible genome, defined as that portion of the reference sequence that remains after excluding regions with many ambiguously placed reads or unexpectedly high or low numbers of aligned reads (Supplementary Information). This approach balances the need to reduce incorrect alignments and false-positive detection of variants against maximizing the proportion of the genome that can be interrogated.</blockquote>

<blockquote>For the low-coverage analysis, the accessible genome contains approximately 85% of the reference sequence and 93% of the coding sequences. Over 99% of sites genotyped in the second generation haplotype map (HapMap II)4 are included. Of inaccessible sites, over 97% are annotated as high-copy repeats or segmental duplications. However, only one-quarter of previously discovered repeats and segmental duplications were inaccessible</blockquote>

It's an interesting decision -- just focus and report on the majority of the genome where alignment is easier. 


The paper discusses selection briefly. There's not much new here other than the identification of candidate causal variants for some selected haplotypes. 

<blockquote> First, it provides a more comprehensive catalogue of fixed differences between populations, of which there are very few: two between CEU and CHB+JPT (including the A111T missense variant in SLC24A5 (ref. 38) contributing to light skin colour), four between CEU and YRI (including the ?46 GATA box null mutation upstream of DARC39, the Duffy O allele leading to Plasmodium vivax malaria resistance) and 72 between CHB+JPT and YRI (including 24 around the exocyst complex component gene EXOC6B); see Supplementary Table 7 for a complete list. Second, it provides new candidates for selected variants, genes and pathways. For example, we identified 139 non-synonymous variants showing large allele frequency differences (at least 0.8) between populations (Supplementary Table 8), including at least two genes involved in meiotic recombinationFANCA (ninth most extreme non-synonymous SNP in CEU versus CHB+JPT) and TEX15 (thirteenth most extreme non-synonymous SNP in CEU versus YRI, and twenty-sixth most extreme non-synonymous SNP in CHB+JPT versus YRI). Because we are finding almost all common variants in each population, these lists should contain the vast majority of the near fixed differences among these populations. Finally, it improves the fine mapping of selective sweeps (Supplementary Fig. 14) and analysis of the dynamics of location adaptation. For example, we find that the signal of population differentiation around high Fst genic SNPs drops by half within, on average, less than 0.05 cM (typically 3050?kb; Fig. 5d). Furthermore, 51% of such variants are polymorphic in both populations. These observations indicate that much local adaptation has occurred by selection acting on existing variation rather than new mutation.</blockquote>

This last point is not especially demonstrated by the new sequencing data. What we are looking at is few complete sweeps, but that's expected even if all the selected variants were novel mutations -- there just hasn't been time to fix many variants. It remains to be shown the extent to which standing variants are involved in this selection, partial sweeps of new mutations, or parallel adaptations (<a href="http://johnhawks.net/weblog/topics/evolution/selection/spatial-dynamics/ralph-coop-tesselations-wave-advance-2010.html">"Spatial dispersal, parallel adaptation, and the 'Stooge effect'"</a>). We'll probably see a lot more interesting work on recent selection coming out of the new data. 

<i>Science</i> has a companion paper to the <i>Nature</i> data summary, focusing on copy number variation and gene duplications. I will review that one separately. 

UPDATE (2010-10-27): Dienekes <a href="http://dienekes.blogspot.com/2010/10/1000-genomes-project-has-arrived.html">pulls out an interesting passage</a> about the Y chromosome sequences, which in at least one case recover many markers separating haplogroups once thought to be much closer to each other. Not sure what to make of that yet. 


