---
title: 
draft: 
tags:
  - artifacts/podcast
  - wiki/person
link:
---
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
