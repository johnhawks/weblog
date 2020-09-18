---
layout: single 
title: "Is there a common coding variant of FOXP2 in southern Africa?" 
category: story
permalink: /weblog/reviews/genetics/brain/foxp2-bushman-variant-2010.html
tags: [FOXP2, South Africa, Bushmen, Africa, introgression, DIY genomics, brain, genomics] 
comments: false 
author: John Hawks 
---


Today I was looking through the online data files for <a href="http://johnhawks.net/weblog/reviews/genomics/variation/desmond-tutu-genomics-2010.html">the South African genome</a>. Those online files are available from the <a href="http://main.g2.bx.psu.edu/library">Data Libraries</a> entry of the <a href="http://usegalaxy.com">Galaxy bioinformatics tool website</a>. 

I noted last week that some of the most interesting data -- in particular, the <i>genotypes</i> for new SNPs -- are not yet available to download (<a href="http://johnhawks.net/weblog/reviews/genomics/DIY-genomics/online-galaxy-toolkit-2010.html">"Online toolkits -- the good and the frustrating"</a>). But in the meantime there are some very interesting things there. In particular, the sequencing team has made available a list of amino-acid-coding mutations present in one or more of the five individuals (four Bushmen and Desmond Tutu) for whom the team obtained exome sequence. 

If you look at the summary information for this list, it gives the position of amino-acid-coding mutations against the human reference genome (hg18), the position and identity of the amino acid change. It then gives a "prediction" of whether the mutation is damaging to gene function. 

This kind of prediction can be very misleading. The categories of effects include "tolerated" and "damaging", but these are based on whether the site tends to be conserved in other mammal lineages, and whether the new amino acid is very different in affinity (and possible conformation) compared to the reference. There's no "beneficial" -- even though some fraction of these polymorphisms are probably retained because of selection on the mutant allele. 

I say that because one of the five individuals (TK1) has an amino-acid-coding mutation in <i>FOXP2</i>. 

Yeah, that surprised me when I found it. 

As you'll remember the coding sequence of <i>FOXP2</i> is pretty strongly conserved in other mammals. Two amino-acid-coding substitutions in humans separate us from other primates, an additional one separates primates from the mouse genome (Enard et al. 2002). This area of the genome looks like it had undergone a recent sweep in human populations, with relatively little variation and a strong excess of rare mutations surrounding the gene. Coop and colleagues (2008) gave a point estimate of the time of a sweep in humans as 42,000 years ago, which I wrote about at the time (<a href="http://johnhawks.net/weblog/reviews/neandertals/neandertal_dna/coop-foxp2-recent-selection-2008.html">"FOXP2 is really recent, it really did introgress (if it's not contamination)"</a>). That estimate has to be massively too young -- it's not plausible that a sweep could be that recent and fixed worldwide. 

Meanwhile, last year, Ptak and colleagues (2009) followed up on my suggestion that there might really have been a recent sweep, but one <b>near <i>FOXP2</i></b>, instead of involving one of the two human amino acid substitutions. They found statistical linkage between flanking sites immediately around the gene, which would be unlikely after a fixed sweep of <i>FOXP2</i> itself. That linkage is quite likely if the human-specific substitutions were <b>already fixed</b>, and <b>much later another nearby site underwent a partial sweep</b>. It remains to be demonstrated, however, what nearby site is a plausible candidate for a recent partial sweep. 

So, finding variations near <i>FOXP2</i> is very relevant to the history of this gene region. If there is an ongoing sweep involving some site <i>near</i> the gene, we should expect that some human populations haven't undergone the sweep yet, or have the selected haplotype at a lower frequency than others. The existing datasets from Africa -- mainly HapMap and HGDP sets -- are insufficient to test the hypothesis because they include only common SNP variants at low density. But sequence data from South Africa can give us a direct estimate of the nucleotide diversity around <i>FOXP2</i>, thereby letting us test for the presence of a recent sweep. 

The amino acid coding variant in one of these Bushman genomes came to me as a total surprise. Using the alignment with hg18, the location of the mutation is at position 114089380 on chromosome 7. The mutation changes a leucine in the wild-type sequence to a proline in the mutant, and the algorithm classifies it as "damaging" -- probably because the two residues are very different in their hydropathy. This position is <b>not</b> one of the two human-specific amino acid substitution sites. In fact it is in the forkhead box domain of the protein itself, which is the DNA-binding motif. Without going further into the biochemistry, I really can't guess what the effect of the mutation would be. I'm not really sure it's relevant -- after all, if it is a singleton in the population it might well be a recessive with no effect on the carrier phenotype. 

Still, the mutation could be common in the Bushman population. Our point estimate of the mutation's frequency is one in eight. Maybe it's a new variant that confers some advantage; maybe it's a result of a founder effect tens of thousands of years ago. It could even be widespread within Africa. We won't know until we have more genomes. 

The mutation is not in any of the regions sequenced by Krause and colleagues (2007) in the Neandertals from El Sidr&oacute;n. I wouldn't expect it to be there -- as a derived variant, it would be unlikely to evolve in parallel in Neandertals and southern African populations. But who knows what else we'll find? 




<h4>References:</h4>

<p class="cite">Coop G, Bullaughey K, Luca F, Przeworski M. 2008. The timing of selection at the human <i>FOXP2</i> gene. Mol Biol Evol 25:1257. <a href="http://dx.doi.org/10.1093/molbev/msn091">doi:10.1093/molbev/msn091</a></p>

<p class="cite">Ptak S, Enard W, Wiebe V, Hellmann I, Krause J, Lachmann M, P&aauml;&aauml;bo S. 2009. Linkage disequilibrium extends across putative selected sites in <i>FOXP2</i>. Mol Biol Evol 26:2181-2184. <a href="http://dx.doi.org/10.1093/molbev/msp143">doi:10.1093/molbev/msp143</a></p>

<p class="cite">Krause J, Lalueza-Fox C, Orlando L, Enard W, Green RE, Burbano HA, Hublin J-J, Bertranpetit J, H&auml;nni C, Fortea J, de la Rasilla M, Rosas A, P&auml;&auml;bo S. 2007. The derived <i>FoxP2</i> variant of modern humans was shared with Neandertals. Curr Biol 17:1-5. <a href="http://dx.doi.org/10.1016/j.cub.2007.10.008">doi:10.1016/j.cub.2007.10.008</a></p>

<p class="cite">Enard W, Przeworski M, Fisher SE, Lai CSL, Wiebe V, Kitano T, Monaco AP, P&aauml;&aauml;bo S. 2002. Molecular evolution of <i>FOXP2</i>, a gene involved in speech and language. Nature 418:869-872. <a href="http://dx.doi.org/10.1038/nature01025">doi:10.1038/nature01025</a></p>

<p class="cite">Schuster SC and many others. 2010. Complete Khoisan and Bantu genomes from southern Africa. Nature 463:943-947. <a href="http://dx.doi.org/10.1038/nature08795">doi:10.1038/nature08795</a></p>

