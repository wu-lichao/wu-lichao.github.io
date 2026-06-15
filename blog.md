---
layout: default
title: "Blog"
permalink: /blog/
---

<section class="card" markdown="1">

# Blog

{% for post in site.posts %}
## [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}
{% endfor %}

</section>
