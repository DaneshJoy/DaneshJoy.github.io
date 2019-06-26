---
permalink: /ai/
title: "آموزش های هوش مصنوعی و یادگیری عمیق"
excerpt: "Artificial Intelligence, Deep Learning"
sitemap: true
comments: off
---

-------------------------------------

<p> &#x202b; فعلا خالیه! </p>


## مطالب مرتبط از وبلاگ

{% assign posts = site.posts | where_exp: "post", "post.tags contains 'هوش مصنوعی'" %}
{% for post in posts %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

-------------------------------------


<div class="well">
<div class="rw-ui-container"></div>
</div>
