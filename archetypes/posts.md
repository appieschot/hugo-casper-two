---
title: "{{ replace .Name "-" " " | title }}"
type: post
date: {{ .Date }}
url: /{{.Name}}/
image: /images/{{.Name}}.webp
categories:
---

**Insert Lead paragraph here.**

## Header

Subtext

```json
 { 'test': 'test'}
```

![Some image for {{ replace .Name "-" " " | title }}](/images/{{.Name}}.webp)

[Some link](https://www.cloudappie.nl)
