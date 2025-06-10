---
date: "{{ .Date }}"
draft: true
title: "{{ replace .File.BaseFileName "-" " " | title }}"
---