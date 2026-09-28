---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
lang: en
translation: /pt/cv/
author_profile: true
redirect_from:
  - /resume
  - /resume/
---

{% include base_path %}
{% assign cv_file = site.static_files | where: "name", "Ramon_Chaves_CV.pdf" | first %}
{% if cv_file %}
<p><a href="{{ base_path }}{{ cv_file.path }}" class="btn btn--info"><i class="fas fa-file-pdf" aria-hidden="true"></i> Download PDF</a></p>
{% endif %}

Project manager with more than 10 years of experience, the last 7 of them leading the design and implementation of digital solutions for governments (municipal, state and federal levels). I work from planning to delivery of digital solutions, including the training of public managers. Academic trajectory in smart cities and digital government, with a focus on human aspects of the adoption of Artificial Intelligence.

Professional experience
======
* **Lemobs** — Project Manager | Apr 2019 – present
  * *BB Alimentação Escolar* project, a partnership with Banco do Brasil: application of AI to operational optimisation, such as a tool and process to support nutritionists in assessing the compliance of municipal education departments under the National School Feeding Programme (PNAE).
  * Training of managers and operational teams, including the preparation of teaching materials, training sessions and adoption follow-up, connecting processes, technology and results.
  * Leadership of development and adoption projects for digital products used by municipal governments (e.g. Maricá-RJ, Itabira-MG, Catanduva-SP) in solid waste, urban maintenance, works inspection and smart school feeding. Work ranges from user diagnosis, solution and journey design and requirements definition to coordination of technical teams, deployment and continuous improvement.
  * Preparation of proposals, budgets and solution architectures for national public tenders (e.g. Correios, Copasa, TCU), with a focus on technical clarity, feasibility and public value.

* **Capgov (PESC/COPPE/UFRJ)** — Research Assistant | Sep 2022 – 2023
  * Facilitation of capacity-building workshops and participatory methodologies with university staff.

* **Federal University of Rio de Janeiro (EBA/UFRJ)** — Substitute Professor | Jul 2021 – Aug 2022
  * Teaching and coordination of activities in Techniques and Representation; lesson planning and assessment.

* **Muda Arquitetura** — Architect and Urban Planner / Project Management | Mar 2013 – Mar 2017
  * Project manager in Building Information Modelling (BIM), strengthening the planning, budgeting and execution base in complex environments.

Education
======
* **PhD in Systems and Computer Engineering**, PESC/COPPE/UFRJ — since Sep 2022
  * Thesis: development of AI to support institutional and public service design processes, with a focus on human–AI cooperation, governance and technology assessment in the public sector.
* **MSc in Informatics**, PPGI/UFRJ — 2018–2022
  * Dissertation: a collective intelligence model to support discussions about the city (recognised with a best dissertation award).
* **Bachelor in Architecture and Urbanism**, EAU/UFF — 2008–2014
  * Final project: exploration of simulation applied to urbanism.
* **Academic exchange**, ETSA/University of Seville (Spain) — 2012–2013

Awards and recognition
======
* Best Paper Award — Digital Government Society (dg.o), 2025
* 2nd place — Three Minute Thesis (3MT), UFRJ, 2025
* Best Paper: best master's dissertation — Brazilian Symposium on Collaborative Systems (SBSC), 2023
* ACM SIGCHI Gary Marsden Travel Award, 2023
* Innovation Seal — Brazilian Computer Society (SBC), 2021

Certifications and courses
======
* 24th International Summer School on Regulation of Local Public Services — Turin School of Regulation, 2022
* Agile Scrum — Product Owner — Fundação Carlos Alberto Vanzolini, 2021
* International Seminar "Digital Governance, Identity and Participation: Investigating 21st Century Cities" — Federal University of Rio de Janeiro, 2018

Languages
======
* Portuguese: native
* English: advanced (professional and academic use)
* Spanish: advanced (professional and academic use)

Selected publications
======
{% assign pubs = site.publications | sort: "date" | reverse %}
<ul>
{% for post in pubs %}
  <li>{{ post.citation }}{% if post.paperurl %} <a href="{{ post.paperurl }}">[DOI]</a>{% endif %}</li>
{% endfor %}
</ul>

The full list is available on my [Google Scholar]({{ site.author.googlescholar }}) and [ORCID]({{ site.author.orcid }}) profiles.
