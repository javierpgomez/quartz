---
title: 
alias: ["000"]
---
# Home 🌎
Your launchpad and home base. That's here. That's home.

## Atlas 
These are maps to launch your `efforts`. Where would you like to go?

- My Main Sensemaking
	- 01 - [[Maps/Thinking MOC]]
	- 02 - [[Inbox]] and [[Maps/Notebox]] and [[Maps/Outbox]]
	- 03 - [[Calendar/Daily Notes]]
-  Things
	- 04 - [[Maps/Library]]
	- 05 - [[Maps/People MOC]]
	- 06 - [[Maps/Sources MOC]]
	- 07 - [[Maps/Concepts MOC]]
- Action and Reflection
	- 08 - [[Maps/Efforts MOC]] and [[Maps/Entrepreneurship MOC]]
	- 09 - [[Maps/Plan and Review]]
- Personal Management and Life Stuff
	- 10 - [[Maps/Health MOC]] and [[Maps/Finance MOC]] and [[Notes/Investments MOC]]
	- 11 - [[Maps/Documents and Details MOC]]
	- 12 - [[Maps/Life Map]] and [[Notes/LYT Kit]] and [[Maps/Meta PKM]] [[Earth|.]]

### Some MOCs with no sorting yet
These notes point directly to this note. But this note doesn't point back.
```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from [[Home]]
and !outgoing([[Home]])
sort file.mtime desc
```

### Unmentioned notes, with related tag
These notes have the tag `#` and are not mentioned above.

```dataview
table file.mtime.year + "-" + file.mtime.month + "-" + file.mtime.day as Modified
from #home  
and !outgoing([[Home]])
sort file.mtime desc
```