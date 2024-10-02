---
title: About this
date: 2024-09-30
tags: simple-blog-gen, about-me, kartik-mudgal
description: a small explanation about this site
---

Hi, I'm Kartik Mudgal. 

I just had fun having claude generate code to pass test-cases, and this blog generator
is the result. 

Next step, I have it generate a static-site generator in a language I do not know, 
and see if it passes the test-cases my own generator already does

[source-code](www.github.com/sprinting/simple-blog-gen) may be found here. comes with support for tagging, sorting, and grouping posts and a simple theme selector. 

tags are cosmetic - since the webapp is generated entirely client side, indexing or permalinking is not supported.

should be fairly easy to implement, if you want to, but please use an actual blog generator if you want to practically use it

there is no backend - the app fetches files directly via an unauthenticated github api call, so you _will_ run into rate limits if you try 
to actually serve your blog with this.
