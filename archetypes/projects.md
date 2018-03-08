---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
image:
summary: ""
relatedProjects:
url: "/projetos/{{ replace .TranslationBaseName "-" " " | lower }}"
layout: none
draft: true
weight:
---
