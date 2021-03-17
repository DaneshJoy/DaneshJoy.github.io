---
permalink: /matlab/
title: "آموزش های کدنویسی در متلب"
excerpt: "Matlab"
sitemap: true
comments: on
feature_row:
  - image_path: /assets/images/matlab_from_zero.png
    alt: "آموزش متلب از صفر"
    title: "&nbsp; آموزش متلب از صفر &nbsp;"
    excerpt: "کار با ماتریس ها و پردازش سیگنال و تصویر مقدماتی<br/>دستورات پر کاربرد، کار با توابع و ...<br/>به روز رسانی: (1399/12/27)"
    url: "/matlab/from_zero"
    btn_class: "btn--info"
    btn_label: "مشاهده دوره"
  - image_path: /assets/images/signal.png
    alt: "پردازش سیگنال دیجیتال در متلب"
    title: "&nbsp; پردازش سیگنال دیجیتال در متلب &nbsp;"
    excerpt: "مشاهده و پردازش سیگنال های دیجیتال و پزشکی<br/>فیلتر، حذف نویز، آنالیز و ...<br/>به روز رسانی: (1398/3/1)"
    url: "/matlab/dsp"
    btn_class: "btn--info"
    btn_label: "مشاهده دوره"
  - image_path: /assets/images/image.png
    alt: "پردازش تصاویر پزشکی در متلب"
    title: "&nbsp; پردازش تصاویر پزشکی در متلب &nbsp;"
    excerpt: "آشنایی و پردازش تصاویر سه بعدی پزشکی<br/>خواندن و نوشتن، بهبود کیفیت و ...<br/>به روز رسانی: (1398/4/1)"
    url: "/matlab/mip"
    btn_class: "btn--info"
    btn_label: "مشاهده دوره"
---

-------------------------------------

{% include feature_row  type="right" %}

## مطالب مرتبط از وبلاگ

{% assign posts = site.posts | where_exp: "post", "post.tags contains 'متلب'" %}
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

-------------------------------------

<div class="well">
<div class="rw-ui-container"></div>
</div>


<!-- <div class="well">

<a href="https://daneshjoy.ir/matlabdsp/" target="_blank" class="btn btn--info btn-lg" role="button"><font size="+2"> پردازش سیگنال دیجیتال در متلب </font></a>

<a href="https://daneshjoy.ir/matlabmip/" target="_blank" class="btn btn--info btn-lg" role="button"><font size="+2"> پردازش تصاویر پزشکی در متلب </font></a>
</div> -->

<!-- <a href="https://daneshjoy.ir/matlabdsp/" target="_blank"> پردازش سیگنال دیجیتال در متلب </a> -->
