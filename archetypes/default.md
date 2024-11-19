---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
author: "{{ .Site.Params.author | default "Default Author" }}"
tags: []
description: "A short summary of the post"
featured_image: "/path/to/image.jpg"
comments: false
draft: true
---
