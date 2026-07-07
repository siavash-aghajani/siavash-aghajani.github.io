---
layout: post
title: "HONEYWELL FSC"
description: "آموزش نقشه خوانی FSC"
categories: [HONEYWELL]
tags: [FSC, HONEYWELL]
redirect_from:
  - /2026/07/07/
---

* Kramdown table of contents
{:toc .toc}

<div dir="rtl"> 
# FLD(functional logic diagram)
</div>
<div dir="rtl"> 
هر صفحه  به 4 بخش تقسیم میشود:
</div>
<div dir="rtl"> 
*	بخش اطلاعات(قسمت پایین) information area
</div>
<div dir="rtl"> 
شامل اطلاعاتی مانند تاریخ، نام واحد، نوع بلاک و... است. در حالت عادی به کاربر نشان داده نمیشود ولی هنگام پرینت گرفتن FLD، در پایین نقشه اضافه میشود.
</div>
<div dir="rtl"> 
*	بخش ورودی(قسمت چپ) input area
</div>
<div dir="rtl"> 
بخش ورودی شامل تمام متغیر های است که به عنوان ورودی به بخش کنترل وارد می‌شوند.
</div>
<div dir="rtl"> 
*	بخش کنترل(قسمت وسط) control function area
</div>
<div dir="rtl"> 
بخش کنترلی با وصل کردن سیمبل های از پیش تعریف شده، طیف گسترده ای از توابع منطقی، عددی و زمان محور را میسازد.
</div>
<div dir="rtl"> 
*	بخش خروجی(قسمت راست) output area 
<div dir="rtl"> 
</div>
نتیجه و خروجی بخش کنترلی به بخش خروجی میرود. این متغیرها میتوانند باعث روشن شدن تجهیز در سایت شود یا به تجهیز کامپیوتری دیگری فرستاده شوند. 
</div>

<a class="post-image" href="/assets/images/posts/Picture1.png">
<img itemprop="image" data-src="/assets/images/posts/Picture1.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>
. 

<div dir="rtl"> 
# FLD symbols
</div>
<div dir="rtl"> 
## basic sheet symbol
</div>
<div dir="rtl"> 
سه بخش دارد و هنگام ساخت FLD  در نرم افزار به طور خودکار ساخته میشود.
</div>

<a class="post-image" href="/assets/images/posts/Picture2.png">
<img itemprop="image" data-src="/assets/images/posts/Picture2.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
## Connection line
</div>


<div dir="rtl"> 
تک خط برای سیگنال boolean و دو خط برای سیگنال باینری است.
</div>
<div dir="rtl"> 
خط ضخیم سیگنال آنالوگ استفاده می‌شود.
</div>

<a class="post-image" href="/assets/images/posts/Picture3.png">
<img itemprop="image" data-src="/assets/images/posts/Picture3.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>
<div dir="rtl"> 
اگر دو خط از هم عبور کنند و یکی از آنها به دو خط تقسیم شود، خط ها به هم وصل نیستند. اگر دو خط از هم عبور کنند یعنی به هم وصلند.
</div>

<a class="post-image" href="/assets/images/posts/Picture4.png">
<img itemprop="image" data-src="/assets/images/posts/Picture4.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<a class="post-image" href="/assets/images/posts/Picture6.png">
<img itemprop="image" data-src="/assets/images/posts/Picture6.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
# LOGIC functions
</div>
<div dir="rtl"> 
شامل گیت های AND, OR و inverter است.
</div>

<a class="post-image" href="/assets/images/posts/Picture7.png">
<img itemprop="image" data-src="/assets/images/posts/Picture7.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<a class="post-image" href="/assets/images/posts/Picture8.png">
<img itemprop="image" data-src="/assets/images/posts/Picture8.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<a class="post-image" href="/assets/images/posts/Picture9.png">
<img itemprop="image" data-src="/assets/images/posts/Picture9.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<a class="post-image" href="/assets/images/posts/Picture10.png">
<img itemprop="image" data-src="/assets/images/posts/Picture10.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
# registers and counters
</div>
<div dir="rtl"> 
فقط بخش کانتر مورد نیاز است. کانتر برای توابع شمارشی استفاده میشود. اگر کانار به ماکزیمم مقدار خود برسد، خروجی f برابر یک میشود.
</div>
<div dir="rtl"> 
اگر کانتر به مقدار MAX+1 برسد، بصورت خودکار به مقدار 0 ریست میشود.
</div>
<div dir="rtl"> 
قسمت CU CD حساس به لبه (بالارونده) است.
</div>

<a class="post-image" href="/assets/images/posts/Picture11.png">
<img itemprop="image" data-src="/assets/images/posts/Picture11.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
# Flip flop
</div>
<div dir="rtl"> 
شامل فلیپ فلاپ S-R و R-S است.خط تیره ورودی با اهمیت تر(dominant) را هنگامی که دو ورودی همزمان تحریک شده باشند، نشان میدهد.
</div>
<div dir="rtl"> 
هر دو ورودی ست و ریست باید وصل شده باشند و حداقل از یکی از خروجی ها باید استفاده شود.
</div>


<a class="post-image" href="/assets/images/posts/Picture22.png">
<img itemprop="image" data-src="/assets/images/posts/Picture22.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<a class="post-image" href="/assets/images/posts/Picture12.png">
<img itemprop="image" data-src="/assets/images/posts/Picture12.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
# Constants and signal conversions
</div>
<div dir="rtl"> 
فقط سیمبل constant از این بخش مورد نیاز است. قسمت چپ نوع متغیر و قسمت راست مقدار آنرا مشخص میکند.
</div>


<a class="post-image" href="/assets/images/posts/Picture13.png">
<img itemprop="image" data-src="/assets/images/posts/Picture13.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
# Time functions
</div>
<div dir="rtl"> 
## PULSE
</div>
<div dir="rtl"> 
این فانکشن برای ساختن پالس استفاده می‌شود.
</div>
<div dir="rtl"> 
هنگامی که پالس ساخته میشود.، ورودی a باید دوباره صفر شود تا پالس جدید ساخته شود.
</div>

<a class="post-image" href="/assets/images/posts/Picture14.png">
<img itemprop="image" data-src="/assets/images/posts/Picture14.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
## Delayed on timer
</div>
<div dir="rtl"> 
هنگامی که لبه بالارونده به ورودی S وارد شود ، بعد از t ثانیه تایمر روشن میشود.
</div>
<div dir="rtl"> 
اگر یک خط به ان وصل شدبه عنوان ورودی استارت در نظر  میگیرد. 
</div>

<a class="post-image" href="/assets/images/posts/Picture15.png">
<img itemprop="image" data-src="/assets/images/posts/Picture15.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>


<div dir="rtl"> 
# IO symbols
</div>
<div dir="rtl"> 
سیگنالهای ورودی خروجی دیجیتال به شرح زیر است:
</div>
<div dir="rtl"> 
*	Digital input
</div>
<div dir="rtl"> 
*	Digital output
</div>
<div dir="rtl"> 


## Digital input
</div>
<div dir="rtl"> 
یک سیگنال بولین که مثلا برای  ZSL ولو به کار رود.
</div>

<a class="post-image" href="/assets/images/posts/Picture16.png">
<img itemprop="image" data-src="/assets/images/posts/Picture16.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
## Digital output
</div>
<div dir="rtl"> 
یک سیگنال بولین که مثلا برای استارت استاپ میتواند به کار رود.
</div>


<a class="post-image" href="/assets/images/posts/Picture17.png">
<img itemprop="image" data-src="/assets/images/posts/Picture17.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>


<div dir="rtl"> 
# Sheet transfers
</div>
<div dir="rtl"> 
اگر نتواتیم یک تابع را در یک FLD طراحی کنیم، از SHEET TRANSFER استفاده میکنیم. داده ها میتوانند بین FLD ها از طریق SHEET TRANSFER FUNCTION منتقل شوند.
</div>
<div dir="rtl"> 
این ویژگی میتواند به ساختن فانکشن های پیچیده و ساختار یافته با چندین دیاگرام کمک کند. این تابع از یک دایره شامل  اطلاعاتی درباره source FLD (قسمت بالا) وdestination  FLD (قسمت پایین) تشکیل شده است.
</div>
<div dir="rtl"> 
ممکن است بین دو FLD چند sheet transfer باشد. برای موقعیت یابی صحیح شیت ترنسفر مورد نظر، یک عدد منحصربه فرد (tag number) در پایین هر شیت ترنسفر قرار داده شده است. 
</div>

<div dir="rtl"> 
## Boolean on-sheet transfer
</div>

<a class="post-image" href="/assets/images/posts/Picture18.png">
<img itemprop="image" data-src="/assets/images/posts/Picture18.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
## On-sheet transfer for repeated digital input
</div>

<a class="post-image" href="/assets/images/posts/Picture19.png">
<img itemprop="image" data-src="/assets/images/posts/Picture19.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

<div dir="rtl"> 
## Boolean off-sheet transfer
</div>
<a class="post-image" href="/assets/images/posts/Picture20.png">
<img itemprop="image" data-src="/assets/images/posts/Picture20.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>
<div dir="rtl"> 
## multiple Boolean off-sheet transfer
</div>
<div dir="rtl"> 
چون چند ترنسفر داریم باید مقصد ها ذکر شود.(حداکثر 5 تا)
</div>
<a class="post-image" href="/assets/images/posts/Picture21.png">
<img itemprop="image" data-src="/assets/images/posts/Picture21.png" src="/assets/javascripts/unveil/loader.gif" alt="Kramdown Overview" />
</a>

