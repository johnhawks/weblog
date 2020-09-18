---
layout: single 
title: "Natural selection 101. Episode 1: The miracle of compound interest" 
category: story
permalink: /weblog/topics/evolution/selection/miracle_of_compound_interest_2007.html
tags: [natural selection, Darwin, exponential growth] 
comments: false 
author: John Hawks 
---

<p>
--Originally posted August 24, 2007.
</p>

<p>
Once upon a time, somebody probably told you that biologists don't need to know any calculus. Well, I suppose they were right: it is certainly true that most biologists don't use any calculus in their work. A purely practical biologist is like a purely practical banker -- as long as the computers do their jobs, why does anybody need to know how to calculate?
</p>

<p>
Still, there is some point to knowing the theory that underpins the study of life. Math gives the theory its power. Understand the math, and you can unleash that power to find answers to new problems. 
</p>

<p>
During the last year or so, I have written nothing here about natural selection, quite purposively, even though anyone who knows me at all can tell you I hardly talk about anything else. Well, I tend not to write about what I'm working on; especially when it involves other people's observations as well as my own. I don't like it that way, but sometimes it's necessary. It especially stings when the major news in biology is that the world has changed to make selection relevant again. Still, to do my part in this change, I've maintained a respectable silence. 
</p>

<p>
Over this time, I have learned many mysteries about Darwin's force. Most geneticists approach natural selection as a kind of black magic. You see, find the right pattern of selection, and you can explain almost anything. You might think this is a desirable quality in a scientific hypothesis, but many people don't see it that way. Selection, in their view, is too often <i>unfalsifiable</i>. It's too hard to disprove. And besides, some things really do happen by chance alone. We have to give random chance at least a fair shot as an explanation, and if you can't <i>disprove</i> genetic drift (so the story goes), then you don't <i>need</i> to invoke selection. 
</p>

<p>
Besides, genetic drift is a much happier, friendlier hypothesis than selection. If somebody dies by genetic drift, it's nobody's fault. "Ooops, just a spot of bad luck, there! Move along, nothing to see here." By contrast, selection thuggishly entails that deaths and births have <i>causes</i>. For some reason, the idea that something should have a cause is offensive to some biologists. That is, after all, the point of <i>The Spandrels of San Marco</i>: Adaptationism, the assumption that phenotypic "traits" have discrete (and identifiable) causes, is a metaphysical assumption, not a tenet of Darwinism. Even those biologists who don't conform to the philosophy of narrow adaptationism, as described by Gould and Lewontin, have often felt the sting of the word; a real scarlet "A" for their dossiers. 
</p>

<p>
Perhaps more to the point, you can learn the essentials about genetic drift with a bit of algebra. Drift in a constant population is a linear process, and drift in non-constant populations can generally be approximated by linear modifications to the case of constant size. In contrast, natural selection is a logistic process, and understanding it requires differential equations. 
</p>

<p>
A combination of philosophy and calculus. You can see how selection got its reputation as black magic. 
</p>

<!-- more -->

<h4>Darwin's non-mathematical math</h4>

<p>
The foundations of Darwinism are economic. This should not come as a shock: Darwin took his inspiration from <a href="http://en.wikipedia.org/wiki/Malthus">Thomas Malthus</a>, who formalized the idea that the geometric growth in population would outstrip resources that grow at a linear rate. That's math -- math that Darwin found compelling and used as the basis for his concept of natural selection. Here's a passage from page 47 of "On the Variation of Organic Beings in a state of Nature":
</p>

<blockquote>It is the doctrine of Malthus (1826) applied in most cases with tenfold force. As in every climate there are seasons, for each of its inhabitants, of greater and less abundance, so all annually breed; and the moral restraint which in some small degree checks the increase of mankind is entirely lost. Even slow-breeding mankind has doubled in twenty-five years; and if he could increase his food with greater ease, he would double in less time. But for animals without artificial means, the amount of food for each species must, on an average, be constant, whereas the increase of all organisms tends to be geometrical, and in a vast majority of cases at an enormous ratio. Suppose in a certain spot there are eight pairs of birds, and that only four pairs of them annually (including double hatches) rear only four young, and that these go on rearing their young at the same rate, then at the end of seven years (a short life, excluding violent deaths, for any bird) there will be 2048 birds, instead of the original sixteen. As this increase is quite impossible, we must conclude either that birds do not rear nearly half their young, or that the average life of a bird is, from accident, not nearly seven years. Both checks probably concur. The same kind of calculation applied to all plants and animals affords results more or less striking, but in very few instances more striking than in man.</blockquote>

<p>
Darwin sat on this expressly mathematical insight for nearly twenty years, until  Alfred Russel Wallace arrived at it independently. Wallace sent Darwin his manuscript, Darwin forwarded it to Charles Lyell, and Lyell arranged the remarkable double publication of Darwin's and Wallace's essays in the <i>Journal of the Linnean Society</i>. Wallace's essay contains a very similar section to Darwin's quoted above -- the observed birth rate of animals should lead to geometric growth, yet this is impossible except over the shortest time span, so the natural check on population growth must cause competition and selection of traits favorable to survival. 
</p>

<p>
Math-avoiding biologists have a true hero in Darwin, who -- even allowing for his characteristic nineteenth-century modesty -- was profoundly self-conscious about his failure to master algebra. In an autobiographical chapter of the collected papers edited by his son Francis, Charles Darwin himself describes his resignment about math: 
</p>

<blockquote>I attempted mathematics, and even went during the summer of 1828 with a private tutor (a very dull man) to Barmouth, but I got on very slowly. The work was repugnant to me, chiefly from my not being able to see any meaning in the early steps in algebra. This impatience was very foolish, and in after years I have deeply regretted that I did not proceed far enough at least to understand something of the great leading principles of mathematics, for men thus endowed seem to have an extra sense. But I do not believe that I should ever have succeeded beyond a very low grade (Darwin 1887:46).</blockquote>

<p>
So it is ironic that Darwin's greatest insight was so expressly mathematical. The force of natural selection emerges from the necessary conflict between the <i>potential</i> of geometric population growth and the <i>constraint</i> of limited resources. The conflict arises from excess reproduction itself, for if many are being born but the population still does not grow, then we can infer that just as many must die. Wallace's essay makes this point crystal clear, after considering that birds produce four or more offspring per year: 
</p>

<blockquote>A simple calculation will show that in fifteen years each pair of birds would have increased to nearly ten millions! whereas we have no reason to believe that the number of the birds of any country increases at all in fifteen or in one hundred and fifty years. With such powers of increase the population must have reached its limits, and have become stationary, in a very few years after the origin of each species. It is evident, therefore, that each year an immense number of birds must perish &mdash; as many in fact as are born; and as on the lowest calculation the progeny are each year twice as numerous as their parents, it follows that, whatever be the average number of individuals existing in any given country, twice that number must perish annually,&mdash;a striking result, but one which seems at least highly probable, and is perhaps under rather than over the truth (Wallace 1858:55).</blockquote>

<p>
Many historians of science have found it very meaningful that the two men independently arrived at this formulation. It suggests that the idea of natural selection was in some sense "ripe" -- that the tenor of the times made science ready for Darwinism. 
</p>

<p>
Maybe so. But this "zeitgeist" argument misses an important point: this <i>mathematical</i> theory went without any mathematical <i>description</i> for over fifty years. 
</p>

<p>
To some extent, this lack of development can be blamed on the lack of a satisfactory theory of inheritance. When the mathematical development of a theory of natural selection was finally advanced by Haldane and Fisher, they had Mendelism to build it upon. If inheritance had turned out <i>not</i> to be Mendelian, a mathematical description of selection would likely have been harder. It is plausible that an earlier acceptance of Mendelian inheritance would have led to an earlier population genetic theory -- it certainly didn't take very long after Mendelism was rediscovered for <a href="http://en.wikipedia.org/wiki/G._h._hardy">G. H. Hardy</a> and <a href="http://en.wikipedia.org/wiki/Wilhelm_Weinberg">Wilhelm Weinberg</a> to describe its statistical foundations (Jim Crow <a href="http://www.genetics.org/cgi/content/full/152/3/821?maxtoshow=&HITS=10&hits=10&RESULTFORMAT=&titleabstract=Punnett&searchid=1109675768213_849&stored_search=&FIRSTINDEX=0&journalcode=genetics">described the context</a> of these discoveries in a 1999 perspective piece). 
</p>

<h4>Demography and selection</h4>

<p>
Still, I don't find the lack of a gene theory to be a very satisfactory explanation. There is nothing <i>genetic</i> about Darwin's and Wallace's logic. Both men posed the problem in exclusively <i>demographic</i> terms. Certainly, both assumed that characters are inherited in some way, because without inheritance, natural selection would be impossible. But they were content to refer to the competition between <i>varieties</i>, which itself is quite sufficient as a basis for a theory of selection. The replacement of one variety by another shares a common demographic basis as the replacement of one <i>gene</i> by another. 
</p>

<p>
In other words, Darwin's and Wallace's description of selection emerged from facts about demography, not inheritance. Both Darwin and Wallace make clear that selection depends on the conditions of existence -- it may be abated when resources are abundant, and it may intensify when populations decline. These demographic conditions could have been easily modeled along the lines that both Darwin and Wallace suggested. The essential facts are all there in the 1858 papers: when populations shrink, varieties that gain resources less effectively may disappear, and when populations grow, more fecund varieties will replace less fecund ones. This is the distinction between survival and fertility selection, already present in Darwin and Wallace. 
</p>

<p>
We can imagine an alternative history in which these insights were rapidly developed into a demographic model of selection. Mathematical models of demography were not only available at the time Darwin and Wallace wrote, they were the advancing frontier of social science. Mathematical descriptions of demography became important in the 1800's for the same reason they remain important today: actuarial predictions. In the 1820's, Benjamin Gompertz considered the effects of changing mortality, while the logistic model had been formulated by <a href="http://en.wikipedia.org/wiki/Pierre_Franois_Verhulst">Pierre Verhulst</a> as early as 1838. Both models presented substantial refinements of Malthus' conception of geometric growth, including the very thing Darwin and Wallace most needed: a description of an equilibrium. For that matter, Euler developed a true age-structured model of population growth in 1760! When we consider that the demographic model of natural selection is entirely <i>pre-Darwinian</i>, the possibility of an earlier development of theoretical population genetics seems quite plausible.
</p>

<p>
Such speculations are something like <a href="http://en.wikipedia.org/wiki/Steampunk">steampunk</a>, that narrow corner of fiction that supposes Babbage had really built his Difference Engine No. 2, and imagines what would have happened next. But there is a point to it: Nineteenth-century demography was already well-equipped to incorporate selection. Doing so may at the least have jump-started epidemiology, which could have made much of good actuarial records. Tracking thousands of people was already undertaken by governments. On the other hand, the development of genetics required somebody to track thousands of flies, and that wouldn't happen for a while. Still, a good demographic theory of selection might have been incorporated into developmental biology, giving Mendelism a run for its money.
</p>

<p>
So why didn't any biologist realize the potential of such modeling for understanding evolution? I can't find any historians of science who have considered this question, but we have some hints. Darwin and Wallace changed the direction of biology, but not its main research approaches. The nascent study of embryology and morphology, what we now would call "evolutionary developmental biology," was not based on demography, and had a radically different conception of possible mathematical descriptions of change. This may also account for the failure of biology to recognize the importance of Mendel's work -- another example of the power of algebra. 
</p>

<p>
Another reason for the tardy mathematical development: Rather than limiting themselves to a simplistic reductionist approach, biological theorists immediately tried to take in the full scope of nature in their evolutionary explanations. Haeckel was well known for this tendency in comparative biology -- he had to subsume every aspect of morphology into his Biogenetic Law. But the problems of demography could be equally baffling, if not reduced into a consideration of a single species at a time. For example, Alfred Lotka (1925:62) quotes this passage from Herbert Spencer's <i>First Principles</i>: 
</p>

<blockquote>Groups of organisms display this universal tendency towards a balance very obviously. In &sect; 85, every species of plant and animal was shown to be perpetually undergoing a rhythmical variation in number -- now from abundance of food an absence of enemies rising above its average, and then by a consequent scarcity of food and abundance of enemies being depressed below its average. And here we have to observe that there is thus maintained an equilibrium between the sum of those forces which result in the increase of each race, and the sum of those forces which result in its decrease. Either limmit of variation is a point at which the one set of forces, before in excess of the other, is counterbalanced by it. And amid these oscillations produced by their conflict, lies that average number of the species at which its expansive tendency is in equilibrium with surrounding repressive tendencies. Nor can it be questioned that this balancing of the preservative and destructive forces which we see going on in every race must necessarily go on. Since increase of numbers cannot but continue until increase of mortality stops it; and decrease of number cannot but continue until it is either arrested by fertility or extinguishes the race entirely (Spencer 1867:502). </blockquote>

<p>
Spencer and others were not content with describing what happened to a single population, because the dynamics of one population obviously depend on the populations of other species -- predators, competitors, and prey. An equilibrium between "expansive and repressive" forces required a consideration of those other species. Interestingly, Lotka quoted this passage in the context of providing just such a complicated model -- a system of equations modeling the interactions of an entire community of species. 
</p>

<p>
Demographic modeling would not make an impact on evolutionary theory until after 1900. Much of the revival was due to <a href="http://en.wikipedia.org/wiki/Lotka">Lotka</a>, who not only developed a continuous version of the Euler age-structured equation for population growth, but also extended the work of <a href="http://en.wikipedia.org/wiki/Vito_Volterra">Vito Volterra</a> to account for predator-prey relationships. Verhulst's logistic model was revived in 1920 by Raymond Pearl and Lowell Reed to describe the growth of the U.S. population. 
</p>

<p>
By this time, the first population geneticists, including Haldane, Fisher, and Wright, were ready to think about the demographic foundations of natural selection. Fisher showed how Mendelian genes could explain the variation in quantitative traits. Haldane showed how an advantageous gene would behave in a population. And then, in rapid order, Fisher demonstrated the essential connection of natural selection to demography. 
</p>

<h4>Compound interest</h4>

<p>
Most descriptions of natural selection begin with Mendelism, and follow Haldane's formulation of the replacement of a deleterious allele by an advantageous one. Certainly there is merit in this approach, but it's not especially Darwinian. Haldane's model is surprisingly complicated in its mathematics -- no doubt to the consternation of many would-be population geneticists. Moreover, its assumption of a static population bears little resemblance to the continuous demographic flux described by Darwin and Wallace.
</p>

<p>
So I'm going to do something very different. Instead of beginning with Haldane, I'm going to start with Fisher's demographic model. Fisher's model is based on the Euler-Lotka equation, and it is often overlooked by geneticists -- in fact I've never seen it in any population genetics text other than Gillespie's. But it is the foundation of life history theory and led directly to Hamilton's insights about strategy variants, later developed by Price and Maynard Smith. Plus, it takes a form that builds immediately upon the logic of Darwin and Wallace. 
</p>

<p>
The essential insight is one that any nineteenth-century banker would understand: population growth is like compound interest. 
</p>

<p>
A hundred dollars in the bank at four percent annual interest will grow to $104 in a year. In two years, you'll have $108.16. That's the initial $100 times 1.04 (104 percent) for one year, times 1.04 again for the second year. 
</p>

<p>
A simple equation will give us that result: if <i>t</i> is the time in years,  <i>r</i> is the rate of interest, and <i>x</i><sub>0</sub> is the original principal, then after <i>t</i> years the account balance will increase to: 
</p>

<div style="text-align:center;">
<img src="/graphics/equations/compound_interest.png" height="34" width="200" alt="x_t = x_0 * (1 + r)^t" />
</div>

<p>
Now, if you will have $104 in a year, how much will you have in your account in six months? Simply, if we allow <i>t</i> to equal one-half (0.5) in the equation above -- for half a year of interest -- we find that the right amount is $101.98. 
</p>

<p>
The amount of interest in the first six months is different from that in the second six months -- and in general, the amount of interest in any period depends not only on the rate of interest but also the amount of principal at that instant. Banks generally simplify matters (to your slight disadvantage) by compounding interest only at long intervals of a month or more. 
</p>

<p>
However, we can write these relations in another form that will make them much more useful to us. In the equation above, we can consider the term (1 + <i>r</i>)<sup><i>t</i></sup> as two parts: a <i>base</i> (1 + <i>r</i>) and an <i>exponent</i> (<i>t</i>). We may substitute a different exponent and base if we choose. In particular, if we substitute the base <i>e</i>, then the equation above may be written:  
</p>

<div style="text-align:center;">
<img src="/graphics/equations/exponential_growth.png" width="293" height="34" alt="x_t = x_0 e^rt" />
</div>

<p>
The exponential base <i>e</i> is exceedingly handy. Transforming our growth equation into an <i>exponential growth</i> equation lets us examine change as an continuous process. What is <i>k</i>? The value of <i>k</i> that will satisfy the equation is <i>k</i>=ln(1 + <i>r</i>). It is often called the <i>constant of proportionality</i> -- it represents not the annual rate of change, but the <i>instantaneous rate</i> of change. For a four percent annual rate of interest, the value <i>k</i> &#8773; 0.0392. In other words, a bank could pay our account 4 percent interest compounded annually by giving us the proceeds from 3.92 percent compounded continuously, and pocket the difference. It's not much of a margin, since <i>r</i> exceeds <i>k</i> by such a small amount. In fact, this amount is the <i>interest on the interest</i> earned continuously during the year. 
</p>

<p>
The equation, <i>x<sub>t</sub></i> = <i>x</i><sub>0</sub><i>e<sup>kt</sup></i>, is a solution to the differential equation
</p>

<div style="text-align:center;">
<img src="/graphics/equations/diff_exponential_growth.png" width="120" height="68" alt="dx/dt = kx" />
</div>

<p>
This equation says that the rate of change in <i>x</i> at each instant equals the product of <i>k</i> and <i>x</i> at that instant. 
</p>

<h4>Malthusian population growth</h4>

<p>
Malthus translated this simple logic underlying compound interest to an insight about populations. To do this, he had to ignore all the complexities that would later be pointed out by Darwin and Wallace. True, the annual numbers of births and deaths within natural populations are always changing. Natural resources change, sources of food, enemies, diseases, and all of these cause fluctuations in the birth and death rates. But if we ignore these fluctuations, and assume that the birth and death rates are <i>perfectly constant</i>, then a population should behave just like a bank account. If the annual rate of births (per individual) is higher than the annual rate of deaths (per individual), then the population will grow according to the equations above. This kind of population growth is generally called <i>Malthusian growth</i>. 
</p>

<p>
During the 1950's up to the 1970's, the human population of Earth grew by around 2 percent annually. Since that time the global population growth has been somewhat less, and the United Nations estimates that in the year 2000, the global population grew at an annual rate of 1.14 percent. 
</p>

<p>
Biologists tend to measure time in generations rather than years. Anthropologists and geneticists often assume a generation length of 20 to 25 years, although these values vary in different populations. These times are intended to represent the <i>average</i> age at which people have children, but of course the <i>actual</i> times vary substantially. Why does all this variation matter? Well, for one thing, it's why we want to use a continuous model instead of a model that involves discrete generations. Since <i>continuous means calculus</i>, it's nice to have a reason for the effort! 
</p>

<p>
In the end, we will do a bit better than this for a model of population growth, by directly considering the variation in the age at reproduction. That will take a bit more doing, which will come after a couple more episodes. 
</p>

<p>
At the current annual rate of growth (1.14%), we can estimate the growth rate per 20-year generation as (1.14)<sup>20</sup>, or 25.4 percent. If this is the rate <i>r</i> per generation, we can estimate the constant of proportionality <i>k</i> as 0.226 per generation. 
</p>

<p>
Clearly Malthus was right: over the long term, this kind of population growth is not sustainable. Indeed, over the <i>very</i> long term, <i>no</i> rate of population growth can be sustainable. And yet, over evolutionary time, no species that is incapable of long-term growth can survive: the inevitable consequence of an indefinite decline in numbers is extinction. 
</p>

<p>
To examine natural selection, we will need a slightly more complicated model of demography -- one that combines the potential of growth with the fact that growth cannot continue indefinitely. In the next installment, we will see that model, and consider some of its distinctive predictions about the rate of change. These demographic conditions, as Darwin and Wallace saw, provide the context by which one variety may replace another. 
</p>

<h4>References:</h4>

<p class="cite">Crow JF. 1999. Hardy, Weinberg and language impediments. Genetics 152:821-825. <a href="http://www.genetics.org/cgi/content/full/152/3/821?maxtoshow=&HITS=10&hits=10&RESULTFORMAT=&titleabstract=Punnett&searchid=1109675768213_849&stored_search=&FIRSTINDEX=0&journalcode=genetics">Full text</a></p>

<p class="cite">Darwin C. 1858. On the tendency of species to form varieties; and on the perpetuation of varieties and species by natural means of selection. J Proc Linnean Soc Lond Zool 3:46-50. </p>

<p class="cite">Darwin C. 1868. The variation of animals and plants under domestication. 1 ed., vol. 1. John Murray, London. </p>

<p class="cite">Darwin F, ed. 1887. The life and letters of Charles Darwin, including an autobiographical chapter. vol. 1. London: John Murray.</p>

<p class="cite">Pearl R, Reed LJ. 1920. On the rate of growth of the population of the United States since 1790 and its mathematical representation. Proc Nat Acad Sci USA 6:275-288. </p>

<p class="cite">Spencer H. 1867. First principles. Williams and Norgate, London. </p>

<p class="cite">Wallace AR. 1858. On the tendency of varieties to depart indefinitely from the original type. J Proc Linnean Soc Lond Zool 3:53-62.</p>
<p>

