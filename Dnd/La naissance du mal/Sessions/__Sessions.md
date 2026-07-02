
```dataview
Table WITHOUT ID link(file.name) AS File, dateformat(date,"yyyy-MM-dd") AS Date, status AS Status, title as Title
FROM -"Templates"
WHERE type = "session"
```

