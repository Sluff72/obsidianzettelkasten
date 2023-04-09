---
created:  <% tp.date.now("YYYY-MM-DD HH:mm") %>
medientyp: Text
---

#Media/PDF

Autor: [[10 - Literatur Notizen/Personen/Autor]]

## Kurze Zusammenfassung
PDF ^summary

## Referenz
Link: <% await tp.system.prompt("Link zu Buch im Verlag") %> 

## Querverweis
<% await tp.file.move("/10 - Literatur Notizen/Medien/NeuesBuch") %>