## Einleitung
#web

[[2023-04-07]]


[Obsidian.md](https://obsidian.md/) ist aus meiner Sicht eine der besten Notizen-Applikationen auf dem Markt.`.md` steht hier für die [Auszeichnungssprache Markdown](https://de.wikipedia.org/wiki/Markdown) und dient sowohl zur Unterscheidung zum gleichlautenden [vulkanischem Gesteinsglas](https://de.wikipedia.org/wiki/Obsidian) als auch zu [Obsidian Entertainment](https://de.wikipedia.org/wiki/Obsidian_Entertainment), einer amerikanischen Firma zur Entwicklung von Videospielen. Ich werde jedoch in meinen Artikeln diesen – für eine effiziente Internet-Recherche wichtigen – Zusatz in Zukunft weglassen.

![Obsidian Preise Cover Bild zeigt die Obsidian.md Oberfläche mit einer Notiz als Text und als verlinktes Diagramm nebeneinander.](https://i0.wp.com/peter.baumgartner.name/wp-content/uploads/2022/11/obsidian-cover-picture-min.png?resize=750%2C397&ssl=1)

Ein Beispiel der Obsidian Oberfläche mit einer Notiz in Text und Vernetzungsansicht entnommen von [Markdown Guide](https://www.markdownguide.org/tools/obsidian/) von [Matt Cone](https://www.mattcone.com/)  ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)). Ich glaube, dass dieses Bildschirmfoto selbst wieder aus dem [Linking Your Thinking (LYT) Werkzeugkasten](https://www.linkingyourthinking.com/download-lyt-kit-6) von Nick Milo stammt.

Dieser Beitrag ist sozusagen die Overtüre für eine differenzierte und daher recht umfangreiche Sammlung von Beiträgen zur Methodik wissenschaftlichen Arbeitens mit Hilfe von Obsidian geplant. Die geplanten Artikel gliedern sich grob in zwei Stränge:

-   Auf der einen Seite gibt es Beiträge, die relativ unabhängig vom jeweiligen Werkzeug kognitive Anforderungen beim wissenschaftlichen Arbeiten und die dafür geeigneten Arbeitsabläufe beschreiben. Diesen Strang meiner Argumentation habe ich auf der Seite zum [Zettelkasten-Konzept](https://peter.baumgartner.name/sammlungen/awdw-buchprojekt/zettelkasten-konzept/) gesammelt.
-   Auf der anderen Seite zeige ich an praktischen Beispielen, wie diese konzeptionellen Ideen effektiv umgesetzt werden können. Dabei muss ich soweit ins Detail gehen, dass eine gewisse technische Schlagseite (macOS, Obsidian, …) unvermeidlich ist. Mit einfachen Internet-Recherchen jedoch können meine Beispiele für andere Betriebssysteme und Software-Applikationen relativ leicht adaptiert werden. Diese How-To Tutorials habe ich auf der Seite [Obsidian Tutorials](https://peter.baumgartner.name/sammlungen/awdw-buchprojekt/obsidian-tutorials/) versammelt.

## Obsidian Preise als Freemium-Modell

Das Freemium-Modell von Obsidan hat 5 unterschiedliche preisliche Modalitäten:

### Personal

Für die persönliche Nutzung ist der gesamte Funktionsumfang von Obsidian kostenlos. Das schließt sowohl die Nutzung aller 742 Erweiterungen (Plugins), den Zugang zur [API-Schnittstelle](https://github.com/obsidianmd/obsidian-api) als auch zu den stark frequentierten freundlichen [Community-Foren](https://obsidian.md/community). Es gibt ein offizielles [Community-Forum](https://forum.obsidian.md/), das besonders hilfreich für die Erklärung von Funktionen, Tipps aber auch Fehler (Bugs) ist. Daneben gibt es auch einen [Discord Kanal für Obsidian](https://discord.com/channels/686053708261228577/@home) mit 80.076 Mitgliedern (Obsidian Member Group, OMG), der besonders für lockeren Umgang und Austausch von Diagrammen, Überlegungen und anderen Ideen ist. Interessant um Hilfe zu bekommen ist wohl auch der [Reddit Kanal](https://www.reddit.com/r/ObsidianMD/) und natürlich die [Hilfeseiten von Obsidian](https://help.obsidian.md/Obsidian/Index) selbst (Zahlen mit Stand 13.12.2022).

### Catalyst

Diese Preisebene ist gedacht als Unterstützung der Entwicklungsarbeit und startet mit einer Einmalzahlung von 25 US $ (nach oben offen). Als Gegenleistung gibt es einen frühzeitigen Zugang zu neuen Versionen („Insider builds“), zu einem Diskussionskanal speziell für Entwickler:innen und zu Badges.

### Commercial

Kommerzielle Nutzung kostet 50 US $ pro Jahr und Nutzer:in und sichert vorrangige Unterstützung (Priority Support).

![Bildschirmfoto der Obsidian Preise: Personal 0 US Dollar, Catalyst Einmalzahlung US Dollar 25+ und Commercial mit 50 US Dollar pro Jahr und Nutzer:in.](https://i0.wp.com/peter.baumgartner.name/wp-content/uploads/2022/11/image-2.png?resize=750%2C573&ssl=1)

**Obsidian Preise 1**: Die persönliche Nutzung von Obsidian ist kostenlos (für immer / forever). Für kommerzielle Nutzung muss jedoch gezahlt werden.

## Obsidian Preise für zusätzliche Services

Außerdem gibt es zwei spezielle zusätzliche Services für die bezahlt werden muss. Sie sind aber für den normalen Betrieb nicht notwendig – und können durch andere (kostenlose) Applikationen zum Teil auch ersetzt werden.

### Obsidian Syn**c**

Das ist die offizielle Synchronisationslösung der Entwickler:innen von Obsidian. Sie kostet 8 US $ pro Monat und soll – nach übereinstimmenden Berichten [in reddit](https://www.reddit.com/r/ObsidianMD/comments/s7u7p5/people_who_use_obsidian_sync_whats_it_like_and_is/) oder [YouTube Foren](https://www.youtube.com/watch?v=Y3lRlLQvYpY) – sehr gut funktionieren.

Allerdings gibt es hierzu auch sehr viele Hinweise für kostenlose vorgefertigte Alternativen, sei es mit [Google Drive](https://drive.google.com/), [One Drive](https://onedrive.live.com/), [iCloud](https://www.icloud.com/), [Dropbox](https://www.dropbox.com/), [FolderSync](https://www.tacit.dk/foldersync), [syncthing](https://syncthing.net/downloads/) (z.B. [hier](https://www.youtube.com/watch?v=t3cy132eeUU "Video: How to sync Obsidian 4 FREE"), [hier](https://www.youtube.com/watch?v=t3cy132eeUU "Video: How to Sync your Obsidian Vault for Free!") und [hier](https://www.youtube.com/watch?v=WyVcUNLs8B0 "Video: How to Sync Obsidian MD Notes for FREE Across Windows and Android/Mobile Devices using OneDrive")). Es gibt auch die Möglichkeit sich z.B. mit [Git](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)/[Github](https://github.com/) selbst eine Synchronisationslösung zurecht zu legen (siehe den dreiteiligen Artikel beginnend mit [Obsidian Sync](https://www.munish-mehta.com/posts/obsidian-sync/) oder über verschiedene (kostenlose) Obsidian Plugins für Synchronisation (z.B. [Remotely Save](https://github.com/remotely-save/remotely-save) oder [Self-hosting Livesync](https://github.com/vrtmrz/obsidian-livesync)).

### Obsidian Publish

Damit können ohne technische Kenntnisse ausgewählte Notizen zu Webseiten umgewandet und publiziert werden. Der Preis ist jedoch mit 16 US $ pro Monat recht ansehnlich.

Allerdings gibt es auch für diese Funktion viele kostenlose Alternativen, sei es mit Obsidian Plugins (z.B. [Obsidian Digital Garden](https://github.com/oleeskild/obsidian-digital-garden), siehe auch die [Dokumentation mit Beispielen](https://dg-docs.ole.dev/), [Obsius Obsidian Plugin](https://github.com/jonstodle/obsius-obsidian-plugin) oder [Obsidian WordPress Plugin](https://devbean.github.io/obsidian-wordpress/) ) oder auch mit anderen Werkzeugen (z.B. [hier](https://beingpax.medium.com/how-to-publish-your-obsidian-notes-online-for-free-851af90e797 "Prakash Joshi Pax: How to Publish Your Obsidian Notes Online For Free"), [hier](https://forum.obsidian.md/t/notenote-link-publish-your-obsidian-notes-with-jekyll-for-free/7951 "Notenote.link - Publish your Obsidian notes with Jekyll for free!") und [hier](https://beingpax.medium.com/7-obsidian-publish-alternatives-to-publish-your-notes-online-for-free-33db4fb06f5 "Prakash Joshi Pax 10 Obsidian Publish Alternatives to Publish Your Notes Online for Free")).

Ich habe selbst die verschiedenen Möglichkeiten noch nicht probiert. Ich vermute aber, dass die kostenlosen Alternativen technisch komplizierter umzusetzen sind und möglicherweise auch nicht alle Funktionen, wie z.B. die wunderschöne dynamische grafische Darstellung der Backlinks von Obsidian, beinhalten.

![Bildschirmfoto der Obsidian Preis für Synchronisation (8 US Dollar / Monat) und Publikation (16 US DOllar / Monat) Webservices.](https://i0.wp.com/peter.baumgartner.name/wp-content/uploads/2022/11/image-1.png?resize=667%2C717&ssl=1)

**Obsidian Preise 2**: Für spezielle zusätzliche Services muss ebenfalls bezahlt werden. Allerdings sind sie für die Funktionsfähigkeit von Obsidian nicht notwendig und es existieren auch viele kostenlose – wenngleich meist technisch etwas aufwändigere –Alternativen.

## Nachhaltigkeit: Lokale, frei zugängliche Textdateien

Ein entscheidender Punkt bei der Beurteilung der Obsidian Preise – wenn auf externe cloud-basierte Lösungen verzichtet wird – ist, dass alle **Notizen als lokale, frei zugängliche Textdateien** verfügbar sind. Obwohl sie die Endung `.md` haben und in Markdown formatiert sind, können sie von jedem Texteditor geöffnet und ohne Hilfsmittel gelesen und somit auch auf der Betriebssystem-Ebene manipuliert (umbenannt, kopiert etc.) werden.

Inzwischen ist die Auszeichnungssprache Markdown soweit verbreitet, dass sie zunehmend als Quasi-Standard für den Transfer zwischen Notizen-Applikationen gilt. Außerdem gibt es dutzende kostenlose Konvertierprogramme oder Webservices, die Markdown-Dateien in alle möglichen Formate und Dateien für Anwendungsprogramme (HTML, [PDF](https://peter.baumgartner.name/glossary/pdf/), Text, Tabellen, MS Word, LibreOffice, …) umwandeln.

Die frei zugängliche Textdateien von Obsidian sind ein großer Vorteil gegenüber anderen Notiz-Applikationen. Häufig sind die Dateien von Notiz-Software unzugänglich, entweder weil sie in Datenbanken versteckt oder anderweitig mit propriäterer Software verschlüsselt sind. Mit lokalen Markdown-Dateien sind Benutzer:innen daher langfristig immer auf der sicheren Seite und nicht vom Auf- und Ab des jeweiligen Anwendungsprogramms abhängig. Weder gibt es Kompatibilitätsprobleme mit unterschiedlichen Dateiformaten bei neuen Versionen, noch ist ein Ausstieg bzw. Umstieg auf eine andere Softwareumgebung gefährdet.

## Zusammenfassung

Dieser Beitrag startet zwar die Serie zur Nutzung von Obsidian, ist aber selbst kein How-To Tutorial. Ich beschreibe die fünf verschiedenen preislichen Optionen von Obsidian und weise auf mögliche Alternativen für kostenpflichtige Services hin.

Zu beachten ist, dass die Installation mancher Ausweichmöglichkeiten ein gehobenes technisches Verständnis und digitale Kompetenz erfordern. Allerdings werden diese kostenpflichtigen Services für eine effiziente – aber nicht-kommerzielle – Nutzung von Obsidian nicht benötigt.