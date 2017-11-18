---
layout: post
title:  "Static site generators"
date:   2017-11-18 11:00:00 +0100
categories: answers school
comments: true
---

# Static site generators
There are something rather compelling with static site generators (SSG). You can really leverage SSGs to create something that looks good and easily updates. However there is some set-up time to it and the experience has not been completely satisfactory to say the least. For some reason most SSGs seems to be dependent on ruby and it has not been without issues working with Jekyll on a Windows machine. Although this issue might be more of a Docker-issue  

## Static or not
As the name static site generators (SSG) imply they generate a static site. Static sites might lack some of the more impressive dynamic parts but there are some serious upsides to the equation. 

A website that is static is easier to develop as there are few(er) movable parts and it has better performance as each page is pre-chached and there are no database queries or processing for each site request. 

Adding, updating and changing the site is quite easy as modern SSGs provide support for
**Partials** - enabling making changes in only one partial, e.g. the header, which is then added to each page that uses that partial without having to make changes to each page.
**Layouts** - enabling different html layouts for different parts of the site or even on different part of a site. Change a layout file and those changes will propagate to each page where it is use when the site is deployed. 
**Content** - Content is provided as individual files rather than stored in some database somewhere.

Security is also a strong suit of static sites. As a static site has very little, if any, server-side functionality the number of attack surfaces are very few.

As with any tool there are of course downsides to SSGs.  SSGs are not suitable for sites that update to often or that has real-time updates. Also if the site is large enough build times actually might become an issue. 
  
Also although there are some functionality that is server-side that can be added to static sites, see Disqus for example, the amount of such functionality is severely limited. This can be worked around but then the main points of a static site are lost. 
