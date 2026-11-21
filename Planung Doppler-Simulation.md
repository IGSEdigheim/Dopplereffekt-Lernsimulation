# Planung Doppler-Simulation

Stand: 20.11.2026, zweite Runde. Ausbau der Doppler-Simulation vom Oktober 2026 (gesichert in `Alte Fassung 2026-10/`) zur Lernsimulation mit dem Skill `lernsimulation`.

## Grundgedanke
Es geht vor allem ums Erkunden und um die Herleitung, weniger ums Messen. Zuerst probieren die Schüler den Versuch frei aus. Dann beobachten sie gezielt, wo der Ton höher und wo er tiefer ist. Danach sehen sie, dass die Wellenberge vor dem Sender dichter liegen. Daraus leiten sie die Formel Schritt für Schritt selbst her und prüfen sie zum Schluss im Wellenfeld. Behandelt wird nur der **bewegte Sender** bei ruhendem Empfänger.

**Rückmeldung des Lehrers zur ersten Fassung:** Seite 1 sollte ganz ohne Aufgabe und ohne die rechte Spalte auskommen. Eine Herleitung, die nur als Formelkette dasteht, hilft Schülern wenig, die in Mathe schwach sind. Sie soll greifbar und animiert sein.

## Schritte
| # | Kurzname | Szene | Rechte Spalte | Inhalt | Fragen |
|---|---|---|---|---|---|
| 1 | Versuch | Wellenfeld über die ganze Breite | **keine** | Freies Ausprobieren, auch mit Überschall. Das Feld „Ausprobieren“ enthält einen Satz Hinweis und „Weiter“. | keine (erledigt, sobald man weitergeht) |
| 2 | Erkunden | Wellenfeld | ja | Empfänger vor, hinter und neben die Bahn stellen. Hier steht auch die Erklärung von Sender, Empfänger und Zeitlupe. | 1 Auftrag, 3 Fragen |
| 3 | Wellenlänge | Abbildung nach LEIFIphysik Abb. 3, neu gezeichnet und bewegt | ja | \(\lambda\), \(v_\mathrm{S}\cdot T\), \(\lambda'\) vorne und hinten; \(f = 400\) Hz fest | 1 Auftrag, 3 Fragen |
| 4 | Herleitung | je nach Stufe Abbildung (mit Markierung) oder Zählszene | **keine** | Herleitung zum Mitmachen in 6 Stufen, siehe unten | 5 kleine Fragen, eine je Stufe |
| 5 | Probe | Wellenfeld, Empfänger auf der Bahn | ja | Messwert und Rechnung im Feld vergleichen | 1 Auftrag, 3 Fragen: zwei Rechnungen und \(v_\mathrm{S} \to c\) |
| 6 | Ausblick (Zusatz) | **keine Szene:** ganzseitige Magazinseite | **keine** | Schneller als der Schall, siehe unten | keine (zählt nicht zum Abschluss) |

## Ausblick „Schneller als der Schall“ (Schritt 6, Zusatz)
Wunsch des Lehrers: Nicht immer muss eine Simulation im Mittelpunkt stehen, die Seite darf die ganze Breite und Höhe einnehmen. Deshalb gibt es eine Magazinseite (`page`, `voll`, `extra`):
- **Links das Foto:** F/A-18 mit Kondensationswolke, `992akustik-schallkegel-F18-Hornet-schallmauer.webp` von LEIFIphysik, als Daten-URI eingebettet. Es wird nicht beschnitten; dahinter liegt dieselbe Aufnahme unscharf. Die Bildunterschrift sagt ausdrücklich, dass die Wolke Kondensation ist und **nicht** der Machsche Kegel. Quellenangabe: „Foto: U.S. Navy, gefunden bei LEIFIphysik“.
- **Bewegtes Bild:** Der Sender fährt und sendet Kreiswellen aus. Am Ende stehen Kegel und Dreieck mit \(c\cdot t\), \(v_\mathrm{S}\cdot t\) und \(\alpha\). Das Bild läuft einmal ab, „Noch einmal abspielen“ startet es neu. Der Regler stellt die Machzahl von 1,2 bis 3,0 ein. Daneben steht die Herleitung \(\sin\alpha = \frac{c}{v_\mathrm{S}} = \frac{1}{\mathrm{Ma}}\) mit den aktuellen Werten, dazu eine aufklappbare Frage „spitzer oder breiter?“.
- **Karte „Wann knallt es?“:** Regler für die Flughöhe von 1 bis 15 km, dazu eine Seitenansicht im richtigen Winkel. Ergebnis: \(x = \frac{h}{\tan\alpha}\) und die Zeit nach dem Überflug, vereinfacht mit \(c = 340\) m/s in jeder Höhe. Kontrollwert: Ma 2 und 10 km ergeben 17,3 km und 25 s.
- **Karte „Auch Licht kann das“:** Tscherenkow-Leuchten (Licht in Wasser etwa 225 000 km/s) und der Peitschenknall.
- Aufgeräumt am 22.11.2026 (rechte Spalte war zu gequetscht): Foto und Text im Verhältnis 0,78 : 1,5 statt 0,85 : 1,3, beide Karten gleich breit, Abstände und Überschrift wachsen mit dem Bildschirm. Beschriftungen, Knöpfe, die Aufklapp-Frage und der Kicker stehen in der Schrift der Bedienung, der Lesetext in der Leseschrift.
- Bei 1366 × 768 und 1920 × 1080 passt alles ohne Scrollen. Bei 1280 × 720 scrollt die rechte Spalte etwas (27 px), schmale Bildschirme zeigen alles untereinander.

## Herleitung zum Mitmachen (Schritt 4)
Das Feld „Herleitung“ nimmt die ganze Breite ein und hat drei Spalten:
- **links** der Gedanke mit einer kleinen Frage, die drei Antworten zur Wahl bietet;
- **Mitte** „Allgemein“: die Formel. Nach der richtigen Antwort wird sie Schritt für Schritt umgeformt, und der neue Teil leuchtet auf. Mit „Nochmal zeigen“ läuft das noch einmal ab;
- **rechts** „Mit Zahlen“: dieselbe Rechnung für das Beispiel \(f = 400\) Hz und \(v_\mathrm{S} = 68\) m/s \(= c/5\). In jeder Stufe kommen 500 Hz heraus.

\(\lambda\), \(\lambda'\), \(v_\mathrm{S}\cdot T\) und \(f'\) haben in den Formeln dieselben Farben wie in der Abbildung. Über der Herleitung sind die Stufen als Knöpfe aufgereiht. „Weiter“ wird erst frei, wenn die Frage der Stufe richtig beantwortet ist.

| Stufe | Szene | Formel | Frage |
|---|---|---|---|
| 1 \(\lambda'\) | Abbildung, \(\lambda'\) markiert | \(\lambda' = \lambda - v_\mathrm{S}T\), Zahlen 0,85 m − 0,17 m = 0,68 m | keine |
| 2 Zählen | **Zählszene:** zwei Wellenzüge, oben mit ruhendem, unten mit fahrendem Sender. Die Wellenberge, die in 0,01 s ankommen, tragen Nummern, und der Empfänger zählt mit. Ergebnis: 4 bzw. 5 Wellenberge | „Weg in 1 s durch Abstand“ wird zu \(f' = \dfrac{c}{\lambda'}\) | Wie viele Wellenberge kommen in 0,01 s an? (5) |
| 3 Einsetzen | Abbildung, \(\lambda'\) markiert | \(f' = \dfrac{c}{\lambda - v_\mathrm{S}T}\) | Was setzt man für \(\lambda'\) ein? |
| 4 Ersetzen | Abbildung, \(\lambda\) und \(v_\mathrm{S}T\) markiert | \(\lambda \to \dfrac{c}{f}\), \(T \to \dfrac{1}{f}\) | Was wird aus \(v_\mathrm{S}\cdot T\)? |
| 5 Erweitern | Abbildung | oben und unten mal \(f\), \(f\) kürzt sich (durchgestrichen) zu \(f\cdot\dfrac{c}{c - v_\mathrm{S}}\); Hinweis \(\frac12 = \frac{1\cdot 3}{2\cdot 3}\) | Was bleibt unten übrig? |
| 6 Ergebnis | Abbildung, \(\lambda'\) vorne und hinten markiert | beide Formeln eingerahmt | Welche Formel gilt hinter dem Sender? Danach ist der Regler für \(v_\mathrm{S}\) frei, die Zahlen rechnen mit. |

Bis zur letzten Frage steht \(v_\mathrm{S}\) fest auf dem Beispielwert 68 m/s. Die Szene der Herleitung zeigt nur den gezeichneten Ausschnitt und ist dadurch größer.

## Bedienung
- Feld „Sender“: Regler für \(f\) (200 bis 1000 Hz) und \(v_\mathrm{S}\) (0 bis 510 m/s, je nach Schritt begrenzt), „Neu starten“, Schalter „Wellenfeld: fertig / baut sich auf“.
- Feld „Empfänger“: LCD mit der gemessenen Frequenz, Ton an/aus. In Schritt 3 zeigt es stattdessen die Längen der Abbildung, in Schritt 5 die Rechnung.
- Den Empfänger kann man in der Szene ziehen, nahe der Bahn rastet er ein. Die Zeitlupe ist fest auf 1 : 300 eingestellt.
- Ist die Szene breiter als 1000 Einheiten (Seite 1 ohne Anleitung), reicht das Wellenfeld bis an den Rand.

## Design
- Rahmen, Kopfzeile, Felder, Anleitung, KaTeX, Lehrermodus und SCORM kommen aus dem Skill.
- **Neu im Kern:** Ein Schritt mit `voll: true` hat keine Anleitung. Szene und Felder nutzen dann die ganze Breite, und „Weiter/Zurück“ liefert ein Feld des Themas. Das steht seit 20.11.2026 auch im Skill: in der Vorlage mit `#vollNav` für Zurück und Weiter, im Klicktest und in der Doku, zusammen mit der „Herleitung zum Mitmachen“ als Muster in `design.md`. Diese Datei hat noch ihre eigene Fassung im Kern, mit eigenen Knöpfen im Feld „Ausprobieren“.
- Auf Wunsch des Lehrers ist die **Szene hell** wie in der alten Fassung (Papierton, blaugraue Wellen, roter Sender, blauer Empfänger), auch im dunklen Design.
- Die Bezeichnungen folgen LEIFI: Sender, Empfänger, \(f\), \(f'\), \(\lambda\), \(\lambda'\), \(v_\mathrm{S}\), \(c = 340\) m/s.
- Der Speicherstand hat die Version 2 (`defaults.ver`, Speicherschlüssel `-sim-2`). Stände der ersten Fassung werden nicht übernommen.

## Modell und Kontrollwerte
- Das Wellenfeld wird aus den Laufzeiten der Wellen berechnet (retardierte Phase), wie in der alten Fassung. Die gemessene Frequenz ergibt sich aus der Phasenänderung beim Empfänger.
- Bei \(f = 400\) Hz und \(v_\mathrm{S} = 170\) m/s kommen vorne 800 Hz und hinten 266,7 Hz an. Messwert und Formel stimmen im Test auf 1 % überein.
- Die Zählszene nutzt dasselbe Modell. In 0,01 s kommen 4 Wellenberge an (Sender steht), 5 bei 68 m/s und 8 bei 170 m/s.
- Selbstcheck: 500 Hz und 40 m/s ergeben 566,7 Hz (zu) und 447,4 Hz (weg).

## Stand
- 20.11. vormittags: Die erste Fassung mit 4 Schritten liegt in Moodle (Kurs 644, cmid 36550).
- 20.11. abends: Die zweite Fassung mit 5 Schritten und dem Ausblick als Zusatz ist vom Lehrer abgenommen. Das ZIP ist neu gebaut, der Klicktest am entpackten Paket lief mit 199 Prüfungen ohne Fehler. Um 23:10 ist das Paket in Kurs 644, cmid 36550, ersetzt. Die SHA1-Prüfsumme in Moodle stimmt mit dem ZIP überein. „Neuen Versuch erzwingen“ ist an, die Simulation öffnet im eigenen Fenster.
- 22.11.: Neues Design der Vorlage (lernsimulation ec540a6): Kern, Zeichenhilfen und Design-CSS aus der Vorlage, Schriften Atkinson Hyperlegible Next und Source Serif 4 eingebettet; das Doppler-eigene CSS und das Thema bleiben (Speicherschlüssel weiter `-sim-2`). Ausblick aufgeräumt (siehe oben). Klicktest 150 von 151: Die neue Prüfung „Szene und Felder bleiben an ihrem Platz“ meldet Schritt 4, weil die Herleitung absichtlich nur ihr eigenes breites Feld zeigt. Paket in Kurs 644, cmid 36550, ersetzt. Seitdem ist der Ordner ein Git-Repository.

## Quellen
- LEIFIphysik, Doppler-Effekt, 1. Fall: Der Sender bewegt sich (Screenshots `Herleitung Teil 1.png`, `Herleitung Teil 2.png`).
