---
layout: post
title:  "Open graph, robots and humans"
date:   2017-11-18 11:15:00 +0100
categories: answers school
comments: true
---

## OPEN GRAPH, ROBOTS and HUMANS

### OPEN GRAPH
Open graph (OG) is a protocol, originating from Facebook, that gives a representation of a website when it is shared on the web. The protocol is implemented basically through adding meta tags with OG properties in the head of the webpage. This site use the required tags of title, type, image and url. It also uses the  site_name property. An If-statement is used in my implementation to check if a specific page has a title or not in order to ensure correct title and url.

### Robots.txt
Robots.txt is a file added to the root of a site to provide instructions for web robots on what parts of your site not to index. These instructions can however be ignored by the robots and cannot be used to hide information. 

The instructions are called the Robots Exclusion Protocol and as the name states it provides instructions on what part of a website that should excluded from one, more or all web robots that follows the protocol.

In my implementation I choose to exclude the blog-posts from all robots. I do not mind having a public site but have no real wish for my thoughts to be spread further than necessary.

### Humans.txt
The Humans.txt initiative was started to provide, in a non-invasive way, information on what people are behind a website. This file is also, as the robots.txt, places in the site root.

I choose the basic implementation of just placing the humans.txt in the site root. Beyond that I only added the link-tag in the head of my site. 
