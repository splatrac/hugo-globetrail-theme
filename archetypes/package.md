---
title: "{{ replace .Name "-" " " | title }}"
description: ""
date: {{ .Date }}
image: "images/"
time: ""
pax: "{{ index .Site.Data.packages (index (where .Site.Data.packages 'name' .Name) 0) 'pax' }}"
country: ""
price: ""
reviews: ""
rating: ""
featured: false
weight: 0
---
