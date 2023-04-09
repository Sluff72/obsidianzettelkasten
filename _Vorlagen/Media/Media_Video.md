---
created:  <% tp.date.now("YYYY-MM-DD HH:mm") %>
medientyp: Video
---

#Media/Video

Speaker: [[10 - Literatur Notizen/Personen/Speaker]]

## Kurze Zusammenfassung
Video ^summary

## Referenz
Link: <% await tp.system.prompt("URL zum Video") %> 

## Querverweis
<% await tp.file.move("/10 - Literatur Notizen/Medien/NeuesVideo") %>