---
tags:
  - history/country
Wikipedia: https://en.wikipedia.org/wiki/Holy_Roman_Empire
EndDate: 
Date:
---
## Notes referenced to 
```dataview
table
    SourceDate as "Source",
    Date as "Noted"
from "100 Notes Box"
where contains(reference,this.file.link)
SORT Date DESC
```

## Notes about to
```dataview
table
    Date as "Noted",
    SourceDate as "Source",
    reference as "Reference"
from "100 Notes Box"
where contains(about,this.file.link)
SORT Date DESC
```
