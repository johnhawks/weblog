---
layout: single 
title: "What is the human mutation rate?  " 
description: "The 1000 Genomes Project is finding that the mutation rate is half the value usually assumed." 
category: story
permalink: /weblog/reviews/genomics/variation/human-mutation-rate-review-2010.html
tags: [mutation rate, chumans, chimpanzees, population genetics, mutation, 1000 Genomes Project, genetic divergence] 
comments: false 
author: John Hawks 
---

Last spring I wrote about a study that used whole-genome comparisons between parents and offspring to estimate the rate of per-genome mutation in humans (<a href="http://johnhawks.net/weblog/reviews/genetics/divergence/roach-family-quartet-mutation-rate-2010.html">"A low human mutation rate may throw everything out of whack"</a>). 

The study was by Jared Roach and colleagues <bib>Roach:whole:2010</bib>, and as you might guess from my post title, the result was surprising. Previous work had suggested a human mutation rate around 2.5 x 10<sup>-8</sup> per site per generation. The new study found less than half the expected number of mutations between these parents and offspring, an estimated rate of only 1.1 x 10<sup>-8</sup> per site. 

If this lower rate of mutation were to hold up, it would affect much of our understanding of the chronology of human evolution. Fossils and archaeological sites would not change in date, but some hypotheses about their relationships would be challenged. For example, the higher rate of 2.5 x 10<sup>-8</sup> per site suggests a chimpanzee-human population divergence around 4 million years ago. A new rate of 1.1 x 10<sup>-8</sup> would not have a linear effect on this divergence time -- the genes don't have genealogical roots at the same instant as the population divergence. But the human-chimpanzee divergence time would be radically higher than in many recent estimates. 

The same might be true for other primate divergences, and for genealogical relations within human populations today. Basically any times that are estimated from genetic differences may be affected by our knowledge of the per-generation rate of mutations.

What does this mean? <a href="http://johnhawks.net/weblog/reviews/genomics/variation/human-mutation-rate-review-2010.html">Open below the fold to read more</a>.
<!--break-->
<h4>What mutations are we counting?</h4>

Human genomes differ from each other in many ways. There are single base-pair changes in sequences, insertions and deletions, repeat polymorphisms, and larger-scale rearrangements such as inversions and gene duplications. Recent work suggests that some of these larger-scale effects may be very important to phenotypic variation among people. So why should we be talking about only the first of these kinds of variation? 

Single nucleotide mutations have been the focus of most attention about mutation rates because they are relatively easy and quantify. In high-quality sequence data, a single nucleotide change is relatively unambiguous. Reversals are fairly unlikely, although at a small fraction of "hotspot" sites, recurrent mutations can make a big difference. 

It is somewhat misleading to refer to "a" rate of single nucleotide mutations, because some kinds of sites (e.g., CpG nucleotides) have had a much higher probability of mutations than others. This affects the apparent rate of mutations in noncoding versus synonymous sites <bib>Subramanian:Kumar:2003</bib>. Also, the germline in males has been estimated to be as much as 6 times more likely to suffer mutations than the germline in females (discussed by Crow <bib>Crow:mutation:2000</bib>). The idea of a genome-wide rate assumes that when we bin all the single nucleotide mutations together, across large amounts of sequence, we do arrive at a relatively stable rate that can be applied to similarly broad extents of sequence data. Or at least that we can identify sequence regions with compatible rates (e.g., noncoding DNA or synonymous sites). 

At the moment, technical issues make it hard to find and quantify many other kinds of variation. The current generation of sequencing devices tend to generate short reads, which make it difficult to assess the presence of insertions or deletions of more than a few base pairs. Duplications and other rearrangements require special treatment such as higher coverage or longer sequence reads. By contrast, a single nucleotide mutation will typically align in the proper location and be quite evident in a read. In principle, we can just run down the genome and count them. 

Still, finding novel mutations is not without its problems. Recent sequencing projects have yielded a very high rate of false positives. The rate of false negatives is really not yet known. We have a good reason to suspect that the false negative rate will be high. In a low-coverage genome, many short segments of the genome will have very low read numbers, making it likely that the sequence reads represent only one of the two copies of the genome present at that location. Any novel mutations in that area have a 50-50 chance of being missed by our sequencing efforts. This false negative risk can be reduced by adding higher sequence coverage, but we're not yet at the point where we have a lot of genomes sequenced at the 10x or higher coverage that we would really want. 

So while sequencing a parent and offspring genome is the most direct way to estimate the per-generation mutation rate, it is not yet ideal. 

<h4>Where did the high rate come from?</h4>

That means we need to look very closely at other sources of data, to see if they may provide some independent confirmation of a lower per-generation mutation rate. In the process, we should ask, why did the higher rate, around 2.5 x 10<sup>-8</sup> per generation, become so widely accepted? 


The source cited by Roach and colleagues for the higher rate, 2.5 x 10<sup>-8</sup> per site, is a paper by Michael Nachman and Susan Crowell <bib>Nachman:Crowell:2000</bib>. Nachman and Crowell examined processed pseudogenes in humans and chimpanzees, under the assumption that mutations in these pseudogenes would be neutral to selection in the human and chimpanzee lineages. 



<blockquote>The average mutation rate was calculated from the average autosomal rate of evolution assuming a generation time of 20 years (Table 3). Recent estimates of the time since humans and chimpanzees diverged (T) include 4.5 mya (TAKAHATA and SATTA 1997 ), 5.5 mya (KUMAR and HEDGES 1998 ), and 6.0 mya (GOODMAN et al. 1998 ). ARNASON et al. 1998  estimated the Homo-Pan divergence at 1013 mya; however, their estimate is based on a calibration using distant, nonprimate species and is at odds with most other recent estimates. Mutation rates were calculated for a range of different human-chimpanzee divergence times and for two different ancestral population sizes. Mutation rate estimates vary from 1.3 x 10<sup>-8</sup> (assuming T = 6 mya and Ne = 10<sup>5</sup>) to 2.7 x 10<sup>-8</sup> (assuming T = 4.5 mya and Ne = 10<sup>4</sup>). If the average generation time is assumed to be 25 years (e.g., EYRE-WALKER and KEIGHTLEY 1999 ), then mutation rates are estimated to be between 1.6 x 10<sup>-8</sup> and 3.4 x 10<sup>-8</sup>.</blockquote>

Wait a minute. <b>There's no independent estimate of mutation rate here at all!</b> 

What they did was to assume values for the human-chimpanzee divergence and ancestral (chuman) effective size, and then provide an estimate of mutation rate <b>consistent with those assumptions</b>. That's perfectly reasonable as a way of quantifying the genetic divergence that they observed. If our goal is to predict the per-generation mutation rate from interspecific divergence, that's more or less the kind of estimate that we want. 

But many, many other studies have instead used a citation to the Nachman and Crowell rate as a justification for <i>their own estimates of the human-chimpanzee divergence time!</i> That's <b>not</b> perfectly reasonable, in fact, it's perfectly circular. It's turtles all the way down!

Worse, those citations tend to cite the midpoint of Nachman and Crowell's range of estimates (2.5 x 10<sup>-8</sup>) as if it were a true value measured with little error. Reading the original reference, you can plainly see that Nachman and Crowell reported estimates that varied over a factor of three, corresponding to a wide range of chuman population histories. From their discussion: 

<blockquote>Mutation rates estimated for a range of divergence times and ancestral population sizes fall between 1.3 x 10<sup>-8</sup> and 2.7 x 10<sup>-8</sup> assuming a generation time of 20 years (Table 3) or between 1.6 x 10-8 and 3.4 x 10<sup>-8</sup> assuming a generation time of 25 years. We suggest that 2.5 x 10<sup>-8</sup> is a reasonable estimate of the average mutation rate per nucleotide site (but caution that the actual rate may be between 1.3 x 10<sup>-8</sup> and 3.4 x 10<sup>-8</sup>). </blockquote>

That 2.5 x 10<sup>-8</sup> is simply the midpoint of their range of estimates with the 25-year generation time. 

What would be more reasonable? For hominins and chimpanzees, we probably want to apply a shorter generation length, a larger ancestral effective size, and a higher time of divergence. All of these would have yielded a lower rate for the Nachman and Crowell data. But we don't want to just assume these values, we should try to test whether they are valid based on other data. 

<h4>Other mutation rates from phylogenetic comparisions</h4>

Nachman and Crowell have not been alone in their ultimate reliance on fossil evidence as an assumption underlying the per-generation mutation rate. But several other studies came to a slower mutation rate. Mostly, these studies have assumed that the human-chimpanzee divergence happened significantly earlier than 5 million years ago. Necessarily, then, the human per-generation mutation rate would have to be lower, as long as the sequence divergence remained the same. 

These estimates are ultimately rooted in the date of one or more fossils, among which the generation time certainly varied. The resulting per-site mutation rates are often reported as per-year instead of per-generation. For example, Yi and colleagues <bib>Yi:2002</bib> yielded a rate of 0.99 x 10<sup>-9</sup> per year for the human-chimpanzee comparison, which would multiply to 1.98 x 10<sup>-8</sup> per 20-year generation. They propose this as a <i>maximal</i> rate, assuming that <i>Sahelanthropus</i> at a minimum date of 6 million years ago is a hominin. With an older divergence date, they propose a correspondingly lower rate (e.g., 0.79 x 10<sup>-9</sup> per year, not accounting for ancestral population polymorphism). 

Similarly, Steiper and Young <bib>Steiper:Young:2006</bib> considered a long (1.9 Mb) alignment of sequence from 19 primate species. In their model to estimate relative rates on different branches of the primate phylogeny, they incorporated the assumption that <i>Sahelanthropus</i> is on the hominin clade. A divergence date of 6 million years gave rise to a human per-site mutation rate of 0.65 x 10<sup>-9</sup> per year (1.3 x 10<sup>-8</sup> per 20-year generation). A divergence date of 7 million years lowered the mutation rate to 0.57 x 10<sup>-9</sup> per year. 

Low mutation rates do not always result from these studies. Several have arrived at either a high human mutation rate or a recent human-chimpanzee divergence time. Sometimes a recent human-chimpanzee divergence emerges simply by assuming the rate given by Nachman and Crowell. Yang <bib>Yang:2002</bib> provides an example of this -- a paper that very thoroughly explores the relationship of divergence time and ancestral effective population size, but ultimately roots the estimates on a single value for mutation rate. This rate we have already seen was itself based on an <i>assumption</i> about divergence time. 

Kumar and colleagues <bib>Kumar:2005</bib> came to a much lower estimate for the human-chimpanzee divergence time, based on an Old World monkey-hominoid divergence at 23.8 million years ago. This estimate did not consider the effect of ancestral polymorphism on the mean genetic divergence time, and so should -- in the language of computer software -- be deprecated. 


I should reiterate that none of these estimates are suitable for <i>testing</i> the times of phylogenetic divergences, because they all <i>assume</i> that the date of some particular fossil (or set of fossils, by fitting a model) is the minimum divergence time for a clade. 

So much of the literature in this area is ultimately circular, I'm pulling out my sparse hair reading through it. By the time we get back to the mid-1990's, the sequence data are even sparser than my hair by today's standards -- only a few hundred base pairs, or a sampling of restriction sites. But the divergence time estimates have propagated forward from that time to today, recycled through the assumptions of papers in the intervening time. It's like the genetic equivalent of money laundering!



<h4>Evidence from parent-offspring sequence differences</h4>

There is another way besides phylogenetic comparison: Simply look at living people and see how many new mutations they have. 

But this is tricky because we are rarely in a position to know which mutations are new. Most variations that we see between two people have persisted in the population for hundreds of generations or more. It takes a special kind of mutation to make its newness evident. 

Up until the advent of large-scale sequencing, the most important source of information about the mutation rate came from the rates of spontaneous Mendelian diseases. When a person has a dominant genetic disorder not carried by either of his parents, you know that the mutation must be new. Disease rates have long been tracked as standard public health data. 

However, the per-genome or per-locus rate of Mendelian disorders can estimate the per-site rate of mutations only by adding well-resolved information about the target size of functional genes. For example, if we know the average gene length and the proportion of different amino acids in functional proteins we can make some estimate of the ratio of synonymous to nonsynonymous sites. But we would still lack information about the fraction of nonsynonymous mutations that cause deleterious effects on protein function.  For this reason, it was possible for very early workers (e.g., Haldane) to come within the ballpark of per-locus mutation rates even before the genetic code was available. Yet such estimates are not strictly useful for understanding per-site rates of mutation. 

By 2000, widespread sequencing had begun to identify disease-causing mutations at the sequence level. When exons are known, it is possible to determine the "target size" -- the number of sites at which loss-of-function mutations may occur. These two values provide the numerator and denominator for an estimate of the per-site mutation rate. 

Kondrashov <bib>Kondrashov:rate:2003</bib> applied this method to estimate the per-site mutation rate across 20 human genes. He surveyed the literature for genes where more than 100 patients had been sequenced completely for the causative locus, finding the causal mutations. Using this value and the disease incidence allowed an estimate of the per-site rate of mutation for different categories of transitions and transversions. There was some variation among loci, with an average rate of per-site mutation equal to 1.8 x 10<sup>-8</sup> per generation.

Kondrashov observed a few hotspots in these genes, with substitution or deletion rates as much as a hundred times the average site. He also observed that the per-gene rate of mutation varies according to the number of CpG sites. The rate of short deletions was on the order of 5 x 10<sup>-10</sup>, insertions were even less frequent. 

The rate estimate by Kondrashov is within the range considered by Nachman and Crowell, but only 3/4 of the value 2.4 x 10<sup>-8</sup> widely cited as the long-term estimate. If this rate were applied to Nachman and Crowell's pseudogene data, it would predict a human-chimpanzee divergence time around 6 million years. 

This year, Lynch <bib>Lynch:spectrum:2010</bib> performed a more extensive comparison using similar methods as Kondrashov. Including more genes, and considering a broader range of mutational effects (including missense as well as nonsense coding mutations), Lynch found an even lower estimate of mutation rate per generation -- only 1.28 x 10<sup>-8</sup> per site. 

These estimates are not precisely the same as comparing parent-offspring pairs, but they are exceedingly powerful because the data on disease rates encompass very large populations of people. 

We should keep in mind the result of Subramanian and Kumar <bib>Subramanian:Kumar:2003</bib>, which showed that exons have a higher effective rate of substitution than do noncoding regions. That result implies that the genome-wide rate of change should be <i>lower</i> than estimated by Lynch, because his estimate encompasses only coding mutations. Also, any effect of purifying selection on these mutations will tend to decrease the long-term rate of substitutions per site to a lower value than the rate of mutations. The rate estimated by Lynch should then be an overestimate of the substitution rate that would be applicable to hominoid phylogenetic relationships. 



<h4>A slower rate</h4>

These estimates of the per-generation mutation rate are all low compared to the commonly-cited 2.5 x 10<sup>-8</sup>. They are not quite as low as the rate estimated by Roach and colleagues <bib>Roach:whole:2010</bib>, but the Lynch estimate is very close: 1.28 x 10<sup>-8</sup> compared to 1.1 x 10<sup>-8</sup> per site. 

The lower estimate from Roach and colleagues is a direct comparison of parent and offspring. In my earlier discussion of that rate, I suggested that false negatives in the sequence comparisons might have lowered the apparent rate of mutations. I still think we can't rule out that possibility. But the rate is not alone, and so it is less surprising than it may have seemed. 

My post last week on the 1000 Genomes Project results (<a href="http://johnhawks.net/weblog/reviews/genomics/variation/1000-genomes-2010.html">"Now for anthropological genomics"</a>) mentioned that the 1000 Genomes comparisions have arrived at essentially the same rate as Roach and colleagues. Comparison of one family trio led to a rate of 1.0 x 10<sup>-8</sup> per site per generation; the other family trio gave rise to an estimate of 1.2 x 10<sup>-8</sup> per site per generation. These bracket the estimate given by Roach and colleagues. 

My basic observation about the human-chimpanzee divergence time is still sound: 

<blockquote>If this mutation rate is accurate, then the average human-chimpanzee gene divergence has to be up around 11 million years ago. That can be accommodated with a 7-million-year-old species divergence only if we assume a very large ancestral population -- on the order of 50,000 or higher. Or, the ancestral effective size could be lower -- but that would make the species divergence substantially older -- 9 million years or more.</blockquote>

As we go further back in time, this lower human mutation rate may be less and less relevant, because different primate lineages may have higher (or lower) rates. When some of the kinks have been worked out of whole-genome sequencing, it would be tremendously useful to sequence parent-offspring pairs in other primate species. With those data, rate heterogeneity could be tested directly. 

For events <i>within</i> the hominins, the parent-offspring rate of mutations <i>ought</i> to be better than a rate estimated from phylogenetic distance. Phylogenetic distances are estimated with even more error than mutations, increasingly so as our methods for comparing genomes improve. But some fraction of new mutations will ultimately be lost to purifying selection. That implies, again, that the longer term rate of substitutions will be <i>lower</i> than the rate of mutations measured from parent-offspring comparisons. 

A rate of 1.1 x 10<sup>-8</sup> would have no effect on the number of genetic differences observed between people, because these differences are just counted, not estimated by genealogical relationships that are known. It is the unknown genealogical relationships, which are <i>estimated</i> from genetic differences, that may change substantially. 

Let's consider an example. Harris and Hey <bib>Harris:PDHA1:1999</bib> sequenced 4200 bp of the gene <i>PDHA1</i>, an X-linked gene whose product is part of a mitochondrial enzyme complex. At the time of their study (1999), their result was one of the oldest coalescence times estimated for non-African populations based on sequence data; they estimated the root of the <i>PDHA1</i> genealogy was 1.8 million years old. This estimate was based on the assumption that human and chimpanzee copies, which differed by an average of 40.42 substitutions, had diverged at 5 million years ago. That would imply that the average genetic difference between humans across the deepest root of the genealogy, 15.05 mutational differences, corresponds to 1.86 million years of time. If we instead assert a per-generation rate of 1.1 x 10<sup>-8</sup> per site, these data would generate an estimate of 163,000 generations for the root of the genealogy, roughly 3.3 million years. 

In other words, a coalescence that appeared to have happened in early <i>Homo</i> now looks rooted at the age of <i>A. afarensis</i>. The chimpanzee-human genetic root would be around 8.7 million years for these data. 

These estimates would likely be biased too low, because the X chromosome has a lower rate of mutation than the autosomes by some extent. That issue was addressed by Lynch <bib>Lynch:spectrum:2010</bib>, due to the fact that X chromosomes are in males (with their higher rate of mutations) only 1/3 of the time compared to 1/2 the time for autosomes. Any purifying selection would also bias the estimate too low. If these 4200 bp have a higher-than-average CpG content, that is one factor that might require a higher per-generation rate. 

Is any of this a problem? I don't think we know yet. A lower rate must readjust the apparent correspondence of some molecular time estimates with the archaeological record. But to be honest, most of the apparent correspondences of such dates have been illusory, because genealogical relationships among genes have such large expected variance under any realistic human population model. It is really the availability of whole-genome comparisons that has a chance of improving these population models.

