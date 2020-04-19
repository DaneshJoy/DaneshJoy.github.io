---
permalink: /matlab/from_zero
title: " آموزش متلب از صفر "
excerpt: "matlab from Zero"
sitemap: true
comments: on
tags:
    - متلب
    - پردازش سیگنال
    - پردازش تصویر
    - هوش مصنوعی
    - آموزش
---

**کدهای کلاس آموزش متلب از صفر**

## دانلود کدها
- صفحه گیتهاب کدها: <a  href="http://github.com/DaneshJoy/matlab_from_zero" target="_blank"><img src="{{ '/assets/images/github.png' | relative_url }}" width="30px" title="Matlab_from_Zero on Github" alt="Matlab_from_Zero on Github"></a><br/>
- دانلود مستقیم کدها: <a  href="https://github.com/DaneshJoy/matlab_from_zero/archive/master.zip"><img src="{{ '/assets/images/download.png' | relative_url }}" width="40px" title="دانلود" alt="دانلود"></a><br/>

-------------------------------------
## فهرست مطالب
-------------------------------------

## جلسه 1
- **معرفی متلب، مزایا و معایب**
- **آشنایی با محیط و امکانات متلب**
- **انواع متغیرها (integer / double / char / logical)**
- &#x202b; **ساخت و نمایش بردارها و سیگنال ها (مقدماتی)**
- &#x202b; **کدنویسی در فایل (script) و قواعد نام گذاری**
- **دستورات**
```
clear / clc / sin / cos / tan / plot / logo
```

## لینک ویدیوهای جلسه 1

| **موضوع** | **یوتیوب** | **آپارت** |
| 1-1- چرا متلب | <a href="https://youtu.be/b927dRAXwNY" target="_blank"><img src="{{ '/assets/images/youtube.png' | relative_url }}" width="30px" title="یوتیوب" alt="یوتیوب"></a> | <a href="https://www.aparat.com/v/Am63Y" target="_blank"><img src="{{ '/assets/images/aparat.png' | relative_url }}" width="30px" title="اپارات" alt="اپارات"></a> |
| قسمت 1: فرمت های مرسوم تصاویر پزشکی | <a href="https://youtu.be/JTSoTTFx1CE" target="_blank"><img src="{{ '/assets/images/youtube.png' | relative_url }}" width="30px" title="یوتیوب" alt="یوتیوب"></a> | <a href="http://aparat.com/v/68AKo" target="_blank"><img src="{{ '/assets/images/aparat.png' | relative_url }}" width="30px" title="اپارات" alt="اپارات"></a> |
| قسمت 2: صفحه ها و جهت های آناتومیکی | <a href="https://youtu.be/WHgDRzEVgMQ" target="_blank"><img src="{{ '/assets/images/youtube.png' | relative_url }}" width="30px" title="یوتیوب" alt="یوتیوب"></a> | <a href="http://aparat.com/v/4HMFO" target="_blank"><img src="{{ '/assets/images/aparat.png' | relative_url }}" width="30px" title="اپارات" alt="اپارات"></a> |
| قسمت 3: نحوه اضافه کردن تولباکس ها به متلب | <a href="https://youtu.be/plIgjus59gM" target="_blank"><img src="{{ '/assets/images/youtube.png' | relative_url }}" width="30px" title="یوتیوب" alt="یوتیوب"></a> | <a href="http://aparat.com/v/p3V2t" target="_blank"><img src="{{ '/assets/images/aparat.png' | relative_url }}" width="30px" title="اپارات" alt="اپارات"></a> |
| قسمت 4: نحوه استفاده از تولباکس های معرفی شده | <a href="https://youtu.be/ZQbXGj571ng" target="_blank"><img src="{{ '/assets/images/youtube.png' | relative_url }}" width="30px" title="یوتیوب" alt="یوتیوب"></a> | <a href="http://aparat.com/v/NvdKb" target="_blank"><img src="{{ '/assets/images/aparat.png' | relative_url }}" width="30px" title="اپارات" alt="اپارات"></a> |
| قسمت 5: خواندن تصاویر Meta یا MHD و نحوه نمایش تصاویر | <a href="https://youtu.be/3-BFaQU2zjQ" target="_blank"><img src="{{ '/assets/images/youtube.png' | relative_url }}" width="30px" title="یوتیوب" alt="یوتیوب"></a> | <a href="http://aparat.com/v/c03zb" target="_blank"><img src="{{ '/assets/images/aparat.png' | relative_url }}" width="30px" title="اپارات" alt="اپارات"></a> |


--------------------------
## جلسه 2
- &#x202b;**ساخت سیگنال سینوسی (بر اساس رادیان یا فرکانس)**
- **رسم سیگنال (plot و subplot)**
- **&#x202b;تعامل با کاربر (گرفتن ورودی از کاربر)**
- **معرفی نویز**
- **دستورات**
```
subplot / input / rand / randn / num2str / figure
```

--------------------------
## جلسه 3
- &#x202b; **رسم سیگنال ها (بر روی هم)**
- **استفاده از تابع**
- **برنامه محاسبه BMI**
- **دستورات**
```
hold on / mean / function / sum / length / numel / close all / if / elseif / else / str2double / inputdlg / helpdlg / warndlg / errordlg / msgbox / beep / fprintf / sprintf
```
--------------------------
## جلسه 4
- **خواندن و نمایش تصاویر**
- **بهبود کیفیت تصاویر**
- **ذخیره تصاویر**
- **حذف نویز**
- **دستورات**
```
imread / imshow / image / imagesc / montage / imshowpair / im2double /  mat2gray / rgb2gray / imcomplement / imreducehaze / imwrite / imhist / histeq / adapthisteq / imnoise / medfilt2 / wiener2
```

--------------------------
## جلسه 5
- **حل معادلات چند جمله ای**
- **حل چند معادله و چند متغیر**
- **حلقه ها (for و while)**
- **Pre-Allocation مقدار دهی متغیرها از ابتدا**
- **دستورات**
```
solve / root / roots / poly / ezplot / vpa / dsolve / integral / for / while
```

--------------------------
## جلسه 6
- **تشخیص چهره در تصاویر**
- **نمایش مستطیل و متن بر روی تصاویر**
- **استفاده از وب کم برای گرفتن تصویر**
- **تشخیص اشیا با هوش مصنوعی (Deep Learning)**
- **حذف نویز با هوش مصنوعی (Deep Learning)**
- **دستورات**
```
uigetfile / fullfile / vision.CascadeObjectDetector / rectangle / text / insertObjectAnnotation / webcam / preview / snapshot / questdlg / alexnet / imresize / classify / denoisingNetwork / denoiseImage / cat
```

-------------------------------------

## لینک ویدیوهای آموزشی برای هر کد

-------------------------------------

در حال حاضر ویدیوهای این دوره در دسترس نیستند!

-------------------------------------

<p align="center">
  <a href="https://daneshjoy.ir">
    <img src="{{ '/assets/images/DaneshJoy.png' | relative_url }}" width="300px" title="DaneshJoy" alt="DaneshJoy"> 
  </a>
</p>

<div class="well">
<div class="rw-ui-container"></div>
</div>

