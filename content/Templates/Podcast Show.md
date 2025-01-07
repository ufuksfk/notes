---
title: 
draft: 
tags:
  - artifacts/podcast
link:
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
