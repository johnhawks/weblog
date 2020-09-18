---
layout: single 
title: "Reading a genetic map: the beta-globin gene cluster" 
description: "The beta-globin gene cluster provides a way to examine how a genetic map portrays the positions and sizes of genes." 
category: explainer
permalink: /explainer/laboratory/genetic-map-hemoglobin
tags: [Anthropology 105, kilobase, genome browser, chromosome, beta-globin gene cluster, explainer, hemoglobin, genetic map, hemoglobin, genetic map, blood] 
comments: false 
author: John Hawks 
---

A genetic map shows the location of genes and other DNA elements on a chromosome. The Human Genome Project created a genetic map that lists more than 3 billion nucleotides of DNA in an order that represents a partial consensus of many human DNA sequences. This map continues to be refined as we develop more understanding of human DNA structure and variation. The results are openly available to the public for download or analysis. 

We can examine this human genetic map by using a tool called a <strong>genome browser</strong>. One of the best-known genome browsers was constructed and is maintained by the Genome Bioinformatics Group of the University of California-Santa Cruz, called the <a href="http://genome.ucsc.edu/cgi-bin/hgGateway">UCSC Genome Browser</a>. The tool can be found on the web at <a href="http://genome.ucsc.edu/cgi-bin/hgGateway">http://genome.ucsc.edu/cgi-bin/hgGateway</a>, and a broader set of genome tools can be found at the home page, <a href="http://genome.ucsc.edu/">http://genome.ucsc.edu/</a>



One of the most widely known molecular structures is <strong>hemoglobin</strong>. Normal hemoglobin in human red blood cells is labeled <strong>HbA</strong>. Hemoglobin is not a protein, but a structure of four proteins bound with a smaller molecule called <strong>heme</strong>. An iron atom in the heme can bind oxygen, so that hemoglobin can transport oxygen throughout the body. The heme is strongly associated with one each of &alpha; and &beta; protein subunits. Because HbA includes four subunits, two &alpha; and two &beta;, it can be denoted &alpha;<sub>2</sub>&beta;<sub>2</sub>. 



The protein subunits of hemoglobin are each encoded by a separate gene. We are going to explore the regions around these two genes, <em>HBA1</em> (&alpha;-globin) and <em>HBB</em> (&beta;-globin). 


<div class="middle-picture">
<img src="/graphics/using-the-genome-browser-guide.png" alt="Guide to using the genome browser" />
<p class="caption">Some representative screenshots from the UCSC Genome Browser. The middle picture shows the whole length of the database entry for <em>HBB</em>, while the bottom shows the view zoomed in to the base level. Both screenshots were taken with all genome browser tracks turned off except for the UCSC Genes track. </p>
</div>


<ol>

<li> Open a browser window with the <a href="http://genome.ucsc.edu/cgi-bin/hgGateway">UCSC Genome Browser search page</a>. </li>

<li> Enter "beta globin" as the search term. </li>

<li> The results page will give a list of several genes as possible matches. The first on the list is <em>HBB</em>, which is the &beta;-globin gene. Choose it. </li>

<li> The browser will now show you <a href="http://genome.ucsc.edu/cgi-bin/hgTracks?position=chr11:5203272-5204877&hgsid=169883322&knownGene=pack">a graphic representing the region of the <em>HBB</em> gene</a>. At any time, you can enter <em>HBB</em> into the "gene" query box to return to this location. </li>

<li>The result will look something like this: </li>

<div class="middle-picture">
<img src="/graphics/genome-browser-hbb-whole-gene.png" />
<p class="caption">Genome browser result for <em>HBB</em>, showing the length of the whole gene. The only database track in this result is "UCSC Genes", all others are turned off. </p>
</div>

<li>The "position" box and the chromosome ideogram both show which chromosome we are looking at: Chromosome 11. The scale at the top of the genetic map will tell you the range of positions that is covered by the coding sequence of <em>HBB</em>. At the top of the figure, you can see the positions, here running from 5,203,500 past 5,204,500 &mdash; more than a thousand bases across, in other words. </li>

<li> <em>HBB</em> has three exons, or coding intervals, and these are indicated in the figure by the darker bars. The three dark bars are connected by thin lines that represent the two non-coding intervals, or <strong>introns</strong>. The <em>HBB</em> gene runs from right to left in the figure, as indicated by the small "arrow feathers" coming off the line running through the exons. In addition, the database has a second entry for <em>HBB</em>, which comes from an alternative transcript found in some tissue samples. </li>

<li> Click the button that says "base", or zoom in by dragging the mouse across a small part of the gene display. You should be able to see the nucleotide sequence at the top of the display. </li>

<div class="middle-picture">
<img src="/graphics/genome-browser-hbb-base-pair-zoom-level.png" />
</div>

<li> Here you can see the actual sequence of human chromosome 11, across roughly 80 bases. The initial zoom brings us into the intron between exons 2 and 3 of the <em>HBB</em> gene. You can explore this zoom level by clicking on the arrows. Eventually you will reach the exons, where the UCSC Genes display can show you the amino acid sequence of the gene. </li>

<div class="middle-picture">
<img src="/graphics/genome-browser-hbb-base-level-showing-amino-acids.png" />
</div>

<li> <a href="http://genome.ucsc.edu/cgi-bin/hgTracks?&db=hg18&position=chr11:5,203,272-5,204,877">Return to the display of the whole <em>HBB</em> gene.</a> Again, you will see the interval covering all three exons of <em>HBB</em>. </li>

<li> Now click the button that says "zoom out 10x." Now instead of looking at roughly 1000 bases, you are looking at more than 10,000 &mdash; or 10 <strong>kilobases</strong>. You will be looking at the immediate neighborhood around <em>HBB</em>. Notice to the right of <em>HBB</em> is another gene, <em>HBD</em>. This is &delta; (delta) globin, which takes the place of &beta;-globin in a small fraction of circulating hemoglobin. You can click on this gene to get more information about it. </li>

<div class="middle-picture">
<img src="/graphics/genome-browser-hbb-zoom-out-10x.png" />
<p class="caption">Genome browser display zoomed out 10 times from the <em>HBB</em> gene. To the bottom right, you can see the map position of <em>HBD</em>, human &delta;-globin.</p>
</div>


<li> Zoom out again. Instead of 10 kilobases, you are now looking at more than 100 kilobases of chromosome 11. Now you will see a string of genes stretching downstream of <em>HBB</em>. First <em>HBD</em>, then <em>HBBP1</em>, <em>HBG1</em> and <em>HBG2</em>, and <em>HBE1</em>. All of these genes are structurally similar to &beta;-globin. The reason why they are similar is that they all originated by gene duplications during the early evolution of vertebrates. Originally, they were copies of a single sequence, but they became different over time and some of them took on new functions. This area is called the <strong>&beta;-globin gene cluster.</strong> </li>

<div class="middle-picture">
<img src="/graphics/genome-browser-hbb-zoom-out-100x-beta-gene-cluster.png" />
</div>

<li> The gene labeled <em>HBBP1</em> is a <strong>pseudogene</strong>. It has a structure similar to a functional gene but does not correspond to a functional gene product. This kind of pseudogene is almost like a fossil within the genome. </li> 

<li> The &gamma; (gamma) and &epsilon; (epsilon) globin proteins are part of variant hemoglobins. Fetal hemoglobin, HbF, is produced before birth and includes two &gamma; instead of two &beta; subunits, making it &alpha;<sub>2</sub>&gamma;<sub>2</sub>. Embryonic hemoglobin produced in the embryonic yolk sac includes &epsilon; subunits along with &zeta; (zeta) subunits instead of &alpha;. 

</ol>

If you have time at this station, enter "HBA1" in the genome search box. This is the &alpha;-globin gene found in HbA. 

<ol>

<li> On which chromosome is &alpha;-globin? Is it inherited together with &beta;-globin? </li>

<li> Zoom out on this region. You will find the other genes in the <strong>&alpha;-globin gene cluster</strong>. What are they? </li>

<li> What would you hypothesize about the origin of these genes? </li>

</ol>


