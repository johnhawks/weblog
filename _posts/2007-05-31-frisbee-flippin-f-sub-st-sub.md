---
layout: single 
title: "Frisbee flippin&#39; F<sub>ST</sub>" 
category: story
permalink: /weblog/reviews/evolution/mathematical/fst_frisbee_2007.html
comments: false 
author: John Hawks 
---


<p>
Evolgen's RPM <a href="http://scienceblogs.com/evolgen/2007/05/always_choose_same.php">writes about</a> the opening coin flip of Ultimate: 
</p>

<blockquote>The beginning of many Ultimate (nee, Frisbee) games is marked by flipping discs to decide which team must pull (kick off) and which goal each team will defend at the start of the game. This is sort of like the coin flip before an American Football game. Two players -- one from each team -- flip a disc in the air. A third player -- a representative from one of the teams -- calls "same" or "different", referring to whether both discs land with the same side (top/bottom or heads/tails) facing up or different sides facing up. If he guesses right, his team gets to choose whether they want to pull or receive to start the game or if they would like to choose which end of the field to defend.</blockquote>

<blockquote>From my casual observations, most players tend to pick "same" or "different" quite randomly. That would be all well and good if the probability of each event were equal, but they are probably not. If the probability the disc lands top side up (we'll call that heads) is equal to <i>p</i> and the probability it lands bottom side up (tails) is equal to <i>q</i>, then we can calculate the probability of the same and different outcomes of two flips of the disc. The probability both discs land heads up is <i>p</i><sup>2</sup> (assuming the two flips are independent), and the probability that both discs land tails up is <i>q</i><sup>2</sup>. That means the probability of "same" is <i>p</i><sup>2</sup>+<i>q</i><sup>2</sup> because the two outcomes are mutually exclusive. The two discs can land with different sides up if the first disc lands heads up and the second lands tails up (this occurs with probability <i>pq</i>) or if the first disc lands tails up and the second lands heads up (with probability <i>qp</i>). Because these two events are also mutually exclusive, the probability of "different" is 2<i>pq</i>.</blockquote>

<p>
In other words, your opening frisbee flip is a diploid, drawn from a population with allele frequencies <i>p</i> and <i>q</i>. The call is "homozygote" or "heterozygote", and the population probabilities of the two options are the heterozygosity (2<i>pq</i>) and the homozygosity (<i>p</i><sup>2</sup> + <i>q</i><sup>2</sup>).
</p>

<p>
RPM points out that this is an unfair system whenever the allele, er, frisbee flip frequencies vary from 50%. Any other frequency, and the homozygosity exceeds the heterozygosity, by an easily predictable amount. For instance, if both frisbees have a probability 0.7 of landing face-up, then the homozygosity would be 0.58 and the heterozygosity 0.42. You would want to call "same" in this situation, since you would have a 1.38 times better chance of winning the flip. If that makes a difference. 
</p>

<p>
OK, so far so good. 
</p>

<p>
But notice something interesting about the flip: a probability 0.58 of a homozygote flip of two frisbees is substantially less than the probability 0.7 of a <i>single</i> frisbee face-up, in this example. In other words, if the frisbees aren't "fair," (i.e., <i>p</i> &ne; <i>q</i>) flipping <i>two</i> frisbees and calling "same" or "different" is a lot fairer than flipping <i>one</i>. 
</p>

<p>
For a small departure from 50-50 odds, the system of double-frisbee flips almost entirely erases the bias. For example, if <i>p</i>=0.6, then the homozygosity is only 0.52. So a 60-40 single frisbee flip becomes a 52-48 double flip. Not bad. Calling "same" all the time would only eke out a 4% advantage in the long run. 
</p>

<p>
So double-frisbee-flipping is a remarkably good system for correcting small biases in the probability of frisbees landing "up" or "down". I suppose if the frisbees got as bad as 80-20, somebody would notice and start getting out a coin instead. 
</p>

<p>
This is a nice analogy for a problem in genetics that most introductory students (and a fair share of professionals) have trouble understanding: the genotype frequency of heterozygotes in a population decreases much more slowly than the frequency of an allele. 
</p>

<p>
Why is this important? Simple -- the standardized measure of genetic differences between two populations, <i>F<sub>ST</sub></i>, is not a linear function of allele frequencies. It is a linear function of heterozygosity. In particular, it measures the <i>decrease</i> in heterozygosity in a group of subpopulations compared to the <i>expected</i> heterozygosity if the total population including those subpopulations were panmictic (that is, exchanged genes at random).
</p>

<p>
If the average heterozygosity in the subpopulations is <i>H<sub>S</sub></i> and the expected heterozygosity in the total population under panmixia is <i>H<sub>T</sub></i>, then <i>F<sub>ST</sub></i> is given by: 
</p>

<div style="text-align:center;">
<img src="/graphics/fst_heterozygosity.png" width="131" height="40" alt="Fst=(Ht - Hs)/Ht" />
</div>

<p>
Now, let's look at <i>F<sub>ST</sub></i> between two subpopulations. Assume a genetic locus with two alleles, frequencies <i>p</i> and <i>q</i>. In one subpopulation, the frequency <i>p</i>=0.7, in the other, <i>p</i>=0.3. These subpopulations are pretty different in allele frequencies, in other words -- where one has only 30 percent of an allele, the other has 70 percent. Since the two subpopulations are equal in size, the allele frequencies in the total population here are <i>p</i>=0.5 and <i>q</i>=0.5. Here is the setup: 
</p>

<div style="text-align:center;">
<img src="/graphics/fst_subpopulations.png" width="400" height="313" alt="Fst between two subpopulations" />
</div>

<p>
Now, the total allele frequencies of <i>p</i>=0.5 and <i>q</i>=0.5 mean that the expected heterozygosity under panmixia would be <i>H<sub>T</sub></i>=0.5 as well. But the subpopulations have different allele frequencies -- both of which lead to heterozygosities of 0.42. Hence, the <i>F<sub>ST</sub></i> between these subpopulations is 0.16. 
</p>

<p>
An <i>F<sub>ST</sub></i> of 16 percent is not very great -- in fact, it is only a bit larger than the average <i>F<sub>ST</sub></i> between human continental populations, between 0.1 and 0.15. But notice that, like the two-frisbee flip, a small bias toward homozygosity in the subpopulations is the result of a fairly great difference in allele frequencies -- one population has more than twice the frequency of an allele than the other. 
</p>

<p>
As in the case of the frisbees, a 60-40 split leads to a very slight reduction of heterozygosity -- if the allele frequency <i>p</i> in the two subpopulations were 0.6 and 0.4, then the subpopulation heterozygosity <i>H<sub>S</sub></i>=0.48, and the estimate of <i>F<sub>ST</sub></i> would only be 0.04. 
</p>

<p>
The range of 0.1 to 0.15 is the <i>average</i> <i>F<sub>ST</sub></i> for human populations, taken across many different genes. That means that some genes have lower allele frequency differences, and other genes have larger ones.
</p>

<p>
The bottom line is that, although 10 to 15 percent is a small number, and reflects a high historic rate of genetic exchange, it corresponds to rather large differences in allele frequencies. This is because the proportions of genotypes in two populations do not differ as much as the allele frequencies. Since phenotypes are a function of genotypes, and not of allele frequencies, the comparison provided by <i>F<sub>ST</sub></i> is more relevant to phenotypic differentiation than allele frequencies. Still, averaging many genetic loci together provides a muddled comparison, since the average combines some genes that differ greatly with many that differ hardly at all. 
</p>

<p>
In some ways, analogous to the frisbee flip, <i>F<sub>ST</sub></i> greatly reduces the apparent differences between subpopulations. This can mask substantial <i>evolutionary</i> differentiation, because evolution drives the frequencies of alleles. 
</p>

<p>
So it is important to be specific about what you are trying to measure between subpopulations. Do you care about genotype proportions? For that, <i>F<sub>ST</sub></i> is an appropriate measure. In fact, it's ideal for showing whether genotypes are likely to be shared between subpopulations with different allele frequencies. Or do you care about allele frequencies? For that, you should probably deal with the allele frequencies directly. Whatever you do, don't confuse a low <i>F<sub>ST</sub></i> for a lack of evolutionary differentiation; because a low <i>F<sub>ST</sub></i> may nonetheless reflect very substantial differences in allele frequencies. 
</p>


