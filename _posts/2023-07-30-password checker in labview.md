---
layout: post
title: "password checker in labview"
description: ""
categories: [labview]
tags: [labview]
redirect_from:
  - /2023/07/30/
---
* Kramdown table of contents
{:toc .toc}

This is a [link]([https://github.com/siavash-aghajani/password-checker-labview]) for downloading files and exe file.

<a class="post-image" href="/assets/images/posts/pass_front.png">
<img itemprop="image" data-src="/assets/images/posts/pass_front.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<a class="post-image" href="/assets/images/posts/pass_back.png">
<img itemprop="image" data-src="/assets/images/posts/pass_back.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>


## details

* default password is 1234
* for building passwords, I concatenate numbers( of course I turned them to string(why?[^1])
* I used cluster to avoid having a messy program.
* You'll need to pay attention to the index of buttons in cluster for using in case structure.
  *<a class="post-image" href="/assets/images/posts/pass_front2.png">
<img itemprop="image" data-src="/assets/images/posts/pass_front2.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>





[^1]: becuase we use button and the default output is string.
