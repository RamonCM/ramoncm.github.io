---
layout: archive
title: "Currículo"
permalink: /pt/cv/
lang: pt
translation: /cv/
author_profile: true
redirect_from:
  - /pt/curriculo/
  - /curriculo/
---

{% include base_path %}
{% assign cv_file = site.static_files | where: "name", "Ramon_Chaves_CV.pdf" | first %}
{% if cv_file %}
<p><a href="{{ base_path }}{{ cv_file.path }}" class="btn btn--info"><i class="fas fa-file-pdf" aria-hidden="true"></i> Baixar PDF</a></p>
{% endif %}

Gerente de projetos com mais de 10 anos de experiência, sendo os últimos 7 anos liderando o desenho e a implementação de soluções digitais para governos (níveis municipal, estadual e federal). Atuo desde o planejamento até a entrega de soluções digitais, incluindo a capacitação de gestores públicos. Trajetória acadêmica em temas como cidades inteligentes e governo digital, com foco em aspectos humanos na adoção da Inteligência Artificial.

Experiência profissional
======
* **Lemobs** — Gerente de Projetos | Abr/2019 – atual
  * No contexto do projeto *BB Alimentação Escolar*, parceria com o Banco do Brasil, aplicação de IA para otimizações operacionais, como a elaboração de ferramenta e processo para apoiar nutricionistas na avaliação de conformidade das ações das secretarias municipais no âmbito do Programa Nacional de Alimentação Escolar (PNAE).
  * Capacitação de gestores e equipes operacionais, com preparação de materiais didáticos, treinamentos e acompanhamento de adoção, conectando processos, tecnologia e resultados.
  * Liderança de projetos de desenvolvimento e adoção de produtos digitais utilizados por governos municipais (ex.: Maricá-RJ, Itabira-MG, Catanduva-SP) em resíduos sólidos, manutenção urbana, fiscalização de obras e alimentação escolar inteligente. Atuação desde o diagnóstico com usuários, desenho de solução e jornada e definição de requisitos até a coordenação de times técnicos, implantação e melhoria contínua.
  * Elaboração de propostas, orçamentos e arquitetura de soluções para licitações nacionais (ex.: Correios, Copasa, TCU), com foco em clareza técnica, viabilidade e valor público.

* **Capgov (PESC/COPPE/UFRJ)** — Pesquisador assistente | Set/2022 – 2023
  * Facilitação de workshops de capacitação e metodologias participativas com servidores da Universidade.

* **Universidade Federal do Rio de Janeiro (EBA/UFRJ)** — Professor substituto | Jul/2021 – Ago/2022
  * Docência e coordenação de atividades em Técnicas e Representação; planejamento de aulas e avaliação.

* **Muda Arquitetura** — Arquiteto e Urbanista / Gestão de Projetos | Mar/2013 – Mar/2017
  * Gerente de projetos em Building Information Modelling (BIM), fortalecendo a base de planejamento, orçamento e execução em ambientes complexos.

Formação acadêmica
======
* **Doutorado em Engenharia de Sistemas e Computação**, PESC/COPPE/UFRJ — desde Set/2022
  * Tese: desenvolvimento de IA para apoiar processos de desenho institucional e de serviços públicos, com foco em cooperação humano-IA, governança e avaliação de tecnologias no setor público.
* **Mestrado em Informática**, PPGI/UFRJ — 2018–2022
  * Dissertação: modelo de inteligência coletiva para apoiar discussões sobre a cidade (reconhecida com prêmio de melhor dissertação).
* **Bacharelado em Arquitetura e Urbanismo**, EAU/UFF — 2008–2014
  * Projeto final: exploração de simulação aplicada ao urbanismo.
* **Mobilidade acadêmica**, ETSA/Universidade de Sevilha (Espanha) — 2012–2013

Prêmios e reconhecimentos
======
* Best Paper Award — Digital Government Society (dg.o), 2025
* 2º lugar — 3MT (Three Minute Thesis), UFRJ, 2025
* Best Paper: melhor dissertação de mestrado — Simpósio Brasileiro de Sistemas Colaborativos (SBSC), 2023
* ACM SIGCHI Gary Marsden Travel Award, 2023
* Selo de Inovação — Sociedade Brasileira de Computação (SBC), 2021

Certificações e cursos
======
* 24th International Summer School on Regulation of Local Public Services — Turin School of Regulation, 2022
* Agile Scrum — Product Owner — Fundação Carlos Alberto Vanzolini, 2021
* Seminário internacional "Digital Governance, Identity and Participation: Investigating 21st Century Cities" — Universidade Federal do Rio de Janeiro, 2018

Idiomas
======
* Português: nativo
* Inglês: avançado (uso profissional e acadêmico)
* Espanhol: avançado (uso profissional e acadêmico)

Publicações selecionadas
======
{% assign pubs = site.publications | sort: "date" | reverse %}
<ul>
{% for post in pubs %}
  <li>{{ post.citation }}{% if post.paperurl %} <a href="{{ post.paperurl }}">[DOI]</a>{% endif %}</li>
{% endfor %}
</ul>

A lista completa está nos meus perfis no [Google Scholar]({{ site.author.googlescholar }}) e no [ORCID]({{ site.author.orcid }}).
