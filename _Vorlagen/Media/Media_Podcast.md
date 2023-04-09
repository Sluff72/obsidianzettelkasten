---
created:  <% tp.date.now("YYYY-MM-DD HH:mm") %>
medientyp: Audio
---

#Media/Podcast

Speaker: [[10 - Literatur Notizen/Personen/Moderator]]

## Kurze Zusammenfassung
Podcast ^summary

## Referenz
Link: <% await tp.system.prompt("Podcast URL") %> 

## Querverweis
<% await tp.file.move("/10 - Literatur Notizen/Medien/NeuerPodcast") %>