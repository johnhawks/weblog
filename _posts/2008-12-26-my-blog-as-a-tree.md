---
layout: single 
title: "My blog as a tree" 
category: story
permalink: /weblog/site/hawks-blog-as-tree-2008.html
comments: false 
author: John Hawks 
---

I clicked on <a href="http://www.aharef.info/static/htmlgraph/?url=http%3A%2F%2Fjohnhawks.net%2Fweblog">Webpages as Graphics</a> (via <a href="http://sandwalk.blogspot.com/2008/12/webpages-as-graphics-for-sandwalk.html">Sandwalk</a>), which is a Java applet that renders the HTML tags of a website as a tree. 

If you haven't written any HTML from scratch, you may not be aware that a webpage has a treelike structure. The text and images of a page are encased in a &lt;body&gt; tag; the body itself may be <i>divided</i> into several &lt;div&gt; elements; each may contain many &lt;p&gt; (paragraph) elements and/or &lt;img&gt; (image), &lt;table&gt; (table) or &lt;ul&gt; (bullet list) elements. A paragraph will often contain links (&lt;a&gt;), italics (&lt;i&gt;) or other modifiers. Each element is contained in a higher-level element, up to the entire page. 

So the "Webpages as Graphics" applet renders a webpage as a tree. Here's mine: 

<div class="middle-picture">
<img src="/graphics/hawks-blog-as-tree.png" width="600" height="600" alt="Hawks blog as a tree" />
</div>

<p class="caption">Hawks blog as tree. Key: green=div; orange=p; blue=a; purple=img; yellow=form elements; gray=all others (mostly i and b)</p>

OK, so what is this? The big cluster at bottom left is the series of posts on the front page of the blog. Each post is a little cluster rooted on a div tag, with a varying number of orange p tags inside. Every post has at least one blue link, but most have several. There are few pictures. There is one small stem jutting toward the upper right that has a picture, that's the footer of the page. 

The looser cluster at the upper right includes the right and left sidebars. The flowery structure at the extreme right is the blogroll, ordered into several lists, each with a link. The dense cluster of blue links is the tag cloud; the more diffuse pom with the gray center is the recent posts list. The purply umbel toward the left of this cluster is the Amazon zone. And the dangly vine with the yellow form tags is the search box. 

So that's it. I think it's a nice way to look at a website and learn how it's put together. You can see that my daily writing consists of small clusters of tags containing text. The big clusters of links are separated from the daily (and changing) content, connected only by being contained on the same page. 

Try it with a few sites -- the app takes a little while to optimize the spacing between links, but it's fascinating to watch it. For an extremely simple tree, try <a href="http://www.aharef.info/static/htmlgraph/?url=http%3A%2F%2Fgoogle.com">the map of Google's homepage</a>. <a href="http://www.aharef.info/static/htmlgraph/?url=http%3A%2F%2Fscienceblogs.com">Scienceblogs</a> is rather more complicated, with a big dandelion. 

