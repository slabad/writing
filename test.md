```dataview 
TABLE file.day AS "Created", file.mtime AS "Modified" 
FROM #seed
SORT rating DESC 
```

