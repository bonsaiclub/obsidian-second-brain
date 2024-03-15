## General Information
<div class="boxBorder">
	<ul>
		<li>Beschreibung:...</li>
		<li>Ansprechpartner:...</li>
	</ul>
</div>

## Notes
```dataview
TABLE dateformat(file.ctime, "yyyy-MM-dd") as "Created", dateformat(file.mtime, "yyyy-MM-dd") as "Modified"
WHERE contains(file.folder, this.file.folder + "/{{title}}")
```
