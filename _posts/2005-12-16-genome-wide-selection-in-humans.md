---
layout: single 
title: "Genome-wide selection in humans" 
category: story
permalink: /weblog/reviews/genomics/selection/bustamante_2005_protein-coding_selection_nature.html
tags: [genomics, natural selection] 
comments: false 
author: John Hawks 
---


<p>
I spent like a half-hour looking for this paper this morning, which I didn't take notes on when it came out. I don't know if <i>Nature</i> is blocking Google Scholar or what, but it certainly didn't help that I thought I remembered it being in <i>Science</i>! In any event, blogging defeats all memory loss!
</p>

<p>
There's <a href="http://www.livescience.com/humanbiology/051102_natural_selection.html">a LiveScience piece</a> about the paper also. 
</p>

<blockquote><b>Natural selection on protein-coding genes in the human genome</b></blockquote>

<blockquote><b>Carlos D. Bustamante <i>et al.</i></b></blockquote>

<blockquote>...Here we contrast patterns of coding sequence polymorphism identified by direct sequencing of 39 humans for over 11,000 genes to divergence between humans and chimpanzees, and find strong evidence that natural selection has shaped the recent molecular evolution of our species. Our analysis discovered 304 (9.0%) out of 3,377 potentially informative loci showing evidence of rapid amino acid evolution. Furthermore, 813 (13.5%) out of 6,033 potentially informative loci show a paucity of amino acid differences between humans and chimpanzees, indicating weak negative selection and/or balancing selection operating on mutations at these loci. We find that the distribution of negatively and positively selected genes varies greatly among biological processes and molecular functions, and that some classes, such as transcription factors, show an excess of rapidly evolving genes, whereas others, such as cytoskeletal proteins, show an excess of genes with extensive amino acid polymorphism within humans and yet little amino acid divergence between humans and chimpanzees (Bustamante et al. 2005:1153).</blockquote>

<p>
The study identified selection by comparing the level of within-species polymorphism to the level of between-species divergence (comparing humans and chimpanzees) for both synonymous and nonsynonymous sites. Basically, they set up a 2 x 2 contingency table with four cells (divergence-nonsynonymous, divergence-synonymous, polymorphism-nonsynonymous, polymorphism-synonymous) and test for equality of rates -- except they show departures one way or the other with a parameter, gamma: 
</p>

<blockquote>The parameter is negative if a gene shows an excess of amino acid polymorphism (or paucity of amino acid divergence) and positive if a gene has an excess of amino acid divergence relative to the genomic average for synonymous sites. </blockquote>

<p>
They can't apply the test to all genes, because many don't have enough polymorphism -- it takes a few segregating nonsynonymous variants to get a significant result. So they can test for positive selection at 3277 genes and negative selection at 6033. 
</p>

<p>
They find the following: 
</p>

<blockquote>Although we find that most of the genes in the informative data sets (n = 4,916) show no evidence of selection according to our methods, we do classify 813 loci as significantly negatively selected and 304 as positively selected at a 5% cutoff. Of the 50 loci identified by ref. 18 as rapidly evolving, 45 were informative about positive selection in our data set. Of these, 14 (31.1%) had more than 95% of their posterior mass above  = 0, and 37 (82.2%) had a majority of their posterior mass above neutrality, indicating good agreement between population genetic and phylogenetic approaches for identifying rapidly evolving genes. There is a high degree of overlap in the types of genes classified as positively selected by both studies (see Table 1 and Supplementary Table 1), including defence/immunity proteins (P = 0.00965), gametogenesis (P = 0.03411), apoptosis (P = 0.00336) and sensory perception (P = 0.04577). One interesting result of our analysis is that transcription factors as a group seem to be rapidly evolving (P < 0.0001), with 39 out of 240 in the informative data sets (16.25%) having P+ greater than 97.5% as compared to 9.6% of all loci in the IPS data set. Similarly, we find evidence that the categories of nuclear hormone receptors (P = 0.00143) and genes involved in nucleoside, nucleotide and nucleic acid metabolism (P = 0.00467) have an excess of rapidly evolving genes.</blockquote>

<p>
The choice of a cutoff for these kinds of multiple-comparison analyses is an interesting story in itself. I was at a lecture by Bret Payseur yesterday, and he described the problem very well. Naturally, if you choose 5 percent as a cutoff for significance, you are going to be saying that 5 percent of genes are in your category of interest -- which for the human genome is going to amount to 1000 genes or more no matter what. Were 1000 genes under selection? Should you choose a more conservative cutoff -- maybe 1 percent? Maybe 0.1 percent? 
</p>

<p>
The solution these researchers are using is to compare results with functional classes and chromosome position. If you find that there is a nonrandom association between certain functional classes of genes (e.g. immunity proteins) and your selection criterion, then it is <i>prima facie</i> evidence against neutrality. Likewise, if you find a nonrandom association between your selection criterion and chromosome position, that is evidence against neutrality. 
</p>

<p>
In both cases, this is a statistical conclusion taken from lots of loci and not a strong judgment about any individual locus. That is why these papers take to discussing the "top 50" candidates and such arbitrary numbers. The idea is that if you have the most extreme set of genes, these are least likely to be neutral. Find convincing relationships with phenotypes under selection --- like skin color, or muscular dystrophy, or such --- and, again, you confirm the hypothesis of selection. 
</p>

<p>
What we lack thus far is a good way to tell for sure whether a locus has been under selection from molecular information alone. And we may never get such a criterion, because drift can look like selection too often, and vice versa. 
</p>

<p>
I think there may be something more interesting behind these observations: 
</p>

<blockquote>We also used our approach to identify loci and classes of genes that show a paucity of amino acid divergence between humans and chimpanzees, yet have moderate to high levels of amino acid polymorphism, which we believe to harbour an excess of mildly deleterious variation. For example, loci involved in actin binding (P = 0.00013; Supplementary Table 1) and cytoskeletal formation (P < 0.00001) contain an over-representation of negatively selected loci, with 36 out of 205 cytoskeletal proteins in the informative set (17.6%) having P- greater than 97.5% (Table 1). For example, 6 out of the 9 myosin heavy chain loci exhibit a large excess of amino acid polymorphism, including non-muscle myosin (MYH9, P- > 0.983), embryonic (MYH3, P- > 0.999), perinatal (MYH8, P- > 0.962) and adult skeletal (MYH4, P- > 0.946; MYH13, P- > 0.957) myosin as well as the smooth muscle (MYH11, P- > 0.999) form. Other cytoskeletal proteins with excess amino acid polymorphism within human populations include myomesin 2 and 3 (MYOM2, MYOM3), dystrophin related protein 2 (DRP2), alpha- and beta-adducin (ADD1, ADD2), sarcospan (SSPN) and scinderin (SCIN). These results are consistent with the fact that as a group, genes involved in cell structure and motility (Table 1) show a signature of negative or purifying selection (P = 0.00008), with 27 out 176 (15.3%) loci exhibiting excess amino acid polymorphism relative to divergence.</blockquote>

<blockquote>Mutations in cytoskeletal protein-coding genes are known to cause a number of mendelian diseases and have been implicated in various complex disorders. For example, with the dystrophin gene many different types of mutation are known to cause both Duchenne and Becker types of muscular dystrophy (DMD, P- > 0.969). Also in this set is myosin VIIA (MYO7A, P- > 0.99), a gene implicated in Usher syndrome (1B), the most common cause of congenital deafness and blindness in developed countries. Similarly, the alpha- and beta-adducin genes (P- > 0.99 for both) are associated with hypertension and cardiovascular disease, and one known causative variant (ADD1 G460W (refs 19, 20)) is found at moderate frequencies in both African Americans (9.7%) and European Americans (28.9%) in our sample.</blockquote>

<p>
So human variation is enriched for coding variants in many muscle and cell-structure related genes. The low divergence between-species is evidence that these genes are conserved, but they have relatively many coding variants in humans today. Hmmm...
</p>

<p>
Then there is this: 
</p>

<blockquote>Another interesting group of genes that show excess amino acid polymorphism (P = 0.02805) are those involved in ectoderm development, with 12 loci out of 98 exhibiting significantly elevated levels of amino acid polymorphism relative to amino acid divergence (Table 1). These include three loci in which mutations are known to cause disease: GLI3 (polydactyly), NOTCH3 (<i>Drosophila</i> homologue implicated in cerebral arteriopathy) and DCC (colorectal carcinoma). Interestingly, all three of these genes are also involved in neurogenesis according to the Panther molecular function classification. Genes involved in general vesicle transport also show excess amino acid polymorphism as a class (P = 0.00016). Sixteen loci have posterior distributions with more than 95% and four with more than 99% mass above  = 0 (for example, COPE, HD, KIF4A, SEC31L1 and STX11). The most familiar of these is HD -- the gene that causes Huntington's disease.</blockquote>

<p>
So some genes affecting neurogenesis also have an excess of coding polymorphism in humans compared to the amount of between-species divergence. 
</p>

<p>
I'm not sure that negative selection is the story for genes like these. Maybe it is -- for example, one explanation of excess deleterious variation being present in human populations today would be a recent population bottleneck. Genetic drift could have carried a few slightly deleterious variants to detectable frequencies, which ultimately will be selected out of the human population. But if that were true, I'd expect the pattern would be stronger at genes that are <i>really</i> strongly conserved, like histones. You would have to have some explanation for why some conserved genes show an excess of polymorphism and others don't -- presumably, because they happen to be <i>really weakly</i> selected within humans recently, but more strongly selected sometime in the more distant past. 
</p>

<h4>References:</h4>

<p class="cite">Bustamante CD et al. 2005. Natural selection on protein-coding genes in the human genome. Nature 437:1153-1157. <a href="http://www.nature.com/nature/journal/v437/n7062/full/nature04240.html">Full text (subscription)</a></p>

