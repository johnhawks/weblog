---
layout: single 
title: "Data warehousing in genomics interview" 
category: story
permalink: /weblog/reviews/genomics/bioinformatics/data-warehousing-dooling-interview-2009.html
tags: [data access, information, genomics, sequencing] 
comments: false 
author: John Hawks 
---


Software publisher O'Reilly is running an interview with David Dooling, data chief of the Genome Sequencing Center at Washington University: <a href="http://radar.oreilly.com/2009/07/sequencing-a-genome-a-week.html">"Sequencing a genome a week"</a>. If you want a little background on the current challenges in genomics, the history of genome sequencing technologies, and the infrastructure that allows modern bioinformatics, it's a really nice interview. Dooling is a speaker at the upcoming Open Source Convention (OSCON). 

A sample: 

<blockquote>James Turner: It sounds like there are a lot of informatics challenges with genomic data. There's the computational challenge of doing the sequence, which you mentioned. There's a challenge of managing the resulting data and finding meaning in it. And then there's the challenge of applying that understanding to a larger population. First of all, did I miss any of the challenges? And second of all, what are the unique problems in each set of those?</blockquote>

<blockquote>David Dooling: Well, let me talk a little bit about each of the ones you did mention, and maybe that'll bring up some that you didn't. So as far as just analyzing the data and generating the data, that is computationally intensive because essentially what you're getting off of these new instruments is pictures, images. And you need to apply algorithms to detect features in those images and then translate those features accounting for different vagaries of chemistry, and then resulting in a sequence, a series of basic Gs, As, Cs and Ts, the building blocks of DNA. Once you have that information, there's a whole host of secondary analysis, or analysis of biological relevance if you want to think of it that way, that need to happen, and those are project-specific. So for some sorts of projects, for example a cancer project, you would want to find all of the ways that the DNA that you sequenced differs from the reference and then take -- for the tumor, let's say. And then for the normal, do the same thing. And then for all of those variants, find out which ones are unique to the tumor genome as compared to the normal genome.</blockquote>

It's not an interview about biology; it's about technology and how people are working to enable us to test more and more detailed biological questions. 

