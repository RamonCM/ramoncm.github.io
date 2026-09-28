---
layout: archive
title: "Pesquisa"
permalink: /pt/pesquisa/
lang: pt
translation: /research/
author_profile: true
redirect_from:
  - /pt/research/
  - /pt/publicacoes/
---

{% include base_path %}

Minha pesquisa está na interseção entre ciência da computação, administração pública e estudos urbanos. Interesso-me por como pessoas, instituições e sistemas inteligentes podem cooperar para desenhar melhores serviços públicos e melhores cidades, e pelo que é necessário para que governos adotem IA de forma responsável.

Linhas de interesse
======
* **Cooperação humano-IA no setor público:** paradigmas, governança e avaliação de sistemas de IA utilizados por governos, com base nas ciências sociais e humanidades.
* **Governo digital e inovação no setor público:** inovação e colaboração orientadas por IA em serviços públicos e a relação entre startups e governos em chamadas de inovação.
* **Inteligência coletiva e desenho participativo para cidades:** interação entre multidões e máquinas, métodos participativos e cidades inteligentes.
* **Futuros e design fiction:** antecipação de riscos e oportunidades da IA em serviços governamentais.

Pesquisa atual
======
No doutorado no PESC/COPPE/UFRJ, no Laboratório do Futuro (LabFuturo), desenvolvo IA para apoiar processos de desenho institucional e de serviços públicos. A tese tem foco em cooperação humano-IA, governança e avaliação de tecnologias no setor público, perguntando como sistemas inteligentes podem fortalecer, em vez de substituir, o julgamento de gestores públicos e cidadãos.

Pesquisas anteriores
======
* **Mestrado em Informática (PPGI/UFRJ, 2018–2022).** Dissertação sobre um modelo de inteligência coletiva para apoiar discussões sobre a cidade, reconhecida como melhor dissertação de mestrado no Simpósio Brasileiro de Sistemas Colaborativos (SBSC 2023).
* **Bacharelado em Arquitetura e Urbanismo (EAU/UFF, 2008–2014).** Projeto final explorando simulação aplicada ao urbanismo.

Pesquisa aplicada e projetos
======
* **BB Alimentação Escolar (Lemobs e Banco do Brasil).** Aplicação de IA para otimizações operacionais na alimentação escolar, incluindo ferramenta e processo que apoiam nutricionistas na avaliação de conformidade das ações municipais no âmbito do Programa Nacional de Alimentação Escolar (PNAE).
* **Modelo participativo para projetos urbanos na UFRJ (Capgov / ETU/UFRJ, 2022–2023).** Colaboração em um modelo participativo para a elaboração de projetos urbanos, a partir do Plano Diretor físico-territorial 2030 da UFRJ, em parceria com o Parque Tecnológico da UFRJ. O trabalho incluiu capacitações sobre participação digital e um ano de oficinas com servidores, docentes e estudantes da universidade.

Publicações
======
{% for category in site.publication_category %}
  {% assign pubs = site.publications | where: "category", category[0] | sort: "date" | reverse %}
  {% if pubs.size > 0 %}
<h3>{{ category[1].title_pt | default: category[1].title }}</h3>
<ul>
    {% for post in pubs %}
  <li>{{ post.citation }}{% if post.paperurl %} <a href="{{ post.paperurl }}">[DOI]</a>{% endif %}</li>
    {% endfor %}
</ul>
  {% endif %}
{% endfor %}

A lista completa e atualizada está no [Google Scholar]({{ site.author.googlescholar }}), no [ORCID]({{ site.author.orcid }}) e no [ResearchGate]({{ site.author.researchgate }}).
