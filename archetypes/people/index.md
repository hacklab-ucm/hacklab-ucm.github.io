---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
weight: 
draft: false
tags: []
materials: []
resources:
- name: cover
  src: bio-pic.jpg
- name: fallback-cover
  src: images/non_tile.png
- name: image_:counter
  src: '**.jpg'
---
