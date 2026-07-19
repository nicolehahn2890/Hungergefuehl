# Intuition — Hunger & Sättigung

Ein interaktiver Prototyp, der hilft, ein natürliches Hunger- und Sättigungs­gefühl
wiederzuerlernen. Gebaut im echten **Calma-„Luminous / Perla"-Design**, komplett auf
Deutsch.

## Idee
Kein Kalorienzählen, sondern das Trainieren der **eigenen Körpersignale**
(Interozeption). Die App wird nur **vor** und **nach** der Mahlzeit angefasst — während
dem Essen bleibt das Handy liegen. Man nimmt einen einzigen Merksatz mit an den Tisch
und meldet sich danach kurz aus der Erinnerung zurück. Zusätzlich lassen sich
**Signale zwischen den Mahlzeiten** (Magenknurren, Energieloch …) kurz notieren,
ohne dass daraus eine Mahlzeit wird. Ziel ist, die App irgendwann
gar nicht mehr zu brauchen.

## Screens
- **Heute** — Einstieg in den Vorher-/Nachher-Check-in und den
  Zwischendurch-Check, Tagesübersicht (Mahlzeiten und Zwischendurch-Momente
  als getrennte Zeilen, Zählung z. B. „2 Mahlzeiten · 1 Moment")
- **Vor der Mahlzeit** — Hungerskala als ziehbarer Regler (0–10 in Halbschritten,
  „dazwischen" erlaubt), „Bauch oder Kopf?" mit gruppierten, differenzierten
  Merkmalen + Apfel-Check, optionales Freitextfeld, Merksatz für den Tisch
- **Nach der Mahlzeit** — Sättigungsskala als Regler (Halbschritte, aus der
  Erinnerung), Körpergefühl der Sättigung (Mehrfachauswahl), zwei klar getrennte
  Blöcke „Spüren" (Kam ein Genug-Signal? · Wann hat das Essen aufgehört, so gut
  zu schmecken wie am Anfang? — hier zählt nur das Bemerken) und „Handeln"
  (Was hat das Ende bestimmt?: Teller war leer · war satt und habe aufgehört ·
  Geschmack · die anderen waren fertig · unterbrochen · weiß nicht), optionales
  Freitextfeld. Die Auswertung
  trennt Wahrnehmung, Handlung und Ergebnis — „Signal gespürt, aber Teller leer
  gegessen" wird als normaler Zwischenschritt gewürdigt, nicht als Scheitern.
- **Zwischendurch** — Signale zwischen den Mahlzeiten festhalten, ohne zu essen:
  dieselbe 0–10-Skala (Standard 4), Signal-Chips (Magen knurrt · leeres/flaues
  Gefühl · Gedanken kreisen ums Essen · Energieloch · leicht gereizt · Lust auf
  etwas Bestimmtes · eher Durst? · diffus), dann die Frage „Wie gehst du mit dem
  Signal um?" (warten · jetzt essen · erst ein Glas Wasser · weiß noch nicht),
  optionales Freitextfeld. Die Einordnung passt sich an: Hunger-Wellen-Botschaft
  beim Warten, Durst-Check beim Trinken, unter Wert 2 der ehrliche Hinweis, die
  Mahlzeit lieber vorzuziehen. Bei „Ich esse jetzt etwas" führt ein Button
  **direkt in den kompletten Vor-der-Mahlzeit-Check** — der Hungerwert ist
  vorbelegt (Regler bleibt anpassbar), alle weiteren Fragen wie gewohnt.
- **Muster** — wöchentliche Übersicht ohne Kalorien, nur Signaltreue: eine
  waagerechte 0–10-Zeile pro Mahlzeit (○ Start-Hunger → ● Stopp-Sättigung, mit
  Wohlfühl-Fenster und Klartext-Werten wie „5 → 7"), Zahlen-Kacheln (Anzahl,
  vom Körper gestoppt, Ø Start, Ø Stopp), fünf Prozentbalken in drei
  Gruppen — 1·Spüren (Genug-Signal gespürt, Kipppunkt bemerkt), 2·Handeln
  (Start-Timing, „Dein Körper hat den Stopp bestimmt"), 3·Ergebnis (im Fenster
  gelandet) und ein mehrteiliges „Was auffällt" mit konkreten, aus den eigenen
  Angaben berechneten
  Beobachtungen (Start-Timing, Stopp-Verhalten, Geschmacks-Kipppunkt,
  Zwischendurch-Signale mit häufigstem Signal und Warten-Quote,
  Kopf-Hunger-Zeiten, häufigstes Körpergefühl), „Alle Einträge löschen"
- **Wissen** (früher „Merkmale") — Nachschlagewerk in acht Themen-Tabs:
  Hungerverlauf (inkl. Hunger-Wellen & Gewohnheits-Hunger), Sättigungsverlauf
  (inkl. satt werden vs. satt bleiben), Bauch- vs. Kopf-Hunger (inkl.
  Apfel-Check), Geschmacks-Trick, Störfaktoren (Schlaf, Zyklus, Durst,
  Stress/Medikamente), Denkfallen (Stopfen, Verschwendung,
  „Was-soll's"-Effekt, Geduld/Diät-Vergangenheit), Food Noise (was das
  Gedanken-Rauschen lauter macht und sieben natürliche Wege, es leiser zu
  drehen) und Hormone (Landkarte Ghrelin/GLP-1/CCK/PYY/Leptin/Insulin/Cortisol,
  GLP-1 natürlich fördern, Insulin & Blutzucker-Achterbahn vermeiden,
  Cortisol senken)

## Interaktion
- Skalen sind **ziehbare Regler mit Halbschritten** — man darf bewusst zwischen zwei
  Werten landen (z. B. „3–4"), die App bestätigt, dass „dazwischen" völlig ok ist.
- Die Folgefragen bieten **differenzierte, gruppierte Auswahlmöglichkeiten**,
  „bin mir nicht sicher"-Optionen und je ein **optionales Freitextfeld**, falls
  nichts genau passt.
- **Wissen** ist in acht Themen-Tabs gegliedert (Hunger · Sättigung · Bauch
  oder Kopf · Geschmack · Störfaktoren · Denkfallen · Food Noise ·
  Hormone). Jedes Thema folgt derselben Dramaturgie: Kernaussage →
  Mechanismus/Biologie (teils als kompakte Signal-Kette dargestellt) →
  Praxis → eine abgesetzte „Studienlage"-Karte mit Quellenhinweis. Jedes
  Thema mit
  Stufenliste inkl. Skalenwerten, Praxis-Tipps und einer kurzen
  Wissenschafts-Karte. „Denkfallen" behandelt die
  psychologischen Muster: Stopfen aus Knappheits-Gefühl (du darfst jederzeit wieder
  essen), „Teller leer"-Konditionierung (Übriglassen ist keine Verschwendung —
  versunkene Kosten) und den „What-the-hell"-Effekt (eine Mahlzeit drüber ruiniert
  nichts, nicht kompensieren).

## Speicherung & Messlogik
Check-ins werden **lokal auf dem Gerät** gespeichert (localStorage, Schlüssel
`intuition.entries.v1`) — keine Cloud, keine Anmeldung. „Vor der Mahlzeit" legt
einen Eintrag an, „Nach der Mahlzeit" ergänzt den letzten offenen Eintrag von
heute (oder von gestern spätabends — Mitternachts-Fall). Zwischendurch-Momente
werden als eigener Eintragstyp gespeichert (`type:'zwischen'`). Doppel-Tipp-Schutz
verhindert Duplikate. Unter Muster → „Alle Einträge löschen" lässt sich alles
zurücksetzen.

Messregeln der Auswertung:
- **Zwischendurch-Momente zählen nie als Mahlzeit**: Sie fließen nicht in die
  Mahlzeiten-Zeilen, Kacheln und Prozentbalken ein und werden vom
  Nachher-Check nie als „offene Mahlzeit" aufgegriffen — auch dann nicht, wenn
  sie zeitlich zwischen Vorher- und Nachher-Check liegen. Sie bekommen unter
  „Was auffällt" eine eigene Beobachtung.
- **Wertbasierte Kennzahlen** (Ø Start, Ø Stopp, „im Wohlfühl-Fenster gelandet"
  = Sättigung 6–7,5, Start-Timing, Mahlzeiten-Zeilen) zählen alle
  Mahlzeit-Einträge.
- **Fragebasierte Kennzahlen** zählen nur Einträge, in denen die jeweilige Frage
  beantwortet wurde: „vom Körper gestoppt"/Teller-Quote nur mit beantwortetem
  Stopp-Grund, „Genug-Signal gespürt" nur mit beantworteter Signal-Frage.
  Einträge aus früheren Frage-Versionen verfälschen diese Quoten nicht (sie
  fallen aus dem Nenner).

## Sprache
Alle Texte sind auf einen natürlichen, nicht wertenden Ton hin überarbeitet:
Spüren und Handeln werden sprachlich getrennt behandelt, „Teller leer" wird als
normale Antwort behandelt statt als Fehler, und die Auswertungen sprechen konkret
über die eigenen Angaben statt in Floskeln.

## Design
Basiert auf dem Calma-Design-System („Luminous / Perla"), farblich auf das eigene
Hintergrundbild abgestimmt:
- **Hintergrund:** rosa-türkises Glitzerwasser (`assets/bg-water.jpg`) als Vollbild,
  mit hellem Schleier im Kopfbereich für Lesbarkeit
- **Farbpalette:** kräftiges Pink (#e878bd) → Wasser-Türkis (#55cfd6) für alle
  Buttons, Chips, Regler und Akzente; Skala-Polfarben ans Bild angeglichen
- Cormorant Garamond (Display) + DM Sans (Text), tiefes Pflaumen-Ink
- die signature **Glasperlen** für die Skalen-Werte (weiße Ziffer auf farbiger Perle)
- Waage-Symbol als Wortmarken-Perle — steht für die Balance zwischen Hunger und
  Sättigung
- **Homescreen-Icon:** pinke Waage-Perle auf dem echten Wasserbild
- Glas-Karten, Pill-Buttons und Chips nach den Original-Calma-Tokens

## Wissenschaftliche Grundlage
Hunger-Sättigungs-Skala &amp; Intuitive Eating (Tribole &amp; Resch), Interozeptions-Training,
sensorspezifische Sättigung (Geschmack wird neutral = körperliches „genug"), das
~20-Minuten-Sättigungsfenster (CCK/PYY), Unterscheidung körperlicher vs. emotionaler
Hunger (Ghrelin, Apfel-Test). Störfaktoren: Schlafmangel (Ghrelin ↑ / Leptin ↓),
Zyklus (erhöhter Bedarf in der Lutealphase), Durst-Hunger-Verwechslung, Stress
(Cortisol) und Medikamente. Sättigungsdauer: Eiweiß/Ballaststoffe/Volumen halten
lange vor, Flüssigkalorien und stark Verarbeitetes kurz. Hunger-Wellen und
Ghrelin-Gewöhnung an Essenszeiten. Ess-Psychologie im Denkfallen-Tab: Knappheits-/
Verbots-Effekt und bedingungslose Erlaubnis, versunkene Kosten („Teller leer"-
Konditionierung), „What-the-hell"-Effekt und die Normalisierung der Signale nach
Diät-Vergangenheit. Food Noise & Hormone: GLP-1/CCK/PYY als Sättigungs-Boten
und ihre natürliche Förderung (Eiweiß, Ballaststoffe/kurzkettige Fettsäuren,
langsames Essen, Volumen; GLP-1-Analoga als Beleg für die hormonelle Natur des
Food Noise), reaktive Unterzuckerung nach schnellen Kohlenhydraten (Kombination,
Reihenfolge Gemüse/Eiweiß zuerst, Bewegung nach dem Essen), chronisch erhöhtes
Cortisol und Appetit (verlängertes Ausatmen, Tageslicht/Bewegung, Koffein-Timing)
sowie das Minnesota-Hunger-Experiment (Essensgedanken als Versorgungs-Signal).

## Struktur
```
index.html                     komplette App (ein eigenständiges File)
manifest.webmanifest           Web-App-Manifest (Homescreen-Installation)
assets/
  bg-water.jpg                 Hintergrundbild (rosa-türkises Glitzerwasser)
  app-icon-180/192/512.png     Homescreen-Icons (pinke Waage-Perle auf Wasserbild)
  textures/                    Calma-Perlmutt-Texturen (Reserve, aktuell ungenutzt)
```

## Öffnen
- **Live:** https://nicolehahn2890.github.io/Hungergefuehl/ (GitHub Pages, Branch
  `main`) — am Handy über „Zum Home-Bildschirm hinzufügen" als App installierbar
- **Lokal:** `index.html` in jedem Browser öffnen — keine Installation, kein
  Build-Schritt nötig.
