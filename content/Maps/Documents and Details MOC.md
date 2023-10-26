up:: [Home](Maps/Home.md)
tags:: #map 

[AnyType Recovery Phrase](AnyType%20Recovery%20Phrase.md)

### Orphaned Notes
These notes point directly to this note. But this note doesn't point back.
```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from [Documents and Details MOC](Documents%20and%20Details%20MOC.md)
and !outgoing([Documents and Details MOC](Documents%20and%20Details%20MOC.md))
sort file.mtime desc
```

### Unmentioned with # tag
These notes have the # tag but aren't mentioned here

```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from # 
and !outgoing([Documents and Details MOC](Documents%20and%20Details%20MOC.md))
sort file.mtime desc
```