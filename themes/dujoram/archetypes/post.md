---
title: "{{ .BaseFileName | title }}"
date: {{ .Date }}
draft: true
type: "post"
references:
  - Type: "journal"
    Ref: "SURF00"
    Title: "Article Title"
    Journal: "Journal name"
    Volume: 0
    Number: 0
    Authors:
      - "Firstname M. Surname"
    Year: 1900
    Month: 12
    PageFirst: 0
    PageLast: 0
  - Type: "web"
    Ref: "SURF01"
    Title: "Web Title"
    Authors:
      - "Firstname M. Surname"
    Year: 2015
    Available: "https://www.example.com/"
---

Introduction

<!--more-->

# Subtitle 1

[[SURF00]]({{< relref "#SURF00" >}})
