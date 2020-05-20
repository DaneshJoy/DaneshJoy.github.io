---
permalink: /ai/
title: "آموزش های هوش مصنوعی و یادگیری عمیق"
excerpt: "Artificial Intelligence, Deep Learning"
sitemap: true
comments: on
feature_row:
  - image_path: /assets/images/deep_intro.png
    alt: "آموزش یادگیری عمیق (مقدماتی)"
    title: "&nbsp; آموزش یادگیری عمیق (مقدماتی) &nbsp;"
    excerpt: "معرفی یادگیری عمیق و انواع روش های آن<br/>مدل های مختلف، منابع یادگیری و ...<br/>به روز رسانی: (1399/2/30)"
    url: "/ai/deep_intro"
    btn_class: "btn--info"
    btn_label: "مشاهده دوره"
---

-------------------------------------

{% include feature_row  type="right" %}

## مطالب مرتبط از وبلاگ

{% assign posts = site.posts | where_exp: "post", "post.tags contains 'هوش مصنوعی'" %}
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

-------------------------------------


<div class="well">
<div class="rw-ui-container"></div>
</div>
