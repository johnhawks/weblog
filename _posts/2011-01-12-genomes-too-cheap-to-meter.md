---
layout: single 
title: "Genomes too cheap to meter" 
category: story
permalink: /weblog/topics/biotech/whole-genome/sequencing-1000-dollar-genomes-2011.html
tags: [sequencing, biotech, future, technology] 
comments: false 
author: John Hawks 
---

Matthew Herper is a science and medicine contributing writer at Forbes.com. He has just written a series of posts themed as "Gene Week", focusing on advances in genomics. One of the most provocative, <a href="http://blogs.forbes.com/matthewherper/2011/01/06/why-you-cant-have-your-1000-genome/">"Why You Cant Have Your $1,000 Genome"</a>, focuses on the hidden costs of interpretation and high-coverage necessary for clinical use of genome data.
<!--break-->
His argument is that even if the cost of sequencing a low-coverage genome goes to $1000, the true cost of using the data will remain much higher: 

<blockquote>Great buzzword, but it may never happen, especially not any time soon and especially not at a cost of $1,000. Research costs for sequencing a human genome may drop that low very soon, but that doesnt include paying the doctors or the cost of information technology to process the data. Research genomes are not accurate enough for medical use. Getting better accuracy requires sequencing the DNA more times, which drives the cost back up. Id think if were talking about actual medical use, $10,000 is a more accurate number. Certainly, it is not going to drop below the $2,000 level for a magnetic resonance imaging scan. And once the technology is in use, I think it is possible that the costs will go back up.</blockquote>

Daniel MacArthur replied to this argument, <a href="http://scienceblogs.com/geneticfuture/2011/01/why_you_can_have_your_1000_gen.php">"Why you CAN have your $1000 genome - so long as you learn what to do with it"</a>. 

<blockquote>None of this is simple, but it will become easier with time. As the retail costs of sequencing drops, a substantial niche will develop for innovators providing affordable, intuitive, accurate interpretation tools (embryonic versions already exist: see, for instance, Promethease or Enlis Genomics). Open-source academic software built for large-scale sequencing projects will be adapted for use by non-specialists. The increasing availability of large-scale computing power (for instance, via Amazon EC2), coupled with this intuitive software, will make even compute-intensive analyses available to the educated, motivated lay-person.</blockquote>

MacArthur sketches out a genome interpretation landscape in which professionals and tinkerers support a community of genome hobbyists. This landscape is already taking shape thanks to MacArthur and many others (even me), and it's a solid prediction that this kind of human genomics will become more and more important, using open access tools to investigate history and phenotype prediction.

Herper has a reply and consideration of the two posts, Herper <a href="http://blogs.forbes.com/matthewherper/2011/01/07/debating-the-1000-genome/">"Debating The $1,000 Genome"</a>. In it, he notes the comments of several professionals that the $1,000 number itself is not an important fact, it is the availability of sequencing within that order of magnitude. 

The inevitability of the $1000 genome has already made it irrelevant. We should expect a $1000 genome announcement this year. This will be hype, because the real $1000 genomes won't be here until...<i>next</i> year! Before the end of 2014, whole genome sequences at 4x coverage will cross the $100 mark. I think there's a good chance they will be less than $50 at that time. 

Based on numbers I've seen, those numbers are around six months optimistic. Geneticists are already planning projects anticipating $100 genomes -- some suggest that the next big project should be a "Million Genomes", because there isn't any sense bothering with a hundred thousand. 


It helps to realize what is driving the rapid reduction in price. The "next-gen" approaches have shared many basic assumptions (e.g., in situ amplification) but have not thus far been stymied by bottlenecks caused by patent overlaps because they have progressed along semi-independent pathways. As the technology moves to long single-strand approaches, multiple approaches still seem viable, although we are awaiting a solid demonstration of these methods at higher throughput. Price is not the only factor differentiating startups -- sequence quality and ease of sample prep are very important. But major research institutions justify new equipment by runtime and amortized acquisition costs, over years. A new sequencer needs to run enough this year not only to pay its overhead, but to pay the opportunity costs of a five-fold cheaper sequencer next year. As long as progress along multiple trajectories is possible, tech startups will continue the rapid reduction in per-genome price -- because price is the most visible way of differentiating their offerings and extending the sequencing market. 

This cannot continue indefinitely: at some point there may remain only one viable path to faster or cheaper sequencing. Or one company may be able to make startups more difficult by cornering the essential patents along multiple development trajectories. 

There are two fundamental questions: 

1. <b>Where's the bottom?</b> Cells replicate DNA fairly slowly, and they don't transmit the resulting data in a form that computers can read. Today, rapid sequencing depends on running massively parallel reactions, exploiting imaging electronics and computers and far from the limit of either (which themselves continue to increase in capacity subject to Moore's Law). We may be surprisingly close to a portable sequencing device the size and expense of a film camera. 

But the bottom of the market depends may depend less on supply and more on demand. Maybe human genomes will be clinical necessities, or maybe they will remain niche diagnostic data. In either case, there's an upper limit. We'll never need much more medical sequencing than we have people. 

Genomics cannot work on the microcomputer model. Computer companies sell new equipment to people and companies who already have lots of last-generation equipment. Genomics cannot work on that model: once you have your genome sequence in the cloud, you won't need it again. By itself, this business model stabilizes at fairly expensive prices. As long as you need to bill a technician and maintain highly regulated records, your service costs will be very high. That leaves little incentive for lowering the sequencing cost. It's like the genomics DMV -- when was the last time your state gave you a technology rebate on vehicle registration?

Future cost reductions must depend on applications of massive sequencing in agriculture, genetic engineering and synthetic DNA. Those areas can support a different business model, one that can operate on an annual basis. They create potentially a much larger, decentralized global market, like the market that supported the development of microcomputers. 

The problem is developing the applied genetics -- the "killer app" to take advantage of the cheaper technology. And that brings us to...


2. <b>Where's the utility?</b> The reduction in cost is happening despite the fact we don't really know why genomes will be useful. Both Herper and MacArthur agree that one obstacle to clinical use of genomic data will be annotating and interpreting the sequences. This problem generalizes to applications far beyond clinical contexts. How do we use genomes to do anything interesting or useful? 

At the margins, of course, we know what to do with a genome. Look for damaging mutations. This is a straightforward empirical challenge -- find out how alterations to particular nucleotides would affect phenotypes, both by themselves and in combination with common variants elsewhere in the genome. Annotation and interpretation will <i>require</i> us to have genomes from millions of people and expression data from hundreds of thousands of human tissue samples and animal models. 


Every other use of genomic information poses similar challenges. Do we want to use genomes to place individuals in a genealogical context? We need to work out the genealogical trees for loci genome-wide and find the historical causes for correlations within these trees. Want to use genomes to predict the response of old-growth forests to rainfall fluctuations? Testing 10,000 dead blackbirds for causal factors? Same story -- gene variants, microclimates, and functional networks. 

There will be an expensive, professional class of genome interpretation. In medicine, these will be clinicians or clinical assistants of some kind. In applied genetics, these will be research geneticists and postdocs. If you want a personalized genealogical consultation, a gut microbiome assessment of your beef cattle, or a read on that speck of black mildew in the basement, there will be a consultant for you. Like today's IT consultants, these genome consultants' knowledge, skills, and price structures will vary. They may offer knowledge of the latest discoveries, a crew of paid tinkerers, or the comfort of hand-holding, but mostly they're adding value to the software. 

Off-the-shelf software may always be a step behind the state of the art in genome interpretation, but it will always be cheap. Today you can compare your genome to cataloged SNP-phenotype associations for free, or you can pay $5 a month to 23andMe for a more user-friendly interface and non-expert information presentation. I expect HMO's to incorporate similar information applications as they embrace genomics, just as most are currently moving to patient-accessible charting software. Last year's research information will always be cheap, and for most purposes it will be good enough. 

Put these things together, and personal genomics today is where personal computing was in 1973. We haven't yet had an Altair, much less an Apple 2. But it's almost in reach. Quasi-professional hobbyists can cobble together data using primitive tools, and carry out the same analyses as postdocs. Sequencing costs falling by an order of magnitude every other year. The state of the art in interpretation totally free for the trained, with applied genomics and synthetic biology as growing industries. Genomes may not be literally too cheap to meter, but they'll certainly be, as George Church has suggested, free with additional purchase.

