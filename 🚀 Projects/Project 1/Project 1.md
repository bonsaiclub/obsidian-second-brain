---
banner: https://images.unsplash.com/photo-1555099962-4199c345e5dd?ixlib=rb-4.0.3&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=3600
---
# Notes
```dataview
TABLE Tag, dateformat(file.ctime, "yyyy-MM-dd") as "Created", dateformat(file.mtime, "yyyy-MM-dd") as "Modified"
WHERE contains(file.folder, this.file.folder)
```