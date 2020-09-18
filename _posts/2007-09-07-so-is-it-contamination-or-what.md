---
layout: single 
title: "So is it contamination, or what?" 
category: story
permalink: /weblog/reviews/neandertals/neandertal_dna/wall_kim_2007_dna_contamination.html
tags: [Neandertal DNA, Neandertals] 
comments: false 
author: John Hawks 
---

<p>
The abstract of the paper by Jeffrey Wall and Sung Kim is terse: 
</p>

<blockquote>Two recently published papers describe nuclear DNA sequences that were obtained from the same Neanderthal fossil [1, 2].  Our reanalyses of the data from these studies show that they are not consistent with each other and point to serious problems with the data quality in one of the studies, possibly due to modern human DNA contaminants and/or a high rate of sequencing errors. </blockquote>

<p>
That is a pretty sharp contrast with <a href="http://johnhawks.net/weblog/reviews/genetics/ancient/neandertal_sequencing_damage_2007.html">the story earlier this summer</a> that profiled the damage to the ancient sequences coming off the 454 platform. That study, by Adrian Briggs and colleagues, showed that most misincorporated nucleotides were near the ends of fragments, and promised that reliable sequences could be obtained by correcting for this damage. 
</p>
<!--break-->
<p>
The most compelling piece of the analysis is the demonstration that the shorter and longer transcripts give different estimates of genetic divergence. Wall and Kim show that the short fragments in the data reported by Green and colleagues (2006) yield the same estimate of <i>population</i> divergence that they (Wall and Kim) estimate from the data reported by Noonan and colleagues (2006). In contrast, Wall and Kim find that the <i>long</i> transcripts in the data reported by Green and colleagues yield a much <i>lower</i> estimate of population divergence. Wall and Kim interpret this as evidence that relatively long contaminants from a modern human have been included in the Green data. 
</p>

<p>
Still, Green et al. (2006) tested directly whether the "long" (>100bp) fragments of mtDNA sequence had a higher contamination rate than the "short" (<60bp) fragments, and found no difference. And Noonan et al. (2006) tested for a correlation of sequence divergence and fragment length, finding no correlation. Both interpreted these results as evidence against contamination. So it is surprising that the large difference between short and long fragments found by Wall and Kim (2007) was not noticed before. 
</p>

<blockquote>We also tabulated the percentage of HapMap SNPs for which the Neanderthal sequence contains the derived allele for each of the three groups of Green et al. data (see Table 1), and refer to this percentage as <i>N<sub>d</sub></i>.  For comparison, we also estimated (from simulations) the expected value of <i>N<sub>d</sub></i> as a function of the European-Neanderthal population split time and the Neanderthal admixture proportion (see Figure 3). The expected value of <i>N<sub>d</sub></i> increases as the European-Neanderthal population split time decreases and/or the Neanderthal admixture proportion increases, though for reasonable parameter values (i.e., a population split time  150 Kya and a Neanderthal admixture proportion < 25%) <i>N<sub>d</sub></i> is always < 25%. In contrast, <i>N<sub>d</sub></i> = 32.9 for the Green et al. data, which is inconsistent with the true value of <i>N<sub>d</sub></i> being  25% (p < 10-4). Moreover, <i>N<sub>d</sub></i> shows a clear trend of higher values for longer fragments, consistent with the hypothesis of widespread contamination with larger-sized modern human DNA fragments. The expected value of <i>N<sub>d</sub></i> for modern human contaminants is 37.0, so the Green et al. data look in some ways more like modern human DNA than they do like Neanderthal DNA. <b>If we use <i>N<sub>d</sub></i> to estimate very roughly the proportion of the Green et al. [2] data that are actually modern human contaminants, this leads to contamination rates of 72  85% (see Materials and Methods for details).</b>  Alternatively, a likelihood-based estimate of the proportion of modern human contaminants yields an estimate of 78% (95% CI: 70  88%; see Materials and Methods) (Wall and Kim 2007:9, emphasis added).</blockquote>
</p>

<p>
That's a very high amount of contamination. Remember, this comes from the same extracts that Green and colleagues (2006) showed had more than 94% Neandertal-like mtDNA transcripts. 
</p>

<p>
Yet, there is one big sticking point in this analysis: If the data were really around 80% modern human contaminants, then the fragments shouldn't have "Neandertal-specific" mutations in such high numbers. 
</p>

<p>
Remember, that all the comparisons underlying the "divergence dates" are based on the human-<i>chimpanzee</i> differences, and not the human-<i>Neandertal</i> differences. This is because a genuine ancient sequence has a high number of misincorporated bases, which inflate the apparent divergence. As <a href="http://www.johnhawks.net/weblog/reviews/genomics/neandertal/neandertal_genomics_faq_2006.html">I explained</a> last year, both Neandertal genome papers avoided the direct comparison, and instead placed the Neandertal sequence at its location on the mutational spectrum separating humans and chimpanzees. 
</p>

<p>
But it isn't very hard to just count all the Neandertal-specific mutations, and that count should be very high for genuine sequence (which includes both real and damaged changes), and substantially lower for contaminant sequence (which might include some damaged changes, but few real ones). The Green and Noonan datasets have the same proportion of Neandertal-specific changes, which seems like a pretty strong argument against the idea that contamination explains the difference -- especially at the high levels (80%) required to account for the proportion of derived human SNP alleles in the "Neandertal" sequence. Wall and Kim (2007) hypothesize that the Green data have both a very high contamination rate, and a higher proportion of sequencing errors, possibly explaining both observations. 
</p>

<p>
Personally, I want to have some explanation of a <i>mechanism</i> that could contaminate the Green data at a level of 80%, without showing a contamination rate of more than 6% in the mtDNA, and without showing any sign of contamination in the Noonan data taken from the same extracts. By no means do I think that's impossible, by the way -- I've seen a lot of crazy problems at labs. But if it's true, I certainly think it should drain our confidence in these approaches for the time being. 
</p>

<h4>Picking an admixture model</h4>

<p>
Here's a potential problem with the study: the results of the analysis relating to "divergence times" and "admixture proportions" depend very strongly on the particular model of admixture that Wall and Kim have assumed. They assume a complete isolation after some date <i>T<sub>S</sub></i>, followed by a short episode of horizontal admixture at a later date <i>t<sub>a</sub></i>. They then attempt to estimate <i>T<sub>S</sub></i> and the amount of horizontal admixture, <i>p</i>, given the data. 
</p>

<p>
That is one model for admixture, but not the only one. Even this simple model includes six parameters (including mutation rate, pre-split and post-split human effective population sizes). The mutation rate is estimated from the human-chimpanzee divergence, while the pre- and post-split effective sizes are estimated from recent humans. The paper claims that the preferred 325,000-year species divergence is "more consistent" with paleontological evidence, but this is just cherry-picking; they could just as easily have chosen to cite somebody who things a 35,000-year divergence is most "reasonable." So, including this one, we have three parameters to estimate using our one degree of freedom. Not helpful. 
</p>

<p>
Suppose instead that we adopt a simpler four-parameter model: long-term coexistence of Neandertal and modern populations with a (possibly very low) level of gene flow between them. Here, the four parameters are (1) the level <i>m</i> of gene flow, (2) the date <i>t</i> of the Neandertal sample, (3) the human long-term effective size, and (4) the Neandertal long-term effective size.  The date <i>t</i> is directly estimated by radiocarbon, and the human effective size may be estimated from recent humans as above. This leaves our one degree of freedom to estimate the level of gene flow <i>m</i> relative to the Neandertal effective size. 
</p>

<p>
In that model, there is nothing exceptional about a divergence time of 35,000 years, which merely means that some genetic loci may show recent common ancestors between some living humans and some Neandertals. 
</p>

<p>
Also, the HapMap SNPs have an ascertainment bias (toward common, and on average older alleles). This makes it more likely that a real Neandertal would have a human-derived SNP allele, by descent from an ancient common ancestor with a living person. The description of simulations in the paper does not indicate that this bias has been corrected
</p>

<p>
There is one potential explanation that so far everyone is ignoring. <b>There is a very real possibility that the bone in question, Vi 33.16, is not a Neandertal at all.</b> The bone is not securely provenienced, and the only things making it a Neandertal right now are its mtDNA sequence and a radiocarbon date of 38,310 BP. The date is less than convincing -- it is by no means impossible that the bone is modern at that date, and it is unclear how recent changes in AMS protocols might affect it. The mtDNA is only convincing if you assume admixture to be impossible. 
</p>

<p>
Still, if Vi 33.16 were modern, that wouldn't explain the inconsistency between the Noonan and Green datasets in the proportion of derived human SNPs. But then, the Noonan data only include a small number of HapMap SNP sites -- indeed only three derived HapMap SNPs are present in the dataset (Noonan et al. 2006). If the population mixture that led to the apparent "human" character to the sequence was very recent (i.e., within the first few generations of the specimen's ancestry), then the genome might be substantially heterogeneous, meaning a small sample might yield an idiosyncratic result. 
</p>

<h4>References:</h4>

<p class="cite">Briggs AW, Stenzel U, Johnson PLF, Green RE, Kelso J, Pr&uuml;fer K, Meyer M, Krause J, Ronan MT, Lachmann M, P&auml;&auml;bo S. 2007. Patterns of damage in genomic DNA sequences from a Neandertal. Proc Nat Acad Sci USA <a href="http://dx.doi.org/10.1073/pnas.0704665104">doi:10.1073/pnas.0704665104</a></p>

<p class="cite">Green RE, Krause J, Ptak SE, Briggs AW, Ronan MT, Simons JF, Du L, Egholm M, Rothberg JM, Paunovic M, P&auml;&auml;bo S. 2006. Analysis of one million base pairs of Neanderthal DNA. Nature 444:330-336. <a href="http://dx.doi.org/10.1038/nature05336">DOI link</a></p>

<p class="cite">Noonan JP, Coop G, Kudaravalli S, Smith D, Krause J, Alessi J, Chen F, Platt D, P&auml;&auml;bo S, Pritchard JK, Rubin EM. 2006. Sequencing and analysis of Neanderthal genomic DNA. Science 314:1113-1118. <a href="http://dx.doi.org/10.1126/science.1131412">DOI link</a></p>

<p class="cite">Wall JD, Kim SK (2007) Inconsistencies in Neanderthal genomic <br />
DNA sequences. <a href="http://dx.doi.org/10.1371/journal.pgen.0030175.eor">doi:10.1371/journal.pgen.0030175.eor</a></p>

