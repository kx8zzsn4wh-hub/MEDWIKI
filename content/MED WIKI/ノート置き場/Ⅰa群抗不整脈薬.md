
関連疾患検索
```dataview
table without id file.link as 疾患名, tags as "タグ"
from ""
where contains(治療薬, this.file.name)
sort tags asc
```

