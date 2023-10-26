up:: [Library](Maps/Library.md)
tag:: #map 

[The Wine Blueprint](Notes/The%20Wine%20Blueprint.md)

### Orphaned Notes
These notes point directly to this note. But this note doesn't point back.
```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from [Culture MOC](Culture%20MOC.md)
and !outgoing([Culture MOC](Culture%20MOC.md))
sort file.mtime desc
```