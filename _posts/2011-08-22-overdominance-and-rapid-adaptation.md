---
layout: single 
title: "Overdominance and rapid adaptation" 
description: "It should be rare for new alleles to sweep to fixation in a diploid organism. " 
category: research
permalink: /research/cochran-harpending-hawks-overdominance-2011
tags: [balancing selection, my research, theory, Gregory Cochran, John Hawks, Henry C. Harpending, population genetics] 
comments: false 
author: John Hawks 
---

<h4>Introduction</h4>

The last decade has seen an explosion of interest in ongoing and recent natural selection in human populations. The HapMap project and other surveys of SNPs in human populations revealed many regions in the genome where one SNP allele is surrounded by large regions of linkage disequilibrium while the other is on a more heterogeneous background <bib>accel</bib><bib>Pickrell:2009</bib><bib>Voight:2006</bib><bib>Wang:2006</bib>. The inference has been that the former were undergoing or had undergone a selective sweep, and had experienced an increase in frequency too great to be explained by genetic drift. There have been attempts to construct bottlenecked population histories that would explain these patterns, but the elevated concentration of this pattern in genic regions apparently makes such explanations unlikely <bib>accel</bib><bib>Pickrell:2009</bib>.

A puzzling finding of this line of research is that the sweeping SNPs are disproportionately at intermediate frequencies rather than near fixation. Part of the explanation is that the technology for discovering these regions usually relies on contrasting the linkage disequilibrium around the putative sweeping SNP with that around its allele, so both kinds of chromosomes must be present. There is also a ``shortage'' of fixed genomic regions that show high disequilibrium as would be produced by complete sweeps.

Why are there so many incomplete sweeps?  Some have suggested that most phenotypic adaptation occurs in the form of ``soft sweeps'', in which evolution of a phenotype occurs because of slight changes in frequency of many standing genetic variants <bib>Pritchard:soft:2010</bib>. But soft sweeps of standing genetic variants do not explain the pattern of long-range LD haplotypes of intermediate frequency. These appear to be young haplotypes that have risen to intermediate frequencies quite rapidly, not old haplotypes that have changed in frequency marginally. One good possibility is what we have called the ``stooge effect''  - after the Three Stooges all trying to get through a doorway at the same time. Selection following an environmental change will favor <em>any</em> allele (either standing variation or new mutation)that provides increased fitness in the new environment, perhaps leading to change at many loci that decreases the fitness advantage of any one advantageous mutation. For example, the fitness advantage of sickling hemoglobin must have been much greater long ago when there were no high frequency genetic responses to malaria. The competition among adaptive alleles may slow down and perhaps stop the sweep of any one new mutant.

We know that some sweeping alleles, for example some of the hemoglobinopathies, are loss-of-function mutations, broken versions of the ancestral version.  They can have strong negative effects in homozygotes, who have no working copy of the gene. Such overdominant mutations are easy to recognize and understand.

Our analysis (based on Fisher's geometric model) suggests that overdominance is common in newly originated beneficial alleles of large effect, even when the mutation changes gene function, rather than reducing or eliminating it. This is a natural consequence of a high degree of pleiotropy. Such overdominant alleles will never fix. While homozygote fitness will be lower than heterozygote fitness in these cases, usually it will not be extremely low - will not cause death or obvious disease, and so will not be easily observed.


<h4>Fisher's geometric model</h4>

Fisher considered adaptation as an aspect of an organism's phenotype.

<blockquote>An organism is regarded as adapted to a particular situation, or to the totality of situations which constitute its environment, only in so far as we can imagine an assemblage of slightly different situations, or environments, to which the animal would on the whole be less well adapted; an equally only in so far as we can imagine an assemblage of slightly different organic forms, which would be less well adapted to that environment <bib>Fisher:1930</bib>.</blockquote>

Fisher defined the organism's fitness as its capacity for intrinsic population growth, the 'Malthusian parameter'. He imagined an optimal phenotype from which no change in the phenotype, however slight, could increase the organism's fitness&mdash;in some particular environment, obviously.  A well-adapted organism would be one whose phenotype was very close to that optimum. In his discussion, he did not distinguish between the case where the optimal form is the phenotype of an individual, or the average phenotype of a population. Fisher used this model as part of his argument that most evolutionary changes are small, suggesting that most individuals would be very near the average phenotype of the population most of the time. 

Fitness can thus be considered as a function of position in a multidimensional phenotype space. Fisher assumed that the distribution of fitness in that phenotype space has a single optimum (point <strong>O</strong>).  Coordinates are normalized so that fitness is a function of the distance from <strong>O</strong> and declines monotonically as that distance increases.

Consider a non-optimal phenotype, which we model as a point <strong>A</strong> in this phenotype space, at a distance <em>d</em>/2 from <strong>O</strong>.  Fisher considered this distance as the radius of a multidimensional sphere centered on <strong>O</strong>. All the points on that sphere have the same suboptimal fitness; you might say that they are all equally poorly adapted.

Now imagine a mutation that shifts the phenotype a distance <em>r</em> in some random direction, moving it to a new position <strong>B</strong>. If <strong>B</strong> is inside the hypersphere, it will be closer to <strong>O</strong> than is the initial point <strong>A</strong>, and so the mutation will be favored by selection. If <strong>B</strong> is on the hypersphere, the mutation will have equal fitness to the wild type, if <strong>B</strong> is outside the hypersphere, the mutation is deleterious relative to the wild type. Hence, the probability that the mutation is adaptive is the same as the probability that <strong>B</strong> is inside the hypersphere. 

We can derive this probability by considering the boundary condition in which the new position <strong>B</strong> lies exactly on the hypersphere: that is, when the distance <strong>|AO|</strong> = <strong>|BO|</strong>. The angle &theta;' between <strong>AO</strong> and <strong>AB</strong> in that case determines the maximum angle of a change that improves fitness: &theta;' = arccos(<i>r</i>/<i>d</i>).


[Figure 1 here]

If the angle between </strong>AB</strong> and </strong>AO</strong> is less than &theta;, <strong>B</strong> is closer to the optimum than <strong>A</strong> and fitness increases. If the angle is greater, <strong>B</strong> is farther from the optimum than <strong>A</strong> and fitness decreases.

In order to determine the probability that a random change of size <em>r</em> will increase fitness, we need to find what fraction of the surface of a hypersphere of dimension n lies within the cap with half-angle &theta;'.  Hartl and Taubes <bib>Hartl:Taubes:1998</bib> gave an exact expression for this probability:

\begin{equation}
\frac{\int_0^{\theta'} \sin ^{n-2} \theta d\theta}{\int_0^{\pi}
\sin^{n-2} \theta d\theta}
\label{eq:surface-fraction-adaptive}
\end{equation}


Fisher argued that <em>n</em>, the effective dimensionality of the phenotype space, was likely to be large in real cases because many different traits influence biological success. He proceeded to develop a large-n approximation for this probability integral that gives considerable insight.  Back in 1930, it must also have been considerably easier to calculate than the exact integral.

\begin{equation}
\frac{1}{\sqrt{2 \pi}} \int_{x}^{\infty} e^{-t^2/2}dt, x=r (n/d)^{\frac{1}{2}}
\end{equation}

One can see from this expression that the probability of a favorable change is close to 1/2 when r is small, while decreasing rapidly as the size of the change becomes larger than <em>d</em>/&radic;<span style="text-decoration:overline;"><em>n</em></span> - which one might call the  "standard magnitude" of change. Fisher concluded that mutations with small favorable effects are the main players in adaptive evolution.

But there are other factors that Fisher did not consider in his analysis. Kimura <bib>Kimura:1957</bib> considered an additional aspect of selective dynamics that influences the effect size of adaptive phenotypic changes: the fact that new mutations that confer small increases in fitness are likely to be lost by chance, almost as likely as a neutral mutation. The probability of success of a beneficial mutation increases linearly with its fitness benefit <bib>Haldane:5:1927</bib>. Thus, although larger phenotypic changes are less likely to be adaptive, changes of large effect that are adaptive are more likely to persist in the population. Kimura showed that a population is most likely to undergo adaptive changes that are intermediate in effect-large enough to survive genetic drift, but small enough that they remain relatively likely to move the phenotype closer to the optimum.

Orr <bib>Orr:2003</bib> considered not only the first adaptive change, but the entire series of adaptive changes as a population approaches a phenotypic optimum. He showed that Kimura's relation held for the first adaptive change, bringing the population a considerable distance toward the optimum. Subsequent changes are likely to be smaller. As the phenotype nears the optimum, large phenotypic changes are less and less likely to approach it more closely, so the entire sequence is dominated by small changes. Considering the process as a whole, Orr showed that the effect sizes of adaptive changes will be exponentially distributed. The exponential distribution is also the expectation drawn from extreme value theory of the effect sizes of beneficial mutations.



<h4>Diploid genotypes and Fisher's model</h4>

Fisher's geometric analogy holds up well for a haploid, because the phenotypic change induced by a mutation may be thought of as a vector, just as in Fisher's model. The difference between individuals and populations need not be strictly defined in the model, because the effect of a mutation on the fitness of an individual will be the same as on the fitness of a population. Given the amount of effort put into extending Fisher's phenotype model to mutational effects - even in diploid organisms like <em>Drosophila</em> &mdash; it seems remarkable that nobody has observed that the analogy does not hold for diploid genotypes. Diploids are difficult to treat with this geometric model, because each genotype may have a distinct phenotypic effect. Unlike the haploid case, we cannot assume that the effect of a mutation in an individual is the same as the effect of a substitution in the population. For an autosomal mutation to proceed to fixation in the population &mdash; thereby becoming a substitution &mdash; a mutant homozygote must have fitness equal to or greater than that of a heterozygote.  Even if a heterozygote has a phenotype that is intermediate between original-allele and mutant homozygotes, its fitness may not be.

For simplicity, we assume that phenotypic change is a linear function of gene dosage. In that case, two copies of the mutant allele result in exactly twice the change in phenotype caused by one copy. We designate the original phenotype as point <strong>A</strong> and the phenotype resulting from one copy of the mutation as point <strong>B</strong>, as before. We will designate the phenotype in mutant homozygotes as point <strong>C</strong>.  This means that the distance AC is exactly double <strong>AB</strong> (that is, 2<em>r</em> in Fisher's model). Given this constraint, we can find the angle &phi; at which the heterozygote and homozygotes have equal fitness, that is, where <strong>|BO|</strong> = <strong>|CO|</strong>. Since the displacement is larger, &phi;, the critical angle for homozygotes, is smaller than &theta;, the critical angle for heterozygotes.


[Figure 2 here] 



We can use this expression to calculate the probability that individuals who are homozygotes for a beneficial mutation of effect size <em>r</em> are fitter than heterozygotes. If <em>r</em> is small, 50% of mutations increase heterozygote fitness, almost all of which confer even higher fitness in homozygotes. If <em>r</em> is large, most mutations will not increase heterozygote fitness, and even those that do are unlikely to increase fitness further in homozygotes.

\begin{table}[h]\centering
\begin{tabular}{|c|ccccc|}
%\multicolumn{5} {c} {\bf Overall Heading} \\
    \hline
 & $|r|$ &  $0.01$    &   $0.1$  & $0.25$ & $0.5$ \\
    \hline
N   &  &  &  &  & \\
    \hline
16   & & 0.4924 & 0.4244 & 0.3163  & 0.1666  \\
32   & & 0.4890 & 0.3911 & 0.2441  & 0.0803  \\
64   & & 0.4842 & 0.3462 & 0.1606  & 0.0223  \\
128  & & 0.4776 & 0.2868 & 0.7918  & 0.0021  \\
    \hline
\end{tabular}
\caption{Probability that fitness tncreases in heterozygotes}
\end{table}


\begin{table}[h]
  \centering
  \begin{tabular}{|c|ccccc|r|}
    \hline
 & $|r|$ &  $0.01$    &   $0.1$  & $0.25$ & $0.5$ \\
    \hline
N  &  &  &  &  &  \\
%    \hline
16 & & 0.9846 & 0.8277 & 0.5266  & 0.1230  \\
32 & & 0.9775 & 0.7411 & 0.3289  & 0.0190  \\
64 & & 0.9675 & 0.6181 & 0.1388  & 0.0005  \\
128& & 0.9532 & 0.4524 & 0.0270  & 0.0000004  \\
    \hline
\end{tabular}
\caption{Probability that homozygotes are fitter than
heterozygotes} \label{tab:second}
\end{table}


In other words, there are three tests that an adaptive mutation must pass in order to reach fixation. First, it must increase fitness in heterozygotes, which, as Fisher showed <bib>Fisher:1930</bib>, is unlikely if its phenotypic effect is large. Second, it must avoid stochastic loss when rare. Haldane showed that a favorable mutation's probability of avoiding stochastic loss is about 2<em>s</em>, when <em>s</em> is the selective advantage. This means that a new allele will probably be lost if its effect size is small, because a small phenotypic effect leads to a small selective advantage. Third, it must confer higher fitness in homozygotes than in heterozygotes, which is unlikely if it has a large phenotypic effect. The first two tests are considered in most treatments of the genetics of natural selection, but the third has seldom been discussed.

Our assumption of linearity is optimistic. If the phenotypic change induced in homozygotes is nonlinear and in a significantly different direction in phenotype space than the change in heterozygotes, fitness will almost certanly be lower than in heterozygotes, since favorable changes are possible only in a narrow range of angles in a high-dimensional space.

True loss-of-function mutations, in which the gene's function is eliminated, rather than merely reduced, make up an important class of alleles with nonlinear effects. These changes, which eliminate rather than merely reducing gene function, are usually nonsense mutations, frameshifts, radical amino acid changes, etc. Many such alleles have moderate phenotypic effects in single dose &mdash; effects that can increase fitness &mdash; while causing drastic fitness decreases in homozygotes, which have no working copy of the gene. Many are lethal. Such alleles cause some of the most common human genetic diseases, such as cystic fibrosis (the &Delta;F508 mutation) and the &beta;<sup>0</sup> thalassemias.

Generally speaking, this kind of direction-changing nonlinearity should become more and more likely as effect size increases. If it is significant, the phenotypic change in homozygotes will be essentially unrelated to the beneficial change in heterozygotes, it will not even be in the same general direction in phenotype space, and so such mutations are almost always deleterious in homozygotes.

Lower fitness in homozygotes than in heterozygotes doesn't necessarily imply that homozygote fitness is extremely low or obviously depressed.  For example, consider a case in which one copy of a new allele increased fitness in past environments by 5%, while two copies increased fitness by 2%.  The new allele would never go to fixation: it would eventually approach an equilibrium frequency of about 71%. But, quite possibly, none of these genotypes (0,1, or 2 copies) would be obviously ill or seek medical attention.  This is particularly the case in modern environments, which are less harsh in many ways than those our ancestors experienced.  For example, alleles that conferred protection against famine or smallpox might have reached high frequencies in modern populations, but their advantages would be unnoticeable and effectively unmeasurable in modern populations. We would have next to no chance of determining small differences in the fitness effects of that allele in heterozygotes and homozygotes.


<h4>The X chromosome</h4>

The fate of an adaptive variant that appears on the X chromosome is quite different in eutherian mammals &mdash; humans, for example. Males have only a single copy of the X, so their gene dosage does not vary. Females have two copies, but only one copy of the X chromosome is active in each cell, while the other copy is condensed and inactive <bib>Carrel:Willard:2005</bib>. Upwards of 85% of all genes on the condensed chromosome are inactive, except in the pseudoautosomal regions. Since one of the X chromosomes is randomly inactivated in each cell, female heterozygotes will have the wild-type allele in some cells and the adaptive variant in others, while female homozygotes will have the same effective gene dosage as males with their one copy.

So, if a variant on the X chromosome increases fitness in males, it is likely to have the same effect in females with two copies. The effective dose of the new allele will be half as large in heterozygous females, but if the phenotypic effects are linear with gene dosage, heterozygote fitness should still be higher than wild-type In Fisher's model, a fitness increase for a given displacement in a particular direction implies a fitness increase for any smaller displacement in that same direction.

Under these assumptions, most X-chromosome gene variants that increase fitness in males should go to fixation, as long as they escape stochastic loss. Interestingly, the tight regulation of gene dosage on the X chromosome implies that changes in dosage do indeed influence fitness &mdash; why else would X-inactivation have evolved?

Such X-linked beneficial recessive alleles sweep more slowly than an autosomal allele with the same selective advantage, since only one third (those in males) manifest the advantage when the allele is rare. However, the elimination of the requirement that the new variant confer higher fitness in homozygotes than heterozygotes is more important, and should result in a disproportionate number of completed sweeps on the X chromosome. As it happens, that is exactly what we see in humans.

SNPs with high allele frequency differences are relatively rare in humans, but they are particularly common on the X chromosome <bib>Lambert:punctuated:2010</bib><bib>Casto:2010</bib> Out of the 3.2 million SNPs in the HapMap data set, only 479 have <em>F</em><sub>ST</sub> greater than or equal to 0.90.  Of those 479 high-Fst SNPs, 379 are on the X chromosome .  The majority of those highly differentiated SNPs cluster into five distinct regions. Those five regions apparently correspond to six selective sweeps.  Two of these sweeps happened near the centromere (in different populations). Of the six sweeps, five are in populations outside sub-Saharan Africa, with the sweep reaching fixation in East Asia, existing at lower frequencies in Europe and West Asia, while being rare in Sub-Saharan Africa. One of the two sweeps near the centromere has the opposite pattern &mdash; essentially fixed in sub-Saharan Africa and rare outside. That second pattern is unusual: there are few high-Fst SNPs for which the derived alleles are near fixation in sub-Saharan Africa. The best-known example is the mutation responsible for the Duffy <em>Fy*O</em> blood type.




<h4>Conclusion</h4>

Our conclusion is that most mutations with strong effects that increase fitness in heterozygotes confer lower fitness in homozygotes &mdash; that is, are overdominant.

This effect may not matter much in a well-adapted, stable species. Over many generations, overdominant alleles that partially solve some adaptive problem should eventually be replaced by alleles that confer high fitness in both heterozygotes and homozygotes and so go to fixation.  This could occur through the evolution of modifier loci and by rare favorable mutations that are essentially additive.  In steady-state, there should be relatively few common overdominant alleles, except for cases of frequency-dependent selection.

It may, however, play an important role in species that have experienced strong selection, ones whose environment has changed drastically. As it happens, this is the case for a number of species of interest: we would put humans and most domesticated species in this category.




