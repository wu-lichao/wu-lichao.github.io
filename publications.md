---
layout: default
title: "Publications"
permalink: /publications/
---

<section class="section" markdown="1">

# Publications

Check my [Google Scholar](https://scholar.google.com/citations?user=1cteIHQAAAAJ&hl=en) for the full and up-to-date list of papers. Selected papers below, grouped by year.

{% assign pubs_by_year = site.data.publications | group_by: "year" %}
{% for group in pubs_by_year %}
## {{ group.name }}
{% for pub in group.items %}
- {%- if pub.venue == "arxiv" -%}
  [arxiv]
  {%- else -%}
  [**{{ pub.venue }}{% if pub.award %} — {{ pub.award }}{% endif %}**]
  {%- endif -%}
  {%- if pub.link %} [*"{{ pub.title }}"*]({{ pub.link }}){% else %} *"{{ pub.title }}"*{% endif -%}
  {%- if pub.status %} ({{ pub.status }}){% endif -%}
  . {{ pub.authors }}.
{% endfor %}
{% endfor %}

</section>
