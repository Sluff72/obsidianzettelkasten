---
created:  <% tp.date.now("YYYY-MM-DD HH:mm") %>
medientyp: Text
---
<%* const source = await tp.system.prompt("Link zu Buch im Verlag") %><%* const title = await tp.system.prompt("Titel") %><%* const autor = await tp.system.prompt("Ein Autor") %>
#Media/Buch #<% await tp.system.suggester(["Muss","Sollte","Könnte","Uninteressant","Gelesen"],["Lesen/Muss","Lesen/Sollte","Lesen/Könnte","Lesen/Uninteressant","Lesen/Gelesen"]) %> #<% await tp.system.suggester(["Gekauft","Wunsch"],["Kaufen/Gekauft","Kaufen/Wunsch"]) %>
Autor: [[10 - Literatur Notizen/Personen/<% autor %>]]

## Kurze Zusammenfassung
Buch ^summary

## Referenz
Link: <% source %>
Verlag: [[10 - Literatur Notizen/Firmen/Verlag]]
ISBN-10:
ISBN-13:

## Klappentext

## Querverweis
<% await tp.file.move("/10 - Literatur Notizen/Medien/" + title) %>