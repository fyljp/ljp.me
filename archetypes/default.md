---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
slug: {{ md5 .Date }}
---

