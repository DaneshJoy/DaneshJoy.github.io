---
permalink: /python/
title: "کدنویسی در پایتون"
excerpt: "Python"
sitemap: true
comments: on
---

-------------------------------------

<p> &#x202b; فعلا خالیه! </p>

## مطالب مرتبط از وبلاگ

{% assign posts = site.posts | where_exp: "post", "post.tags contains 'پایتون'" %}
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

-------------------------------------

<div class="well">
<div class="rw-ui-container"></div>
</div>