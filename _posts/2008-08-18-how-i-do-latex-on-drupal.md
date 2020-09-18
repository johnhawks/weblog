---
layout: single 
title: "How I do LaTeX on Drupal" 
category: story
permalink: /weblog/site/drupal-latex-2008.html
tags: [admin] 
comments: false 
author: John Hawks 
---

<p class="noindent" >Some people wanted to know what I am using to enter my LaTeX code into <a  href="http://drupal.org/" >Drupal</a>. There are several Drupal modules that can deal with some LaTeX, but none of them really suited my needs. <p class="indent" >   The most important advantage of LaTeX blogging is that I&#8217;m able to use my reference database seamlessly in my blog with BibTeX. Another is that I can generate PDFs of my posts from the same source as the blog (believe it or not, I get a lot of PDF requests). Slightly less important, I can repurpose text more easily. <a  href="http://drupal.org/project/drutex" >DruTeX</a> and other Drupal-centric solutions are especially good if you want to use LaTeX code as a Markdown-like shorthand instead of HTML, but don&#8217;t fill my requirements. <p class="indent" >   To generate HTML from LaTeX, I depend on <a  href="http://www.cse.ohio-state.edu/~gurari/TeX4ht/" >Tex4ht</a>. I also use this to transfer LaTeX to RTF for publishing articles and my textbook, and it does an excellent job for most purposes. <p class="indent" >   No matter your destination format, TeX4ht always seems to take some tweaks to get everything converted. The strict XHTML produced by Tex4ht works fine in a browser, but it contains a number of elements that stymie Drupal&#8217;s &#8220;Full HTML&#8221; filter, including lots of HTML comments and superfluous newline characters (Exactly why &#8220;Full HTML&#8221; doesn&#8217;t mean full HTML, I don&#8217;t understand.) I wrote a short Python script that strips these things out. At the moment it&#8217;s just a hack, but it works. <p class="indent" >   <span  class="cmbx-10">Styling</span>: For whatever reason, TeX4ht doesn&#8217;t like the simple bold and italic tags of standard HTML and instead applies styles with SPAN tags and custom classes like &#8220;cmbx-10,&#8221; for the LaTeX-native Computer Modern fonts. It&#8217;s simple enough to include these classes in your CSS file, and apply whatever styling you like. If you <span  class="cmti-10">really </span>don&#8217;t like it, you could always rig up a custom config file for TeX4ht. <p class="indent" >   <span  class="cmbx-10">Math</span>: Math goes to PNG pictures by default under TeX4ht; I keep all graphics in a common directory on my server. Copying the PNG files, and updating references in the HTML source (again, that Python script), is all it takes for equations to come out right. <p class="indent" >   <span  class="cmbx-10">Hyperlinks</span>: The hyperref package for LaTeX does a nice job with links and internal references (including bibliography references). Links come out the same whether through Drupal or PDF. <p class="indent" >   So, that&#8217;s easy enough, but probably not recommended unless you&#8217;re ready to do a little scripting.   

UPDATE (2008/08/24): A reader writes: 

<blockquote>Not sure which Drupal version you have (it might not be in 4.x), but if you go to Administer -> Input Formats; and then click on 'configure' near 'Full HTML' you can disable the HTML filter and line break filter altogether and it might remove the necessity for your intermediate step.</blockquote>

That will probably do the trick for a lot of people. 



