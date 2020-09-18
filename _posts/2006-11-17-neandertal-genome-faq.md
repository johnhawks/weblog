---
layout: single 
title: "Neandertal genome FAQ" 
category: story
permalink: /weblog/reviews/genomics/neandertal/neandertal_genomics_faq_2006.html
tags: [Neandertal DNA, Neandertals, introgression, metagenomics, genomics] 
comments: false 
author: John Hawks 
---


<p>
With the release of the initial two papers describing chromosomal DNA sequences from a Neandertal, I thought I would put together some frequently asked questions and answers to them. I actually have been frequently asked most of these questions this week -- mostly by journalists -- so I think this is a good list. 
</p>

<p>
I'll be following up over the next few weeks with additional details, particularly as some of our own work moves forward. I've left some loose ends dangling here deliberately -- sometimes for the sake of brevity, in other cases because they await further developments. 
</p>

<p>
UPDATE (11/17/2006): I'm editing through this, making changes here and there to make things clearer. So as this progresses, it won't be identical to the initial version, although changes will be minor. 
</p>

<h4>There are two papers in two journals, by two different teams of people. What's the difference?</h4>

<p>
Both teams used samples from the same specimen, Vindija (Vi) 80 -- so in principle, they are sequencing the same genome. The difference between the two comes from their methods of sequencing the DNA. 
</p>

<p>
The Rubin group (Noonan et al. 2006) is using a <i>metagenomics</i> method based on the creation of a <i>clone library</i> from the ancient DNA. To make a clone library, DNA from a sample is cut with a restriction enzyme, which cuts the DNA at every place that it displays the same short sequence (usually 4- or 6-bp sequences, such as "ATTA"). The short fragments of DNA are mixed together and bound to vectors that can be maintained and replicated in cells. This is the "cloning" process, and the "library" consists of all the short fragments, which (hopefully) overlap each other so that they can be reconstructed.  
</p>

<p>
People have made libraries for a long time. For example, the entire mRNA complement in a given tissue type may be made into a library of complementary DNA (cDNA). Once the library is made, it can be probed with short, labeled DNA sequences to assess whether a given gene is expressed in that tissue type. Or contrariwise, after cDNA from the library is sequenced, it can be used to design probes to find where in the genome it came from. 
</p>

<p>
The unique aspect of the metagenomic approach is that <i>all</i> DNA sequences from a sample will be included in the library, potentially seqeunced, and ultimately reconstructed with computers into separate genomes. Usually cloning is preceded by an amplification step (generally using PCR), which selects and amplifies DNA of particular interest for cloning. But metagenomic methods skip this amplification -- because they cannot predict in advance what they are looking for. One of the most important early applications of metagenomics has been to reconstruct the genomes of microbes that cannot be cultured. Even though these organisms are not amenable to keeping in laboratory colonies, their genomes can be reconstructed by sampling their environments -- for example, soil or pondwater. 
</p>

<p>
Or fossils. For the Vindija 80 fossil, the extract includes only around 6 percent identifiable "primate" DNA sequences. Out of the roughly 20 percent that are identifiable at all, over half are microbial. 
</p>

<p>
I suppose if you were interested in the long-term microbial decomposition of fossil bone, you could do your disseration on those. For the rest of us, the final step is to let the computer spit out the humanlike sequences, which are assumed to be the Neandertal DNA plus some proportion of human contamination. 
</p>

<p>
In contrast, the 454 group (Green et al. 2006) used a method called bead-based emulsion PCR. That is a mouthful, so it bears some explanation (for which I'm paraphrasing material from Margulies 2005 and Ronaghi 2001). 
</p>

<p>
The "polymerase chain reaction," or PCR, is a method of replicating many copies of a DNA sequence from a single template. Usually to do PCR, you design a "primer," which is a short sequence of DNA that causes the target sequence to be preferentially replicated by the DNA polymerase. With a number of heat cycles and sufficient primer, you end up with a whole lot of copies of just the piece of DNA that you want. 
</p>

<p>
This is, of course, exactly why standard PCR is so problematic for ancient sequences. There, you <i>can't</i> get exactly what you want, because it is broken into tiny bits and damaged. You would be happy to get <i>anything</i>. But if you amplify everything together in one giant vat, then the <i>less damaged</i> sequences will be the ones that amplify preferentially, and these are going to be <i>worthless</i> to you because they all represent contaminants of various kinds, like microbial DNA or modern human sequences. 
</p>

<p>
The 454 method attaches all the tiny bits of sequence to tiny beads and separates these beads into oil droplets within a water suspension. The oil droplets are the "emulsion" part, and by separating them in this way, the process can employ PCR while keeping all the tiny sequences seperate from each other. Because they are kept separate,  one good sequence can't swamp out all the others in the solution. The PCR products all stick to the bead so that after they come out of the emulsion the copies of different sequences are still separate. 
</p>

<p>
After PCR, the DNA is broken down into single strands, still attached to their beads, and the beads are deposited on a fiber-optic slide assembly. The slide has tiny wells that are optically connected to a light-sensing CCD, which is essential for the "pyrosequencing" step. Nucleotides flow across the slide and into these wells one after another (T, A, C, then G). When the DNA polymerase connects one of these nucleotides to the single-strand DNA in a well, it releases a molecule of pyrophosphate (PPi). 
</p>

<p>
That's when the magic happens. The solution also contains luciferase -- the enzyme that makes fireflies glow. With some additional chemistry, the PPi gives a burst of energy to the luciferase, which then emits a spark of light. The CCD picks up the light, which is a signal that the nucleotide was incorporated into the sequence. 
</p>

<p>
Since nucleotides are added only every few seconds, a clever person with a notebook could reconstruct the sequence of the DNA fragment in each well. The real trick is that the fiber-optic slide contains well over a million wells, all being sequenced <i>simultaneously</i>. As the CCD picks up the series of flashes from every cell, the system is tracking many megabases of DNA in every run. 
</p>

<p>
At present, this is the fastest method of DNA sequencing on the planet. It can construct the complete genome of a microbe in a couple of hours. 
</p>

<h4>If the 454 sequencing method is so much faster, then why would anybody ever want to build clone libraries?</h4>

<p>
The claim is that the library approach is superior as a way to probe for specific genetic loci. For instance, here's a passage from p. 1071 of the Pennisi article: 
</p>

<blockquote>[Rubin] envisions several libraries, each from a different Neandertal. Researchers would pull out the same fragment from each library to compare with each other and with living people. A pilot project has already demonstrated probes that ferret out specific target sequences, so the team needn't analyze the billions of bases shared by Neandertals and living humans, or among different Neandertals. "We will be able to identify and confirm sequence changes in more than one Neandertal without having to sequence several Neandertals to completion," Rubin says. "Seeing the same change in multiple Neandertals will give us confidence that we got [the sequence] right.</blockquote>

<p>
This sounds similar to <a href="http://johnhawks.net/weblog/reviews/genomics/ancient/mammoth_blondes_rompler_2006.html">the study</a> earlier this year that found <i>Mc1r</i> variants in different mammoths, but in fact that study used direct PCR rather than cloning (I suppose because they have a heck of a lot more mammoth tissue to work with!). 
</p>

<p>
It's not obvious to me that this is really that much of an advantage. I mean, it's certainly true that we really want to sample some genes (like <i>MCPH1</i>) from several different Neandertal fossils. But I don't see any point to drilling into fossils for this purpose without <i>also</i> sequencing their full genomes. 
</p>

<p>
Now, somebody will say, "Well, sequencing the <i>full genome</i> of every fossil is just too expensive. We can limit to work on just a few genes <i>much more cheaply</i>, and we can use the same samples later to sequence other genes, or whole genomes." 
</p>

<p>
Personally, I don't see the rush. These fossils were in the ground for 40,000 years, and they're not going anywhere. If we can sequence whole genomes cheaply in 10 or 20 years, and additionally have better means of dealing with contamination, I don't see why we just shouldn't <i>wait</i>. Training graduate students in metagenomics is not a good enough reason to work on these rare fossils. 
</p>

<p>
One may say that the <i>same samples</i> will be sufficient for later sequencing of whole genomes, or other genes, or Neandertal athlete's foot fungus, or whatever, but in my experience it somehow never works out that way. Somebody is always coming back to grind up, dissolve, or laser ablate more bone. 
</p>

<p>
In fact, if I were looking to make the next advance in metagenomics, I would take some of that mammoth flesh, mix in some elephant blood, and find ways to resolve the parts of the resulting mix. <i>That</i> would be something. 
</p>

<h4>Are you saying you are against destructive sampling of these fossils? </h4>

<p>
Not at all. In fact, I think that genomics gives the most compelling reason <I>ever</i> for grinding up more bones. 
</p>

<p>
There is just a huge quantity of information from DNA sequences; far more than from the morphology -- especially for samples like bone fragments or isolated teeth. 
</p>

<p>
Heck, if <b>the devil came to me</b> and said I could have the full genome sequence of every fossil if I would agree to their destruction, I think that would be a good bargain!
</p>

<p>
But it's pretty clear that we're <i>not</i> in that situation. We can have our cake and eat it too -- and the longer we wait, the cheaper and less destructive this is likely to be. And frankly, just <i>one</i> Neandertal genome is going to give us plenty to work on for a long time. 
</p>

<p>
But then, I was trained as a fossil guy, and I'm used to working with a few bits and pieces. It gives me a natural advantage!
</p>

<h4>They say there's no significant evidence of interbreeding. Yet you told us last week that there <b><i>is</i></b> significant evidence of interbreeding. What gives?</h4>

<p>
A few years ago I gave a talk where I laid out what I saw as the problems interpreting nuclear DNA sequences from Neandertals. Now, this was long before we had any reasonable prospect of getting such sequences, so it was purely based on knowledge about human genetic variation. As I saw it then, there were two problems: 
</p>

<ol>
<li>Human mtDNA is really variable, with greater than 1 percent sequence divergence between people, and much higher in some places. In contrast, human nuclear DNA has less than <b>one base pair in a thousand</b> different between copies. To get a reasonable picture of variation among people, you need long nuclear sequences so that you will find polymorphisms. But ancient DNA is broken into short little sequences that are very difficult to reconstruct. With mtDNA, this is less of a problem because it is clonal and a person basically has one sequence in many copies. But most nuclear DNA (all autosomal DNA) exists in two, possibly different copies. <b>So reconstructing long enough sequences to study polymorphisms is very difficult.</b> </li>

<li>The coalescence age of human mtDNA is only a couple hundred thousand years, so sampling ancient humans is sort of likely to result in sequences that lie outside this range of variation -- and with Neandertals, that is precisely what happened. But nuclear loci have coalescence ages on the order of 600,000 to 2 million years or older. With these dates, the diversity among living people must significantly predate any divergence of archaic humans for most nuclear genetic loci. This means that <b>Neandertals ought to have shared a high proportion of  polymorphisms that are <i>still</i> variable in humans</b>. Since we can expect that Neandertals will not be very genetically divergent for these nuclear genes, compared to the genetic differences among living people, we can conclude that no gene is likely to tell us very much about the phylogenetic relationships of an ancient Neandertal with living people. </li>

</ol>

<p>
These two problems are still stumbling blocks for interpreting Neandertal sequences. But the research teams found a very clever way to circumvent them, by using <i>genomics</i> approaches instead of <i>genetic</i> approches. 
</p>

<p>
If you've been scratching your head wondering exactly why "genomics" has a buzz, then this is a good example. 
</p>

<p>
Because of projects like the HapMap and the chimpanzee genome project, we know a lot (not everything, but a lot) about human genetic polymorphisms and our genetic differences from chimpanzees. In fact, we have databases of human single nucleotide polymorphisms (SNPs), and human-chimpanzee comparisons. For each SNP, some humans have an <i>ancestral</i> nucleotide -- generally the one that chimpanzees have. Other humans have a <i>derived</i> nucleotide -- the one that appeared in some ancient human, and different from chimpanzees. 
</p>

<p>
For the most part, derived SNP alleles are <i>recent</i>. A few of them are very old, and these tend to be found at high frequencies (because the person who originated them had lots of descendants in that time). But many more of them are recent, found in a relatively small number of people today, who descend from a common ancestor during the past couple hundred thousand years. 
</p>

<p>
If Neandertals diverged from humans over 200,000 years ago, and they <i>didn't</i> interbreed after that time, then the Neandertal genome should have relatively few derived human SNPs. In contrast, if the two populations continued to interbreed after 200,000 years ago, they might share fairly many of these derived SNPs. 
</p>

<p>
Hence, we have <b>a potential test for Neandertal-human genetic interactions</b>. 
</p>

<p>
Noonan et al. (2006) looked for these derived SNPs and found very few of them. They concluded that there was no significant evidence of Neandertal-human interbreeding, although their statistical test couldn't rule out as much as 25 percent admixture (for reference, Plagnol and Wall 2006 estimated only 5 percent ancestry from <i>all</i> archaic humans, not only Neandertals). 
</p>

<p>
Green et al. (2006) also looked for derived SNPs. They had a much bigger sample of DNA to work with, so they ought to have a stronger test. Here's what they wrote (p. 334): 
</p>

<blockquote>Using the SNPs that overlap with our data from two large genome-wide data sets (HapMap, 786 SNPs and Perlegen, 318 SNPs), we find that the Neanderthal sample has the derived allele in 30% of all SNPs. This number is presumably an overestimate since the SNPs analysed were ascertained to be of high frequency in present-day humans and hence are more likely to be old. Nevertheless, this high level of derived alleles in the Neanderthal is incompatible with the simple population split model estimated in the previous section, given split times inferred from the fossil record. This may suggest gene flow between modern humans and Neanderthals. Given that the Neanderthal X chromosome shows a higher level of divergence than the autosomes (R.E.G., unpublished observation), gene flow may have occurred predominantly from modern human males into Neanderthals. More extensive sequencing of the Neanderthal genome is necessary to address this possibility.</blockquote>

<p>
If this observation holds (i.e., if it is not influenced by contamination, and the ascertainment function does indeed show this to be an excess of derived SNPs), then it is one of the strongest pieces of evidence for genetic intermixture of Neandertals and modern humans. Note that there are two avenues for this gene flow -- either from the ancient ancestors of modern humans <i>into</i> Neandertals, or <i>out of</i> Neandertals into early modern humans. I'm sure we will hear more about this when they have more sequence. 
</p>

<p>
In the meantime, the other source of evidence about Neandertal-human genetic interaction is the genomic variation of living people. Last week's paper on <i>MCPH1</i> (discussed <a href="http://johnhawks.net/weblog/reviews/neandertals/neandertal_dna/introgression_faq_2006.html">here</a>) is a good example of what that evidence looks like. The key feature is that if you troll through the genome, you begin to notice some loci with interesting genealogies. The interestingness is a combined signature of recent selection and ancient population structure. 
</p>

<p>
Looking for genes like <i>MCPH1</i> in the Neandertal genome is a no-brainer. We probably won't find a lot of them, because the Neandertals were a small subset of the ancient human population. 
</p>

<p>
There is one further problem. We can recognize these interesting loci in living people because they lie on relatively long haplotypes with little recombination. The inference is that such an allele must have begun from a very low copy number around 30,000 years ago, presumably because it was introduced from some archaic population. But the SNPs that are <i>presently</i> linked to the selected site were probably polymorphic within the archaic population, not fixed on a long haplotype. Unless we know exactly which SNP is the selected site on a human allelic variant, we may have some trouble telling whether an archaic genome has the allele. And as I note below, a large proportion of SNPs are going to be missing from the draft Neandertal genome even when it reaches an average 1x coverage. 
</p>

<p>
This just means that evidence from the genomics of living people and from the Neandertal genome won't mesh together seamlessly. There remains some complexity interpreting these relationships. 
</p>

<h4>The divergence date of Neandertal and human sequences is estimated at around 520,000 years ago. What does that mean? </h4>

<p>
First, what it <i>doesn't</i> mean. It doesn't mean that the human and Neandertal <i>populations</i> diverged 520,000 years ago. I noted above that the estimate of the genetic divergence time comes from the proportion of chimpanzee-human differences for which the Neandertal shares the human allele. But of course, some <i>living humans</i> have the ancestral, chimpanzee-like allele for many polymorphisms, so this comparison of polymorphisms is <i>not</i> saying that Neandertals were like chimps. Instead, we are just disregarding the Neandertal-specific evolutionary events. 
</p>

<p>
I'm sticking with the 520,000 year genetic divergence estimate from Green et al. (2006), instead of the older estimate from Noonan et al. (2006), because of the vastly larger sample in the Green paper. Still, most of the discussion does not hang too critically on the precise date; although the date changes the interpretation by degrees. 
</p>

<p>
The real interesting observation is the Neanderal-human genome draft difference compared to the human-human difference. Here's a passage from p. 354 of Green et al. (2006): 
</p>

<blockquote>We analysed the DNA sequences generated from a contemporary human using the same sequencing protocol as was used for the Neanderthal. Although ancient DNA is degraded and damaged, this comparison controls for many of the aspects of the analysis including sequencing and alignment methodology. In this case, 7.1% of the divergence along the human lineage is assigned to the time subsequent to the divergence of the two human sequences. The average divergence time between alleles within humans is thus 459,000 years with a 95% confidence interval between 419,000 and 498,000 years. As expected, this estimate of the average human diversity is less than the divergence seen between the human and the Neanderthal sequences, but constitutes a large fraction of it because much of the human sequence diversity is expected to predate the human-Neanderthal split. Neanderthal genetic differences to humans must therefore be interpreted within the context of human diversity.</blockquote>

<p>
They don't specify where this "contemporary human" was from. The draft human genome is a chimera made up of anonymous people from different populations. That means that wherever the "contemporary human" is from, it will be the same region as represented by some part of the draft genome, but not all. So the divergence between these two mystery sequences is likely to be greater than average within a single population, and less than average between different populations. 
</p>

<p>
Keeping that in mind, the human-Neandertal difference is <b>startlingly close</b> to this human-human difference measurement. The Neandertal is only 10 percent more different from the draft human genome than these two human sequences are from each other. 
</p>

<p>
It seems very likely that we will find pairs of living human populations where the <i>average</i> genetic divergence is older -- maybe much older -- than this human-Neandertal divergence. For instance, it seems almost certain that <b>the great genetic variability among living African groups will exceed this human-Neandertal difference</b>. 
</p>

<p>
Some geneticists have noted that European and Asian populations seem to be a genetic "subset" of African populations, at least for many genetic loci. With these kinds of numbers, it looks like Neandertals may be a subset of living human diversity in the same sense. I've never much liked that formulation, because "subset" is never really an accurate description of the genetic relationships. But if the seat of living human diversity is Africa, <b>adding Neandertals to the mix may not change that pattern at all</b>. 
</p>

<p>
As Green and colleagues note, most of the genetic divergence between humans and Neandertals, and between humans and other living humans, is actually much older than the divergence of these populations from each other. 
</p>

<p>
At one limit (that is, assuming complete isolation of humans and Neandertals after some date), the <i>population</i> divergence time depends on the effective size of the population that was <i>ancestral</i> to living humans and Neandertals. It is basically not possible to obtain a good estimate of this ancestral effective population size from the current Neandertal data -- mainly because good estimates depend on heterogeneity in divergence times among loci, which we can't infer for the short Neandertal sequences. 
</p>

<p>
Both papers assume that this ancestral effective population size was small -- even smaller than the long-term human effective population size of around 10,000 individuals. A smaller effective size for the human-Neandertal ancestral population is fairly unlikely, though, since it must have been distributed across large parts of Europe and Africa at a minimum. More likely, the effective size was close to 10,000, just as in humans, since the human effective size is inferred to have been that small over at least the past million years. 
</p>

<p>
If you're reading the term "effective population size" for the first time, don't worry. It doesn't mean "population size", and it has mainly a technical genetic meaning. It is sort of important that the Neandertal sequence supports this particular effective size over the long term, but it will take another post to explain why. 
</p>

<p>
As noted above, the populations may never have been isolated. The derived SNP evidence might suggest that there was never <i>any</i> population divergence, or at least no long period of complete isolation, between humans and Neandertals. We'll have to wait and see. 
</p>

<h4>Why does this bone have such a low level of contamination compared to other Neandertals?</h4>

<p>
I should start by pointing out that "contamination" here means "modern human sequence". All fossil bones are loaded with exogenous DNA, like bacterial and fungal genomes that invaded after the animal died. From a certain point of view, those exogenous genes are contaminants -- we are generally not interested in <i>their</i> sequences, and sorting them out from the endogenous Neandertal DNA is a real nuisance. But because we have a <i>reference</i> genome from humans to compare with the sequences from the ancient bone, we <i>can</i> sort out these bacterial and other exogenous sequences. So although they do "contaminate" the bone, they don't distort our picture of the sequence. 
</p>

<p>
The real problem is that there are contaminating sequences from recent <i>humans</i> in the ancient bones. These sequences come from excavators, anthropologists who studied the bones, museum personnel, graduate students who cleaned and prepared the bones for sequencing, other samples from the labs doing the work, and who knows where else. 
</p>

<p>
I have been asked many times why they can't eliminate this contamination. For example, why can't they just clean the bone, or take samples from deep inside the bone, or take samples from deep inside of teeth, or use a clean room, yada yada yada. 
</p>

<p>
The answer is that they <i>do</i> wash the bones, and they <i>do</i> eliminate the outer surface, and they <i>do</i> take samples from deep inside of bones, and they <i>do</i> work in a clean room, with ultraviolet lights and positive air pressure so that DNA can't get sucked into the room, and rubber gloves and bunny suits, and the whole nine yards. And <i>the bones are still contaminated</i>, deep inside them. 
</p>

<p>
Now, you may imagine anthropologists picking their noses with the bones, and using them as chopsticks, and putting them up to their ears to hear them breathing, and all manner of other things. The truth is, I have no idea how the contamination gets in there, and neither does anybody else. It's just there, and apparently we can't avoid it. 
</p>

<p>
The extraction team looked at lots of Neandertal specimens, with one question in mind: How much human contamination does this bone have? To answer this question, they amplified mtDNA sequences, and assessed what proportion of transcripts were Neandertal-like and what proportion were human-like. Vindija 80 stood out as having a very low proportion of human-like transcripts -- less than 2 percent. So they inferred that there was little contamination of the sample by recent human DNA, and are working under the assumption that the nuclear genome is contaminated in a similar low proportion. 
</p>

<p>
As for why this particular bone has such low contamination, well, nobody really knows that either. Svante P&auml;&auml;bo speculates that it is because Vi 80 was originally identified as fauna and hasn't been handled much. He might well be right. Which would bring us back to the nose-picking chopstick bone theory, I suppose. 
</p>

<h4>If Vindija 80 was put in a box with fauna, it can't be very diagnostic. This high preservation seems very unusual. How do they know it was a Neandertal?</h4>

<p>
The radiocarbon date is 38,310 +/- 2130, and they found very high preservation of a Neandertal-like mtDNA sequence. If you think that fails to answer the question, well...
</p>

<h4>How can they deal with the damage to ancient DNA sequences?</h4>

<p>
One of the things that has become clear about ancient DNA research is that DNA from ancient fossils undergoes various kinds of damage. The most obvious is the fragmentation of the DNA into very small pieces, a problem that both the sequencing approaches have been designed to circumvent. 
</p>

<p>
But a more serious problem is that some bases become degraded over time in ways that cause the sequencing methods to misidentify them. For example, cytosine (the "C" base) can be chemically modified over time into a base called uracil, which sequencing methods misidentify as a thymine (the "T" base). 
</p>

<p>
There seems to be no way to tell which base pair changes are diagenetic (i.e. DNA damage-induced) and which are genuine Neandertal changes. 
</p>

<p>
So, the teams took a radical approach: just ignore all the changes that are possibly damage. Instead of analyzing Neandertal-specific changes, they decided to assess the status of human polymorphisms and human-chimpanzee differences in the Neandertal seqeunce. This method is how they estimated the Neandertal-human genetic divergence time, for example -- because the Neandertals have approximately 96 percent similarity with humans for human-chimpanzee genetic differences, it is possible to infer that their genes diverged from the average human gene only 4 percent of the evolutionary time separating humans and chimpanzees. The research teams assumed that humans and chimpanzees are separated by 13 million years of evolution -- this includes the time on <i>both</i> the human and chimpanzee lineages since their common ancestor, assumed to be 6.5 million years ago. These dates and genetic differences produce an estimate of around 520,000 years ago for human-Neandertal genetic divergences.
</p>

<p>
In the long run, it should be possible to sequence the genome with multiple coverage, which would allow damage to be resolved. With many copies, the damage to any individual DNA sequence will be unique, while changes that are evident in multiple copies must probably be real. 
</p>

<p>
But we are quite a ways from the long run, so for the time being we have to deal with DNA damage. For individual genes, it may be possible to reason exactly what effects changes would have and thereby arrive at a conclusion about which changes are diagenetic. For instance, only a minority of such changes will affect coding regions, and some of those will be synonymous changes, so only a small proportion will make amino acid changes, and if there are only a couple of these per gene the resulting protein structure may be able to be analyzed. So from a functional perspective, it should be possible to work with damaged sequence. 
</p>

<p>
The main problem is from the statistical perspective (i.e., assuming neutrality), and here I think the teams have taken a very reasonable approach by just throwing the changes out. 
</p>

<h4>Will they really be able to sequence the full Neandertal genome in two years?</h4>

<p>
I got a lot of questions from journalists on this point. I really see no reason to doubt it -- they know their average sequence yield from a given amount of extract, and the proportion of that yield that is actually Neandertal DNA. 
</p>

<p>
The main caveat is a statistical one: 3 billion base pairs of sequence is -- on average -- one full coverage of the genome, but in practice some loci will be sequenced many times, while a fairly large proportion (a bit over 30 percent) won't be sequenced at all. 
</p>

<p>
A billion missing bases may not seem like a big deal, but there is a catch: the short average fragment size means that the missing patches will be distributed throughout every gene. Since the average gene covers a region of a few kilobases, complete gene sequences will be pretty rare -- most will have gaps in them amounting to around 30 percent of their length. 
</p>

<p>
Or to put it another way, a bit more than 30 percent of informative SNPs in humans will not be represented in the first Neandertal genome draft. 
</p>

<p>
A second issue is that the genome of Vindija 80 is <i>not haploid</i> -- there are two copies of most everything in that bone. Some of these copies were polymorphisms in Neandertals, and if these are reconstructed into a single sequence, there will be mixed-up haplotypes. This means that it will be difficult, if not impossible, to assess whether there were functional multi-SNP differences between the human and Neandertal sequences of particular genes. 
</p>

<p>
Anyway, that's probably getting beyond ourselves. No doubt somebody will think of some way to improve these problems; and it will eventually become cheap enough to do 10x coverage instead of 1x coverage. 
</p>

<h4>They're already making plans to clone Neandertal super-soldiers, aren't they?</h4>

<p>
Maybe unsurprisingly, this question about Neandertal cloning is the one most journalists so far have wanted to ask me. I'm sure they're asking everybody, hoping that somebody will slip a really pithy quote for them. 
</p>

<p>
Since I have clones here at home, I can't bring myself to get to worked up about it. A Neandertal clone army would definitely be an improvement over a Neandertal Jar-Jar. 
</p>

<p>
Personally, I have another problematic scenario in mind, which I am developing elsewhere. 
</p>

<h4>References:</h4>

<p class="cite">Green RE, Krause J, Ptak SE, Briggs AW, Ronan MT, Simons JF, Du L, Egholm M, Rothberg JM, Paunovic M, P&auml;&auml;bo S. 2006. Analysis of one million base pairs of Neanderthal DNA. Nature 444:330-336. <a href="http://dx.doi.org/10.1038/nature05336">DOI link</a></p>

<p class="cite">Lambert DM, Millar CD. 2006. Evolutionary biology: Ancient genomics is born. Nature 444:275-276. <a href="http://dx.doi.org/10.1038/444275a">DOI link</a></p>

<p class="cite">Margulies M and 55 others. 2005. Genomie sequencing in microfabricated high-density picolitre containers. Nature 437:376-380. <a href="http://dx.doi.org/10.1038/nature03959">DOI link</a></p>

<p class="cite">Noonan JP, Coop G, Kudaravalli S, Smith D, Krause J, Alessi J, Chen F, Platt D, P&auml;&auml;bo S, Pritchard JK, Rubin EM. 2006. Sequencing and analysis of Neanderthal genomic DNA. Science 314:1113-1118. <a href="http://dx.doi.org/10.1126/science.1131412">DOI link</a></p>

<p class="cite">Pennisi E. 2006. The dawn of stone age genomics. Science 314:1068-1071. </p>

<p class="cite">R&ouml;mpler H and 8 others. 2006. Nuclear gene indicates coat-color polymorphism in mammoths. <a href="http://dx.doi.org/10.1126/science.1128994">DOI link</a></p>

<p class="cite">Ronaghi M. 2001. Pyrosequencing sheds light on DNA sequencing. Genome Res 11:3-11. <a href="http://www.genome.org/cgi/content/abstract/11/1/3">Abstract</a></p>

<p class="cite">Schloss PD, Handelsman J. 2003. Biotechnological prospects from metagenomics. Current Opinion in Biotechnology 14:303-310. </p>


