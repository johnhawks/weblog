---
layout: single 
title: "Heritability and stature" 
description: "Heritability is the proportion of variance in a phenotype explained by additive genetic variance." 
category: explainer
permalink: /explainer/stats/heritability-and-stature
tags: [Anthropology 105, heritability, explainer, heritability, stature, stature, variance] 
comments: false 
author: John Hawks 
---


Tall parents tend to have tall children. 

That's a simple generalization, not an absolute statement. You may be a short person with two tall parents. If you know many families, you'll probably know someone who is an exception to the rule. Two short parents may have a very tall daughter, and two siblings may be very different heights. 

Still, if we look at many families we will find that the stature of the parents lets us make some fair predictions about the statures of their children. We can look at data to quantify just how parent and offspring heights are related. 

For example, here is a plot of the statures of students in my Anthropology 105 class in 2010, compared to the mean of their mothers' and fathers' statures. The average of mother and father's heights are the <strong>midparent</strong> stature. 

<div class="middle-picture">
<img src="/graphics/stature-plot-male-female-midparent-no-regression.png" />
</div>


Young men in this class have a taller average stature than young women. The picture separates men and women, and both taller sons and daughters tend to come from taller parents.

We can do a bit better than this to quantify the relationship of the parents' and sons' and daughters' statures: We can put lines on the graph to show how the sons' and daughters' heights tend to increase with the midparent stature: 

<div class="middle-picture">
<img src="/graphics/stature-plot-male-female-midparent-regression.png" />
</div>

Each of these lines is called a <strong>linear regression</strong> between midparent stature and offspring stature. The linear regression is the line that has the smallest squared distance from all of the points, added together. 

The squared distance is special. In statistics, the average squared distance from all points to the mean is called the <strong>variance</strong>. When we consider a trait like stature, there are many possible biological causes that can contribute to individuals being taller or shorter than the average. In statistical terms, these causes are all <strong>factors that contribute to the variance</strong> of stature. 

In the chart above, the linear regression represents the amount of the variance of the stature of the offspring that was contributed by the variance of their midparent statures. Parent statures can predict offspring statures and the linear regression is the prediction. 

It's not a perfect prediction. Take a look at the midparent value of 160 cm. When the midparent average is 160 cm, the regressions predict that daughters will be 156 cm and sons will be 168 cm. Out of Anthropology 105 students last year, two men had parents with an average of 160 cm, and both of them were very close to 168 cm in height &mdash; a good prediction! But the two women with parents this stature have very different heights. One is only 148 cm, the other 162, both more than 2 inches from the predicted value, in different directions. The regression gives the best prediction we can make from the parents, but there is obviously a lot of variation that can't be predicted in that way.  

Let's look more closely at the female students. The following chart adds together females from several years of Anthropology 105, with their midparent statures. 


<div class="middle-picture">
<img src="/graphics/stature-plot-female-midparent-many-years-regression.png" />
</div>

The slope of the regression across these 300 women is 0.72. That means that roughly 72 percent of the variance of the students' stature can be attributed to variance in their midparent stature. 

This regression is special in genetics. Daughters resemble their parents because they inherit genes from them. The regression between the midparent and daughters' statures gives us a way to estimate the effects of those genes. In fact, the <strong>proportion</strong> of variance in a trait that can be explained by genes is the same as the slope of the regression. Geneticists call this proportion the <strong>heritability</strong> of stature. In my Anthropology 105 classes over the last few years, we would estimate the heritability of stature as 0.72, or 72%. 

Again, there are exceptions. Sometimes parents give <em>other</em> things to their children besides genes. The right foods, the right resources can make a difference to growth and development. And some genes can have unexpected effects. Most obviously, some genes make sons a lot taller than daughters, which is why we've considered the two sexes separately. 

The heritability of a trait is a powerful concept. It's important to understand some of its strengths and limits: 

<ol>
<li>Heritability refers to a population. A female in my Anthropology 105 class may be taller or shorter than her parents. We can't predict 72% of that student's stature; instead, 72% of the variance in the students can be explained by the variance among their parents. </li>
<li>Traits with higher heritability have a lower influence from the environment. Traits that are highly influenced by the environment have a lower heritability. </li>
<li>The response of a population to selection on a trait is determined by the heritability. </li>
<li>Geneticists can look at other relatives besides parents to estimate heritability. Some of the strongest estimates come from comparing identical twins (who have the same genes) to fraternal twins (who share on average half their genes). </li>
<li>Estimating heritability doesn't require us to know anything about the actual genes themselves.</li>

</ol>

The last point is very important. <strong>We can quantify the influence of genes without knowing anything about which genes even affect a trait</strong>. Francis Galton invented the parent-offspring method of estimating heritability, more than twenty years before the word "gene" was coined. Remembering this helps to remind us that the concept of heritability is limited. It is not a guide to how genes work, it is a simple scale of which traits have a stronger or weaker genetic influence. 

Because it is a proportion, heritability varies only between zero and one. A trait with zero heritability is one for which none of the variance can be explained by the parents' variance. 

Heritability may be very low because the individuals in the population have little genetic variability. For example, an orchard of apple trees may consist of genetically identical individuals that are clones of a single parent tree. The apples (hopefully) all taste the same. But the trees may be very different in height, branch form, and the number of apples. These traits may be strongly influenced both by the environments of individual trees and by chance. By contrast, wild populations of oak trees are not made up of clones. The heights of individual trees are still strongly influenced by environments, but they may also be influenced by differences in genes. 



