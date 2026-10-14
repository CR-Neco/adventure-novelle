# Dokumentation und laufende Buchpflege

## Ziel
Aus den tatsächlich gespielten Sitzungen entsteht eine **fortlaufende Fantasy-Novelle**. Die Romanfassung wird nach Spielsitzungen aktualisiert; das GitHub-Repository dient als langfristiger Speicher und Übergabepunkt zwischen Chats.

## Verbindliche Dateien
- **`export/Die_Glocken_von_Dornwacht.docx`** – vollständige Word-Romanfassung (30 Seiten, Stand: Ende der ersten Sitzung), als **Originaldatei** übertragen.\n- **`roman/Die_Glocken_von_Dornwacht.md`** – **vollständige durchsuchbare Textfassung**, absatzgetreu aus dem Word-Dokument übernommen und mit vier explizit gekennzeichneten Spielerpassagen. Für neue Chats direkt über die GitHub-Verbindung lesbar.
- **`KAMPAGNENSTAND.md`** – knapper, aber präziser bekannter Spielstand; immer mit letztem Satz und nächstem Zug.
- **`SPIELREGELN.md`** – Regeln und OOC-Konventionen.
- **`SPIELLEITUNG_START.md`** – vollständige Übergabe für neue Spielleiter-Chats.
- **`charaktere/*.md`** – Profile und nur tatsächlich entwickelte Beziehungen.
- **`WELT_UND_KANON.md`** – bekannte Orte, Figuren und Beobachtungen.
- **`bilder/`** – verbindliche Bildreferenzen und später freigegebene Illustrationen.

## Ablauf am Sitzungsende
1. Alle neuen Spieler- und Spielleiterbeiträge aus dem Sitzungsverlauf zusammentragen.
2. **Nur** tatsächlich erzählte Handlung und Dialoge an die Word-Romanfassung **und die Markdown-Textfassung** anhängen. Keine frei erfundenen Übergänge, Entscheidungen oder Reaktionen.
3. Spielerpassagen **marineblau** formatieren (Referenzfarbe `#16396D`); übriger Romantext schwarz.
4. Nur Rechtschreibung, Tippfehler, Zeichensetzung und direkte Rede behutsam korrigieren.
5. OOC-Passagen **nicht** in den Roman übernehmen.
6. Neue Kapitel und Absätze lesefreundlich setzen; bestehende Texte und Szenen nicht ohne Auftrag umschreiben.
7. `KAMPAGNENSTAND.md` auf den **exakten** Haltepunkt aktualisieren, einschließlich offener Fragen und der Position der Beteiligten.
8. Neue **bekannte** Fakten in `WELT_UND_KANON.md`, veränderte Beziehungen in den Charakterprofilen ergänzen.
9. **Word und Markdown inhaltlich synchron halten.** Dateien nach GitHub übertragen, anschließend Commit und Dateipfade **überprüfen**. Bei fehlendem Schreibzugriff nichts als gespeichert behaupten.

## Übergabe an neuen Chat
Die Kurzform des Start-Prompts steht in `README.md`. Im neuen Chat sind die Repository-Dateien zu lesen. Ein bloßer Link ohne tatsächlichen Abruf ist keine ausreichende Kontextübernahme.

## Vertraulichkeit der Handlung
Keine geheimen Spielleiterinformationen ins Repository schreiben, auch nicht verschlüsselt. Der Spieler hat Zugriff auf sämtliche Repository-Dateien.

## Illustrationen
Skarra hat vom Spieler vorgegebene Bildreferenzen. Andere Figuren und Szenen werden erst auf ausdrücklichen Wunsch illustriert. Bei Einbindung in das Word-Manuskript Quelle, Zuordnung und Position im Text sorgfältig pflegen.

## Technischer Hinweis
Die GitHub-Anbindung kann Textdateien unmittelbar pflegen; für **binäre DOCX-Dateien** kann ein gesonderter Upload-/Git-Blob-Schritt erforderlich sein. Der Spielleiter muss das tatsächliche Commit-Ergebnis überprüfen. Die Word-Datei nicht durch eine bloße Markdown-Zusammenfassung ersetzen.
