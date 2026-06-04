---
layout: default
title: Reading Lists
permalink: /reading-lists/
---

<div class="page-intro">
  <p class="eyebrow">Curated Literature</p>
  <h1>Reading Lists</h1>
  <p>Topical paper collections I maintain. <strong>Active</strong> lists grow over time; <strong>archived</strong> lists are snapshots I no longer update.</p>
  <hr class="section-divider" />
</div>

{% assign active = site.reading_lists | where: "status", "active" | sort: "date" | reverse %}
{% assign archived = site.reading_lists | where: "status", "archived" | sort: "date" | reverse %}

<section class="publication-block blog-timeline-block" markdown="1">
## Active
<hr class="section-divider" />

{% if active.size > 0 %}
<div class="blog-timeline">
{% for list in active %}
	<article class="blog-timeline-item">
		<div class="blog-timeline-date">{{ list.date | date: "%Y.%m" }}</div>
		<div class="blog-timeline-card">
			<h3><a href="{{ list.url | relative_url }}">{{ list.title }}</a></h3>
			{% if list.subtitle %}<p>{{ list.subtitle }}</p>{% endif %}
		</div>
	</article>
{% endfor %}
</div>
{% else %}
<p><em>No active reading lists yet.</em></p>
{% endif %}
</section>

<section class="publication-block blog-timeline-block" markdown="1">
## Archived
<hr class="section-divider" />

{% if archived.size > 0 %}
<div class="blog-timeline">
{% for list in archived %}
	<article class="blog-timeline-item">
		<div class="blog-timeline-date">{{ list.date | date: "%Y.%m" }}</div>
		<div class="blog-timeline-card">
			<h3><a href="{{ list.url | relative_url }}">{{ list.title }}</a></h3>
			{% if list.subtitle %}<p>{{ list.subtitle }}</p>{% endif %}
		</div>
	</article>
{% endfor %}
</div>
{% else %}
<p><em>No archived reading lists yet.</em></p>
{% endif %}
</section>
