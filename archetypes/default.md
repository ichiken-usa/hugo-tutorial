---
date: '{{ .Date }}'
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
author: 'Kentaro Ichihara'
tags: ['tag1', 'tag2']
categories: ['cat1']
draft: true
---