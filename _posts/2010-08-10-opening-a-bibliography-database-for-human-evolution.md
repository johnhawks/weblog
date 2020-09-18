---
layout: single 
title: "Opening a bibliography database for human evolution" 
category: story
permalink: /weblog/site/biblio-announcement-2010.html
tags: [blogging, metascience, site] 
comments: false 
author: John Hawks 
---

UPDATE (2015-01-02): <strong>After moving the site to a different platform (Jekyll), I am no longer using the inline bibliography function. If you are looking for the online bibliography, I'm working on adding this functionality in a different way. </strong>

ORIGINAL POST: 

I'm announcing today the new availability of <a href="http://johnhawks.net/biblio">a bibliography section</a> here on the weblog. At present this database includes more than 11,500 entries. These represent a large fraction of the historical and contemporary literature in human evolution. 



The database as it exists today owes to the work of many, many people. Foremost among these is Milford Wolpoff, who compiled and has curated an immense bibliography as a flat text file over many years. It includes entries that have been cited in many papers by Milford, his students, and many coauthors. 



Milford says that these folks are too numerous to remember. That has the ring of truth. Just by looking through the entries you get a picture of an active group of people over more than forty years. 



To these "legacy" references, I have begun to add fuller bibliographic information during the last few years. This began with Digital Object Identifier (DOI) tags for new, and later for older entries. In the last few months, I have begun to archive further information, including abstract.



I continue to update and backfill references that belong in the database. There are many cited here on the blog that haven't been properly archived, and I will be adding these along with new citations. 





<h4>What you'll find</h4>



<a href="http://johnhawks.net/biblio">The bibliography</a> has a search filter, search terms will match author, keyword, title or abstract (where present). With more than 11,000 entries, you want to be a little selective about how you search. Author names work really well, and yield a list separated by year of publication. 



You'll find each reference preceded by a unique citation key in brackets. I did this purely for my own convenience, but for those who may want to download lists of citations, it may also prove useful. 



A list of search results can be exported to BibTeX or RTF format for download. 



There is also a "filter" tab that allows keyword, author, and year filtering of the list. This is really not very useful; the size of the database makes it much simpler to search than to filter all entries. I have entered keywords for only very recent entries, so keyword filtering is not especially helpful. 



Each citation in the reference list comes accompanied by several links. You can click on the title, taking you to a reference page with full bibliographic information. For recent entries, the reference page includes DOI, direct links to journals, and the abstract. For all entries, the links include Google Scholar lookups and citation downloads (in BibTeX or RTF format). Author links give a list of all my database entries from that author. These require exact name matching, so don't rely too much on them -- a search of the database for an author's last name is usually more complete. 



My bibliography section has <a href="http://johnhawks.net/biblio/rss.xml">its own feed</a>, which lists new entries in reverse chronological order. I tend to upload new references in batches, so you'll frequently see a dozen or so show up at a time. I've put a short excerpt of the feed in a block on the left side of every page, just above my blogroll. 











<h4>Snafus</h4>



On the topic of author names: I know that many of you will immediately search for your own name. You'll find some of your publications there, but you almost certainly will see that many are missing. A few of you may not find a single paper!



Please don't be offended. Remember that the entire list was typed by somebody. If a paper isn't there, it's because nobody typed it into the list. Really, only a few of <i>mine</i> are in there!



I'm not volunteering to add another 11,000 entries to the list right away. It will take me 5 years or so to manage that, at the current rate. But if you find yourself wanting to pitch in, to help add some of your references to the database, then let me know and I'll work with you. 



There are countless typos. I do not intend to fix these, unless I cite the paper moving forward. It would literally take me weeks of work to fix the typos in these entries. Please don't contact me to fix these, because I won't do it! 



Some errors in the database have resulted from a script gone wrong. I scripted them all into BibTeX. When I did this, my script langage was Pascal, which was no picnic. That's a lot of pattern matching on citations. To the credit of all the people who entered data, the overwhelming majority of citations fell into a few common patterns. But there were oddballs, which didn't get translated properly. Over the years I've fixed many of these script-induced errors, but not all. Some of these are ugly and weird. I'm sorry!



A few quirks come from the software that presents the database. I haven't begun hacking on this, and I've decided to leave the defaults for awhile to see how well they handle the requirements. 



Most critically -- inline links to the references get mixed up when there are more than one reference list on the page. Since this is usually true of my front page, that's a problem! This is a minor annoyance, since the inline links only save a bit of scrolling, but it may not be easy to fix. 



Google Scholar lookups work pretty well, but I've run into some issues. For some older entries, the links fail to find papers that Google actually knows about. The problem is that the system passes the full title on to Google as a "quote", requiring an exact match. These often fail. Removing the quotes from these will often recover the citation in Google Scholar. 



If you do a search, the biblio page will continue to filter on your search phrase until you <b>reset it</b>. There's always a "reset search" link right up at the top of the page. 



Keyword searching works quite well with recent entries to the database, but not with the legacy references. If you are working on a research paper and want to do a lot of keyword searches, you'll be much better off starting with <a href="http://scholar.google.com">Google Scholar</a> or Web of Science. 











<h4>The inner workings</h4>



I got to talking with some researchers from Microsoft a few months ago, who were interested in the ways that I curate information. During our conversation, I came to realize that maintaining bibliographic data is the worst bottleneck in my work. 



I use BibTeX in my research work, but I've never had a good workflow that would encompass both research articles and blog posts under the same bibliography system. Often, I'd blog about a paper but fail to get it into my research database. If I wanted to blog about a historical paper, I'd have to go looking for it in my bibliography. 



Once I talked this through, I saw what I needed to do. I had to find a better way. 



Drupal has really significantly added to its bibliographic capabilities in the last couple of years. I found that the <a href="http://drupal.org/project/biblio">Biblio module</a> now has almost everything I need to import and share references. With this module, Drupal can provide inline citations for blog posts and automatically compile formatted bibliographies. It also provides all those cool links to Google Scholar and other online sources. 



One more sed script to replace some macros, and I had all my BibTeX database ready to upload. 



But that didn't solve my problems with data input. I found that CiteULike could take on this task pretty well. The site automatically scrapes bibliography information from the websites of journals. Increasingly, everything with a Digital Object Identifier link has some way for CiteULike to get its information --- even many edited volumes. 



I've tried CiteULike and many other bibliographic tools in the past. I know that other folks like Zotero, or Papers, or Mendeley, or RefWorks, or CiteSeerX. I've tried them all -- every few months I've given them another look to see if they've reached that critical point where they're useful. I never had much luck. There was always some snag keeping me from getting back value for the effort I put in.  



I can't say whether CiteULike is the best of them today, but it did what I needed done -- crucially, <i>accurate</i> BibTeX import of my whole reference file, including citation keys, easy setting citation keys for new references, and bulk export so I can update both my local file and Drupal without extra typing. Plus, the recommendation list is really useful. 





<h4>Final thoughts</h4>



Most of the database is also available under <a href="http://www.citeulike.org/user/hawksjohnd">my CiteULike profile</a>, so if you're a user of that service, you may find that useful. It's more searchable in some respects, less so in others. CiteULike also offers <a href="http://www.citeulike.org/rss/user/hawksjohnd">a feed of my new entries</a>, which run with abstracts. It's like a whole abstracts blog!



Meanwhile, I'll be filling in references very quickly for the next few months. It remains a work in progress, especially as I continue to merge blog citations with the database. If you find it useful, please drop me a note so I'll know how you're using it!



