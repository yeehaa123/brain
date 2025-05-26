```dataview
TABLE WITHOUT ID link(file.link, title) as "Title", series as "Series", publishedAt as "Publication Date"
WHERE type = "article"
SORT createdAt DESC
```