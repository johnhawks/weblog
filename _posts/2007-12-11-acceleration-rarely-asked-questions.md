---
layout: single 
title: "Acceleration rarely-asked questions" 
category: story
permalink: /weblog/topics/evolution/selection/acceleration/acceleration_rarely_asked_questions_2007.html
tags: [natural selection, Neandertals, acceleration] 
comments: false 
author: John Hawks 
---


<p>
Usually an FAQ starts with the easiest-to-answer questions. Those are, after all, the ones that are asked frequently!
</p>

<p>
But today I wanted to handle some of the hardest-to-answer questions: questions about the paper coming from people who are extremely knowledgeable about selection in the genome. We are working on three years of papers describing local and genome-wide scans of positive selection. At this point, the "best" methods each have weaknesses, and our method (the LDD, or "linkage disequilibrium decay" test) is no exception. People who know the weaknesses should be wondering, how have we taken them into account? 
</p>

<p>
In a tight six-page limit, it is impossible to answer every valid question. We accentuated the most obvious ones, but we considered a wide array of others (and dealt with many during peer review). Still, it would be good to have a resource where these issues are hashed out for anyone to read them. 
</p>

<p>
To that end, I've compiled a list of "rarely asked questions": what I see as some of the most critical problems with a study of recent selection like ours, and how we've addressed these in a way that makes our study conservative. 
</p>

<p>
I will be adding to this list as I come across new critiques. And for those who aren't quite conversant with genomic techniques, I will be putting up a <i>frequently</i> asked question list tomorrow!
</p>

<!-- more -->

<h4>Methods to detect recent selection all have biases of one kind or another. How can we be sure that one or more of these biases haven't really exaggerated the number of alleles in your dataset? </h4>

<p>
We are working with a tremendous advantage that previous studies of recent selection have lacked: <b>Mathematics.</b> Unquestionably, there are biases in the data, and as described below we have minimized these to the extent possible. But unlike every other study, we actually describe the theoretical reasons why selection should have accelerated in the human genome. 
</p>

<p>
Personally, I can't believe that nobody noticed how extreme these estimates of recent selection really are. I guess that folks doing genomics just weren't as primed in evolutionary theory to perceive how weird the human estimates looked compared to what is measured in the wild on other species, or even over the span of human evolution!
</p>

<p>
In the earliest studies, when people were finding that 3 or 4 percent of a sample of genes had signs of recent selection, those numbers were already extremely high. They got even higher, as more and more powerful methods of detecting selection came online. Our current estimate is the highest yet, but even this very high number is perfectly consistent with theoretical predictions coming from human population numbers. 
</p>

<p>
At one level, the mathematical answer is as simple as "more people means more mutations." But more deeply, we can predict a linear response of new selected alleles to population size, and we can model this response with respect to a particular frequency range. The genome is a complicated place -- with different mutations originating at different times, selected at different strengths, consequently with different fixation probabilities and different current frequencies. For some reason, nobody really tried to describe this mathematically before. 
</p>

<p>
Now, our model is extremely simple -- it can be challenged on several specific bases. For instance, population increase was not a simple exponential -- it grew in fits and starts, with some significant crashes. The average strength of selected mutations probably changed over time, and the distribution of the strength of selection may have departed from our assumptions. Even the adaptive mutation rate may have changed over time. 
</p>

<p>
Still, the general prediction is quite clear: the population has grown, its conditions of existence have changed, and as a result selection on new mutations should have accelerated. And the observed data fit our theoretical prediction exceptionally well. Certainly we could do better if we made a more detailed model, and we will be doing some of that in future papers. But mathematical simplicity has a great virtue: we can see precisely why human historical changes should have accelerated this aspect of our evolution, and we can see the magnitude of the response. That magnitude greatly outweighs all potential biases. 
</p>

<h4>I read on Gene Expression that the statistical power to detect selection varies based on allele age. You have the greatest power to detect things in the last 20,000 years. So it's no surprise that you find the most variants in that time period. How can you claim this is evidence of acceleration? </h4>

<p>
<a href="http://www.gnxp.com/blog/2007/12/notes-on-evidence-for-acceleration.php">P-ter's post on this problem</a> is well-detailed. This is quite an obvious issue -- if we are trying to detect alleles between 20 and 80 percent frequency, it is clear that we are going to be detecting recent things -- many old things would already have been fixed. 
</p>

<p>
But we won't detect just <i>any</i> recent things -- in fact, we will not be able to detect recent things that are <i>weakly selected</i>. By contrast, we should detect <i>older</i> things that are weakly selected, but we will never detect older things that were <i>strongly</i> selected -- they're the ones that are fixed now. 
</p>

<p>
We find a peak in the number of selected variants around 5500 years ago in Europeans, around 8000 years ago in Africans. That corresponds to a strength of selection around 3 percent or more. We find relatively fewer variants -- in fact, many times fewer, with a strength of selection of 1 percent or less. 
</p>

<p>
In theory, strongly selected mutations <i>ought</i> to be vanishingly rare. In fact, they ought to be <i>exponentially</i> rarer than weakly selected mutations. That doesn't mean the theory has to be right, but it does mean we need some kind of explanation if we find that <i>weakly</i> selected things are rare, and <i>strongly</i> selected ones are common -- I mean, R. A. Fisher was wrong sometimes, but I'm not going out on a limb on this one. 
</p>

<p>
Acceleration can explain this reversal -- there simply weren't as many weakly selected mutations 15,000 years ago, because there weren't as many people. The more strongly selected mutations in the last 8000 years actually were very rare <i>per individual</i>, but there were many, many more people to generate them. 
</p>

<p>
But maybe ascertainment bias for recent alleles might explain this reversal of theoretical expectations? 
</p>

<p>
Here's the problem: Suppose we are missing lots of selected alleles older than 10,000 years ago. That means there has been <i>even more selection than we now think in the last 40,000 years.</i>
</p>

<p>
We were very careful in the paper not to tie the test of acceleration to the age distribution of selection. The age distribution fits the acceleration theory beautifully, but this fit is not enough -- if we are willing to believe that selection was always intensely powerful and rapid in humans, then finding that it has <i>recently</i> powerful and rapid would be no surprise!
</p>

<p>
For this reason, we tested the theory of a <i>constant</i> rate of selection against <i>other kinds of data</i> -- data that <i>aren't</i> drawn from the LDD test. We showed that a constant rate makes many false predictions -- it predicts a tenfold lower heterozygosity than we see genome-wide, it predicts a very powerful association of heterozygosity with recombination rate, it predicts an extremely large number of recently fixed alleles, and it predicts 6 million adaptive substitutions between humans and chimpanzees. None of these predictions are close to reality. The rate couldn't always have been as high as it is now. 
</p>

<p>
Now, suppose we missed a large fraction of old events with the LDD test. That means that the total <i>number</i> of recent events would be much <i>larger</i> than we have estimated. Which means that the recent rate of selection would have been much <i>higher</i>. Which means that a constant rate at that much higher level is even further from reality. 
</p>

<h4>The LDD test is better at detecting selection in areas with low recombination rates. Isn't this is an obvious bias on the analysis? </h4>

<p>
Possibly. But it is a conservative bias. Consider: if we have a higher power in some regions of the genome, then we are actually <i>missing</i> events in others. That makes our assessments into <i>underestimates</i> of recent selection. 
</p>

<p>
We have made this even more conservative by simply eliminating areas of the genome with very low recombination rates. We didn't include such areas at all, even though other studies have found selected variants in them. 
</p>

<p>
But more important, the denser dataset has allowed us greater power in finding selection in areas of higher recombination. This has resulted in a broad addition of new variants to our list of selected alleles, particularly in the Yoruba sample were background LD is lower than the European or Asian samples. 
</p>

<p>
One recent review (Nielsen et al. 2007) showed that a high proportion of alleles found by the LDD test were in areas of low recombination. But this comparison is very misleading -- that review limited itself to selected alleles <i>shared</i> in all sampled populations -- a tiny subset of 90 genes out of the total 1800 listed by Wang et al. (2006). These are predominantly the oldest alleles -- for which the age-related ascertainment bias is the greatest, and the power is strongest in low recombination regions. 
</p>

<p>
Strikingly, we found that increasing the SNP density in the new HapMap made very little difference to the number of selected variants estimated for the CEU sample -- we believe this is because we are finding basically everything there for the method to find. This leaves significant limits -- for instance, the limited frequency window we used. But we don't think we are missing lots of selection in high-recombination regions. 
</p>

<h4>But wait a minute. What if you are finding more variants in areas of low recombination because they are false positives -- in other words, because you are finding alleles that actually <i>weren't</i> selected?</h4>

<p>
Ah, the opposite ascertainment bias. This is what we have worked the hardest to avoid -- false positives. We have deliberately excluded areas of the genome to avoid them, and we have used very conservative threshold values for our tests to minimize them. 
</p>

<p>
There are several strong reasons to believe that we are not looking at neutral alleles. Here's what we wrote in the paper: 
</p>

<blockquote>Recent genetic drift including founder effects would affect all genomic regions equally, but the candidate selected genes occur predominantly in genic regions, and preferentially include genes in functional classes that are plausible targets for recent adaptive changes. Selection is the only explanation consistent with all these features. </blockquote>

<p>
Almost certainly, we have some false positives. But they cannot be very common, or they would distort these clear alternative signs of selection. 
</p>

<p>
And more important, we are talking about a number of selected variants 100 times greater than we would expect under a constant rate. If we overestimated by a third (that would be a high error rate, which I think is very improbable), the rate has accelerated by 70 times. If we threw 90 percent of our list away, we would still be looking at an acceleration of 10 times faster! The numbers coming out of every other group looking at selection are within the ballpark of ours, so this is no surprise. 
</p>

<p>
In other words, our tests of acceleration do not depend very finely on the ascertainment of these alleles. I believe our assessments are correct and conservative -- if we made errors, they were by underestimating selection rather than overestimating it. 
</p>

<h4>But every distribution has a tail. If you use any kind of threshold, even a 99.5% threshold, you are going to have false positives, aren't you? And across the whole genome, doesn't that add up to a large number?</h4>

<p>
Our assessment counts the most extreme 0.5 percent of LD clusters as positively selected. Since the entire genome includes all the selected sites, this is conservative. Simulations showed that this value produced very few false positives. And we have a check against false positives -- if there were many neutral clusters in the data, they would not be associated in genic regions, sorted into certain functional categories, found across the entire range of frequencies, etc. 
</p>

<p>
Also, false positives are very likely to be placed in the oldest time range where LD decay has proceeded to the greatest extent. If false positives were very common, we would see an elevation in this time range, which we don't see. 
</p>

<h4>Why didn't you just used the phased data?</h4>

<p>
Well, the HapMap phased data are freely downloadable now and I've been working with them. The advantage of working with phased data is that we can look for lower-frequency variants. I'll be giving an example of that next week. 
</p>

<p>
But the phased data weren't available when we did the analysis. And the LDD test really is an elegant way of dealing with unphased genotypes. 
</p>

<h4>Don't we expect evolution to be faster on shorter time scales? The "acceleration" you are finding could just be the fact you are looking at a short window of time.</h4>

<p>
Geneticists may not have seen this question, but paleontologists will be intimately familiar with it. When we look at evolutionary changes over very long time scales, there is an averaging effect. Fluctuations over time tend to average out, so that the long-term change is relatively slight when measured <i>per year</i>. 
</p>

<p>
In contrast, when we look at evolutionary changes over a short time, any immediate fluctuation will tend to add to the rate of change. So measuring change <i>per year</i> yields a relatively high rate. 
</p>

<p>
It is quite obvious that a very high rate of change in phenotypes per generation cannot be maintained indefinitely. For instance, a reduction of 0.01 percent per generation shrinks a trait to only 1 percent of its initial size in only 40000 generations. Most organisms can't seamlessly shrink down to one percent of their size -- selection ultimately constrains their size. So even very low rates of change cannot be maintained over evolutionary time scales. 
</p>

<p>
From that perspective, we may view it is basically unsurprising that human skeletal features have been rapidly evolving over the last 10,000 years. Sure, this is a higher measured rate than ever before -- even over equivalent time spans like the Neandertal-modern transition in Europe. But it cannot be sustained indefinitely, and may just be an artifact of looking at a sharp fluctuation in a narrow window of time. 
</p>

<p>
I don't think that argument applies cleanly to the last 10,000 years. For one thing, the measured rate of skeletal change actually is surprisingly high, not only compared to longer timespans in the past, but also compared to equivalent timespans. But more to the point, the direction of change has been consistent across populations even as they grew in size. This is not some momentary fluctuation in our evolution, it is an exceptional transient from one state to another. 
</p>

<p>
But even more important, the distinction between short-term and long-term changes in phenotype are simply not relevant to allele frequencies. Positive selection is <i>always</i> relatively rapid on a geological time scale. Some alleles can reverse themselves over long periods of time -- increasing and then later decreasing in frequency, or even holding themselves in long-term stasis. But when we count an exceptionally large number of recent alleles, we are not looking at a normal situation. Most fluctuations do not involve complete reversal -- it is unlikely for a fixed substitution to subsequently be erased completely from our species. So comparing short and long-term changes to gene sequences is comparing like with like to a much greater extent than is true of phenotypes. 
</p>

<h4>How can you say anything at all about the rate of <i>adaptive</i> mutations? Everybody knows that adaptive mutations (choose one) occur rarely if ever...happen almost as common as deleterious ones...depend on the environment, which was constantly changing!</h4>

<p>
Believe it or not, we actually had a reviewer tell us that positive selection "rarely if ever" happens. <i>Rarely if ever!</i> This was a <i>geneticist!</i>
</p>

<p>
I think it must have been a slip of the keyboard. In any event, the intrinsic rate of new adaptive mutations <i>per genome</i> (as opposed to <i>per population</i>) is incredibly important in determining how fast selection should have happened in recent populations. 
</p>

<p>
The beauty is that we don't have to know what this rate is. We don't have to make any assumption about this rate. In fact, we have structured our analysis so that this unknown rate is what we <i>estimate</i> using the data from the LDD test. 
</p>

<p>
The incredible strength of our analysis is that we can assess the predictions based on this rate against <i>other</i> sources of data. That is, the LDD test generates a hypothesis about the rate of recent change, and we can show that observed rate is absolutely impossible as a <i>long-term</i> rate of change. Hence, evolution accelerated.  
</p>

<p>
The obvious weakness is that for simplicity we assume the rate is constant, but it almost certainly changed over time. However, we have structured the analysis to be conservative with respect to the most probable kinds of changes.
</p>

<p>
For example, what I think is most likely by far is that the intrinsic rate of new adaptive mutations per genome increased greatly during the last 20,000 years, because new environments created new selection pressures. People lived with greater and greater mismatches to their environments, and as Fisher (1930) showed, this means that adaptive mutations should have become more and more likely. 
</p>

<p>
But naturally, if adaptive mutations became more and more likely <i>per genome</i>, that must cause an acceleration of the rate of adaptive mutations <i>per population</i>. So this category of change leads to acceleration. This is precisely what I think happened. 
</p>

<p>
Less likely is that the environmental changes made adaptive mutations <i>less</i> likely per genome. But even in this case, our analysis must be conservative. If such mutations are intrinsically less likely, but we are still seeing a very large number of them, then our data still show acceleration. In fact, the conclusion would be that population number must have been even more important to acceleration than we thought, because on a <i>per population</i> basis it outweighed an intrinsic reduction in the rate of new adaptive mutations <i>per genome</i>.  Again, I think this is unlikely for the time period we are talking about. It might be closer to the actual pattern over the past 100 years or so, when mortality selection really has decreased in many populations. 
</p>

<h4>What about the Haldane limit? I thought such rapid evolution was impossible!</h4>

<p>
J. B. S. Haldane famously estimated that the substitution cost of new alleles in humans limited the rate of adaptive evolution. In his estimate, the slow rate of human reproduction limited substitutions to one every 300 generations. This became known as the "Haldane limit". 
</p>

<p>
Motoo Kimura used Haldane's argument as a reason why selection could not explain the substitution rate, and he asserted that as support for his neutral theory of molecular evolution. We do not challenge neutralism, but it is clear that Haldane's limit is a problem, since every estimate says that humans have been evolving at many times that rate. 
</p>

<p>
Maynard Smith (1968, Nature) showed that Haldane's argument depended on the unrealistic assumption of independence among all selected loci, so that the substitution load depends critically on the fitness of the optimal genotype among all selected loci. If selection on many loci is non-independent, then a very large number of genes may be selected with the same substitution load as a single gene under Haldane's assumptions. Later, Ewens (e.g., 1972, Am Naturalist) made a similar argument. Ewens (2004, Mathematical Population Genetics) reviewed this problem, pointing out an additional weakness of Haldane's argument: it depends solely on mortality selection, while many genes may be under fertility selection. 
</p>

<p>
These considerations show that Haldane's limit does not constrain the adaptive substitution rate in humans to 1/300 generations, and our estimated rate of 13 per generation is not excluded. Moreover, considering the high infant and juvenile mortality evidenced in Neolithic and later populations, much of that death rate resulting directly from disease and dietary deficiencies, the number of selective deaths available to drive substitutions has clearly been high. 
</p>

<p>
No time tonight to add references, I will put these in an update tomorrow. 
</p>


