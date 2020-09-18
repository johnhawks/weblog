---
layout: single 
title: "Handling exponential growth in demographic models" 
category: story
permalink: /weblog/reviews/evolution/demography/voight-demographic-exponential-2008.html
tags: [models, genetic drift, Late Pleistocene, recent selection, demography, exponential growth, non-primate] 
comments: false 
author: John Hawks 
---

Exponential growth is a feature of current human populations, and was may represent how the human population behaved during some episodes of its demographic history. However, "exponential" can mean different things to different people, if you're not used to thinking mathematically about growth. So I need to lay out some definitions:
<!--break-->
1. Linear population growth: The same <b>number</b> of individuals is added in each successive time interval. Hence, population size is a linear function of time. Think of driving your car at a constant velocity. Or, you deposit your paycheck every month into a bank account, without interest. 

2. Geometric population growth: The same proportion of individuals is added in each <b>discrete</b> time interval -- for example, in each generation. Time is not measured continuously. Consider a bank account, compounded annually. 

3. Instantaneous population growth: At one discrete time, the population is considered to transition immediately, without any time passing, from a small to a large size. Suddenly, a benefactor makes a large deposit in your bank account. 

4. Exponential population growth: The population grows by a constant proportion per unit time, measured continuously. Consider a petri dish with a growing colony of <i>E. coli</i>, or a bank account compounded <i>continuously</i>. 

If you drive your car at a constant speed, then in half the time it would take to reach your destination, you will be halfway there. 

But exponential growth does not work this way. Suppose you have a dollar in the bank now, and you invest at a continuous rate equivalent to 5 percent annually. In 100 years, you expect to have $148. If your account grew linearly, you would have $74 in 50 years. But at your exponential growth rate, you will have only $12. In fact, it will take 86 years for your account to reach halfway to its "destination" of $148. 

Now, what if we approached the question from the opposite direction? Suppose that our account <i>really does</i> grow exponentially, that we really did put in one dollar at the beginning, and we really did end up with $148 after 100 years. But suppose that we <i>also</i> really did have $74 in the account after 50 years. The form of the solution here is obvious: we are dealing with at least two different rates of increase -- one for the early part of the 100-year interval, and a different rate for the later part. 

In fact, there are an infinite number of ways that the rate might change over time to attain this result. Maybe it changed 30 years into the span, or 55 years in. Maybe it changed continuously. Maybe the account shrank at some times and grew at others. 

We can only attempt to deal with these unknowns by taking additional samples. What was the account balance after 20 years? After 21? 22? 73? I'll call these observations "signposts" -- because they give us markers along the path taken by the size of the account. 

You get the idea: this bank problem is very much like our problem reconstructing ancient demography in human populations. When we consider genetic variation, what we observe in today's genes was affected not only by the population sizes at the signposts that we observed in the past, but <b>by every point in between</b>. 

Suppose that our bank account was not merely symbolic money, but that the bank put in <i>actual pennies</i> when the amount increased. It's a simple enough matter to examine all 14,800 pennies at the end of the 100 years. We can ask, how many of those pennies will have mint marks dating 20 years into the span? How many will have mint marks dating 73 years in? The answers to those questions depend on the account balances across the entire 100-year span. That is the kind of question that we address about human history when we observe today's genetic variation. How many people today share haplotypes that originated 5000 years ago? What about 35,000 years ago? 143,000?

When we make a prediction from evolutionary theory -- for example, the prediction of the age distribution of haplotypes in a population given the assumption of no selection -- then we must assert a model of demographic history. It used to be that you could simply assert a constant population size. But that's no longer any good for human evolution, since our population has obviously grown massively over time. 

If we want our predictions to relate to the <i>real</i> population history, then we ought to use as many signposts as we can find, so that we can constrain our models. For human demographic history, those signposts come from several sources, including the archaeological record, ethnographic comparisons, and increasingly genetic sampling. As I'm going to show, it's really not good enough to just pick numbers out of thin air. The reason is that there are many ways that your model can work against you unless you put in as accurate numbers as you can find. 




<h4>How <i>not</i> to handle exponential growth</h4>



A simple exponential model has the benefit of simplicity. But if we don't choose our signposts carefully, a simple model will lead us badly wrong. Here, I'm going to examine the demographic simulations performed by Voight et al. (2006). I'm not picking on this paper in particular -- it actually stands out as a relatively <i>good</i> example of demographic modeling in genetics. This paper has been cited a lot of times, and it is valuable in part because of its detailed analysis of the power of detecting recent selection. 

Some of the power analyses were based on demographic models applied to the data from the Yoruba HapMap sample. Voight et al. (2006) considered only exponential growth models for the Yoruba (as opposed to the Asian and CEU HapMap samples, for which they also considered bottlenecks of various kinds). At the low end, the authors considered a model with no growth at all -- a constant effective population of 11,156 individuals. At the high end, they considered a model in which the population grew exponentially from an ancestral size of 10,018 individuals up to a current size of 1,910,000 individuals, with growth commencing 750 generations in the past. Other models were in between these extremes, although many had earlier onsets of population growth (up to 4000 generations ago). These values are reported in the online correction to the original article. 

At the outset, we can observe that these values are far too low, both for the ancestral and the current populations. The current population size of sub-Saharan Africa is on the order of 650 million individuals. This, of course, disproportionately represents the last few generations of rapid growth. But even in the year 1500, sub-Saharan Africa had a population on the order of 80 million people (Biraben 2003). The effective size of this population would be between 20 and 40 million. Of course, the Yoruba HapMap sample does not represent this population uniformly. The present population of Nigeria is 148 million, the number of Yoruba within this population approximately 30 million. Applying the same growth constant, we might estimate that this population had numbered around 5 million in the year 1500. But as we go back in time, we must encompass a wider cone of ancestry, as genes have flowed into the Yoruba from other populations. Hence, an effective 2 million individuals is certainly too small for the present population by a factor of five to ten, and plausibly too small for the population of 500 years ago by a smaller factor. 

The ancestral size is more seriously in error. Certainly, going back to 500,000 years ago or earlier, the long-term effective population size for humans really was on the order of 10,000 individuals. Since autosomal genes coalesce across that span or longer, we need to employ demographic models that incorporate this small ancestral size. However, we now know that this small size did not characterize <b>any</b> of the Late Pleistocene of Africa (as <a href="http://johnhawks.net/weblog/reviews/genetics/mtdna_migrations/sub-saharan-africa-population-size-behar-2008.html">I discussed last month</a>). Instead, the African population had reached an effective 38,000 individuals by 144,000 years ago, and grew after that time. So the initial size used by Voight et al. (2006) is small by a factor of more than four. 

But what matters much more is the <i>combination</i> of date and size. That's because the <i>entire period</i> matters to genetic variation, not merely the signposts. 

The models applied by Voight et al. (2006) may be fourfold too small at the beginning of the Late Pleistocene. But what does archaeology tell us about the African population in the early LSA, around 20,000 years ago, when Voight et al. (2006) suggest it had just begun to increase in numbers? Biraben (2003) puts the world population over 5 million individuals by that time. Taking this estimate, the sub-Saharan fraction of the global population at that time may have been substantial, more than a million individuals. That would mean that the Voight et al. (2006) estimate is perhaps only a thirtieth of the true value. Still, Atkinson et al. (2008), surveying mtDNA variation, found that the sub-Saharan population was apparently small compared to southern Asia around 20,000 years ago, with a sub-Saharan effective size less than 100,000 individuals. In that view, the Voight estimate is at least a tenth of the most accurate value. 

But what across the span from 10,000 to 5000 years ago -- the time range corresponding to the highest fraction of ascertained selection in their data? At the end of this time range, 5000 years ago, the best demographic estimates place the sub-Saharan African population around 6 million individuals, or perhaps 1.5 to 3 million effective individuals. The largest <b>exponential</b> growth model applied by Voight et al. (2006) predicts a continuous growth rate of 0.00028 per year during the last 750 generations. That would predict an effective size 5000 years ago of only 470,000 individuals -- perhaps a third to a sixth of the real value. 

In other words, the simulations conducted by Voight et al. (2006) have overestimated the power of genetic drift during the last 144,000 years, and most critically in the period around 20,000 to 5000 years ago. The problem is that the signposts are wrong: replace the demographic assumptions with better ones, and you bring them more into line with reality. In this case, the estimate of <i>current</i> effective size was wrong, but not unreasonably so -- it's possibly within factor of two. But the early values are wrong by a factor of ten or more, and the errors compound by the use of the simple exponential growth model. Replacing the more recent interpolated values with real estimates taken from archaeological and ethnographic models would be more complicated, but would actually <i>remove</i> uncertainty in the model. 


What are the effects of these models on the results of the paper? Figure 4 in the corrected paper shows the comparison of the real Yoruba data to the simulated datasets. In all cases, the simulated datasets have <i>less</i> variation in the critical statistic than the real data, which indicates the presence of widespread selection within the real data. If we incorporated a more accurate demographic model, the variation within the simulated data should reduce yet more, because genetic drift should have been much weaker than in the simulations performed by Voight et al. (2006). This would increase the proportion of inferred selection represented by the data. Likewise, the power to detect selection should increase for lower-frequency selected alleles -- because of the smaller chance that a long haplotype would increase by genetic drift alone. 

Next: Bottlenecks

