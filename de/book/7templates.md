# 7.0 Templates

Diese Modul verwendet Templatedateien (.tpl) mit Smarty Tags (http://www.smarty.net), kompatible mit Version 2.

Für den Administrationsbereich gibt es 5 Templates:

|Template|Funktion|
|---|---|
|***contact_about.tpl***| Zur Anzeige der Seite "Über". Der Inhalt wird von der XOOPS ModulesAdmin-Klasse befüllt |
|***contact_contact.tpl*** | Zur Anzeige der Seite "Kontakt". Dieses Template wird mit einer Auflistung der Nachrichten und den wichtigsten Informationen befüllt |
|***contact_index.tpl*** | Zur Anzeige der Hauptübersicht im Administrationsbereich. Der Inhalt wird von der XOOPS ModulesAdmin-Klasse befüllt |
|***contact_logs.tpl*** | Zur Anzeige der Seite "Logs", wobei entwender das Filterformular oder das Ergebnis der letzten Filterung angezeigt wird |
|***contact_tools.tpl*** | Zur Anzeige der Seite "Werkzeuge" |


Für die Benutzerseite ist ein Template vorhanden:
|Template|Funktion|
|---|---|
|***contact_index.tpl*** | Zeigt das Kontaktformular an. Sofern das iframe für Google-Maps definiert wurde, wird die Karte rechts neben dem Kontaktformular angezeigt.|


Für die Blöcke existieren 4 Templates:
|Template|Function|
|---|---|
|***contact_block_stats.tpl*** | Zur Anzeige des Statistikblocks |
|***block_contact_form.tpl**** | Zur Anzeige des Kontaktformular (ohne Standortkarte) |
|***block_contact_form.tpl**** | Zur Anzeige des Standortkarte (ohne Kontaktformular) |
|***block_contact_form_maps.tpl**** | Zur Anzeige des Kontaktformular mit Standortkarte |

Alle Templates können etweder direkt oder über Admin -> System -> Templates -> Contact Us bearbeitet werden.
