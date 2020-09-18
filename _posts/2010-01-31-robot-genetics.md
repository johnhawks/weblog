---
layout: single 
title: "Robot genetics" 
category: story
permalink: /weblog/reviews/behavior/cooperation/robot-evolution-2010.html
tags: [robots, learning, cooperation] 
comments: false 
author: John Hawks 
---


Dario Floreano and Laurent Keller describe experiments that combine genetic algorithms and robots. It's a review essay rather than a description of new research, but unlike most descriptions of "evolutionary robotics", it's actually directed toward biologists instead of AI researchers. 

<blockquote>In this essay we will examine key experiments that illustrate how, for example, robots whose genes are translated into simple neural networks can evolve the ability to navigate, escape predators, coadapt brains and body morphologies, and cooperate. We present mostlybut not onlyexperimental results performed in our laboratory, which satisfy the following criteria. First, the experiments were at least partly carried out with real robots, allowing us to present a video showing the behaviours of the evolved robots. Second, the robot's neural networks had a simple architecture with no synaptic plasticity, no ontogenetic development, and no detailed modelling of ion channels and spike transmission. Third, the genomes were directly mapped into the neural network (i.e., no gene-to-gene interaction, time-dependent dynamics, or ontogenetic plasticity). By limiting our analysis to these studies we are able to highlight the strength of the process of Darwinian selection in comparable simple systems exposed to different environmental conditions. </blockquote>

Some of the simplest machine learning experiments are basically like those used in behavioral psychology -- put the robots in a maze, make them remember where the food is, that sort of thing. Robots are simpler than rats, so the researchers can reverse-engineer the "evolved" software at the end of a series of experiments to see what worked and why: 

<blockquote>Interestingly, the driving speed of the best-evolved robots was approximately half of the maximum possible speed and did not increase even when the evolutionary experiments were continued for another 100 generations. Additional experiments where the speed was artificially increased revealed that fast-moving robots had high rates of collisions because the 300-ms refresh rate of the sensors did not allow them to detect walls sufficiently in advance at high speed. Thus, the robots evolved to move at intermediate speeds because of their limited neural and sensory abilities.</blockquote>

Figuring out that particular optimization would drive a team of human programmers crazy. Can you imagine? "Why do they keep running into that wall?!" 

On the other hand, dumb selection took a lot of generations to get to that point. You can't say selection was more efficient. If you had a crew of programming grunts and forced them to sit in a room for 100 robot generations, they'd come up with something. 

It's quite possible that a human would have come up with much better software, by pushing the robots past the limits of mutations on their "genomes". Selection has its own "sensor limitations", it can get stuck in a local optimum, and depends on the mutation structure to explore the landscape. 

It helps if the landscape has some strong correlation structure. That's what came to my mind as I read their account of experiments to make robots cooperate: 

<blockquote>However, when the arena contained both large and small tokens, the behaviour of robots was influenced by the group kin structure. In groups of unrelated robots (i.e., robots whose genomes where not more similar within than between groups), robots invariably specialised in pushing the small objects, which was the most efficient strategy to maximise their own individual fitness them (i.e., large tokens provided an equal direct payoff as a small token but were more difficult to successfully push). By contrast, the presence of related robots within groups allowed the evolution of altruism. When groups were formed of clonal robots all having the same genome, individuals primarily pushed the large tokens even though it was costly, in terms of individual fitness, for the robots pushing (Video S6).</blockquote>

If you wonder how robots have "kin", it's that they share similar (or the same) genomes. The simplicity of the behaviors suggests a functional explanation for kin selection -- for many kinds of tasks, it may simply be easier to cooperate with other individuals who "work" the same way. Different approaches to the same task may clash. 

They describe a similar result for cooperation by information sharing: 

<blockquote>Similar results were obtained in experiments where groups of light-emitting, foraging robots could communicate the position of a food source at a cost to themselves because of the resulting increased competition near food. In these experiments, robots again readily evolved costly communication when they were genetically related, but altruistic communication never evolved in groups of unrelated robots when selection operated at the individual level [38],[39].</blockquote>

The next logical step for this kind of research is nano-scale: evolutionary robotics on molecular machines. Which is scary. I hope they have the sense not to train them up by eating biological systems...

There's this old course on the books here, "Human aspects of robotics". I suppose it was taught back in the 80's when robots looked like they would replace all the manufacturing workers. I've often thought that someday it may be revived as with robots as the heroes instead of the villains. 

<h4>References:</h4>

<p class="cite">Floreano D, Keller L. 2010. Evolution of adaptive behavior in robots by means of Darwinian selection. PLoS Biol 8:e1000292. <a href="http://dx.doi.org/10.1371/journal.pbio.1000292">doi:10.1371/journal.pbio.1000292</a></p>




