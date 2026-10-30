---
permalink: /
title: "About"
excerpt: "Alexander Vaisvil — Lead Biometrician and Population Modeler, California Department of Water Resources"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

I am the **Lead Biometrician and Population Modeler at the California Department of Water Resources** in Sacramento, California, where I build quantitative tools that help managers weigh water operations against the needs of California's fishes.

Before joining DWR in 2026, I was a Fish Biologist in the Science Division of the **U.S. Bureau of Reclamation's Bay-Delta Area Office** (2023–2026). There I led analytical support for the American River Group Structured Decision Making effort, developing fall-run Chinook Salmon life-cycle models to evaluate flow and temperature management alternatives, and built R Shiny applications that let managers compare scenarios in real time. I also provided weekly salmon operations assessments, contributed to the Delta Life-Cycle Model for winter-run Chinook Salmon, and developed Value of Information frameworks for flow management on the Sacramento River.

I earned my **Ph.D. in Fisheries Science from Oklahoma State University** in 2026. My dissertation examined the population dynamics of Striped Bass in the Robert S. Kerr river–reservoir complex in Oklahoma, drawing on telemetry, tagging, age estimation, and statistical population modeling. Before that, I earned an **M.S. in Fish, Wildlife, and Conservation Ecology from New Mexico State University**, where I used strontium isotopes in otoliths to trace the natal origin of Largemouth Bass and studied the environmental bottlenecks that limit their recruitment in Elephant Butte Reservoir.

Across this work, my goal is to bring rigorous population modeling and sound fisheries science to water management decisions.

Research interests
------
* **Salmon life-cycle modeling** — Chinook Salmon population models that link temperature, flow, and spawn timing to survival and returns
* **Decision support for water management** — structured decision making, value of information analysis, and interactive tools for managers
* **Bayesian and integrated population models** — hierarchical, hidden Markov, and survival models for fish population dynamics
* **Striped Bass ecology** — movement, recruitment, angler exploitation, and harvest regulation in river–reservoir systems
* **Reservoir fish recruitment and natal origin** — water-level and temperature effects on young-of-year fish, and otolith strontium isotopes (<sup>87</sup>Sr/<sup>86</sup>Sr)

Recent publications
------
<ul>
{% assign recent_pubs = site.publications | sort: "date" | reverse %}
{% for post in recent_pubs limit:2 %}
  <li><a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a> — <em>{{ post.venue }}</em>, {{ post.date | date: "%Y" }}</li>
{% endfor %}
</ul>

See all [publications]({{ base_path }}/publications/), [talks and posters]({{ base_path }}/talks/), or my [CV]({{ base_path }}/cv/).

Contact
------
Email: [alexander.vaisvil@water.ca.gov](mailto:alexander.vaisvil@water.ca.gov)
