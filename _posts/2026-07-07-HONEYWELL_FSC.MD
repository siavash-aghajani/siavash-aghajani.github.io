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

# FLD(functional logic diagram)
هر صفحه  به 4 بخش تقسیم میشود:
*	بخش اطلاعات(قسمت پایین) information area
شامل اطلاعاتی مانند تاریخ، نام واحد، نوع بلاک و... است. در حالت عادی به کاربر نشان داده نمیشود ولی هنگام پرینت گرفتن FLD، در پایین نقشه اضافه میشود.
*	بخش ورودی(قسمت چپ) input area
بخش ورودی شامل تمام متغیر های است که به عنوان ورودی به بخش کنترل وارد می‌شوند.
*	بخش کنترل(قسمت وسط) control function area
بخش کنترلی با وصل کردن سیمبل های از پیش تعریف شده، طیف گسترده ای از توابع منطقی، عددی و زمان محور را میسازد.
*	بخش خروجی(قسمت راست) output area 
نتیجه و خروجی بخش کنترلی به بخش خروجی میرود. این متغیرها میتوانند باعث روشن شدن تجهیز در سایت شود یا به تجهیز کامپیوتری دیگری فرستاده شوند. 

