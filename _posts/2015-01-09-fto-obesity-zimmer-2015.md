---
layout: single
title: "Looking more deeply at a study of obesity and genetic risk"
category: story
permalink: /weblog/topics/health/fto-obesity-changing-effect-zimmer-2015.html
description: "A comparison of people in the Framingham study shows that FTO had a different effect in early Baby Boomers, but I question the comparison"
tags: [diet, metabolic syndrome, obesity, genetics, health]
modified: 2015-01-12
author: John Hawks
---

Late in December, Carl Zimmer described a research study showing that a famous gene that influences obesity in living Americans, called _FTO_, has actually increased in its effects during the last 70 years: <a href="http://www.nytimes.com/2015/01/01/science/gene-linked-to-obesity-hasnt-always-been-a-problem-study-finds.html">"Gene Linked to Obesity Hasn’t Always Been a Problem, Study Finds"</a>. 

<blockquote>In 2007, researchers discovered that people with a common variant of FTO tend to be heavier than those without it. Since then, studies have repeatedly confirmed the link. On average, one copy of the risky variant adds up to 3.5 extra pounds of weight. Two copies of the gene bring 7 extra pounds — and increase a person’s risk of becoming obese by 50 percent.</blockquote>

<blockquote>But the gene doesn’t seem to have always been a problem. If scientists had studied FTO just a few decades ago, they would have found no link to weight whatsoever. A new study shows that FTO became a risk only in people born after World War II.</blockquote>

In other words, the difference in environment between the pre-1940s and post-1940s United States must explain the different effects of _FTO_ on body mass index (BMI). Zimmer quotes researchers who speculate that _FTO_ affects obesity today because people are much less active than before World War 2, or that the high availability of fried and sugary food today may increase the effect of a gene that influences appetite. Either explanation or both, or maybe some others, may be the correct one. 

I thought this was a pretty interesting story about a very good example of gene-environment interaction that I might use in class. So I looked more closely at the research study, which was published in the early edition of _PNAS_ (Rosenquist et al. 2015). And then I had that terrible sinking feeling, like **GRRRRR Why can't this be as simple as advertised?** 

### The study is extremely limited in scope

James Niels Rosenquist and colleagues took individuals from the Framingham Offspring Cohort, which sampled the children of the original Framingham Heart Study individuals. These people were studied periodically, and later genotyped, and the data from all these measurements have been archived. Rosenquist and colleagues took all the BMI measurements between 1971 and 2005, and developed a set of models to account for BMI differences by _FTO_ genotype. The offspring were nearly all born between 1920 and 1950, with some outliers before 1920 and after 1950. So when they divide the sample between people born before or after 1942, we are really comparing two groups of very limited extent: 1920-1942 and (mostly) 1942-1950. 

From this point of view, I would immediately come to a different null hypothesis about finding a more substantial genetic effect in the later sample: **The later sample covers a much shorter time, and therefore potentially much less environmental heterogeneity, making the relative effect of genes stronger.** The paper notes that the results are quantitatively similar for any sectioning point between 1942 and 1945; suggesting that there really is a difference between later and earlier subsamples. But the span 1945-1950 is a very short one indeed, again this suggests that the last bit of this sample just had a very constrained variability relative to the earlier part. This last part of the sample excludes everyone who grew up in the Roaring Twenties and the Great Depression, and includes only early Baby Boomers. 

We can't conclude on this basis that the postwar environment was different from the prewar environment when it comes to _FTO_; at best we can conclude that the environmental variance in a shorter, limited time period was less. Whether the additive variance is different or the same in the two periods was not assessed in this paper. 

### We don't know the additive variance

The main results of the paper are reported in three figures, which show BMI as a reflection of age for each of the three possible genotypes for rs993609, AA, AT and TT. Of the two alleles, A is the "risk" allele, which is associated with higher BMI. The figure below shows the relation of average BMI and age for each of the genotypes, with pre-1942 and post-1942 cohorts plotted separately:

<figure>
<img src="/images/rosenquist-2015-fig-1-genotype-fto-bmi.png" alt="Figure 3 from Rosenquist and colleagues 2015, showing BMI versus birth year" />
<figcaption>Figure 1 from Rosenquist et al. 2015. Original caption: "BMI over the ages of 35–60 by birth cohort for AA, TT, and AT/TA genotypes by general birth cohort (born before or during/after 1942)."</figcaption>
</figure>

That's a complicated figure. The key comparison is between what happens with the solid lines and the dotted lines. The dotted blue and green lines essentially overlap, showing that the AT and TT genotypes have basically the same effect in the pre-1942 sample. By contrast, the solid blue and green lines are far apart, showing that the AT genotype leads to substantially higher BMI in the post-1942 sample. That's the major difference. The AA genotype seems to have a much more similar effect in both pre-1942 and post-1942 samples, but less in pre-1942 than in post-1942. 

I wish this were considered in a more standard quantitative genetic framework. Indeed, the words "heritability" or "additive" do not appear in the paper or supplement at all. I'd like to know the additive variance in BMI and the proportion of that explained by _FTO_ genotypes. All we know is that genotypes of a single nucleotide polymorphism (SNP) linked to _FTO_, designated as rs993609, explain some of the variation in BMI among individual, but we don't know how much. The A allele of rs993609 is associated with higher BMI, and it is not evident whether the effect of the allele is additive. Separating out males from females, the effect of AT genotype in males does not reach statistical significance among those born after 1942. The effect of heterozygote genotype is significant only for females. Males, on the other hand, have a significant cohort effect for the AA homozygote genotype, whereas the female sample does not have a significant outcome for this AA genotype. Lumping the two together increases the statistical significance, but that doesn't change the magnitude of the effect. 

I'd love to be able to generalize a bit more about the effects of different environments, but the study just doesn't give us enough to generalize. We need more observations in different environments.  It would be interesting to compare the effect of _FTO_ on BMI in relatives born at different times, and although the sample would be much smaller, this might still lead to a stronger conclusion about genetic versus environmental effects. 

So I'm disappointed that this didn't turn out to be a good teaching example. I had a whole post written about gene-by-environment interaction and the way it might affect natural selection, but it will have to wait.


### Reference

<p class="cite">Rosenquist JN <em>et al.</em> (2015) Cohort of birth modifies the association between FTO genotype and BMI. <em>Proceedings of the National Academy of Sciences, USA</em> (early online). <a href="http://dx.doi.org/10.1073/pnas.1411893111">doi:10.1073/pnas.1411893111</a></p>
