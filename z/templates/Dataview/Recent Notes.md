``` dataview 
list from "" 
where file.mtime >= date(today) - dur(7 days) 
sort file.mtime desc 
limit 10
```
