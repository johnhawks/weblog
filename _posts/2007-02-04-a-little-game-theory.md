---
layout: single 
title: "A little game theory" 
category: story
permalink: /weblog/reviews/behavior/game_theoretic/game_theory_intro_2007.html
tags: [game theory] 
comments: false 
author: John Hawks 
---

<p>
The second week of theory in my seminar focuses on John Maynard Smith and evolutionary game theory. 
</p>

<p>
<a href="http://en.wikipedia.org/wiki/Game_theory">Game theory</a> had a long history before it was appropriated by biologists, and some of this history is relevant to us. The field was invented by <a href="http://en.wikipedia.org/wiki/Von_Neumann">John von Neumann</a>, in his copious spare time away from inventing computational logic, designing atomic bombs, and finding laws of quantum mechanics. If I were a mathematician, von Neumann would be my hero. Von Neumann was joined in this work by economist Oskar Morgenstern, and their joint book, <a href="http://en.wikipedia.org/wiki/Theory_of_Games_and_Economic_Behavior"><i>Theory of Games and Economic Behavior</i></a> focused on the application of the basic principles of the theory to reasoning about real-world problems. 
</p>

<p>
Many people may be familiar with game theory through the popular movie, <i>A Beautiful Mind</i>, which dramatized the life of mathematician <a href="http://en.wikipedia.org/wiki/John_Forbes_Nash">John Nash</a>. Nash developed the theory of game theory equilibria -- which define boundary conditions within games between regions where one strategy or another has an advantage. People of my generation will remember Dabney Coleman's obliviousness to basic game theory in <i>WarGames</i>, where the eminently quotable line, "The only winning move is not to play," is essentially a description of one Nash equilibrium for global thermonuclear war. The funding of much early work in game theory by the <a href="http://en.wikipedia.org/wiki/RAND">RAND foundation</a> helped to propel game theory to a central place in international relations as well as economics. 
</p>

<p>
This post reviews some of the basics of game theory, including the dynamics of two of the best-known games: Chicken and the Prisoner's Dilemma, and the way that one of them saved the world -- at least, Hollywoodly speaking. 
</p>

<!-- more -->

<h4>Chicken run</h4>

<p>
The basic assumption of game theory is that an individual player may choose one out of a set of roles, where the rules of the game and the roles have both been defined in advance. Each role has costs and payoffs defined by the game's rules, which usually vary depending on the strategies adopted by other players. Playing the game requires no innovation, only a choice of roles based on their costs and benefits. A player may choose to follow a <i>strategy</i>, which will determine the roles he or she chooses in one or many trials of the game. The question is, what strategy will a <i>rational actor</i> adopt? The answer to this question depends on the costs and payoffs of the roles, themselves determined by the odds that other players will adopt the same or different roles. 
</p>

<p>
A well-known example is the game of chicken. Chicken is a game with two players, each driving a car -- preferably a early-1950's model souped-up "Greased Lightning" kind of car. The two players each take up positions on the opposite ends of a long straightaway, hit the accelerator, and drive their cars toward each other at high speed. The loser of the game is the driver who swerves off the road first -- he is the "chicken." But if neither driver swerves, both will be involved in a head-on collision. Considering that their early-1950's era cars are not equipped with air bags or shoulder harnesses, this will be a costly result for both drivers. 
</p>

<p>
Let's consider the payoffs and costs of the two roles, "drive" and "swerve". The player who swerves incurs a steep social cost -- the T-birds will mock him mercilessly, they may shove him into his locker, he'll never get a date to prom. But he will avoid a steep physical cost of hospitalization or death. And he may even get lucky -- his opponent may <i>also</i> swerve. A player who doesn't swerve may gain the great social benefit of winning, but runs the risk of dying if his opponent doesn't swerve either. 
</p>

<p>
We can set up these payoffs in the form of a matrix. On the left side are the two roles that our player might adopt; across the top are the two roles that his opponent might adopt. The values in the matrix are the payoffs to our player, given his role and the opponent's role: 
</p>

<div class="pic">
<table>
<tr><td></td><td>Drive</td><td>Swerve</td></tr>
<tr><td>Drive</td><td>-100</td><td>10</td></tr>
<tr><td>Swerve</td><td>-10</td><td>0</td></tr>
</table>
</div>

<p>
Now, what should our player do? It seems obvious that, as a general rule, he should swerve. Surely he doesn't want to end up in the hospital, right? 
</p>

<p>
But the <i>average payoff</i> of each role depends on how often an opponent will adopt them. To figure out the average payoff, we have to consider what will happen not in any one instance of the game, but instead over a large number of trials. To start with, we will assume that every trial is independent -- the players have no memory for what happened last Friday night. 
</p>

<p>
If our player finds himself in a town where all (100 percent) of the opponents will swerve, then his average payoff will only zero if he swerves (zero times 100 percent), but 10 if he drives (10 times 100 percent). On the other hand, when the player is in a town where all the opponents drive, then his average payoff for driving will be -100, and his average payoff for swerving will be -10. Clearly a wandering player could do best for himself if he could find a town where everyone always swerves, because he could then always win by driving. But likewise, a town full of drivers can easily be <i>invaded</i> by a player who always swerves -- and considering that the drivers will spend much of their time in the hospital, he might even avoid getting shoved into his locker so much!
</p>

<p>
The two strategies, "always drive" and "always swerve" are so-called <I>pure strategies</i>. Our quick analysis is sufficient to show that neither of these pure strategies is a winner in all circumstances. In particular, <b>neither is a <i>best response</i> to itself</b>. The best response to "always drive" is to swerve, because the payoff for swerving against a driver is always greater than the payoff for driving against a driver. Likewise, the best response to "always swerve" is to drive. 
</p>

<p>
But what if players can adopt <i>mixed strategies</i>, in which they play one role sometimes and the other role at other times? The "strategy" determines what proportion of trials the player will drive and what proportion he will swerve; the actual choice of "drive" or "swerve" in any particular trial may be considered random based on these proportions. If there actually is a mixed strategy that outperforms either pure strategy, we can expect that all the players will adopt it. In particular, there is one unique mixed strategy that is <i>the best response to itself</i>. This is the Nash equilibrium for the game. Now the question is this: What proportion of the two roles will maximize the average payoff? 
</p>

<p>
We'll call the proportion of driving at the optimum <i>p</i>, while the proportion of swerving is (1 - <i>p</i>). Now what value of <i>p</i> maximizes the average payoff? One way to answer this question is to observe that at an optimum, any change in <i>p</i> will reduce the average payoff. But any change in <i>p</i> is necessarily a change in (1 - <i>p</i>). So if the average payoff is higher for strategy <i>p + &epsilon;</i> than for strategy <i>p</i>, that implies that the payoff for (1 - <i>p</i>)&epsilon; is <i>lower</i> than for (1 - <i>p</i>). Clearly, the optimum is the point where the payoff for <i>p</i> <i>is equal to</i> the payoff for (1 - <i>p</i>). 
</p>

<p>
For the game of chicken with the payoffs above, this point is where
</p>

<div class="pic">
-100<i>p</i> + 10(1 - <i>p</i>) = -10<i>p</i> + 0
</div>

<p>
Or simply, <i>p</i> = 0.1. The payoffs for our game are maximized when a player drives 10 percent of the time. 
</p>

<p>
Note that this doesn't imply that the average payoff is <i>positive</i>. In our case, the average payoff is -9, and all players operate at an average loss!
</p>

<p>
The equation above can be extended to a general case, if we assume the following matrix of payoffs for alternative roles <i>I</i> and <i>J</i>: 
</p>

<div class="pic">
<table>
<tr><td></td><td><i>I</i></td><td><i>J</i></td></tr>
<tr><td><i>I</i></td><td>a</td><td>b</td></tr>
<tr><td><i>J</i></td><td>c</td><td>d</td></tr>
</table>
</div>

<p>
For the game of chicken with these payoffs, the equilibrium strategy is a mixture of roles <i>I</i> and <i>J</i> with the proportion of <i>I</i> being given by (Maynard Smith 1982, equation 2.7): 
</p>

<div class="pic">
<i>p</i> = (<i>b</i> - <i>d</i>) / (<i>b</i> + <i>c</i> - <i>a</i> - <i>d</i>)
</div>

<p>
This relation holds for mixed strategies in the symmetric two-player game, as we are examining here. But as we will see below, there are other games where a pure strategy of playing one role all the time is the optimum. In such cases, the proportion of one role should approach 100 percent. 
</p>

<h4>Global thermonuclear war</h4>

<p>
The premise of <i>WarGames</i> is that the defense department has built a large computer (called the "WOPR") to simulate the payoffs of different strategies for a global nuclear engagement. Matthew Broderick is a computer whiz who calls up the WOPR on his modem and plays a few rounds of chess with the computer. Then, he tries to play "Global Thermonuclear War" with the WOPR, which sets off a fake doomsday clock at NORAD. Drama ensues as the young hero is arrested, then discovers that the computer is going to start a <i>real</i> first strike nuclear attack, and has to stop it. 
</p>

<p>
Ultimately, the computer starts playing many iterations of "Global Thermonuclear War" against itself, trying to find a solution with a positive payoff. Naturally there aren't any, and the computer "realizes" that "The only winning move is not to play." 
</p>

<p>
But wait a second. <i>Why</i> is there no winning move? The two nations with huge nuclear stockpiles, the US and USSR, had been engaged in an arms race for their own safety! This strategy depended on altering the payoffs of a nuclear exchange in such a way that the cost of an attack was certain retaliation, destroying both countries. This doctrine, called "Mutually Assured Destruction," was rooted in the game of chicken, with research funded by the RAND corporation. The computer's sentiment may be more quip-worthy, but it is more correct to say that the game has no positive payoffs, assuming the players are rational actors. 
</p>

<p>
This points to an important principle -- if we alter the payoffs, we will alter the optimum strategy. If we want to increase the number of players who swerve, then we can increase the cost of a collision -- for example, by packing the cars with explosives. If we want to <i>decrease</i> the number who swerve then we can increase the cost of swerving -- for instance, we could reward a winning driver with ownership of the loser's car ("play for pinks"). This certainly would make for an exciting game of chicken, although one in which fatalities are much more likely. 
</p>

<h4>Pure strategies</h4>

<p>
For some games, a pure strategy may provide the maximum payoff. Consider the following game: 
</p>

<div class="pic">
<table>
<tr><td></td><td>Cooperate</td><td>Defect</td></tr>
<tr><td>Cooperate</td><td>-10</td><td>-50</td></tr>
<tr><td>Defect</td><td>50</td><td>-10</td></tr>
</table>
</div>

<p>
This game is called the "Prisoner's Dilemma". Imagine that two suspects ("skels" in <i>CSI Miami</i>-lingo) are arrested by the cops. The police think that both were probably involved in the crime, but their evidence is weak. So they put the suspects into different interrogation rooms and offer various enticements to get each suspect to rat out (that is, defect against) his buddy. If both of them keep quiet (that is, cooperate), they will both get off with a light sentence -- hence the positive payoff. Likewise, if both defect, they will both get a light sentence because neither bears all the blame. But if only one of them defects, he can get off scot free. 
</p>

<p>
Here, the payoff for defecting is always greater than the payoff for cooperating. The pure strategy, "Always defect" is the optimum. 
</p>

<p>
We can write this situation more generally. As above, suppose the following sets of roles and payoffs: 
</p>

<div class="pic">
<table>
<tr><td></td><td><i>I</i></td><td><i>J</i></td></tr>
<tr><td><i>I</i></td><td>a</td><td>b</td></tr>
<tr><td><i>J</i></td><td>c</td><td>d</td></tr>
</table>
</div>

<p>
With this scheme, the pure strategy <i>I</i> will be the optimum strategy if and only if <i>a</i> > <i>c</i> and <i>b</i> > <i>d</i>. This condition guarantees that <br /> <i>ap</i> + <i>b</i>(1 - <i>p</i>) > <i>cp</i> + <i>d</i>(1 - <i>p</i>) for all values of <i>p</i>. This relation is true for the Prisoner's Dilemma, for which the pure strategy of defect is always the optimum. 
</p>

<p>
If defecting is such a good idea, we may wonder why real prisoners ever keep quiet. Don't they realize that their partners will rat them out? Shouldn't they try to minimize their costs?
</p>

<p>
There are really two answers to this. First, of course, they often <i>do</i> rat each other out!
</p>

<p>
The other answer is a bit deeper. Like nations in an arms race, criminal suspects have ways to manipulate the payoffs for cooperation and defection. Getting off "scot free" isn't so appealing if the mafia is going to fit you for cement shoes. Sell out a partner and you lose all the value in the relationship you've established. And don't forget, if you <i>both</i> defect, who's going to watch your back in the joint? 
</p>

<p>
Maybe even more important, suspects can exchange <i>information</i> with each other. Information can change the way players behave -- so much that an equilibrium strategy with information may be very different from the equilibrium without information exchange. 
</p>

<p>
This, of course, is why the police put the suspects in different interrogation rooms. Or why police sometimes manipulate the course of information exchange -- turning on the closed circuit television so that one suspect can watch the other rat him out. It's also why members of a syndicate have the same lawyer, who can carry information in and out.  
</p>

<p>
Last, the relationship between suspects may be <i>asymmetrical</i> -- one may have more of an incentive to defect than the other. Sometimes one suspect just doesn't care as much about the relationship as the other. Other times, a stint in the pokey is just the ticket a young foot soldier needs to rise in his organization. Of course, the police use this information, too: when one suspect is more likely to flip, they will encourage him by any number of means. 
</p>



<h4>References:</h4>

<p class="cite">Maynard Smith J. 1982. Evolution and the theory of games. Cambridge University Press, Cambridge UK. </p>

<p class="cite">Weibull JW. 1997. Evolutionary game theory. MIT Press, Cambridge MA. </p>


