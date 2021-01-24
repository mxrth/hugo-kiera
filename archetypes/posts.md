---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
date: {{ .Date }}

draft: true

_build:
    list: always #change this to never or local to exclude from home but publish
---
