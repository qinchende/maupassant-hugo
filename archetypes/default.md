---
title: "{{ replace .Name "-" " " | title }}"
url: "{{ now.Format "/2006/01/02150405-" }}{{- .Name -}}.html"
date: "{{ .Date }}"
lastmod: "{{ .Date }}"
categories: []
tags: []
toc: false
draft: true
---