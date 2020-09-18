---
layout: single 
title: "Why are organisms modular?" 
category: story
permalink: /weblog/reviews/brain/culture/modular_evolution_circuits_kashtan_2005.html
tags: [brain, culture] 
comments: false 
author: John Hawks 
---


<p>
Modularity is a property of biological organization: organisms are composed of subunits that perform different functions. At the cellular level, the cell is composed of organelles that have different functions in protein assembly, metabolism, growth, and homeostasis. This organization is reflected at the level of DNA, which consists of sequences organized into functional subunits: coding regions, introns, promoter regions, multigene complexes, and ultimately chromosomes. It characterizes the anatomy of multicellular organisms, which are divided into organs such as hearts, lungs, ganglia, and eyes, or leaves, stems, flowers, and roots. 
</p>

<p>
And modularity underlies the organization of the brain. Mammalian brains are divided into different parts --- neocortex, cerebellum, thalamus, etc. These parts contribute differently to different functions, as do the subcomponents of each of the parts. The neocortex is comprised of tissues that contribute to different tasks, such as Broca's area for speech and the 
</p>

<p>
Brains do a lot of things that are analogous to computers, in terms of information processing. Indeed, the things that our brains are really good at are increasingly being done by computers, from adding and subtracting to face recognition. Our brains certainly have talents that are a challenge for computers, and vice versa. For one thing, our brains are well-motivated for the most part while computers have no motivation at all. But they are broadly similar in their ability to take in and manipulate information: a computer is more similar to our brains than, say, to our muscles. 
</p>

<p>
But today's computers are not modular in the same way our brains are modular. Computers have different components, that is true --- they have memory chips and disk drives and power supplies and one or more central processing units (CPUs). But the great strength of computers is that the same CPU can be programmed to perform any algorithmic task. That's the principle of the universal Turing machine: a certain kind of simple device can --- by providing different instructions --- perform any transformation on data that we could think of. Indeed, if we had the right software we could cause today's computers to act like humans; they would just be really, really, really slow. 
</p>

<p>
This provides a hint about why we would want the brain to be modular, rather than to provide different instructions to a single small but fast CPU. Differrent brain tissues can perform different functions at the same time, so that we can very quickly recognize someone's face, remember where we know her from, contort our faces to an pleasant expression of recognition, and say "Hello." Specializing each of these tasks into different tissues allows us to perform them much more quickly. 
</p>

<p>
But that doesn't answer the question of how mental modularity evolved in the first place. After all, at the time that face recognition became important in primate evolution, our primate ancestors weren't doing all the things that we do now. Why couldn't they have simply evolved a single system that added new capabilities as it went along? This kind of mega-system would seem to be the natural consequence of evolution: tinkering slightly with a pre-existing function ought to be much easier than adding whole new modules from scratch. 
</p>

<p>
Now, I should point out that we really don't have a lot of detail about how fine-grained the modularity of the brain actually is. It might very well be that a lot of what we do actually is cobbled together into a few mega-systems. But there is abundant evidence that a lot of cognition is actually very domain-specific: different neural circuits exist to perform discrete tasks. 
</p>

<p>
A new paper by Nadav Kashtan and Uri Alon of the Weizmann Institute finds a reason why modularity might commonly evolve. Here's the abstract: 
</p>

<blockquote>Biological networks have an inherent simplicity: they are modular with a design that can be separated into units that perform almost independently. Furthermore, they show reuse of recurring patterns termed network motifs. Little is known about the evolutionary origin of these properties. Current models of biological evolution typically produce networks that are highly nonmodular and lack understandable motifs. Here, we suggest a possible explanation for the origin of modularity and network motifs in biology. We use standard evolutionary algorithms to evolve networks. A key feature in this study is evolution under an environment (evolutionary goal) that changes in a modular fashion. That is, we repeatedly switch between several goals, each made of a different combination of subgoals. We find that such "modularly varying goals" lead to the spontaneous evolution of modular network structure and network motifs. The resulting networks rapidly evolve to satisfy each of the different goals. Such switching between related goals may represent biological evolution in a changing environment that requires different combinations of a set of basic biological functions. The present study may shed light on the evolutionary forces that promote structural simplicity in biological networks and offers ways to improve the evolutionary design of engineered systems (Kashtan and Alon 2005:13773). </blockquote>

<p>
The study simulated the evolutionary process by allowing different kinds of circuits to compete with each other. The circuits that best solved the range of problems in the "environment" were replicated into a new generation (i.e. "selection"), with a small likelihood of random changes (i.e. "mutations") to their function. They also performed a similar simulation using neural networks instead of circuits. 
</p>

<p>
These experiments resulted in many different designs that satisfied the same computational goal. So the evolution in the different simulations was <i>contingent</i>: random factors led different simulations to different optimal solutions. 
</p>

<p>
But this experiment added a novel component: sometimes the computational goals changed slightly over time. Each of the computational goals might involve several subtasks. One possibility is that these different subtasks might remain constant over time. But an additional possibility is that they might change slightly in importance relative to each other: in other words, the circuits might be presented with slightly different problems at some times than others. 
</p>

<p>
Now, if this "environment" of problems to solve changed in a consistent direction over time, then we would expect the circuits likewise to evolve to solve the newer problems more efficiently. 
</p>

<p>
But instead of changing the task from the beginning to the end of the simulations, Kashtan and Alon (2005) caused the tasks to oscillate over time. Sometimes one subtask might be more important, sometimes another, but there was no long-term directional change, just a steady variability in what kinds of tasks were important. 
</p>

<p>
In this fluctuating environment, the circuits evolved to be modular. Changing different requirements at different times caused different subsystems to arise to solve each of these subtasks. These modular systems were slightly less efficient than the nonmodular systems that evolved to solve fixed tasks: they required additional logic gates to do the same job. But it took them a much shorter time to make the adjustment to solving slightly different problems. 
</p>

<p>
You might think that this evolution was the result of the division of the computational goal into perceivable subtasks. But interestingly, when the environment encompassed goals that could logically be divided into subtasks but did not vary over time, the circuits did not evolve toward modular solutions. Here's an example:  
</p>

<blockquote>A human engineer would easily notice the modularity in this problem and design a network that is made of two modules, one that analyzes the left side of the retina, and the other for the right side of the retina. In contrast, the structure of the evolved networks was not modular (Fig. 5b)(Qm = 0.15 0.02). As in the case of electronic circuits, fixed-goal evolution produces a nonmodular network even though the problem itself is readily decomposable into separate subgoals (Kashtan and Alon 2005:13776). </blockquote>

<p>
Nor was the effect simply the result of variation over time: when tasks were made to vary randomly, instead of by the emphasis of different subtasks, no modular structure resulted in the evolving circuits. 
</p>

<p>
The authors discuss their results: 
</p>

<blockquote>Why do modularly varying goals speed up evolution (in terms of the number of generations to reach perfect solution) when compared with evolution under a fixed goal? One reason that fixed-goal evolution is often slow is that the population becomes stuck in local fitness maxima. Because the fitness landscape changes each time that the goal changes, modularly varying goals can help move the population from these local traps. Over the course of many goal changes, modularly varying goals seem to guide the population toward a region of network space that contains fitness peaks for each of the goals in close proximity. This region seems to correspond to modular networks (ibid:13777). </blockquote>

<p>
The other element of the study is the demonstration that these kinds of modular circuits consist of similar structures repeated to comprise different modules. Such repeated elements are here called "network motifs". This is another characteristic of some biological organization, so it is very interesting:
</p>

<blockquote>In addition to their modular structure, the networks evolved under modularly varying goals display significant network motifs. The same motifs are reused throughout each network in different modules. Some of these motifs are also found in biological information processing networks. For example, feed-forward loops and bifans are found in transcription networks (7). Feed-forward loops, bifans, and diamonds are found in signal transduction and synaptic neuronal networks (7). In signal transduction networks (34) and the neuronal network of C. elegans (39), multilayered feed-forward patterns similar to those in Fig. 5c, are strong network motifs. An example is multilayered protein kinase cascades, in which families of kinases in each layer activate families of kinases in the next layer (34, 40, 41). </blockquote>

<blockquote>One possible explanation for the origin of the motifs in the olved networks is that modular networks are locally denser than nonmodular networks of the same size and connectivity. This local density tends to increase the number of subgraphs (42). To test this possibility, we evolved networks to reach the same modularity measure Q as the networks evolved under modularly varying goals, but with no information-processing goal (see Supporting Text). We find that these modular networks have no significant network motifs (Fig. 9). They show relatively abundant feedback loops that are antimotifs in the networks evolved under modularly varying goals. It therefore seems that the specific network motifs found in the evolved networks are not merely caused by local density, but may be useful building blocks for information processing (ibid:13777-13778). </blockquote>

<p>
The authors end with a discussion of how their results may apply to biological evolution, with specific biological examples, although not drawn from the brain. 
</p>

<h4>References:</h4>

<p class="cite">Kashtan N, Alon U. 2005. Spontaneous evolution of modularity and network motifs. Proc Nat Acad Sci USA 102:13773-13778. </p>


