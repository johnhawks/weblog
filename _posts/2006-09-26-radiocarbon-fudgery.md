---
layout: single 
title: "Radiocarbon fudgery" 
category: story
permalink: /weblog/reviews/archaeology/upper/radiocarbon_calibration_mellars_2006.html
tags: [radiocarbon, Upper Paleolithic, archaeology, Neandertals, dating] 
comments: false 
author: John Hawks 
---

<p>
I skipped last week's (9/15/2006) <i>Science</i>, and so missed <a href="http://www.sciencemag.org/cgi/content/full/313/5793/1560">this article by Michael Balter</a> on radiocarbon dating. But some online discussion boards <a href="http://tech.groups.yahoo.com/group/Paleoanthro/message/13835">have been talking about it</a>, and this passage especially is worth reading:
</p>

<blockquote>Encouraged by their recent successes, radiocarbon researchers now have their eyes on the bigger prize of the 50,000-year limit. Indeed, when the IntCal group began work on the 2004 curve, it had high hopes of extending it back to this final barrier. Yet it was not to be. Although the marine data sets were reasonably consistent with each other up to 26,000 years ago, after that they began to scatter and diverge, in some cases by up to several millennia. Geochronologist Paula Reimer of Queen's University in Belfast, Northern Ireland, who coordinates the working group, says that the differences--among the raw data as well as among the researchers--were just too great: "We had four or five people, all of whom thought their records were right." So the group settled for publishing in Radiocarbon a comparison of the data sets earlier than 26,000 years, which they ironically called "NotCal"--meaning, Reimer and other members say, that it was not intended to be used as a calibration curve.</blockquote>

<blockquote>But archaeologist Paul Mellars of the University of Cambridge in the U.K. used the published data to essentially do just that. Mellars was eager to get the most accurate dates for possibly contemporaneous Neandertal and modern human sites in Europe. So he used the midpoint of the differing "NotCal" curves to approximately calibrate the radiocarbon ages of 19 hominid sites ranging from Israel in the East to Spain in the West. Using this best-guess method, Mellars found that modern humans had not only spread across Europe faster than previously thought, but that they had overlapped with Neandertals during a shorter interval: only about 6000 years rather than 10,000 years in Europe as a whole, and as little as 1000 years in some parts of the continent. Mellars concluded in the 23 February 2006 issue of Nature that Neandertals must have "succumbed much more rapidly to competition" from modern humans than many had assumed.</blockquote>

<blockquote>But Reimer and others say Mellars should not have used the NotCal data as he did. "It is dangerous to draw too fine conclusions using these data sets," says Reimer, because they have not been finalized and the divergences between them have yet to be reconciled. Other researchers have started asking van der Plicht whether they can use the "Mellars curve" for calibration. "This is a bad thing," says van der Plicht.</blockquote>

<blockquote>Mellars insists that archaeologists can't wait for a final calibration curve. "Are we all really expected to keep studies of modern human origins on hold for the next 5 years, until they decide they've finally got the calibration act together?" he asks. The working group, he argues, "has hijacked the term 'calibration' to mean an absolutely agreed, rubber stamped, legalistic, signed, sealed, and delivered curve." And even when the experts agree on a curve, Mellars says, it will not be "final and absolute" but "simply the best estimate from the data at the time."</blockquote>

<p>
Now, even something that isn't <i>officially approved</i> by geochronologists might still be correct. So the question is whether errors were introduced by Mellars into the chronology by using the "NotCal" not-calibrated calibration (and yes, the Mellars paper uses without noting the irony "the recent NotCal04 'best estimation' calibration curve"). 
</p>

<p>
The problems are noted in a communication to <i>Nature</i> last week (9/14/2006) by Chris Turney, Richard Roberts and Zenobia Jacobs:
</p>

<blockquote>Atmospheric <sup>14</sup>C variability has not followed a simple, smooth pattern, as suggested by Mellars. Instead, smoothing took place during the statistical analysis of these data sets to develop the NotCal04 mean best-fit line. By using the mid-point of the mean best-fit line, Mellars artificially improves the apparent precision of calibrated ages in his Fig. 3; even 'infinitely' old ages are reported with improved precision, whereas calibration almost invariably results in age ranges that are significantly larger than the radiocarbon measurement error.</blockquote>

<p>
It's a bad sign when your method improves the precision of infinite dates. In fact, you always add to the variance of a measurement when you multiply it by some correction that itself entails measurement error. 
</p>

<p>
But Mellars' central point was not principally about the ages of particular sites, but instead about the <i>total</i> time taken by modern humans to invade Europe. Can we still get an estimate of a <i>reduced</i> time period for this "invasion" if we use the calibrated dates <i>properly</i>? 
</p>

<p>
To answer that, we need to look at two graphs. First, the graph used by Mellars (2006) to support the idea that the total time taken by modern humans to occupy Europe was short: 
</p>

<div style="text-align:center;">
<img src="/graphics/mellars_2006_radiocarbon.png" /></div>

<p class="caption">Radiocarbon dates for sites from West Asia and Europe, Figure 3 of Mellars (2006). Sites numbered as in original text. </p>

<p>
You can see in this graph the effect of "calibration", at least according to Mellars -- it reduces the statistical error associated with each date. Indeed, the caption to this figure says: 
</p>

<blockquote>Owing to the slope of the calibration curves, the error bars ( 1 s.d.) on the calibrated dates are smaller than those on the uncalibrated dates.</blockquote>

<p>
A moment's reflection reveals this to be a nonsensical statement. The error bars may be attributable either to measurement error (in the proportion of <sup>14</sup>C) or to calibration error (relating the current proportion to the original atmospheric proportion). But these error estimates are applied to dates in "radiocarbon years" -- meaning that they <i>don't include</i> possible error in the original atmospheric proportion. Indeed, if they <i>did</i> include this error, these error bars would have to <i>stretch to cover the NotCal-produced dates!</i>

<p>
But the "slope of the calibration curve" certainly can't reduce error due to measurement in the sample. At best, the current calibration can predict that a given date must represent a slightly larger number of half-lifes than the uncalibrated date, because the original atmospheric proportion of <sup>14</sup>C was higher than today. It can't reduce the standard error due to measurement, and therefore won't reduce the confidence interval on the date <i>as reported in radiocarbon years</i> (it certainly may reduce the <i>total</i> error, which is usually overlooked). 
</p>

<p>
To understand how Mellars came to this erroneous conclusion -- and to see how it affects his assertion regarding the time period of modern human dispersal -- we need to consider the NotCal04 calibration curve itself:
</p>

<div style="text-align:center;">
<img src="/graphics/c14_calibration_turney_2006.png" /></div>

<p class="caption">Radiocarbon calibration data, Figure 1 from Turney et al. (2006). I added the pink rectangular regions. The lower pink rectangles represent the low variance on dates drawn from the NotCal correlation region, as apparently Mellars did. The upper, wide, pink rectangles represent the error that might be assigned to the full calibration process, including uncertainties in the underlying calibration data. In other words, they encompass the range of calendar dates that might be attributed to different samples of a single radiocarbon date. This error range does not necessarily include measurement error (except insofar as error on calibration samples is distributed <i>just like</i> error on fossil samples.</p>

<p>
OK, you probably read the caption, so you get the gist of this picture and my pink rectangle additions. In short, the width of the NotCal calibration is very narrow, because it is a summary of many data sets. But the <i>dispersion</i> within those original data sets is very high. This means that for any given radiocarbon date, there is actually a very wide interval of possible calibrated dates that it might represent. The range of this dispersion is high partly because it includes dates from different regions and raw materials (here, mostly coral and shells) -- and <i>these are exactly the kinds of problems that create variance in archaeological radiocarbon dates</i>. So we should be looking at wide error bars -- much wider than we are used to doing. 
</p>

<p>
Making this source of error explicit certainly doesn't <i>decrease</i> the error bars of measurements -- it vastly increases the error bars. This is a good thing -- it is a more accurate understanding of the potential error in radiocarbon dates. 
</p>

<p>
But what can we conclude about the time interval represented by early modern humans (or more properly, of early Aurignacian sites, since it is far from demonstrated that they were left by modern humans) and their dispersal across Europe? 
</p>

<p>
Looking at the Mellars graph, his interpretation is apparent from his numbers. The leftmost European site on his graph is number 4, Bacho Kiro. It is estimated at more than 43,000 radiocarbon years; Mellars put it at more than 46,000 "calibrated" years. The youngest site (17, Roc de Combe) is 35,000 radiocarbon years; Mellars put it at 40,000 "calibrated" years. So the interval from oldest to youngest is 11,000 radiocarbon years, compared to only 6,000 "calibrated" years, according to Mellars:
</p>

<blockquote>[W]e can now see from the new calibrated chronology that this must be shortened to at most about 6,000 yr (at least in the more central and northern parts of Europe), with periods of overlap within the individual regions of Europe (such as western France) of perhaps only 1,000-2,000 yr. Evidently the native Neanderthal populations of Europe succumbed much more rapidly to competition from the expanding biologically and behaviourally modern populations than previous estimates have generally assumed.</blockquote>

<p>
But again, this is quite plainly wrong. First, it assumes the reduction in length of the error bars, which the calibration process shows must actually be greatly <i>increased</i> in length. And second, it ignores the visually apparent "kink" in the calibration curve over just the time range represented by the early Aurignacian. That "kink" means that true dates over a very wide time range will come out with the same radiocarbon date estimate. 
</p>

<p>
And remember that Neandertals persisted well after 40,000 years in the sequence, with a number of dates after 33,000 years ago now (and possibly as recent as 28,000). These dates are radiocarbon years, and calibrated dates might be older (and closer to the early Aurignacian "calibrated" dates). But they don't fit into the blitzkrieg model very readily. 
</p>

<p>
The real question is whether the radiocarbon data address the pattern of change in biology and archaeology -- a sudden shift might still be a piecewise or mosaic transition, and a long shift might nevertheless have discrete boundaries. I think there is sufficient evidence that the transition in Europe was mosaic in character. From there, the pace of change (and migration or gene flow) might be 6000 years or 20,000, it doesn't much matter from the perspective of pattern. On the other hand, folks interested in climatic forcing and other more time-centric scenarios might care very deeply about whether we are looking at a short or long timeframe. 
</p>

<p>
In any event, it is safe to conclude that the evidence for a rapid dispersal based on these data is pretty much all based on faulty statistics. 
</p>

<p>
By the way -- has anybody else noticed that the vast preponderance of totally wrong research lately has been in <i>Nature</i>? 
</p>

<h4>References:</h4>

<p class="cite">Mellars P. 2006. A new radiocarbon revolution and the dispersal of modern humans in Eurasia. Nature 439:931-935. <a href="http://dx.doi.org/10.1038/nature04521">DOI link</a></p>

<p class="cite">Turney CSM, Roberts RG, Jacobs Z. 2006. Archaeology: Progress and pitfalls in radiocarbon dating. Nature 443:E3. <a href="http://dx.doi.org/10.1038/nature05214">DOI link</a></p>




