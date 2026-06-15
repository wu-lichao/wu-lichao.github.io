---
layout: default
title: "Service"
permalink: /service/
---

<section class="section" markdown="1">

# Service & activities

## Service

<ul class="timeline">
{% assign services = site.data.service | where: "type", "service" %}
{% for item in services %}
<li><span class="when">{{ item.date | replace: "-", "." }}</span><span>{{ item.text | markdownify | remove: "<p>" | remove: "</p>" }}</span></li>
{% endfor %}
</ul>

## Activities

<ul class="timeline">
{% assign activities = site.data.service | where: "type", "activity" %}
{% for item in activities %}
<li><span class="when">{{ item.date | replace: "-", "." }}</span><span>{{ item.text | markdownify | remove: "<p>" | remove: "</p>" }}</span></li>
{% endfor %}
</ul>

</section>
