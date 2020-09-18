---
layout: single 
title: "The problems of computer-aided biologists, 1" 
category: story
permalink: /weblog/topics/metascience/timmer-biology-computer-replication-2010.html
tags: [bioinformatics, models, metascience, modeling, computing] 
comments: false 
author: John Hawks 
---


On the subject of <a href="http://johnhawks.net/weblog/topics/metascience/models/archaeology-mature-discipline-genetics-2010.html">modeling in genetics</a>, John Timmer of <i>Ars Technica</i> has been running an excellent series on the challenges of computer models in biology. I'll devote a few words to some of these articles in the next several days. 

An article from earlier this winter, <a href="http://arstechnica.com/science/news/2010/01/keeping-computers-from-ending-sciences-reproducibility.ars">"Keeping computers from ending science's reproducibility,"</a> discusses the problems with replicability. Data from genomes and genotyping platforms go through frequent revisions, so that the same methods may lead to different results depending on the version of the dataset. Not replicable, in other words, and it may be very hard to track down exactly <i>why</i> slight differences in results persist. It's also hard to verify that the methods are working the same way when the same results <i>aren't</i> found -- it's not like the problem of significant digits in measurement, in other words. 

That problem is compounded when it comes to analytical methods: 

<blockquote>An analysis pipeline may involve dozens of specialized software tools chained together in series, each with a number of parameters that need to be documented for their output to be reproduced. Like the data, some of these tools are proprietary, and many of them undergo frequent revisions that add new features, change algorithms, and so on. Some of them may be developed in-house, where commenting and version control often take a back seat to simply getting software that works. Finally, even the best commercial software has bugs.</blockquote>

"Getting it to work" is too often the major goal in human genetics, where in-house development of population history models is the norm. Rigorous validation of these models is beyond any single lab's purview; to be published, it is enough to cite prior art. 

The end of the article includes some reporting on possible solutions, including this: 


<blockquote>Even if we solve the legal and computational portions of the problem, however, we're going to run into issues with the fact that many of the people who use computational tools understand what they do, but don't feel compelled to learn the math behind them. That's where a paper in the latest edition of Science comes in. Its author, Jill Mesirov of the Broad Institute, describes how many biologists aren't well versed in computational analysis, but are increasingly reliant on tools created by those who are; she then goes on to describe one type of solution, called GenePattern, that she and her colleagues put together with the help of Microsoft Research.</blockquote>

The idea is to "embed" the actual bioinformatic research methods into the paper, as one would embed a spreadsheet into a Word document. That way, anyone who reads the paper could just run an active version of the methods, to verify the results were accurate, and (potentially) play with the parameters. 

Not a bad idea for the toy example, but for simulations that take days or more to run, it isn't going to be practical. What we need is people to learn the math, not people to dumbly click buttons in a paper. 

The specific idea of an interactive workflow is implemented fairly well in the <a href="http://usegalaxy.org">Galaxy bioinformatics platform</a>. There are definite strengths to that approach -- most importantly, for simple operations it can be incredibly useful to have a running record of what you've done, so that you can get it again yourself. But an equivalent record can fairly easily be accomplished using Python, Perl or any other scripting language. A risk of an online system is that it runs into the versioning problem very quickly -- interactive downloads may bring inconsistent datasets that use different genome draft assemblies, for example. 

In any event, much pain can be circumvented with a little math, in many cases. We should make it a priority to get students a common-sense understanding of how genetic parameters relate to each other. 

UPDATE (2010-03-18): Another section of the article is worth discussion. Along the lines of my post from earlier this year regarding the importance of code sharing and transparency (<a href="http://johnhawks.net/weblog/topics/meta/ince-software-assurance-open-access-2010.html">"The bugs will out"</a>), Timmer wrote: 

<blockquote>"You need the code to see what was done," [Victoria Stodden]  told Ars. "The myriad computational steps taken to achieve the results are essentially unguessableparameter settings, function invocation sequencesso the standard for revealing it needs to be raised to that of when the science was, say, lab-based experiment." This sort of openness is also in keeping with the scientific standards for sharing of more traditional materials and results. "It adheres to the scientific norm of transparency but also to the core practice of building on each other's work in scientific research," she said. But the same worries that apply to more traditional data sharingresearchers may have a competitor use that data to publish firstalso apply here. In the slides from her talk, she notes that a survey she conducted of computational scientists indicates that many are concerned about attribution and the potential loss of publications in addition to legal issues. (The biggest worry is the effort involved to clean up and document existing code.)</blockquote>

A lot of the code we use is really rather simple. The coalescent can be implemented in a few lines, and most common alterations of it can be handled with 10-line subroutines. A forward-time simulation can be done in a single line of Python, and again the common alterations don't take too much to implement. 

There are rather radically more complicated models in use, and we should direct more attention to making these human-readable, separating modular elements apart so that they can be run with different simulation engines, and making clear distinctions between functional code, parameters, and data. I've been doing this long enough to know how simple it can be to hard-wire your parameters into the code, undocumented, so that nobody can figure out what is going on but the author. That's not where you want to be. 


