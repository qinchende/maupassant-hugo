---
title: {{ replace .Name "-" " " | title }}
url: {{ with replace .File.Dir "content" "" -}}{{- replace . "\\" "/" -}}{{- end -}}{{- .Name -}}.html
date: {{ .Date }}
tags: []
categories: []
toc: false
draft: true
---