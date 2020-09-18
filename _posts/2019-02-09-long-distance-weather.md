---
layout: single
title: "Long-distance weather 'teleconnections'"
description: "A study of weather records finds that some patterns in different parts of the world are correlated."
category: story
permalink: /weblog/reviews/climate/long-distance-weather-teleconnections-2019.html
tags: [climate]
image:
  feature: banner-1500-new-mexico-rainfall-john-fowler-397527-unsplash.jpg
  credit: John Fowler on Unsplash
  creditlink: https://unsplash.com/photos/qQIb6343A8U
comments: false
author: John Hawks
---

Last week <em>Nature</em> released an intriguing paper that demonstrates super-long-distance correlations in rainfall patterns, showing how the South Asian monsoon is synchronized with East Asia, Africa, and even events in North America. The paper, by Niklas Boers and coworkers, is titled, <a href="https://doi-org.ezproxy.library.wisc.edu/10.1038/s41586-018-0872-x">"Complex networks reveal global pattern of extreme-rainfall teleconnections"</a>.

According to the statistics provided with the paper, it has one of the longest submission-to-acceptance times I've ever seen. It was received August 7, 2016, and finally accepted December 4, 2018.

The basic idea is that weather patterns are correlated over short distances, but become less and less correlated as distance increases. Over distances less than 2500 km, the loss of correlation is approximately linear with distance, but over longer distances the loss of correlation is faster than linear---a power law with exponent greater than one. But against this pattern of rapid loss of correlation at long distances, some events stand out as being much more correlated than expected. These types of correlations are identified in the paper as "teleconnections".

Finding such teleconnections is a big data problem, where the datasets involve weather observations in a dense worldwide matrix. As geneticists would recognize, this gives rise to a problem of multiple comparisons. The paper includes a fun discussion of the multiple comparisons problem as applied to weather network data:

<blockquote>Before proceeding, however, a statistical problem needs to be solved, which arises in all data-driven interdependency analyses, and in particular in networks that are constructed on the basis of statistical similarities. Such approaches are generally biased because of multiple comparisons. In this case, we compare each timeseries with 575,999 other timeseries, which amounts to more than 10<sup>11</sup> comparisons in total. Therefore, the network will contain links that—despite corresponding to statistically significant pairwise synchronization values—are present only because of random coincidences, and not because of physical mechanisms.</blockquote>

The method used to address this problem in the paper is to reduce the problem to "bundles" of spatial links, thereby identifying channels of long-distance interaction above the noise of incidental similarities. This method lies behind the identification of long-distance couplings:

<blockquote>After applying our correction technique, a concise teleconnection pattern associated with the northern part of the South Asian monsoon is revealed: in addition to regional links covering most of the Indian subcontinent, we observe pronounced link bundles connecting SCA with eastern Asia, the African tropics, large parts of Europe and the eastern coast of North America, as well as the Southern Hemisphere extratropics. The break between regional and teleconnection scales (Fig. 2) is not affected by this correction (Extended Data Fig. 2).</blockquote>

By examining the time lags separating these correlated patterns in different parts of the world, the authors conclude that Rossby waves are the most important mechanism driving long-distance weather correlations. I didn't know anything about Rossby waves before reading this paper, and they seem like an interesting phenomenon.

One implication of such long-distance correlations is that what seem like "clusters" of extreme events may actually be a single event with long distance results. That has importance for studying the frequency of extreme weather events of all kinds, which have been suggested as a consequence of a warming climate.

<blockquote>We hope that our results will inspire further work on the predictability of EREs arising from these large-scale teleconnection patterns and on their representation in weather and climate models. Many studies have recently raised the concern that the characteristics of extreme events will change under ongoing climate change. A particular challenge in this regard is the discrimination between natural variability and anthropogenic influences6,7. With the increasing temporal lengths of global, high-resolution rainfall datasets, investigating changes of the global rainfall teleconnection structure along the lines of this study should become possible in the near future.</blockquote>

It is possible that the long-distance correlations are actually present within current climate models, and themselves give rise to the increase in extreme weather events in models. Or the Rossby wave-driven correlations might be a mechanism not yet replicated in climate models.

