---
layout: single 
title: "Sequence surrounding conserved Alu elements yields human-chimpanzee chromosome X divergence times consistent with previous estimates" 
category: research
permalink: /research/slavney-hawks-human-chimpanzee-effective-2011
comments: false 
author: John Hawks 
---


INTRODUCTION: 
Despite the many insights into human evolution provided by fossil and genetic evidence, the timing and circumstances surrounding the origin of genus Homo remain unclear. Genetic comparisons varying widely in method and compared loci have yielded estimates of the Homo-Pan divergence time between approximately 4 and 6 million years ago (Takahata 1995, Patterson 2006, Glazko 2003): a period during which several putative hominin species coexisted in overlapping regions of eastern and southern Africa (Wilkinson 2011). Of particular interest to questions of hominid speciation is chromosome X, which shows the highest homology between humans and chimpanzees (Patterson 2006). Because this chromosome harbors several genes known to affect fertility (Morey 2011) and brain function (Chiurazzi 2008, Nguyen 2006), this pattern could be explained by strong directional selection on X loci (Lambert 2010). However, it has also been suggested that incomplete lineage sorting as a result of an extended period of hybridization between Homo and Pan ancestors (Patterson 2006) or sex-biased migration (Vicoso 2006) contributed significantly to X chromosome evolution. Differentiating between the effects of selection and population dynamics might be achieved through multi-species comparisons between shared, ancient, neutral sequences, ideally distributed densely and evenly throughout the genome. 
Alu transposable elements fit these criteria well. This family of approximately 300 bp, non-autonomous elements originated in primate lineages approximately 60 mya (Price 2004) and today comprises 10% of the human genome, with approximately one element every 3 kb (International Human Genome Consortium 2001). By current estimates, Alu insertion events occur once per ~20 births in humans (Cordaux 2006), and Huff et al. (2009) showed that genomic intervals containing these rare events show approximately twice as much nucleotide diversity between hg18 and HuRef as the genome average  supporting their neutrality and ancient origins (Tajima 1983).
Some Alu elements have been shown to facilitate non-neutral processes such as expression or suppression of certain genes (Cui 2011, Gong 2011) and non-homologous recombination (Cordaux 2009). Nonetheless, even elements that are not neutral themselves have utility for locating neutral sequences with deep genealogies: the sequence surrounding fixed Alu elements is expected to be neutral because the insertion was tolerated in the ancestral genome, and as Huff et al. showed, sequence within ~10 kb of these elements fits the expectations of neutral evolution (Huff 2009, Kimura 1983). Additionally, Alu elements with both flanking sequences conserved between sister species are unlikely to have undergone or facilitated non-homologous recombination or inversion events.
Here, we hypothesize that if selection accounts for the young divergence time of the X chromosome, we will observe no significant departure in S  the average number of segregating sites between two homologous intervals  from that predicted by neutral evolution. Alternatively, if neutral sequences mutating randomly yield a significantly younger average speciation time, we cannot reject the hypothesis that the entire chromosome may have undergone unusual divergence events.

METHODS:

According to coalescent theory and a neutral mutation model, we assume that the total time since sequence divergence Ttot has negative exponential distribution with the mean 2NA (where NA is the ancestral populations effective size), and that the average number of segregating sites S has a Poisson distribution with mean ?S =2?LTtot (where ? is the per generation genome-wide mutation rate and L is the length of the sequences being compared)(Hudson 1990). Additionally, the NA of the X chromosome is expected to be 75% of that of the autosomes (Patterson 2006). Both theories also assume a constant population size and that the sequences being compared are homologous and neutral.
Locating Alu elements:
We obtained the locations of all annotated human (hg18), chimpanzee (panTro2) and orangutan (ponAbe2) Alu elements on chromosomes X and 7 from the RepeatMasker dataset
on the UCSC Genome Browser ftp database (http://genome.ucsc.edu/).
Alignment and S count:
We used the genome analysis platform Galaxy (Goecks 2010) to perform pairwise alignments of 500bp intervals 5kb up and downstream of each Alu element in the reference genome. Each genome was used once as the reference and again as the target for a total of six pairwise alignments per chromosome. Out of each set of alignment blocks, only those consisting of exactly 500 base pairs on homologous chromosomes and the same strand were included in the final data set. The number of single base pair differences (S) in each interval was counted in Galaxy and downloaded as a plain text file for analysis.
Estimation of divergence times and ancestral population sizes:
We adjusted the standard model (Hudson 1990) in which the number of segregating sites (S) is Poisson distributed around Savg= 2?Ttot to include separate time variables for sequence (Tseq) and species (Tspe) divergence times. In this model, Tseq is the time interval during which the probability of coalescence is between zero and one, Tspe is the time interval during which the probability of coalescence is zero, and Ttot is the sum of Tseq and Tspe, or the total time during which mutations can arise in both lineages.
According to coalescent theory, Tspe has the mean 2NA for chromosome 7 and 1.5NA for chromosome X, giving:
Savg7 = 2Ttot?  = (2Tseq+4NA)? and variance{S7} = (2Tseq)2?2 + Savg7 for Chr 7
SavgX = 2Ttot? = (2Tseq+3NA)? and variance{SX} = (2Tseq)2?2 + SavgX for Chr X
Using our observed S values, we calculated NA, Ttot and Tspe. We assumed a per-generation per-interval average mutation rate ? of 10-5 (using L = 500 bp).
RESULTS:
Results for all twelve alignments are summarized in Table 1.
Human-chimpanzee divergence parameter estimates:
On chromosome X, human and chimpanzee comparisons showed a Tseq of ~1.7 my and a Tspe of ~2.8 my for a Ttot of ~4.5 my. On chromosome 7, Tseq was ~1.9 my and Tspe was ~4.1 my for a Ttot of ~6.0 my. NA was ~70-90,000 for chromosome X (~69,000 using hg18 as the reference and ~92,000 using panTro2) and ~100,000 for chromosome 7.
Human-chimpanzee-orangutan divergence parameter estimates:
On chromosome X, human-chimpanzee-orangutan comparisons showed a Tseq of ~3.5 my for chromosome X and a Tspe of ~9.8 my for a Ttot of 13.3 my. On chromosome 7, Tseq was ~4.1 my and Tspe was ~13.0 my for a Ttot of ~17.1 my. NA was ~320,000 for chromosome X and ~330,000 for chromosome 7.
CONCLUSIONS:
By limiting DNA comparisons to homologous, non-coding regions, we derived divergence time (Ttot) estimates for human-chimpanzee comparisons on chromosomes X (~4.5 my) and 7 (~6.0 my) that are consistent with previous estimates of human-chimpanzee divergence times and show no significant reduction in Ttot between 7 and X beyond the 25% predicted by theory. Our estimates of effective population size in the human-chimpanzee ancestral population (~80,000 for chromosome X and ~100,000 for chromosome 7) exceed many earlier estimates, but also reflect this pattern.

DISCUSSION:
Alignment bias:
 Comparing pre-aligned blocks of sequence introduced a bias towards conserved sequence because homologous regions with many single base pair differences would not be included in the pairwise alignment data sets. This  effect is demonstrated by the dramatically smaller number of aligned blocks in the human-orangutan chromosome 7 alignment compared to the human-chimpanzee alignment on the same chromosome.
Proximity of Alu elements to coding regions: 
Our S values may have been artificially low because we did not exclude blocks near genic sequence, which may have experienced the effects of selection via hitchhiking.
Evolutionary history of chromosome X: 
The high NA for the human-chimp X ancestral population contradicts a model of the lower Tspe of chromosome S resulting from late human-chimpanzee lineage interbreeding and hybrid sterility, which would be expected to reduce the X NA compared to the autosomes. However, from our estimates for the human-chimpanzee  X NA, whether or not this occurred is unclear.
Using sequence surrounding Alu elements as a molecular clock: 
 Whether or not our interval set is truly evolving neutrally remains uncertain and will require further investigation. We propose looking for patterns of clustering by S in our alignment intervals. Futhermore, verifying whether or not our Alu flank data sets exhibit a  truly neutral pattern of evolution will require performing modeling experiments.


