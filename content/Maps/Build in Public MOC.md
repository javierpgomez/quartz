up:: [Entrepreneurship MOC](Maps/Entrepreneurship%20MOC.md)
tags:: #map 

[1 Year Since I started out on my own](Notes/1%20Year%20Since%20I%20started%20out%20on%20my%20own.md)

### Orphaned Notes
These notes point directly to this note. But this note doesn't point back.
```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from [Build in Public MOC](.md)
and !outgoing([Build in Public MOC](.md))
sort file.mtime desc
```