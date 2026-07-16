# Intuition — Hunger & Sättigung

Ein interaktiver Prototyp, der hilft, ein natürliches Hunger- und Sättigungs­gefühl
wiederzuerlernen. Gebaut im echten **Calma-„Luminous / Perla"-Design**, komplett auf
Deutsch.

## Idee
Kein Kalorienzählen, sondern das Trainieren der **eigenen Körpersignale**
(Interozeption). Die App wird nur **vor** und **nach** der Mahlzeit angefasst — während
dem Essen bleibt das Handy liegen. Man nimmt einen einzigen Merksatz mit an den Tisch
und meldet sich danach kurz aus der Erinnerung zurück. Ziel ist, die App irgendwann
gar nicht mehr zu brauchen.

## Screens
- **Heute** — Einstieg in den Vorher-/Nachher-Check-in, Tagesübersicht
- **Vor der Mahlzeit** — Hungerskala als ziehbarer Regler (0–10 in Halbschritten,
  „dazwischen" erlaubt), „Bauch oder Kopf?" mit gruppierten, differenzierten
  Merkmalen + Apfel-Check, optionales Freitextfeld, Merksatz für den Tisch
- **Nach der Mahlzeit** — Sättigungsskala als Regler (Halbschritte, aus der
  Erinnerung), Körpergefühl der Sättigung (Mehrfachauswahl), Geschmacks-Kipppunkt
  (5 Stufen), Stopp-Punkt (inkl. „noch hungrig"), optionales Freitextfeld
- **Muster** — wöchentliche Übersicht ohne Kalorien, nur Signaltreue: Wochengrafik
  (Start-Hunger ○ und Stopp-Sättigung ● pro Mahlzeit), Prozente, „Was auffällt",
  „Alle Einträge löschen"
- **Merkmale** — Nachschlagewerk in sechs Themen-Tabs: Hungerverlauf (inkl.
  Hunger-Wellen & Gewohnheits-Hunger), Sättigungsverlauf (inkl. satt werden vs.
  satt bleiben), Bauch- vs. Kopf-Hunger (inkl. Apfel-Check), Geschmacks-Trick,
  Störfaktoren (Schlaf, Zyklus, Durst, Stress/Medikamente) und Denkfallen
  (Stopfen, Verschwendung, „Was-soll's"-Effekt, Geduld/Diät-Vergangenheit)

## Interaktion
- Skalen sind **ziehbare Regler mit Halbschritten** — man darf bewusst zwischen zwei
  Werten landen (z. B. „3–4"), die App bestätigt, dass „dazwischen" völlig ok ist.
- Die Folgefragen bieten **differenzierte, gruppierte Auswahlmöglichkeiten**,
  „bin mir nicht sicher"-Optionen und je ein **optionales Freitextfeld**, falls
  nichts genau passt.
- **Merkmale** ist in sechs Themen-Tabs gegliedert (Hunger · Sättigung · Bauch
  oder Kopf · Geschmack · Störfaktoren · Denkfallen) — jedes Thema mit Stufenliste inkl. Skalenwerten,
  Praxis-Tipps und einer kurzen Wissenschafts-Karte. „Denkfallen" behandelt die
  psychologischen Muster: Stopfen aus Knappheits-Gefühl (du darfst jederzeit wieder
  essen), „Teller leer"-Konditionierung (Übriglassen ist keine Verschwendung —
  versunkene Kosten) und den „What-the-hell"-Effekt (eine Mahlzeit drüber ruiniert
  nichts, nicht kompensieren).

## Speicherung
Check-ins werden **lokal auf dem Gerät** gespeichert (localStorage, Schlüssel
`intuition.entries.v1`) — keine Cloud, keine Anmeldung. „Vor der Mahlzeit" legt
einen Eintrag an, „Nach der Mahlzeit" ergänzt den letzten offenen Eintrag des Tages.
Die Heute-Liste, die Wochengrafik, die Prozente und „Was auffällt" berechnen sich
aus den echten Einträgen. Unter Muster → „Alle Einträge löschen" lässt sich alles
zurücksetzen.

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
Diät-Vergangenheit.

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
