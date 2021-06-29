---
title:      "{{ replace .TranslationBaseName "_" " " | after 11 | title }}"
date:       {{ now.Format "2006-01-02" }}
draft:      true
categories: []
tags:       []
url:        "post/{{.TranslationBaseName | after 11}}"
---
