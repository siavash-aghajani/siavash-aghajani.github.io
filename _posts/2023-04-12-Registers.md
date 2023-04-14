---
layout: post
title: "Registers"
description: "ALL types of registers"
categories: [digitalsystems]
tags: [digital systems, FPGA, register]
redirect_from:
  - /2023/04/12/
---


* Kramdown table of contents
{:toc .toc}

# SR FF (Set Reset Flip Flop) 

* characteristic Table

    |--
    | S| R | Q(t+1) 
    |:-:|:-:|:-:
    | 0 | 0 | Q(t) 
    | 0 | 1 | 0 
    | 1 | 0 | 1  
    | 1 | 1 | unvalid 
    
## note
> if we set S=R=1, then both of Q and Q' would be 0, which is unvalid.(these two outputs should be complement of each other.)
<a class="post-image" href="/assets/images/posts/nor.jpg">
<img itemprop="image" data-src="/assets/images/posts/nor.jpg" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

  


# D FF (Data Flip Flop)

* characteristic Table

    |-
    | D | Q(t+1) 
    |:-:|:-:
    | 0 | 0 
    | 1 | 1 
  
# Jk FF (Jump kill Flip Flop)

* characteristic Table

    |--
    | j | k | Q(t+1) 
    |:-:|:-:|:-:
    | 0 | 0 | Q(t) 
    | 0 | 1 | 0
    | 1 | 0 | 1 
    | 1 | 1 | Q **'**(t) 
  
# TFF (Toggle Flip Flop)

* characteristic Table

    |-
    | T| Q(t+1) 
    |:-:|:-:
    | 0 | Q(t) 
    | 1 | Q **'**(t) 
  

