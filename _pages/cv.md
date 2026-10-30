---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% comment %}TODO(Alexander): add a downloadable PDF CV, e.g. upload files/Vaisvil_CV.pdf and add:
     [Download CV (PDF)]({{ base_path }}/files/Vaisvil_CV.pdf){% endcomment %}

## Education
* **Ph.D., Fisheries Science** — Oklahoma State University, Stillwater, OK, 2026
  * Dissertation: *Population dynamics of Striped Bass in the Robert S. Kerr river–reservoir complex, Oklahoma*
* **M.S., Fish, Wildlife, and Conservation Ecology** — New Mexico State University, Las Cruces, NM, 2019
  * Thesis: *Natal source and the influence of environmental bottlenecks on Largemouth Bass recruitment in Elephant Butte Reservoir, New Mexico*
* **B.S., Biology** (minors: Chemistry; Environmental Studies) — Xavier University, Cincinnati, OH, 2016
  * Senior thesis: *(E)-6,10-dimethyl-5,9-undecadien-2-yl acetate: a likely attractant pheromone of* Nicrophorus defodiens

## Professional experience
* **Fish Biologist** — Bay-Delta Area Office, Science Division, U.S. Bureau of Reclamation, Sacramento, CA *(Dec 2023–present)*
  * Lead analytical support for the American River Group Structured Decision Making (SDM) effort, developing and applying fall-run Chinook Salmon life-cycle models to evaluate flow and temperature management alternatives on the American River
  * Develop and maintain salmon population models in R that integrate temperature-dependent mortality, spawn-timing dynamics, and age-structured returns
  * Build interactive R Shiny applications for real-time decision support, letting managers visualize model outputs and compare scenarios
  * Contribute to Delta Life-Cycle Model development, implementing mechanistic approaches to quantify the effects of water exports on winter-run Chinook Salmon
  * Develop Value of Information frameworks to assess flow management alternatives and minimize impacts to endangered salmon in the Sacramento River
  * Provide weekly salmon operations assessments, synthesizing real-time monitoring data to inform water management decisions affecting ESA-listed species
  * Lead analytical work for regulatory actions and temperature analyses for salmon habitat restoration; prepare technical input to environmental compliance documents
* **Graduate Research Assistant** — Natural Resource Ecology and Management, Oklahoma State University *(Jun 2019–Jun 2023)*
  * Coordinated field work with state (ODWC) and federal (USACE, USFWS) agencies and led field and lab teams
  * Boat electrofishing around dams and in swift current; passive and active radio and acoustic telemetry, including transmitter implantation surgery; reward tagging, PIT tagging, and an angler tag-reporting database
  * Age estimation from otoliths, scales, and dorsal spines, including daily-ring counts on age-0 Striped Bass otoliths; delayed hooking-mortality study
  * Advanced statistical modeling in R, Stan, JAGS, and MARK
* **Graduate Research Assistant** — Fish, Wildlife, and Conservation Ecology, New Mexico State University *(Jun 2016–May 2019)*
  * Led field and lab research: boat and backpack electrofishing, water quality and temperature monitoring
  * Strontium isotope analysis of dorsal spines and otoliths; age estimation; physiological assays (vitellogenin, 17β-estradiol)
* **Seasonal Fisheries Technician** — Hancock Biological Station, Murray State University, Murray, KY *(May–Jul 2015)*
  * Trophic ecology of Silver Carp in Kentucky Lake; gill and trawl netting; stream habitat assessment
* **Seasonal Biological Technician** — Xavier University and U.S. Forest Service, Juneau, AK *(May–Jul 2014)*
  * Carrion beetle attractant pheromone project; early detection of invasive longhorned beetles
* **Laboratory Assistant** — Department of Biology, Xavier University *(Aug 2013–Aug 2014)*
  * Aquatic macroinvertebrate collection and identification

## Publications
  <ul>{% assign cv_pubs = site.publications | sort: "date" | reverse %}{% for post in cv_pubs %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

### Manuscripts in preparation
* Vaisvil, A., D. Shoup, and S. Brewer. A meta-analysis and review of catch-and-release mortality estimates of riverine fishes and future directions.
* Vaisvil, A., D. Shoup, and S. Brewer. Temperature and flow thresholds for Striped Bass recruitment in a regulated river system.
* Vaisvil, A., D. Shoup, and S. Brewer. Optimizing harvest regulations for freshwater Striped Bass using integrated population models.
* Vaisvil, A., D. Shoup, and S. Brewer. Environmental drivers of Striped Bass movement and habitat use in a fragmented river–reservoir system.

## Talks and posters
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

## Peer review
* *North American Journal of Fisheries Management* (2021, 2025)
* *Scientific Reports* (2024)

## Grants, scholarships, and awards
* Outstanding Graduate Fisheries Scholarship ($1,000), 2021 and 2022
* Bass Pro Shops Conservation and Community Grant ($5,000), 2021
* Lester and Norma Jean Fisher Memorial Endowed Scholarship ($500), 2019
* 2nd Place Best Poster Award — First Annual Open House, College of Agricultural, Consumer, and Environmental Sciences, New Mexico State University, 2018
* Bass Pro Shops Conservation and Community Grant ($5,000), 2017

## Service and outreach
* **R instruction:** led R Team meetings teaching R within the Bay-Delta Area Office Science Division, with training materials and mathematical guides for fisheries applications; taught spatial mapping in R to New Mexico State University graduate students (2020)
* **Science communication:** guest on *The Fisheries Podcast* (Episode 112)
* **Mentoring:** undergraduate research mentor at Oklahoma State University (2020–2023) and New Mexico State University (2016–2019)
* **Fisheries outreach:** helped relocate Largemouth Bass with New Mexico B.A.S.S. Nation and the New Mexico Department of Game and Fish (2018)
* **NMSU Fish, Wildlife, and Conservation Ecology Graduate Student Organization:** President (2018–2019), Secretary (2017–2018)
* **American Fisheries Society:** Habitat Subsection Twitter manager (2020) and contributing writer (2018–2020); chapter member in Minnesota (2023), Oklahoma (2020–2022), Arizona/New Mexico (2016–2020), and Ohio (2015–2016)

## Technical skills
* **Expert:** R (analysis, data manipulation, visualization, mapping, Quarto, R Markdown, Shiny)
* **Proficient:** ArcGIS, Python, Unix/Bash, SQL, Git/GitHub, JAGS, Stan
* **Methods:** Bayesian hierarchical models, integrated population models, hidden Markov models, time-series analysis, mixed-effects models, survival analysis, population dynamics modeling, structured decision making, value of information analysis

## Selected training and certifications
* Introduction to Structured Decision Making — USFWS National Conservation Training Center
* Hierarchical Ecological Modeling Using R and JAGS — USFWS National Conservation Training Center
* ECO-PTM model training
* Side-scan sonar for habitat and fisheries
* Software Carpentry: Unix and Python (2023)
* USGS Motorboat Operator Certification (2017, with refresher)
* Open Water Dive Certification (2017)
