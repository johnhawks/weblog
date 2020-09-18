---
layout: single 
title: "Will Wolfram make bioinformatics obsolete?" 
category: story
permalink: /weblog/reviews/genomics/bioinformatics/wolfram-alpha-bioinformatics-2009.html
tags: [biotech, Stephen Wolfram, information, computing] 
comments: false 
author: John Hawks 
---

I was talking with a scientist last week who is in charge of a massive dataset. He told me he had heard complaints from many of his biologist friends that today's students are trained to be computer scientists, not biologists. Why, he asked, would we want to do that when the amount of data we handle is so trivial? 

Now, you have to understand, to this person a dataset of 1000 whole genomes <i>is</i> trivial. He said, don't these students understand that in a few years all the software they wrote to handle these data will be obsolete? They certainly aren't solving interesting problems in computer science, and in a short time, they won't be <i>able</i> to solve interesting problems in biology. 

I said, well, yeah. I've been through this once already -- fifteen years ago, the hot thing was setting up a wet lab for sequencing -- or worse, RFLP. That sure looked like a lot of data at the time, and a lot of students spent a lot of time figuring out how to do it. Some of them successfully started careers, got grants, and moved on with the times. Others fell by the wayside. Meanwhile, clusters of people at the DOE, Whitehead Institute, Wellcome Trust and several private companies were spending <i>their</i> time figuring out faster and faster ways of automating sequencing. Now one machine can do the work of ten thousand 1990's graduate students. 

Anyway, I've was thinking about that conversation. And then I ran across <a href="http://www.twine.com/item/122mz8lz9-4c/wolfram-alpha-is-coming-and-it-could-be-as-important-as-google">an article by Nova Spivack, describing the new Wolfram Alpha</a>. 

<blockquote>Stephen Wolfram is building something new -- and it is really impressive and significant. In fact it may be as important for the Web (and the world) as Google, but for a different purpose. It's not a "Google killer" -- it does something different. It's an "answer engine" rather than a search engine.</blockquote>

<blockquote>...</blockquote>

<blockquote>Wolfram Alpha is a system for computing the answers to questions. To accomplish this it uses built-in models of fields of knowledge, complete with data and algorithms, that represent real-world knowledge.</blockquote>

<blockquote>For example, it contains formal models of much of what we know about science -- massive amounts of data about various physical laws and properties, as well as data about the physical world.</blockquote>

<blockquote>Based on this you can ask it scientific questions and it can compute the answers for you. Even if it has not been programmed explicity to answer each question you might ask it.</blockquote>

This sounds very pie-in-the-sky. And indeed, commenters on the article (as well as <a href="http://www.semanticuniverse.com/blogs-i-was-positively-impressed-wolfram-alpha.html">this article by Cycorp head Doug Lenat</a>) come up with lots of questions that would be impossible for such a system to answer. 

But I'm not really interested in the things that will stump the system. Compared to restaurant reviews and kinship systems, bioinformatics is pretty simple. Right now, there are two things that make it a multi-year effort to learn: mutually incompatible databases, and the various kludges necessary to model ascertainment bias. 

I'm a Mathematica user, and am familiar with its theorem-proving capabilities. Mathematica already has genome lookup utilities, which I use quite often -- it's just easier to do a lookup on my own system than to plow through two or three webpages to get to the query. It really wouldn't take that much to bring intelligent and interactive genome analysis into the system. 

Alpha could turn into an online robot armed with basic genetics knowledge. And if not Alpha -- genetics is a logical priority for Wolfram, but it may not be the first or primary one -- certainly some other system using similar technology will emerge. Put it to work on public databases of genetic information, and you have a system that can resolve the incompatibilities by adding semantic knowledge. A bit of effort on existing databases would allow the resolution of discrepancies in ascertainment. Or, more likely, another couple of years of whole-genome sequencing will solve most of ascertainment biases by drowning them in new data. 

So it's not a stretch for me to imagine a year from now entering this search query: 

<blockquote>"List all human genes with significant evidence of positive selection since the human-chimpanzee common ancestor, where either the GO category or OMIM entry includes 'muscle'"</blockquote>

It seems to me that bioinformatics is what generates the output to that query. What you do with the output of that query is evolutionary biology. 

So that raises the obvious question. Tomorrow's high-throughput plain-English bioinformatics tool will do the work of ten thousand 2009 graduate students.  If a freely-available (or heck, even a paid) service can do the bioinformatics, what should today's graduate students be learning? 

UPDATE (2009-03-19): 

Some folks have interesting reactions to this post, including <a href="http://www.mailund.dk/index.php/2009/03/19/automating-scientific-grunt-work/">Thomas Mailund</a> and <a href="http://scienceblogs.com/geneticfuture/2009/03/why_biology_students_should_be.php">Dan MacArthur</a>. They make good points. 

I will add that I'm not arguing against modeling or simulation in biology. There are lots of interesting things in evolutionary biology you can do -- must do, in all practical terms -- with computers. But I don't like the five-year degree program in genetics where only one semester is given to population genetics, and most of the student's time is spent learning scripting, doing data entry, and figuring out ten or twelve database formats. 

I come back to my first example -- fifteen years ago, people were telling you how essential and wonderful sequencing would always be. If you're pursuing a five-year degree program and two or three years of postdoc, I hope you're thinking about what skills you'll need fifteen years from now. 



