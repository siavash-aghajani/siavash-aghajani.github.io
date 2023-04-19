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

## how it works?
> its obvious! 
> S=1 and R=0 mean that we set 1 on the output.
> S=0 and R=1 mean that we reset the output.
> S=R=0 means that output will not change.

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

## how it works?
> this flip flop put input on output directly.


# Jk FF (Jump kill Flip Flop)

* characteristic Table

    |--
    | j | k | Q(t+1) 
    |:-:|:-:|:-:
    | 0 | 0 | Q(t)
    | 0 | 1 | 0
    | 1 | 0 | 1 
    | 1 | 1 | Q **'**(t) 

## how it works?
> its really simple.
> j=1 and k=0 mean that output will jump on 1.
> j=0 and k=1 mean that output quantity will be killed.
> j=k=0 means that output will not change.
> j=k=1 means that output will be toggled.
>



# TFF (Toggle Flip Flop)

* characteristic Table

    |-
    | T| Q(t+1) 
    |:-:|:-:
    | 0 | Q(t) 
    | 1 | Q **'**(t) 

## how it works?
> if input is T=0, output will not change.
> if input is T=1, output will be toggle( zero to one and vice versa).
  

