---
layout: default
title: "Publications"
permalink: /publications/
---

<section class="section" markdown="1">

Check my [Google Scholar](https://scholar.google.com/citations?user=1cteIHQAAAAJ&hl=en) for the full and up-to-date list of papers. Selected papers below.

{% assign pubs_by_year = site.data.publications | group_by: "year" %}
{% for group in pubs_by_year %}
## {{ group.name }}

<ul class="pubs">
{% for pub in group.items %}
<li class="pub">
<span class="venue{% if pub.award %} award{% endif %}">{% if pub.venue == "arxiv" %}arXiv{% else %}{{ pub.venue }}{% if pub.award %} — {{ pub.award }}{% endif %}{% endif %}</span>
{%- if pub.link %}<a class="title-paper" href="{{ pub.link }}">{{ pub.title }}</a>{% else %}<span class="title-paper">{{ pub.title }}</span>{% endif -%}
{%- if pub.status %} <span class="status">({{ pub.status }})</span>{% endif %}
<span class="authors">{{ pub.authors | replace: "Lichao Wu", '<span class="me">Lichao Wu</span>' }}.</span>
</li>
{% endfor %}
</ul>
{% endfor %}

</section>
