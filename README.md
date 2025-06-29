# Tiermanagement-App

## 1. Export-Tabelle aller Anforderungen (MoSCoW, User Story, Beschreibung, Typ)
 
| Nr. | Titel                                     	| Beschreibung / User Story | Priorität | Typ (funktional/nicht-funktional) |
|-----|-----------------------------------------------|---------------------------|-----------|-----------------------------------|
| F1  | Mehrere Tiere/Tierarten verwaltbar        	| Mehrere Tiere anlegen und verwalten. | Muss | Funktional |
| F2  | Rollenmodell mit Besitzer, Co-Besitzern, Kurzzeit-Helfern | Verschiedene Personen mit unterschiedlichen Rechten einladen. | Muss | Funktional |
| F3  | Eigene Nutzerprofile mit E-Mail und Passwort  | Registrierung, Login, Profildaten. | Muss | Funktional |
| F4  | Einladungsfunktion (Link, Gastzugriff etc.)   | Andere per Link/Benutzername einladen, Gastzugriff, Rechteverwaltung. | Muss | Funktional |
| F5  | Homescreen mit Aufgaben, Terminen, Notfallkontakten | Übersicht über aktuelle Aufgaben, Termine, neue Notizen, Notfallkontakte. | Muss | Funktional |
| F6  | Medizinische Infos & Historie (Upload/Download) | Medizinische Dokumente als PDF/Bild hochladen, Verlauf exportieren. | Muss | Funktional |
| F7  | Termine & Aufgaben pro Tier               	| Aufgaben und Termine pro Tier verwalten. | Muss | Funktional |
| F8  | Notizen pro Tier (anpinnbar, "neu" etc.)      | Notizen erstellen, anpinnen, als "neu" markieren. | Muss | Funktional |
| F9  | Haltungsinformationen pro Tier                | Haltungshinweise und Steckbrief für Dritte. | Muss | Funktional |
| F10 | Berechtigungsmanagement                   	| Bearbeitungsrechte flexibel vergeben/entziehen. | Muss | Funktional |
| F11 | Benachrichtigungssystem (E-Mail, Push, in-App, pro Tier) | Individuell steuerbare Erinnerungen/Kanäle pro Tier. | Muss | Funktional |
| F12 | Plattformunabhängigkeit (App/Web, offlinefähig) | Nutzung auf Mobil und Desktop, Notizen offline erfassbar. | Muss | Funktional |
| F13 | Impfpass/Impfhistorie                     	| Impfungen dokumentieren, Erinnerungen an Folgeimpfungen. | Muss | Funktional |
| F14 | Medikamentenverwaltung inkl. Vorrat/Ablauf	| Medikamente, Dosierung, Vorrat, Ablaufdatum, Erinnerungen. | Muss | Funktional |
| F15 | Futterplan/Futterhistorie inkl. Unverträglichkeiten | Fütterungshistorie, Unverträglichkeiten, Diäten dokumentieren. | Muss | Funktional |
| F16 | Notfallkontakte pro Tier & globaler Notdienst | Notfallkontakte (Tierärzte etc.), globaler Notdienst immer sichtbar. | Muss | Funktional |
| F17 | Dokumentenablage (allgemein)              	| Wichtige Dokumente (Versicherungen, Verträge, etc.) ablegen. | Muss | Funktional |
| F18 | Kontaktverwaltung                         	| Kontakte wie Hundetrainer, Pensionen, etc. speichern. | Muss | Funktional |
| F19 | Datenschutz: DSGVO-Konformität            	| Alle Anforderungen der DSGVO erfüllen. | Muss | Nicht-funktional |
| F20 | Barrierefreiheit: WCAG 2.2 AA             	| Design und Usability nach WCAG 2.2 AA für App und Web. | Muss | Nicht-funktional |
| F21 | Sicherheit (Passwort, HTTPS, etc.)        	| Sichere Konten, verschlüsselte Speicherung und Übertragung. | Muss | Nicht-funktional |
| F22 | Responsives Design                        	| Optimale Darstellung auf Mobil und Desktop. | Muss | Nicht-funktional |
| F23 | Komponentisiertes UI Design               	| Wiederverwendbare, modulare UI-Komponenten. | Muss | Nicht-funktional |
| F24 | Offline-Funktion (nur Notizen, Sync, Status)  | Notizen offline erfassen und nachträglich synchronisieren. | Sollte | Funktional |
| F25 | Export medizinischer Historie pro Tier    	| Medizinische Historie als PDF/Bild exportieren. | Sollte | Funktional |
| F26 | Alerts für neue/aktualisierte Einträge    	| Benachrichtigung bei neuen/aktualisierten Einträgen. | Sollte | Funktional |
| F27 | Erinnerungen an Routineaufgaben (Pflege etc.) | Automatische Erinnerungen an Routinepflege, Wurmkur, etc. | Sollte | Funktional |
| F28 | To-Do-Liste für gemeinsame Aufgaben       	| Aufgaben aufteilen, „wer hat was erledigt“. | Sollte | Funktional |
| F29 | Wachstums-/Gewichtskurve                  	| Wachstum und Gewicht als Verlauf/Diagramm. | Sollte | Funktional |
| F30 | Budget-/Ausgabenübersicht                 	| Ausgaben pro Tier dokumentieren. | Sollte | Funktional |
| F31 | Fotogalerie pro Tier                      	| Bilder/Fotos pro Tier speichern. | Sollte | Funktional |
| F32 | Tierkalender (alle Termine)               	| Übersicht aller wichtigen Termine für alle Tiere. | Sollte | Funktional |
| F33 | Mehrsprachigkeit (Vorbereitung im Design) 	| UI/UX für spätere Mehrsprachigkeit vorbereiten. | Könnte | Nicht-funktional |
| F34 | Export weiterer Daten (z.B. Aufgaben, Notizen) | Export von weiteren Datenformaten ermöglichen. | Könnte | Funktional |
| F35 | Standort-/Spaziergangshistorie            	| Spaziergänge/GPS-Daten dokumentieren. | Könnte | Funktional |
| F36 | Erinnerungen an Abo-Produkte/Nachbestellung   | Automatische Erinnerung an Futter, Medikamente etc. | Könnte | Funktional |
| F37 | Checklisten (Urlaub, Notfall etc.)        	| Checklisten für Reisen, Notfall, etc. erstellen. | Könnte | Funktional |
| F38 | QR-Code-Export für Notfalldaten           	| Notfalldaten als QR-Code exportieren. | Könnte | Funktional |
| F39 | Backup-/Wiederherstellungsfunktion        	| Daten sichern und auf neuem Gerät wiederherstellen. | Könnte | Funktional |
| F40 | FAQ-Bereich/Wissensdatenbank              	| Hilfebereich mit häufigen Fragen und Antworten. | Könnte | Funktional |
| F41 | Community-Chat/Forum                      	| Austausch mit anderen Tierhaltern. | Könnte | Funktional |
| F42 | Integration mit Tierärzten (API, Terminbuchung) | Daten und Termine mit Tierarzt austauschen. | Könnte | Funktional |
 
WCAG 2.2 AA Anforderungsliste

| Nr. | WCAG-Kriterium                                     	| Anforderung / Beschreibung                                                                                                | Beispiel Mobile                                                                | Beispiel Desktop                                                                               |
| --- | ------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| W1  | **Kontraste**                                      	| Text und interaktive Elemente müssen einen Kontrast von mind. 4.5:1 haben.                                                | Buttons, Links, Text auch bei Sonnenlicht gut lesbar.                      	| Navigation, Überschriften und Buttons immer ausreichend kontrastiert.                      	|
| W2  | **Flexible Schriftgrößen**                             | Text muss durch Betriebssystem/Browser vergrößerbar sein (bis 200%), ohne dass Inhalte verloren gehen oder überlappen.	| Zoom/Vergrößerung in iOS/Android; UI bleibt lesbar.                            | Browser-Zoom und Textgrößenanpassung ohne Layoutfehler.                                    	|
| W3  | **Bedienbarkeit per Tastatur**                     	| Alle Funktionen müssen ohne Maus bedienbar sein (Tab, Enter, ESC etc.).                                                   | Für mobile: Fokus-Indikatoren sichtbar beim Tab-Wechsel via Hardware-Tastatur. | Navigation, Formulare, Buttons komplett per Tastatur steuerbar, inkl. sichtbare Fokus-Anzeige. |
| W4  | **Touch-Ziele & Abstand**                              | Alle Touch-Elemente mind. 24x24px, optimal 44x44px, ausreichend Abstand.                                                  | Große Schaltflächen/Checkboxen, keine zu engen Touch-Flächen.              	| Buttons nicht zu klein, Abstände zwischen interaktiven Elementen.                          	|
| W5  | **Screenreader-Kompatibilität**                    	| Alle UI-Elemente müssen korrekt und eindeutig beschriftet sein (ARIA-Labels, Alt-Texte, Rollen, Überschriftenstruktur).   | Bilder und Icons mit Alt-Text, Buttons klar benannt, Labels für Formulare. 	| Strukturierte Überschriften (H1–H3), semantische HTML-Tags, sprechende ARIA-Labels.        	|
| W6  | **Fehlermeldungen verständlich**                   	| Fehler müssen klar, präzise und direkt am Eingabefeld ausgegeben werden; Korrekturmöglichkeit anbieten.               	| Validierungshinweis unter dem Feld, klare Sprache.                         	| Feldfarben, Icon & Text bei Fehler, Tastaturfokus auf Fehlermeldung.                       	|
| W7  | **Keine Informationen nur über Farbe**                 | Wichtige Infos nie ausschließlich über Farbe darstellen (z. B. Fehler rot + Symbol/Text).                                 | Status-Badges mit Icon/Symbol & Text.                                      	| Tabellen mit Farbcodes zusätzlich mit Symbolen/Beschriftung.                               	|
| W8  | **Bedienhilfen/Unterstützende Technologien**       	| App soll mit unterstützenden Technologien funktionieren (Screenreader, Sprachausgabe, Tastaturhilfen).                	| Test mit TalkBack/VoiceOver.                                                   | Test mit NVDA, JAWS, Windows-Screenreader.                                                     |
| W9  | **Verzicht auf Timeouts oder gut steuerbare Timeouts** | Keine automatischen Timeouts ohne Vorwarnung und Möglichkeit zur Verlängerung.                                        	| Nutzer wird vor Logout gewarnt, kann Zeit verlängern.                      	| Session-Timer mit Verlängerungsoption.                                                         |
| W10 | **Barrierefreie Formulare**                        	| Alle Formularfelder haben Labels, Hinweise, Fokus-Indikatoren und nachvollziehbare Fehlerausgabe.                     	| Label immer sichtbar, Fehler sofort erklärt.                               	| Alle Felder per Tab erreichbar, Fokus-Indikator klar sichtbar.                             	|
| W11 | **Einfache Sprache/Klarheit**                      	| Informationen, Hinweise, Menüs und Anleitungen müssen klar verständlich und einfach formuliert sein.                  	| Kurz & eindeutig („Aufgabe erledigt“, „Speichern“).                        	| Keine Fachbegriffe ohne Erklärung, klare Navigation.                                       	|
| W12 | **Fokus-Management nach Aktionen**                 	| Nach Öffnen/Schließen von Modals oder nach Fehler springt Fokus logisch auf das nächste sinnvolle Element.            	| Nach Pop-up schließt, landet Fokus wieder auf passender Schaltfläche.      	| Nach Fehleingabe springt Fokus auf Fehlerfeld.                                                 |
| W13 | **Vermeidung von Blinken/Flackern**                	| Keine Inhalte dürfen mehr als 3x pro Sekunde blinken (Epilepsie-Prävention).                                          	| Keine animierten Warnhinweise oder blinkenden Banner.                      	| Ruhige Animationen, keine schnellen Wechsel.                                                   |
| W14 | **Zugängliche Tabellen & Listen**                  	| Tabellen haben Kopfzeilen, strukturierte Listen, sprechende Überschriften.                                                | Produktliste als Liste mit Labeln, keine reinen Farbcodes.                 	| Medizinische Historie als Tabelle mit Headings und Spaltenbeschreibung.                    	|
| W15 | **Responsive/Adaptives Design**                    	| Inhalte passen sich jedem Bildschirm an, ohne zu scrollen/zu zoomen.                                                      | Keine horizontale Scrollbar, alle Inhalte auf kleinen Displays lesbar.     	| Desktop und Tablet Layouts klar strukturiert.                                                  |
| W16 | **Barrierefreie Benachrichtigungen**               	| Systemmeldungen (z. B. neue Aufgabe, Erinnerung) werden als ARIA-Live-Regionen oder systemkompatible Meldungen umgesetzt. | Neue Push-Meldung wird auch von VoiceOver vorgelesen.                      	| In-App-Benachrichtigung per Screenreader erfassbar.                                        	|

## 2. User Flows für die wichtigsten Use Cases

A. Tier anlegen & Basisdaten eintragen
Start: Nutzer wählt „Neues Tier anlegen“.
Basisdaten eingeben: Name, Tierart, Geburtsdatum, Geschlecht, Rasse, evtl. Foto.
Optionale Felder: Besondere Merkmale, Chipnummer, Allergien.
Steckbrief/Haltungshinweise erfassen (für Fremdbetreuer).
Speichern: Tier erscheint in der Übersicht, kann nun gepflegt werden.

B. Medizinische Informationen und Historie verwalten
Tier auswählen, Tab „Medizin“ öffnen.
Neuer Eintrag: „Medizinischer Vorfall/Behandlung/Impfung hinzufügen“.
Art auswählen: Behandlung, Impfung, Medikament, Sonstiges.
Daten eintragen: Datum, Art der Behandlung, Tierarzt, Dokument (PDF/Bild) hochladen, Notizfeld.
Optional: Erinnerungsfunktion (Folgetermin, nächste Impfung).
Speichern: Neuer Eintrag erscheint in der Historie, kann als PDF/Bild exportiert werden.

C. Aufgaben & Termine für ein Tier erstellen
Tier auswählen, Bereich „Aufgaben/Termine“ öffnen.
Neue Aufgabe oder Termin hinzufügen.
Details: Titel, Beschreibung, Fälligkeitsdatum, Uhrzeit, Wiederholung (z.B. täglich, wöchentlich), Erinnerung aktivieren (E-Mail, Push, In-App).
Zuweisung: Aufgabe ggf. an Mitnutzer zuweisen oder offen lassen.
Speichern: Aufgabe erscheint in der Tagesübersicht/Homescreen.
Statusänderung: Nutzer kann Aufgabe als „erledigt“ markieren (inkl. History).

D. Notizen erstellen, anpinnen & als „neu“ markieren
Tier auswählen, Tab „Notizen“ öffnen.
Neue Notiz verfassen, Text eingeben.
Optional: Notiz anpinnen (Schalter/Pin-Icon setzen).
Speichern: Notiz erscheint oben in der Liste (bei Pin) und mit Label „neu“ (für 2 Tage sichtbar).
Bearbeitung/Entfernen: Notiz kann (je nach Rechte) editiert oder entfernt werden.

E. Einladen von Co-Besitzern / Kurzzeithelfern
Tierprofil öffnen, Bereich „Mitwirkende“ auswählen.
Person per E-Mail, Benutzername oder Link einladen.
Rolle auswählen: Co-Besitzer (Standard: Schreibrechte) oder Kurzzeithelfer (Standard: Nur Notizen).
Für Kurzzeithelfer: Zeitraum festlegen (Zugriffsende).
Einladung versenden: Eingeladene Person erhält E-Mail oder Link.
Status sichtbar: Liste aller Mitwirkenden mit Rollen- und Rechteverwaltung.

F. Notfallkontakt hinzufügen & nutzen
Tier auswählen, Bereich „Notfallkontakte“ öffnen.
Neuen Kontakt hinzufügen: Name, Art (Tierarzt, Notdienst, Person), Telefonnummer, E-Mail, Adresse.
Optional: Markieren, ob Kontakt global (alle Tiere) oder nur für dieses Tier gilt.
Speichern: Kontakt erscheint in der Liste.
Im Notfall: Kontakt auf dem Homescreen/Notfallseite anklicken und direkt anrufen/anschreiben.

G. Impfpass / Impf-Erinnerung nutzen
Tier auswählen, Tab „Impfpass“ öffnen.
Impfung eintragen: Datum, Impfstoff, Tierarzt, Dokument (Impfpass-Scan) hochladen.
Erinnerung setzen: Zeitpunkt für Folgeimpfung festlegen.
App erinnert aktiv per Benachrichtigung an nächste Impfung.
Historie exportieren: Impfpass als PDF exportierbar.

H. Medikamentenverwaltung & Vorratsüberwachung
Tier auswählen, Tab „Medikamente“ öffnen.
Neues Medikament hinzufügen: Name, Dosierung, Einnahmezeiten, Vorratsmenge, Ablaufdatum.
Erinnerungen: An Einnahme und rechtzeitiges Nachkaufen erinnern lassen.
Bei Unterschreiten der Mindestmenge oder Ablaufdatum: Automatische Benachrichtigung/Reminder.

I. Aufgaben-/Kalenderübersicht für alle Tiere
Globalen Kalender öffnen (alle Tiere)
Alle Termine, Aufgaben, Impfungen, Medikamenteneinnahmen und Erinnerungen einsehen.
Filtern nach Tier, Aufgabe oder Zeitraum möglich.

J. Upload und Verwaltung von Dokumenten
Tier auswählen, Tab „Dokumente“ öffnen.
Neues Dokument hochladen: Kategorie wählen (Versicherung, Vertrag, Fotos etc.), Datei als PDF oder Bild auswählen.
Metadaten vergeben: Name, Datum, kurze Beschreibung.
Speichern: Dokument erscheint in der Dokumentenübersicht und kann heruntergeladen werden.
 

## 1. Testbeschreibungen zu den wichtigsten User Flows

A. Tier anlegen & Basisdaten eintragen
Ziel: Ein neues Tier erfolgreich anlegen und alle Pflichtfelder ausfüllen.
Vorbedingungen: Nutzer ist eingeloggt.
Ablauf:
Navigiere zum Bereich „Neues Tier anlegen“.
Trage Name, Tierart, Geburtsdatum, Geschlecht, ggf. Rasse/Farbe ein.
(Optional) Lade ein Foto hoch.
(Optional) Fülle Haltungshinweise/Steckbrief aus.
Klicke auf „Speichern“.
Erwartetes Ergebnis: Das Tier erscheint in der Übersichtsliste. Die Daten sind korrekt gespeichert und sichtbar.

B. Medizinische Informationen & Historie verwalten
Ziel: Eine medizinische Behandlung/Impfung erfassen, Dokument hochladen.
Vorbedingungen: Ein Tier ist angelegt.
Ablauf:
Öffne das Profil des Tiers, gehe zum Tab „Medizin“.
Klicke auf „Neuer medizinischer Eintrag“.
Trage Datum, Behandlungsart, Beschreibung, Tierarzt ein.
Lade ein PDF/Bild als Dokument hoch.
Klicke auf „Speichern“.
Erwartetes Ergebnis: Neuer Eintrag erscheint in der Historie mit Dokument. Download funktioniert, Daten stimmen.

C. Aufgaben & Termine für ein Tier erstellen
Ziel: Aufgabe mit Erinnerung für ein Tier anlegen.
Vorbedingungen: Ein Tier existiert.
Ablauf:
Öffne das Tier, gehe zu „Aufgaben/Termine“.
Erstelle neue Aufgabe, wähle Datum/Uhrzeit, Beschreibung.
Setze Erinnerung (E-Mail, Push, In-App).
Speichere.
Erwartetes Ergebnis: Aufgabe ist sichtbar und wird zum angegebenen Zeitpunkt als Erinnerung angezeigt.

D. Notizen erstellen, anpinnen & als „neu“ markieren
Ziel: Notiz erstellen, anpinnen und nach 2 Tagen prüfen, ob das „neu“-Label verschwindet.
Vorbedingungen: Ein Tier existiert.
Ablauf:
Gehe zum Tab „Notizen“.
Schreibe eine neue Notiz, pinne sie an.
Speichere.
Prüfe, ob sie als „neu“ angezeigt wird und oben in der Liste erscheint.
(Optional) Zeit simulieren/nach 2 Tagen testen, ob das Label entfernt ist.
Erwartetes Ergebnis: Notiz ist sichtbar, als „neu“ markiert, gepinnt; Label verschwindet nach Ablauf.

E. Einladen von Co-Besitzern / Kurzzeithelfern
Ziel: Co-Besitzer und Kurzzeithelfer erfolgreich einladen und Rechte prüfen.
Vorbedingungen: Nutzer ist Besitzer eines Tiers.
Ablauf:
Öffne das Tierprofil, Bereich „Mitwirkende“.
Gebe E-Mail/Benutzername eines Testnutzers ein.
Wähle Rolle: Co-Besitzer/Kurzzeithelfer.
Für Helfer: Enddatum setzen.
Sende Einladung, prüfe E-Mail/Link.
Logge dich mit eingeladenem Nutzer ein, prüfe Rechte (Notizen, Lesen, Schreiben).
Erwartetes Ergebnis: Nutzer kann sich anmelden, erhält die passenden Rechte und sieht das Tier korrekt.

F. Notfallkontakt hinzufügen & nutzen
Ziel: Notfallkontakt erfassen und direkt anrufen.
Vorbedingungen: Ein Tier existiert.
Ablauf:
Gehe zu „Notfallkontakte“.
Erfasse Tierarzt/Notdienst mit Telefonnummer.
Speichere.
Klicke auf Kontakt, um Anrufoption zu testen.
Erwartetes Ergebnis: Kontakt ist sichtbar, Anklicken öffnet Telefonwahl (auf Smartphone).

G. Impfpass / Impf-Erinnerung nutzen
Ziel: Impfung erfassen, Folge-Erinnerung setzen, Export testen.
Vorbedingungen: Tier ist angelegt.
Ablauf:
Gehe zum „Impfpass“-Tab.
Erstelle neuen Impfeintrag (Datum, Impfstoff, Tierarzt).
Setze Termin für Folgeimpfung.
Teste Export als PDF.
Erwartetes Ergebnis: Eintrag erscheint, Erinnerung wird aktiv, Export funktioniert.

H. Medikamentenverwaltung & Vorratsüberwachung
Ziel: Medikament samt Vorrat/Ablaufdatum erfassen, Nachbestell-Erinnerung prüfen.
Vorbedingungen: Tier existiert.
Ablauf:
Gehe zum Tab „Medikamente“.
Neues Medikament (Name, Dosierung, Vorrat, Ablaufdatum) hinzufügen.
Erinnerung aktivieren.
Simuliere, dass der Vorrat unter Mindestwert fällt/Datum erreicht wird.
Erwartetes Ergebnis: Erinnerung wird korrekt angezeigt.

## 2. Testprotokoll-Vorlage (Markdown-Tabelle)

Du kannst diese Tabelle für jeden Testlauf (manuell oder digital) nutzen und nach Bedarf anpassen.

| Testfall-Nr. | Testbeschreibung         	| Tester  | Datum     | Status (OK/Fehler) | Bemerkung/Fehlerbeschreibung          	|
|--------------|------------------------------|---------|-----------|--------------------|-------------------------------------------|
| 1        	| Tier anlegen & Basisdaten	| Max 	| 01.08.25  | OK             	|                                       	|
| 2        	| Medizinische Infos eintragen | Lisa	| 01.08.25  | Fehler         	| Upload fehlgeschlagen (Format nicht erkannt)|
| 3        	| Aufgabe mit Erinnerung   	| Tom 	| 01.08.25  | OK             	|                                       	|
| ...      	| ...                      	| ... 	| ...       | ...            	| ...                                   	|

Spalten-Erklärung:
Testfall-Nr.: Nummer laut Testplan/Flow.
Testbeschreibung: Kurzbeschreibung, was getestet wird.
Tester: Wer testet.
Datum: Testdatum.
Status: OK, Fehler, Nicht getestet.
Bemerkung/Fehlerbeschreibung: Genaue Problembeschreibung, falls aufgetreten.
