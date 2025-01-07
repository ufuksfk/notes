---
title: 
draft: 
tags:
  - artifacts/movie
link: 
datePublished: 
author:
---
```dataview
```dataview
TABLE
    publisher as "Publisher",
    published_date as "Date"
FROM
    "Highlights/Matter"
WHERE 
    contains(publisher,this.file.link)
SORT published_date DESC
```
