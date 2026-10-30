---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

All pages on this site. An [XML sitemap]({{ base_path }}/sitemap.xml) is also available.

<h2>Pages</h2>
<ul>
  <li><a href="{{ base_path }}/">About</a></li>
{% for link in site.data.navigation.main %}
  <li><a href="{{ base_path }}{{ link.url }}">{{ link.title }}</a></li>
{% endfor %}
</ul>

<h2>Publications</h2>
<ul>
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for post in pubs %}{% unless post.sitemap == false %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ post.title | markdownify | remove: "<p>" | remove: "</p>" | strip }}</a>{% if post.venue %} &mdash; <em>{{ post.venue }}</em>{% endif %}, {{ post.date | date: "%Y" }}</li>
{% endunless %}{% endfor %}
</ul>

<h2>Talks and posters</h2>
<ul>
{% assign talks = site.talks | sort: "date" | reverse %}
{% for post in talks %}{% unless post.sitemap == false %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ post.title | markdownify | remove: "<p>" | remove: "</p>" | strip }}</a>{% if post.type %} ({{ post.type }}){% endif %}, {{ post.date | date: "%B %Y" }}</li>
{% endunless %}{% endfor %}
</ul>
