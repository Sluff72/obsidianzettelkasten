<%* const baseFile = tp.config.active_file.basename %><%* const noteFileName = "/00 - Flüchtige Notizen/" + tp.date.now("YYYY-MM-DD") + " Notizen - " + baseFile %>---
created:  <% tp.date.now("YYYY-MM-DD HH:mm") %>
status: Offen
priorität: 1
related: <% baseFile %>
---

#Notizen 

Quelle: [[<% baseFile %>]]

## Inhalt

## Querverweis

<%*
	let fileExists = await tp.file.exists(noteFileName + ".md");

	if (fileExists) {
		let file = tp.file.find_tfile(noteFileName + ".md"); 
		app.workspace.activeLeaf.openFile(file);
		return;
	} else {
		await tp.file.move(noteFileName);
	}
%>
