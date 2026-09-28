---
layout: archive
title: "Research"
permalink: /research/
lang: en
translation: /pt/pesquisa/
author_profile: true
---

{% include base_path %}

My research sits at the intersection of computer science, public administration and urban studies. I am interested in how people, institutions and intelligent systems can cooperate to design better public services and better cities, and in what it takes for governments to adopt AI responsibly.

Research interests
======
* **Human–AI cooperation in the public sector:** paradigms, governance and evaluation of AI systems used by governments, informed by the social sciences and humanities.
* **Digital government and public-sector innovation:** AI-driven innovation and collaboration in public services, and how startups and governments work together in innovation calls.
* **Collective intelligence and participatory design for cities:** crowd–machine interaction, participatory methods and smart cities.
* **Futures and design fiction:** anticipating risks and opportunities of AI in government services.

Current research
======
In my PhD at PESC/COPPE/UFRJ, at the Laboratory of the Future (LabFuturo), I am developing AI to support institutional and public service design processes. The thesis focuses on human–AI cooperation, governance and technology assessment in the public sector, asking how intelligent systems can strengthen, rather than replace, the judgement of public managers and citizens.

Previous research
======
* **MSc in Informatics (PPGI/UFRJ, 2018–2022).** Dissertation on a collective intelligence model to support discussions about the city, recognised as the best master's dissertation at the Brazilian Symposium on Collaborative Systems (SBSC 2023).
* **Bachelor in Architecture and Urbanism (EAU/UFF, 2008–2014).** Final project exploring simulation applied to urbanism.

Applied research and projects
======
* **BB Alimentação Escolar (Lemobs and Banco do Brasil).** Application of AI to operational optimisation in school feeding, including a tool and process that support nutritionists in assessing municipal compliance with the National School Feeding Programme (PNAE).
* **Participatory model for urban projects at UFRJ (Capgov / ETU/UFRJ, 2022–2023).** Collaboration on a participatory model for the elaboration of urban projects, based on UFRJ's 2030 physical-territorial Master Plan and developed in partnership with the UFRJ Technology Park. The work included training on digital participation and a year of workshops with university staff, faculty and students.

Publications
======
{% for category in site.publication_category %}
  {% assign pubs = site.publications | where: "category", category[0] | sort: "date" | reverse %}
  {% if pubs.size > 0 %}
<h3>{{ category[1].title }}</h3>
<ul>
    {% for post in pubs %}
  <li>{{ post.citation }}{% if post.paperurl %} <a href="{{ post.paperurl }}">[DOI]</a>{% endif %}</li>
    {% endfor %}
</ul>
  {% endif %}
{% endfor %}

The full and up-to-date list is available on [Google Scholar]({{ site.author.googlescholar }}), [ORCID]({{ site.author.orcid }}) and [ResearchGate]({{ site.author.researchgate }}).
