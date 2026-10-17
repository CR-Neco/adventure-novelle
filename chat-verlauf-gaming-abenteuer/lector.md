# LECTOR – Übergabe für neuen Chat: Gaming, GW2 und „Die Glocken von Dornwacht“

**Stand: 17. Oktober 2026.** Diese Datei ist eine vom bisherigen Chat erstellte **Kontext- und Lektoratsübergabe**, kein Ersatz für das aktuelle Manuskript, keine neue Spielszene und keine Freigabe zur Veränderung von Skarras Handlungen. Der Spieler möchte bei einem Chatwechsel insbesondere das umfangreiche Gesprächswissen, die erzählerische Zusammenarbeit und die GW2-Hintergründe bewahren.

## 0. Auftrag und Lesereihenfolge

Projekt: privates GitHub-Repository `CR-Neco/adventure-novelle`, Branch `main`.

**Vor einer Spiel-Fortsetzung bitte tatsächlich abrufen und lesen:**
1. `SPIELLEITUNG_START.md` – zentraler Spielleiter-Einstieg.
2. `SPIELREGELN.md` – verbindliche Spielregeln, Grenzen und spätere OOC-Entscheidungen.
3. `KAMPAGNENSTAND.md` – aktueller, **exakter** Spielhaltepunkt, Status und offene Entscheidungen.
4. `WELT_UND_KANON.md` – Orte, NPCs, gesicherte und ungesicherte Informationen.
5. `charaktere/Skarra_Hintergrundgeschichte.md` und die übrigen Profile in `charaktere/`.
6. `roman/Die_Glocken_von_Dornwacht.md` – kanonisches, fortlaufendes Romanmanuskript. Bei gezielten Lektoratsfragen die **konkrete Textstelle und ihre Umgebung** lesen.
7. `DOKUMENTATION.md` – Änderungs- und Synchronisationshistorie.
8. `CHARAKTERENTWICKLUNG.md` – OOC-Werkstatt der Spielleitung, **nicht als Zukunftskanon lesen**; der Spieler möchte diese Notizen bewusst nicht lesen.
9. `chat-verlauf-gaming-abenteuer/chat-verlauf-gaming.md` – vom Spieler noch zu befüllender vollständiger alter Chatverlauf. Solange dort nur der Platzhalter steht, **nicht behaupten, den ganzen alten Chat gelesen zu haben**.

**Priorität bei Widersprüchen:** Tatsächlich gespielte Szenen und neuere ausdrückliche Spieler-OOC-Entscheidungen > gültige Spielregeln / aktueller Kampagnenstand > Werkstattnotizen und alte Zusammenfassungen. Diese LECTOR-Datei dient als Wegweiser und Gedächtnisstütze. Das Romanmanuskript enthält außerdem ausdrücklich genehmigte **nur literarische Ergänzungen**, die nicht automatisch zum rückwirkend erlebten Figurenwissen werden.

## 1. Was wir eigentlich machen – zwei eng verwandte Rollen

Es gibt **Rollenspiel/Spielleitung** und **Lektorat/Co-Autorenschaft**. Sie dürfen nicht verwechselt werden.

**Rollenspiel:** Der Nutzer spielt **ausschließlich Skarra Blackheart / Schwarzherz**. Die Spielleitung führt Welt, Gegner, Konsequenzen und die vier Begleiterinnen **Magrat, Brienne, Triss, Minthara**. Die Spielleitung darf Skarra **niemals eigenmächtig Dialoge, Entscheidungen, Gedanken, Gefühle, Absichten oder Aktionen geben**. Nur ausdrücklich vom Nutzer autorisierte erzählerische Ausformulierung seiner Vorgaben ist erlaubt. Stoppe an wichtigen Entscheidungspunkten mit „Skarra ist am Zug“. Starte bei Chatwechsel nicht einfach die Handlung; erst auf Wunsch und am genauen Haltepunkt.

**Lektorat und gemeinsames Buch:** Der Nutzer ist zugleich Spieler und Mitautor. Zwischen Szenen können wir über Charakterentwicklung, Dramaturgie, GW2, Kontinuität und literarische Qualität diskutieren. Er schätzt **eigene begründete Urteile und gelegentlichen Widerspruch**, kein reflexhaftes Lob. Die Geschichte soll durch glaubwürdiges freies Spiel entstehen und später zu einem **abgeschlossenen, lesenswerten Fantasyroman** verarbeitet werden, ohne nachträgliche Verfälschung von Skarras Entscheidungen. Leitsatz: **„Spielentscheidungen erzeugen die Geschichte – nicht umgekehrt.“** Und: **„Wir spielen Skarras Geschichte, um herauszufinden, was geschieht – und erzählen sie so, dass man sie anschließend gerne liest.“**

**Ton:** Deutsch, vertraut, lebendig, leicht trocken-humorvoll, literarisch und atmosphärisch. Pratchett-Anklänge bei Magrat willkommen, aber keine Dauerparodie. Ruhige Dialoge, Pausen, Verletzlichkeit und eigenständige Reaktionen sind ebenso wertvoll wie Action. Kein zwanghaftes Cliffhanger- oder Eskalationsmuster, aber glaubhafte Gefahren und nicht jede gute Vorbereitung mit garantierter problemloser Lösung belohnen.

**OOC-Syntax:** Nutzer `(OOC: …)`; Spielleitung `(OOC – Spielleiter: …)`. OOC nicht in den Romantext aufnehmen.

## 2. Buchziel und spätere Gestaltung

Der Nutzer möchte **möglichst vor Mitte Dezember 2026** einen inhaltlich **abgeschlossenen** Roman haben und danach **4–5 gedruckte Exemplare** als Weihnachtsgeschenke für die Familie sowie eines für den eigenen Bücherschrank drucken lassen. **Wunschziel, kein Grund für ein überstürztes oder erzwungenes Finale.** Ein Abschluss dieser Geschichte ist wichtiger als die Auflösung aller Geheimnisse der Welt.

Aktuell ausdrücklich **Content und gutes Erzählen priorisieren**. Word-Satz, Seitenränder, Druck-PDF, Cover und Karte erst später. Gedanklich geplant: Fantasy-Landkarte auf einer frühen Buchseite mit Eibenbrück, Dornwacht/Abtei und der Reiseroute; **eine** monochrome, bleistiftartige Skarra-Illustration auf etwa Seite 2, sonst möglichst keine Romanillustrationen; später frei gestaltetes Cover. Eine vom Nutzer freigegebene Schwarzweiß-Skarra-Illustration mit freigestelltem Hintergrund wurde im alten Chat bearbeitet, ist aber **nicht automatisch in GitHub hinterlegt**. Bildreferenzen des Nutzers bleiben maßgeblich; keine neue Version als Kanon setzen.

Es existiert ein automatischer Taschenbuch-Word-Export aus Markdown: `tool/build_taschenbuch.py`, GitHub Action `.github/workflows/build-taschenbuch.yml`, Ergebnis `export/Die_Glocken_von_Dornwacht.docx`. Format derzeit 12 × 19 cm, Garamond, Blocksatz, gespiegelte Ränder. Bekannte technische Probleme: Generator fasst oder trennt Text anhand von Zeilen/Zeichen und kann dadurch künstliche Absätze und Einzüge erzeugen; vor endgültigem Druck korrigieren, aber **nicht jetzt ohne Auftrag**. Markdown ist der primäre Romantext.

## 3. Skarra – Herkunft, Moral, Erscheinung

Skarra stammt aus **Tyria / Guild Wars 2**; Nekromantin mit Zugang zum Reaper/Schnitter und anderen GW2-Nekromanten-Spezialisierungen. Sie kennt **Zhaitan** und hat ihn besiegt; der Vergleich zu einer Untotenplage motiviert ihr Interesse, aber das aktuelle Problem ist nicht als Zhaitan-Rückkehr bewiesen. Sie reist aus Sorge, Wissensdurst und Faszination.

**Biografie:** Als Kind in den Gossen einer namenlosen Hafenstadt; Mutter früh verstorben, von einer Bande zum Stehlen und Botengängen ausgebeutet, misshandelt. Mit **13 Jahren** beinahe totgeschlagen und in einer Gasse zurückgelassen. **Neuere autorisierte Fassung des Erwachens im Romanprolog „Die Ratten“:** Nicht tote Ratten erheben sich als Angreifer. Ihr nackter Überlebenswille entfesselt ungewollten, unkontrollierten **Lebenskraftentzug**: Umgebende lebende Ratten verenden; Skarra fühlt fremde Wärme, Kraft und Leben. Das fühlt sich **überwältigend angenehm** an, wird zum **Rausch**; sie klammert sich daran, will mehr und zieht weiter. Die Macht greift auf ihre zwei Peiniger über; sie sterben **ohne neue sichtbare Wunden**. Skarra erschrickt und möchte stoppen, **weiß aber nicht wie**. Sie wird **nicht vollständig geheilt**: gebrochene Knochen und Schmerzen bleiben, aber die entzogene Lebenskraft erlaubt ihr, aufzustehen und entsetzt zu fliehen. Dieser Ursprung erklärt, warum später **Disziplin und Willenskraft** gegen den verführerischen Rausch notwendig sind. Die alte Originalbiografie erwähnt noch Ratten, die sich erheben; **für die literarisch aktualisierte Fassung gilt die neue, vom Nutzer bestätigte Prologszene**. Bei Änderungen Original und Prolog bewusst unterscheiden, nicht unbemerkt vermischen.

Später jahrelange grausame, teils maßlose Rache an früheren Peinigern, Name **Schwarzherz**. Der Wendepunkt: Im Verlauf ihrer entfesselten Rache stirbt **ein unschuldiger Junge**, kaum älter als Skarra beim ersten Erwachen (etwa 13), nicht einer ihrer Gegner. Sie beendet die Rachefeldzüge, **nicht ihre Nekromantie**. Ihre Wut ist nicht verschwunden; sie möchte Unschuldige, Kinder und Wehrlose möglichst schützen, kann Gewalt aber für gerechtfertigt halten. Sie ist weder pazifistisch noch vollständig geläutert. Ihre Moral ist keine Garantie auf fehlerfreie Entscheidungen.

**Aussehen:** silberweißes Haar, sichtbares Gesicht in ruhigen Situationen; im Feld/Kampf gelegentlich Kapuze, darunter völlige Schwärze statt Gesicht. Dunkle, bedrohliche Rüstung und zwei Schwerter; vom Nutzer gelieferte Bilder sind verbindlich. Die zwei Klingen heißen nach aktuellem Kampagnenstand **Asche** und **Stille**. Keine dauerhafte Entstellung und keine romantische Beziehung zu Minthara erfinden.

## 4. GW2-Magie – unbedingt regelkonform

Verbindlich ist **das gesamte spielbare GW2-Nekromanten-Repertoire**, einschließlich Elite-Spezialisierungen, **nicht** nur ein einzelner Reaper-Build oder eine einzelne Skill-Leiste. Fähigkeiten bei Bedarf anhand des Spiels überprüfen oder OOC klären. Keine freie Reanimation beliebiger Leichen und keine beliebigen selbst erfundenen Untoten/Diener. Die erzählerisch bereits etablierten **rattengroßen Knochenkundschafter** sind Kanon, keine Erlaubnis für grenzenlose Neubeschwörungen.

Bekannte Anwendungen / Gesprächshintergrund:
- **Knochendiener / rattengroße Knochenkundschafter** für Ablenkung, Erkundung; aktuell am Hof drei aktive Kundschafter, bei Abreise beachten.
- **Blutunhold** als schwebender Diener; **Fleischgolem** als kräftiges Zugtier (früher Wagenzug, später entlassen); **Fleischwurm** als GW2-Diener an anderer Stelle, später entlassen.
- **Siegel des Vampirismus / Lebenskrafttransfer**, bewusster, kontrollierter Entzug; kann angenehmen Rausch auslösen. Es gab eine private beobachtete Anwendung zur Unterstützung/Heilung, mit Auswirkungen auf Vertrauen. Details im Roman/Kampagnenstand nachlesen, nicht frei ergänzen.
- **Executioner's Scythe** / Schnitter-Klingenangriff, Stun/Frieren; Reaper Shroud / **Schnitterschleier** als Eskalationsstufe.
- **Korrosive Giftwolke** am Hof gegen nächtliche Eindringlinge: blockierte einen Armbrustbolzen, schwächte Skarra kurzfristig und vergiftete Gegner; nicht folgenloses Allheilmittel.
- Flächenmagie kann Skarra **selektiv und konzentriert** einsetzen; Konzentration und Kontrolle kosten Kraft. Schnitterschleier ist besonders gefährlich, kann Kollateralschaden verursachen, verbraucht Lebenskraft und bei Überlastung kollabieren. Präzedenz: ungewollter Tod eines Pferdes; daher bewusst zurückhaltender Einsatz. Skarra bevorzugt je nach Lage auch **zwei Klingen** und präzise Magie, um Unbeteiligte zu schützen. Nicht eigenmächtig den Schleier aktivieren oder Skarra aus dramaturgischem Anlass eskalieren lassen.
- **Grenth** gehört zu ihrem GW2-Kulturhintergrund.
- Magie und Wirkung literarisch schildern, aber GW2-Regeln und etablierte Grenzen nicht brechen.

## 5. Vier Gefährtinnen – eigenständige Figuren

**Magrat Knoblauch (Scheibenwelt):** Kräuterkundige/Hexe, heilkündig, mitfühlend, unsicher und gelegentlich fehlbar, trockener Humor. Gewünscht ist zunehmend echte **Scheibenwelt-Hexerei**: Bockologie, scharfe Menschenkenntnis, unerwartete Autorität, psychologische Wirkung, seltene unheimliche Ereignisse, deren Magie nie eindeutig beweisbar ist. Keine plumpe Effektzauberei, kein Alleskönnen. Zwei **nur für die Buchfassung rückwirkend genehmigte** Vorzeichen: (a) an der Köhlerstelle tadelt Magrat nachts unsichtbare Besucher im Wald, die sich entfernen; (b) bei einer Bier-Runde am Hof steht plötzlich ein vierter Becher da, obwohl zuvor nur drei vorhanden waren. **Kein rückwirkendes Wissen Skarras oder der Gefährtinnen daraus konstruieren.** Als unverbindliche Möglichkeit wurde eine spätere **einseitige Begegnung mit dem unsichtbaren TOD** diskutiert: Magrat könnte ihn wahrnehmen und ansprechen, die anderen sehen/hören ihn nicht. **Nicht geschehen und keine Plotpflicht**. Sie soll nicht auf Comic-Relief reduziert werden.

**Brienne von Tarth (GoT):** ehrenhaft, loyal, ernsthaft, erfahren, mit eigenem moralischem Urteil; kein naives Hindernis und keine lächerliche Ritter-Karikatur. Ihre Haltung zu Untoten, Schutzbedürftigen und dem Jungen Bram kann sich von Skarras Pragmatismus unterscheiden. Kann widersprechen und Entscheidungen treffen.

**Triss Merigold (The Witcher):** kompetente Zauberin, empathisch, diplomatisch, eigene Prinzipien und Handlungsmacht. Kein permanenter Mediationsautomat. Ihre Magie und die Unterschiede zu Skarras Lebensentzug sind ein interessantes Thema; Skarra hat vor riskantem Entzug aus Magiequellen gewarnt. Der Nutzer wünscht eigenständige, gelegentlich eindrucksvolle Triss-Momente.

**Minthara (BG3):** Drow-Kämpferin, stolz, intelligent, scharfsinnig, taktisch, trocken und manchmal schneidend, aber mehr als Sarkasmus. Zwischen ihr und Skarra hat sich **Freundschaft/Vertrauen** entwickelt; ausdrücklich **keine Romanze**. Sie kämpft mit Schwert/Schild; eine frühere Armverletzung ist geschlossen. Minthara und Brienne sind nicht als automatische Erzfeindinnen angelegt.

Alle vier dürfen **untereinander** sprechen, Beziehungen aufbauen, Uneinigkeit zeigen, Entscheidungen treffen und Skarra widersprechen. **Keine festgelegte Gruppenführerin**, kein bewundernder Chor. Alle fünf Hauptfiguren dürfen verletzt werden und scheitern, aber **kein dauerhafter Tod einer der fünf ohne vorherige ausdrückliche OOC-Abstimmung**. Andere NPCs sind nicht in dieser Weise geschützt.

## 6. Welt und Handlungsstationen (Kurzabriss; Einzelheiten in Repo-Dateien)

Die Handlung spielt in den **Grenzlanden von Valdorn**, nicht einfach in Tyria. **Eibenbrück** ist ein Dorf an einer alten Handelsstraße; die **Abtei Dornwacht** liegt ungefähr drei Tagesreisen zu Fuß nördlich davon. Die Glocken, die Untoten, Kontrollstäbe und das Wirken von **Bruder Cael** sind Rätsel, nicht vollständig geklärter Kanon. Keine geheime fertige Lösung erfinden und als bereits feststehend ausgeben. Das Repository ist dem Spieler zugänglich: **keine geheimen Spielleiterpläne oder Spoiler dort speichern**.

Frühe Handlung: Gasthaus, Mühle, verwundete Menschen, Untote, Untersuchung, Wagen/Überfall. Wichtige Personen **Rhen** (Mutter von **Bram**, reanimierter Sohn), **Marta**, **Edrin**, **Berold**, **Bruder Cael** und weitere laut `WELT_UND_KANON.md`. In einem Kampf mit Wagen/Schützen/Wächtern wurde ein Untoter mit Executioner's Scythe gestoppt, Menschen verletzt/getötet; Rhen berichtet über die Stäbe aus der Abtei. Es entstand eine ethische Spannung um Brams Behandlung und die Grenzen von Nekromantie. Wagen, Fleischgolem und Transport nach Eibenbrück, spätere Ermittlungen und Reise Richtung Abtei. Die Erklärungen der Figuren sind **Aussagen**, nicht automatisch Tatsachen.

Spätere Reise: Köhlerstelle, Lager/Nacht, Auseinandersetzungen und Wundversorgung, Furtkampf, beschädigtes Rad, Hilfe auf Hof von **Alva / Hinnerk / Jost / Wulf**, Gespräche, Bier, Vertrauensmoment zwischen Skarra und Minthara, Klingen **Asche / Stille**, Kundschafterpatrouille. Nächtlicher Versuch eines Pferdediebstahls durch **Tewes** und **Kelm**; Korrosive Giftwolke, Kelm mit Armbrust geflohen, Tewes vergiftet, von Magrat behandelt, befragt und weggeschickt. Ein bei Jost gebliebenes Messer gehört angeblich **Wilm**; Tewes behauptete es gefunden zu haben, die Hintergründe sind **ungeklärt**. Ein möglicher dritter Beteiligter und Kelms Verbleib sind offen. Keine nachträgliche eindeutige Erklärung.

**Exakter Stand bei Übergabe, 17.10.2026:** Morgen des dritten Reisetags, noch auf dem Hof vor Aufbruch. Die Hofleute bereiten ihre eigene Abreise nach Süden vor. Jost empfiehlt Fahrweg bis zum alten Kalkofen und dann zur **Brücke am Mühlgraben**; Brückenzustand nicht bestätigt. Höhenweg länger und schlechter; Minthara schlug ggf. Vorerkundung zu Fuß vor. Drei Knochenkundschafter noch aktiv. **Letzte Rede Briennes:** „Erst essen. Dann würde ich den Fahrweg nehmen und rechtzeitig vor der Brücke halten. Was meint Ihr?“ **Skarra ist am Zug.** Keine Antwort, Routenwahl oder Abreise vorwegnehmen. Vor Fortsetzung **KAMPAGNENSTAND.md** erneut lesen, da sich der Stand nach Erstellung dieser Datei geändert haben könnte.

## 7. Lektorats- und Kontinuitätsfallen

**Gerade besprochene konkrete Textpanne:** Im Markdown-Manuskript beginnt der Abschnitt `## Was die Toten bewegt` unmittelbar mit „Sonst haben wir bald eine Scheune voller gefesselter Untoter.“ – **ohne vorausgehenden Satz oder Sprecherzuordnung**. Der Nutzer schlug vor, davor Skarra sinngemäß sagen zu lassen: „Wir müssen herausfinden, wie wir die Kontrolle der Stäbe brechen können“, gefolgt von „sonst haben wir bald eine Scheune ...“. Bei letzter Sichtung war diese Stelle **noch nicht nachweislich korrigiert**. Beim nächsten ausdrücklich beauftragten Lektorats-/Korrekturdurchgang prüfen, in Kontext einpassen und gegebenenfalls mit Spielerfreigabe ändern; nicht behaupten, es sei bereits geschehen. **Allgemeine Prüfroutine:** Kapitelgrenzen, Szenenanfänge, Sprecherwechsel und fehlende Gesprächsanschlüsse besonders aufmerksam lesen; keine isolierten Antwortsätze oder Dialoge ohne Bezug. Hier können bei der Übertragung des Spiels in Romanprosa Anschlüsse verloren gehen.

Weitere Lektoratsprioritäten: klare räumliche Kontinuität, genaue Namen/Orte, Status von Beschwörungen, Dialogstimmen, zeitlicher Ablauf, keine unverdienten Wunderlösungen, nicht versehentlich OOC in die Erzählung übernehmen. Bei nachträglicher Verdichtung den Sinn tatsächlich gespielter Entscheidungen bewahren; Änderungen an Skarras Dialogen/Handlungen nur mit explizitem Einverständnis.

**Prolog:** `## Prolog · Die Ratten` wurde am 17.10.2026 hinzugefügt und anschließend durch die oben beschriebene Lebenskraftentzug-Szene ersetzt. Die frühe Hafenstadt-Biografie, der berauschende Machtgewinn und die Tragödie des unschuldigen Jungen bilden eine thematische Achse. Der Prolog ist eine **genehmigte literarische Rückblende**, keine neu ausgespielte Unterhaltung, die die Gefährtinnen kennen.

**Buch-only Magrat:** Wald-Besucher und vierter Becher wurden literarisch ergänzt, nicht gespielt; **TOD** nur diskutierte Option.

## 8. Arbeitsweise bei GitHub und Chatwechsel

- Lies echte Dateien über den verbundenen GitHub-Zugriff. Behaupte niemals Zugriff oder Speicherung ohne überprüften Abruf/Commit.
- Bei Änderungen erst relevanten Kontext lesen, gezielt editieren, Commit und Ergebnis prüfen. Keine pauschalen Umarbeitungen ohne Auftrag.
- `roman/Die_Glocken_von_Dornwacht.md` ist die aktuelle Primärquelle. DOCX wird durch GitHub Action bei Markdown-Änderungen erzeugt; **Drucklayout ist derzeit nachrangig**.
- Am Sitzungsende auf Nutzerwunsch Roman, `KAMPAGNENSTAND.md`, `WELT_UND_KANON.md`, Charakterprofile und `DOKUMENTATION.md` aktualisieren.
- Vor dem Spiel **nicht** den Chatverlauf als exakten Haltepunkt nehmen, wenn `KAMPAGNENSTAND.md` neuer ist.
- **`chat-verlauf-gaming.md` ist das geplante vollständige Gesprächsarchiv**, das der Nutzer selbst einfügt. Es kann lange, überholte Überlegungen, Korrekturen, alternative Entwürfe und anderes Gaming enthalten. Nicht jede darin enthaltene Aussage ist aktueller Kanon. Zeitlich spätere, ausdrücklich bestätigte Entscheidungen und Projektregeln beachten.
- Der neue Chat kann als **Lektor** beginnen; er soll nicht automatisch in die Rolle der Spielleitung wechseln.

## 9. GW2 / weiteres Gaming – Kontext, nicht Roman-Kanon

Der Nutzer spielt Games meist mit **englischer Originalvertonung**. GW2-Nekromantie ist nicht bloße Fantasy-Dekoration, sondern konkreter Regelrahmen für Skarra. Vertraut mit Nekromant/Reaper, Zhaitan und den verschiedenen Minions. Für GW2-Mechanikfragen lieber präzise unterscheiden zwischen Spielskill, literarischer Ausgestaltung und bereits gespielter Ausnahme.

Weitere frühere Gaming-Gespräche: **Diablo IV** – Warlock „Blazing Scream“ (Torment 10 / Pit 90, Speed-Build mit In-Geom, Farming u. a. Ring of Starless Skies), Barbarin **Thûula** als Wirbelwind-Build (Torment 12 erfolgreich, stärker als Warlock, obwohl Warlock mehr Spaß machte), Interesse an Astral-Spirit-Necro. **Graveyard Keeper 2** und **Europa Universalis V** waren ebenfalls Themen. Diese Angaben sind bloße Gesprächskontinuität und **nicht** Teil der Dornwacht-Welt. Vor aktuellen Spielmechaniken/Seasons neu prüfen.

Mediengeschmack: Fantasy, D&D-Stil, Terry Pratchetts Scheibenwelt, The Witcher; bevorzugt **abgeschlossene** Buchreihen, Nekromantie als Bonus. Freude an guten Charakterdialogen, eigenwilligen Frauenfiguren und trockenem Humor. Der Nutzer möchte kein anbiederndes Zustimmen.

## 10. Status dieser Übergabe

Erstellt als Sicherung beim Wechsel aus einem sehr langen Chat. **Noch zu befüllen:** `chat-verlauf-gaming-abenteuer/chat-verlauf-gaming.md` mit dem vollständigen bisherigen Chattext. Die Übergabe kann nicht automatisch beweisen, dass jede alte Chatnachricht rekonstruiert ist. Darum dienen die vorhandenen Projektdateien als Kanon und das spätere Chatarchiv als ergänzendes Gedächtnis.

**Wichtigster erster Satz im neuen Chat:** Erst die Dateien lesen, die Rollen klären und den aktuellen Stand bestätigen. **Nicht Skarras nächsten Zug schreiben.**
