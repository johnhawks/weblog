---
layout: single 
title: "Medical records, research, and personalized genomics" 
category: story
permalink: /weblog/topics/biotech/testing/health-records-cringely-2009.html
tags: [politics, health, biotech, testing] 
comments: false 
author: John Hawks 
---


I'm reading through Chris Anderson's <a href="http://www.amazon.com/gp/product/1401322905?ie=UTF8&tag=johnhawksanth-20&linkCode=as2&camp=1789&creative=390957&creativeASIN=1401322905"><i>Free</i></a>, and ran across a sidebar on page 104, titled, "How can healthcare software be free?". The answer is by selling data from patient charts with identifying information redacted: 

<blockquote><b>Sell access to your data.</b> Using free software, Pracice Fusion attracts a critical mass of users (doctors) who, in turn, create a growing database of patients. Medical associations conducting research on specific conditions require longitudinal health records for a large set of patients. Depending on the focus of a study ... each patient's anonymized chart could fetch anywhere from $50 to $500. A physician typically sees about 250 patients, so Practice Fusion's first 2,000 clients translates to 500,000 records. </blockquote>

I've pulled this quote because it is relevant to Bob Cringely's current column, <a href="http://www.cringely.com/2009/07/medical-records-r-us/">"Medical Records R Us"</a>. Cringely is a technology writer, and his interest in medical records is that upcoming government action has the opportunity to set standards for anonymized records, which could be integrated into longitudinal research: 

<blockquote>There are lots of advantages to computerizing health records. A couple of years ago I visited the Mayo Clinic in Rochester, Minnesota, to discuss this very issue. Mayo has been in the forefront of digitizing all of its six million patient records. This is a bigger job than most of us realize since it involves not just blood tests and doctors notes but also X-Rays and CAT scans.</blockquote>

<blockquote>Mayo, which was a century ago the first clinic in America to standardize the way it kept records in the first place, is also at the forefront in creative ways to use those records once they are in the system. You see Mayo doesnt have six million patients, they have six million patient records  many of those being records of people long dead. But keeping extensive records of dead people creates a powerful database for statistical testing of possible treatments and even drug interactions. Surely in those six million records there is something similar to this medical mystery we are trying to solve today. And often there is.</blockquote>

<blockquote>Figuring out from an analysis of records that combining drugs A, B, and G sometimes kills people can be good to know.</blockquote>

<blockquote>Mayo is taking the process even further to include DNA data for many patients with the goal of being able to statistically identify genetic trends within the population through records analysis.</blockquote>

Cringely focuses on the government role because of the current health care proposals before Congress. In essence, record-keeping is a problem that requires both technological and governance innovations. As Cringely points out, the general trend of Congressional involvement in health records has been to make this kind of information harder for researchers to use, in the interests of patient privacy. At present, legal requirements for health records protect privacy by limiting access, requiring costly means of data security and extensive gatekeeping. A more effective solution might leave patients free to keep records with doctors or third parties, and free to opt in or out of research or other data sharing. Meanwhile, better anonymity protection would allow researchers to test for genetic or phenotypic associations on samples of hundreds of thousands of individuals while protecting those individuals' privacy. 

I want to concentrate on the impact of genetic information on medical records in the future. Genetics generates much more potential for privacy violation, because people are uniquely identifiable from their genotypes. Strong protections will be necessary, and those strong protections should be based on cryptography or other technological solutions, not mere access restrictions. Meanwhile, a smart records system has a huge potential advantage: An individual record could retrieve disease associations from PubMed, dbSNP or other databases. A record that had been included in a study could update itself with the <i>results</i> of the study. 

As more and more individuals receive their genetic data, it's clear we need some kind of standard format for storage and interchange of the data. Trusting a single company with your data is a bad idea -- what do you do when the company's business plan fails? Will you be left with a CD containing your data in some proprietary format that no other software can read? 

Yet it's also clear that the business models of <i>some</i> testing firms depend on <i>applying the data themselves</i>. The only privacy in such interactions, so far, is only guaranteed by clicking "Agree" on a web form. 

In the future, we'll want to protect our health data, be able to exchange it easily with doctors and others when necessary, provide ways for people to easily participate in research, and do it all while maintaining privacy. Ideally, the research datasets will be openly disseminated for replication and meta-analysis, which means that anonymity protection must be very strong. Possibly, a number of different data formats would be suitable, as long as they have common methods for interchange and update. A totally modular system is even imaginable, with individual records capable of interlinking with many distinct services. Imagine an independent Weight Watchers link that would track weight and BMI readings in a way that you could make accessible to your doctor or nutritionist, <b>but only if you want to</b>. 

Cringely's comments already list many objections to his approach, and there are doubtless many others. But the problem isn't going away -- any intelligent use of genetic data in health diagnosis is going to require some sophisticated AI, applied to heterogenous data that come from many providers. Better if that process can facilitate research and catch important associations itself. 



