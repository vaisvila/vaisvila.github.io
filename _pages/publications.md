---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign journal_pubs = pubs | where: "pubtype", "journal" %}
{% assign report_pubs = pubs | where: "pubtype", "report" %}

{% if journal_pubs.size > 0 %}
<h2 id="peer-reviewed">Peer-reviewed articles</h2>
{% for post in journal_pubs %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% if report_pubs.size > 0 %}
<h2 id="reports">Reports</h2>
{% for post in report_pubs %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

<h2 id="in-preparation">In preparation</h2>
<ul>
  <li>Vaisvil, A., D. Shoup, and S. Brewer. A meta-analysis and review of catch-and-release mortality estimates of riverine fishes and future directions.</li>
  <li>Vaisvil, A., D. Shoup, and S. Brewer. Temperature and flow thresholds for Striped Bass recruitment in a regulated river system.</li>
  <li>Vaisvil, A., D. Shoup, and S. Brewer. Optimizing harvest regulations for freshwater Striped Bass using integrated population models.</li>
  <li>Vaisvil, A., D. Shoup, and S. Brewer. Environmental drivers of Striped Bass movement and habitat use in a fragmented river&ndash;reservoir system.</li>
</ul>
