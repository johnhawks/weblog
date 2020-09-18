---
layout: single 
title: "Copy number variation in 1000 Genomes" 
category: story
permalink: /weblog/reviews/genomics/duplication/cnv-1000-genomes-sudmant-2010.html
tags: [diet, agriculture, population structure, recent selection, genomics, gene duplication, 1000 Genomes Project, copy number variants] 
comments: false 
author: John Hawks 
---



When I wrote earlier in the week about the 1000 Genomes Project results, I mentioned that a second paper was being published in <i>Science</i>. That paper, by Peter Sudmant and colleagues <bib>Sudmant:2010</bib>, works to quantify the amount of copy number variation of genes in the genomes of the study participants. 

It can be challenging to study copy number variation using shotgun sequencing methods, because each duplicated part of the genome creates multiple alignment targets for short reads. One way to deal with this problem is to use the drawbacks of shotgun sequencing as an advantage: Look for template regions of the genome that have much higher read depth than others. These places include many where a gene has been duplicated in the target genome, giving one-and-a-half or twice the number of reads for each duplication. Looking at read depth genome-wide is a quick way to assess copy number variation at sites where it was previously unknown. Once these are ascertained in a sample of genomes, they can be targeted for further study, including characterizing the boundaries of the duplicate region. 

The paper describes this methodology in some detail, with various embellishments to get more precise answers to certain kinds of structural questions. They developed a large set of SNPs that differentiate paralogous gene copies, among other things allowing them to examine which members of various gene families had been duplicated, and whether events were shared between populations. 

<blockquote>Through our analysis, we identified that duplicated regions are more likely to be stratified between human populations when compared with copy number variation within unique regions of the genome. For example, 59 (92%) of the top 64 stratified gene families overlap segmental duplications (P < 2.2 x 10<sup>16</sup>). Remarkably, many of these highly polymorphic genes map to duplications that promote recurrent rearrangements associated with intellectual disability, autism, schizophrenia and epilepsy. We hypothesize that the extreme polymorphism may contribute to genomic instability associated with disease and may predispose certain populations to different chromosomal rearrangements (30).</blockquote>

Segmental duplications can be relatively effective ways to change the amount of gene product without changing the gene product. In other words, a duplication can increase the dosage of a particular gene product. That can sometimes be very useful. For example, salivary amylase production varies among people due to the number of duplicate copies of the gene <bib>Perry:amylase:2007</bib>. The copy number variation is related to population history of agricultural subsistence -- old agricultural populations have more amylase copies. It's a simple case where the dietary ecology favors a dosage increase for an enzyme. 

Gene duplications and other structural changes to the genome are rare events -- any particular kind of change is substantially less likely than a single nucleotide mutation at a given point in the genome. So it is of some interest to consider which regions are actually <i>invariant</i> in copy number -- duplications that occurred on the human lineage but have been conserved in more recent populations -- because these may reflect old adaptations essential to the evolution of hominins. Here's what the paper concludes: 

<blockquote>We have also defined the ~49% of gene duplicates that are largely invariant in copy among humans. Although this is based only on an assessment of 159 genomes from select populations, the fact that this fraction of genes remains copy number invariant in a milieu of recurrent unequal crossover suggests functional importance. Among these, we find a number of genes involved in neurological development and disease. We note that many of these duplicated genes are themselves incomplete and may represent nonprocessed pseudogenes, which may modulate the expression of the ancestral gene. The characterization of the most recently duplicated genes should facilitate identification of those that acquired new functions (neofunctionalization) versus those that have become pseudogenes or have partitioned their function among duplicate copies (31).</blockquote>


I was going to write that there's not much analysis in the paper and let it go at that. But the paper has a 108-page supplement. 

I know I write this like once a week, but what the heck is the point of a 4-page paper with a 108-page supplement? Granted, 7 of the supplement pages are the author list (!!), but I view the whole thing mainly as a rip-off for the people who did the analyses in the supplement. Why don't they get their own first-authored publications? Are other journals satisfied to accept first-authored versions of analyses that have already been in a supplement in <i>Science</i>? 

The supplement lists 64 gene families including segmental duplications that differ substantially in average copy number among the CEU, YRI and CHB/JPT samples to which the low-coverage whole-genome sequencing has been applied thus far. The table (S8) lists the mean copy number in the three populations and the total variance in copy number; the key statistic is a value called Vst, which is analogous to <i>F</i><sub>ST</sub> for length variations. 

These are not generally duplications of whole genes, and their boundaries don't generally correspond to the boundaries of coding regions or exons. Without further analysis, it is not clear which of these duplicated regions may have functional import. Many of the additional copies may be inactive, either because of pseudogenization or because the duplication may not include the promoter/enhancer elements needed for gene expression. Some of the duplications occur in regions with known pseudogenes. The "involvement" of some genes in these regions with neurological development and disease is interesting, but the paper attempts no statistical assessment of this. It's a list of candidates, with some interesting ones that are obviously worth further examination, but without a clear story for any of them. 

It is maybe interesting that salivary amylase didn't make the list. It's not clear from the supplement whether that is an omission or whether its population differentiation, great as it is, is not as high as the lower cutoff. The greatest differentiation for amylase copy number is between populations that are not yet represented in the 1000 Genomes whole-genome sequencing. 

That raises an interesting question: What if we applied the same methods to the read data from some of the other public genomes? The <a href="http://johnhawks.net/weblog/reviews/genetics/brain/foxp2-bushman-variant-2010.html">Bushman genomes</a> from earlier this year are an especially interesting sample because they are notably not drawn from a long-time agricultural population. In which areas would they score atypical copy number variation compared to the 1000 Genomes samples? 


