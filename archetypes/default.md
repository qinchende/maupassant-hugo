---
title: {{ replace .Name "-" " " | title }}
url: {{ replace .File.Dir "content" "" -}}{{- .Name -}}.html
date: {{ .Date }}
tags: []
categories: []
toc: false
draft: true
---