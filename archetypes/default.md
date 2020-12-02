---
title: "{{ replace .Name "-" " " | title }}"
description: ""
date: {{ .Date }}
lastmod: {{ .Date }}
draft: false
images: ["{{ .Name | urlize }}.png"]
menu: "main"
categories: [""]
---

{{< img src="{{ .Name | urlize }}.png" alt="{{ replace .Name "-" " " | title }}" caption="{{ replace .Name "-" " " | title }}" class="wide" >}}
