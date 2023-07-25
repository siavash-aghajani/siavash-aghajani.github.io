---
layout: post
title: "plot a sin function in labview"
description: "plotting a sin function with high resolution"
categories: [labview]
tags: [labview]
redirect_from:
  - /2023/07/24/
---


# final project

This is [a link](https://github.com/siavash-aghajani/sin_labview) exe and project file.
<a class="post-image" href="/assets/images/posts/sin_front.png">
<img itemprop="image" data-src="/assets/images/posts/sin_front.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>
<a class="post-image" href="/assets/images/posts/sin_back.png">
<img itemprop="image" data-src="https:/assets/images/posts/sin_back.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>
# detaols
* I in for loop builds the x-axis for sin(x).
  * multiplying I with a low double number gives us a high resolution plot.(think why?[^1]) 
* sin in labview uses radian, so I change it to degree.
* delay in for would help us to see the plot.

  [^1]: because the step for x would be smaller, so we have more x (and y) in an area rather than bigger x.


