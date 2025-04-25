---
layout: post
title: "Categorical data"
description: "what is categorical data?"
categories: [AI]
tags: [classification, regression, AI]
redirect_from:
  - /2024/03/15/
---
* Kramdown table of contents
{:toc .toc}

# what is it?
Categorical data is information that fits into groups, like fruits (apple, banana, orange) or types of books (comic, novel, textbook). In machine learning, many tools need numbers, not words, so we turn categorical data into numbers.

# some solutions
One way is one-hot encoding, where each group gets a column with a 0 or 1. For example, "apple" might be [1, 0, 0], and "banana" [0, 1, 0]. Another way is giving each group a number, like 1 for comic and 2 for novel.
Choosing the right way helps your model work better. Good handling of categorical data makes your answers more accurate.

<a class="post-image" href="/assets/images/posts/ct.jpg">
<img itemprop="image" data-src="/assets/images/posts/ct.jpg" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>
