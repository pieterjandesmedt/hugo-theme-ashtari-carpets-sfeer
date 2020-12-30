---
title: {{ replace .Name "-" " " | replaceRE "^[0-9]*" "" | replace "_" " " | trim | title }}
date: {{ .Date }}
author: Wendy Guns
category: design stories
description:
banner: image0.jpg
images:
- image1.jpg
- image2.jpg
tags:
- tag1
- tag2
---

Summary or first few lines of the article goes here.

<!--more-->

Here comes the rest of the article.
