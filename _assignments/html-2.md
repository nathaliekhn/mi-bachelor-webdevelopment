---
titel: Semantisches HTML // Formulare, Typografie & Basislayout
tags: HTML
---

Wir werden zur Bearbeitung der Aufgaben wieder GitHub Classroom nutzen.

Die Aufgaben bauen auf den Markup von den Übungen aus dem Workshop „HTML Basics”auf. Verwenden Sie daher das Repository/ Assignment, aus dem Workshop „HTML Basics”. 

Erzeugen Sie nun einen neuen Branch mit dem Namen „session-2” und wechseln Sie bitte in diesen Branch.

## Aufgabe 1 - HTML // Formulare und Tabellen
Zur Verwaltung der Daten für den digitalen Museumsführer wird eine Pflegemaske benötigt. Über diese soll es möglich sein, sich alle gespeicherten Daten zu den Gemälden anzeigen zu lassen, neue Gemälde hinzuzufügen, zu löschen und zu bearbeiten.

Erstellen Sie in ihrem Repository einen Ordner `backend` und darin eine Datei `uebersicht.html`.

Erzeugen Sie für folgendes [Wireframe](../../material/frontend-development-1/session-2/aufgabe-1/pflegemaske.png) möglichst semantisch reichhaltiges Markup.

Die Daten für die Gemäldeübersicht finden Sie hier als [Markdown Datei](../../material/frontend-development-1/session-2/aufgabe-1/gemaeldedaten.md) oder als [PDF](../../material/frontend-development-1/session-2/aufgabe-1/gemaeldedaten.pdf)

## Aufgabe 2 - CSS // Typografie

Bitte überarbeiten Sie Ihre Bildübersicht mit den Angaben aus der [Cranach Demodaten Tabelle](https://docs.google.com/spreadsheets/d/e/2PACX-1vSZDap28Dr0Q7gV3RFQ_rSa-KXBNwzSEvmsWp3p26qbQc0nBuoh0jo6cF-q_FclOTMl7dmgLcJ07b6w/pub?output=csv). Erzeugen Sie bitte Markup für 16 Bilder.

Als Basis für diese und die folgenden Aufgaben dienen folgende Dokumente:  
* [Styleguide](https://finnge.github.io/mi-sd-cranachproject/assets/img/style-guide.svg) 
* [Layout](../../material/frontend-development-1/session-2/aufgabe-2/cda_timeline_size-small.png)

Um ein browserübergreifend konsistentes Grundlayout zu erhalten, binden Sie zunächst eine `reset.css` oder `normalize.css` aus einem  Content Delivery Network ein.

Erzeugen Sie nun ein Verzeichnis mit der Bezeichnung `styles` und darin eine Datei mit dem Namen `cda-base.css`. Binden Sie diese CSS-Datei in die Datei `index.html`, aus dem HTML Basics Workshop, ein.

Definieren Sie in der `cda-base.css` folgende Regeln:

* Alle Elemente sollen die im Styleguide angegebene Schriftart verwenden. Binden Sie die Schriftart dazu bitte über [Google Fonts](https://fonts.google.com) ein.
* Die Textelemente sollen, hinsichtlich der typografischen Angaben (Schriftgröße, -schnitt, -farbe und Zeilenabstand), mit dem Styleguide im Einklang sein.

## Augabe 3 - CSS // Basislayout

Legen Sie in der `cda-base.css` die im Styleguide definierten Hintergrundfarben für den Header und Contentbereich fest. Nutzen Sie dazu bitte class-Attribute im HTML und die dazugehörigen CSS-Selektoren.

Erzeugen Sie mit Hilfe von CSS-Grids das Grundlayout, bestehend aus Header und dem zwei spaltigen Contentbereich. Verwenden Sie dazu die Angaben unter „Grid” im Styleguide.

Mergen Sie zum Schluss den Branch `session-2` in den `master`.
