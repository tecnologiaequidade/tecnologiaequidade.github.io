---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}
image:
summary: ""
relatedProjects:
url: "/projetos/{{ replace .TranslationBaseName "-" " " | lower }}"
draft: true
weight:
---
