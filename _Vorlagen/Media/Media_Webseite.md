---
created:  <% tp.date.now("YYYY-MM-DD HH:mm") %>
medientyp: Text
---

#Media/Webseite

## Kurze Zusammenfassung
Webseite ^summary

## Referenz
Link: <% await tp.system.prompt("Webseiten URL") %> 

## Querverweis
<% await tp.file.move("/10 - Literatur Notizen/Medien/NeueWebseite") %>