---
layout: default
title: "Service"
permalink: /service/
---

<section class="section" markdown="1">

# Service & activities

## Service
{% assign services = site.data.service | where: "type", "service" %}
{% for item in services %}
*[{{ item.date | replace: "-", "." }}]* {{ item.text }}
{% endfor %}

## Activities
{% assign activities = site.data.service | where: "type", "activity" %}
{% for item in activities %}
*[{{ item.date | replace: "-", "." }}]* {{ item.text }}
{% endfor %}

</section>
