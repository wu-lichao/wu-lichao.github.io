---
layout: default
title: "Teaching"
permalink: /teaching/
---

<section class="card" markdown="1">

# Teaching

{% for course in site.teaching %}
## {{ course.title }}
*{{ course.type }}, {{ course.venue }}, {{ course.location }} — {{ course.date | date: "%B %Y" }}*

{{ course.content | markdownify }}
{% endfor %}

</section>
