---
layout: single 
title: "A new look for the site" 
category: story
permalink: /weblog/site/a-new-look-for-the-site-2013.html
description: "New demand and open science initiatives send me to a new server and blogging platform."
tags: [site] 
comments: false 
author: John Hawks 
---

Two things have always driven my writing online. 

One is the desire to share with a broader public the exciting work that is changing the way we understand human origins. I worked very hard to find ways to do this with traditional websites during the late 1990's and early 2000's. Blogging software solved my problem: it gave me a way to write incrementally, making my notes into a way to share with everyone. 

The other is my secret love of hacking. I find it so appealing to tinker with a new programming system to see how it works. I began with HTML 3 in the mid-90's, moved to CSS/HTML 4 in the early 2000's, worked with early blogging systems built on Perl scripts, experimented with database-driven stacks and transitioned to a fully MySQL-PHP-based system with Drupal. In the process I have programmed the back-end to research sites, designed three different public-facing websites and three different web systems for students. 

Even though I love to tinker with the site, I wouldn't have undertaken a complete overhaul right now without some very compelling reasons. 

Let me tell you, having my mom not able to get through to the server was pretty compelling. 

The site has greatly increased in popularity over the last several months. Daily usage has grown by nearly 50%. Peak demand for the site has scaled even higher. Obviously my upcoming course, <a href="https://www.coursera.org/course/humanevolution">Human Evolution Past and Future</a> has driven a lot of interest, with an enrollment of more than 28,000. Last month's <a href="{{ site.url }}/tag/Rising%20Star.html">Rising Star Expedition</a> also brought in many new readers. I am so pleased at the people who are finding new information about the science of paleoanthropology here! I'm even more excited that our long work preparing open science projects has begun to make a real impact on how we do paleoanthropology in the field. 

Drupal 7 has been very flexible, allowing me to design a unique structure and layout for the site. But it's a memory hog. Even with advanced caching on the server, the site was not able to keep up with peak demand. As the server began to drop connections, people weren't able to get through. Even after shifting my Rising Star posts off the site, new readers looking for information about the Sima de los Huesos DNA results brought the site to a standstill. 

Ironically, technology has allowed me to go back to the solution that I first implemented in 1996: plain static pages.

When I started this blog in 2004, I relied on a scripting system to take plain text files and template them as a blog. That system, Blosxom, worked extraordinarily well for me for a long time, but couldn't handle the demand of an increasingly large site. I didn't want to abandon it, but with nearly 2000 posts and a readership growing toward 3500 visits a day, I had to make a change. The next stage was a huge advance in content and performance, but left some compromises that have really started to show this year.

Static blog solutions have really evolved during the past five years. Jekyll is a Ruby-based system that takes plain text files, combines them with templates, and presents them as a blog. The site itself is now static, so it's limited only by download speeds, not database performance. Unlike the systems of ten years ago, Javascript and CSS now allow a responsive site layout and dynamic elements in a static site. 

I've done a bit of a facelift for the site. I've taken the mobile-first layout to the next level with a theme that works seamlessly from phone browser to desktop. The sidebar is entirely gone, and I for one don't miss it. 

Well, maybe I'll miss some Amazon referrals. I've put the Amazon link down at the bottom of the page, and you can still support the site with 6% of all purchases without any additional cost to you. I do rely on the funds to maintain my server, but I will be moving to a different strategy to maintain the site during the next few months.



<h4>What's not working yet?</h4>

My transition to the new system has left some strings untied. 

The bibliography system will require a separate solution instead of being integrated live. For the moment older posts are missing bibliography data. As I transition to the new bibliography system I will be scripting the citations back in. 

Tags and search are up and working, but both are a bit unwieldy because of the size of the archives. I'll be working to increase the value of the sitemap and curating content for use outside the site. 

I have not retained the old links for tag pages, in favor of establishing a clear new organization. If you've been following tag feeds, these will not work now. 

Moving the posts from the database has introduced errors in some of the content quoted from other sources -- basically, losing some smart quotes and apostrophes that were not encoded for HTML. Those glitches have a pretty low priority for me, but I'll probably fix them.

Undoubtedly some other things are broken but many, many more old problems have been fixed!


<h4>What's coming?</h4>

The new layout enables me to feature more of my field photography, and I'll be adding more and more graphical elements back into some of the older material. I will also be updating some of the posts that are long-term traffic magnets, evolving the site into a more useful resource for students and researchers. 

The next project to unfold is the open science component of my massive open online course. One of the key pieces is a system that will send personalized reports to students, presenting their data in direct comparison with the entire course. Another piece is obviously the interviews, field footage and lectures themselves, with associated transcripts. I'll be making all that material available to the public outside the course, and that will affect this site.

Events have really moved fast for me this year. When 2013 began, I expected one of my big accomplishments would be to blog my way through Darwin's <em>Descent of Man</em>. Instead I found myself developing a course for 30,000 students, traveling the world to interview and visit field sites, and spending a month in the field supporting a team as they excavated one of the most significant fossil hominin sites ever discovered. 

A few more surprises await in 2014.
