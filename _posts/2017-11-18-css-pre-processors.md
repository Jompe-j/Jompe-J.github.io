---
layout: post
title:  "CSS and CSS pre-processors"
date:   2017-11-18 10:10:00 +0100
categories: answers school
comments: true
---
## CSS - To pre-compile or not to precompile
From a beginners point of view I’m not sure I have experienced the full capability, and benefits of pre-compiled CSS compared to regular CSS. With that stated I can absolutely see the benefits of the extended functionality of CSS Preprocessors especially as projects grow in complexity.

### Techniques used on this site
I have based the style of the page on the default minima theme from Jekyll and adopted it somewhat to suit my own taste. As such there are far more utilization of the Sass-capabilites than I can credit myself but to make my own mark on the site I adopted the following techniques:

**Nesting** - Really enjoyed the visual aspect of nesting in Sass. It’s cleaner and less code to write and much easier to see how it is supposed to work. Also being able to add a pseudo-class to a parent selector using the ‘&’ ensures readability and adopts the DRY-principle.

**Variables** -Although they are now available in regular CSS I hadn’t used variables before and now it seems crazy that they weren't always available. Making changes to the overall look and feel has never been simpler with variables. And as with nesting it really adopts DRY.

**Mixins** - Although they can be “only” blocks of CSS to be reused they can also be passed arguments which extends the functionality a lot. 

### The Good and the bad
For small projects such as this I’m not entirely convinced that having to work with another tool really is beneficial on the whole. But as a project increases in size and complexity I can see that better structure and organisation of code soon can outweigh the drawbacks. Pre-compiled CSS is just another tool in the toolbox and as with any tool the important part is to know when to use it.

As mentioned above the possibility to re-use and structure code is of great benefits to any code project and therefore Sass offers much more than regular CSS. A good structure and use of nesting ensures readability and makes the code easier to maintain. Reusable parts further extends the maintainability of the code. 

Some possible drawbacks is that it is another tool to learn and adopting a good structure is not without its cost in time. It is also not entirely easy to debug as issues from the browser debugger points to the compiled CSS-file. Of Course there are ways to handle this but that is another tool to learn and maintain.   
