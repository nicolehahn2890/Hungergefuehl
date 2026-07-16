# Gespür — Hunger &amp; Sättigung

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
- **Muster** — wöchentliche Übersicht ohne Kalorien, nur Signaltreue
- **Merkmale** — Nachschlagewerk: Hungerverlauf, Bauch- vs. Kopf-Hunger,
  Geschmacks-Trick, Sättigungsverlauf

## Interaktion
- Skalen sind **ziehbare Regler mit Halbschritten** — man darf bewusst zwischen zwei
  Werten landen (z. B. „3–4"), die App bestätigt, dass „dazwischen" völlig ok ist.
- Die Folgefragen bieten **differenzierte, gruppierte Auswahlmöglichkeiten**,
  „bin mir nicht sicher"-Optionen und je ein **optionales Freitextfeld**, falls
  nichts genau passt.

## Design
Übernimmt das Calma-Design-System 1:1:
- echte Perlmutt-Texturen (`pearl-marble.png`, `pearls.png`) als Hintergrund
- Cormorant Garamond (Display) + DM Sans (Text), tiefes Pflaumen-Ink
- die signature **Glasperlen** für die Skalen-Werte (weiße Ziffer auf farbiger Perle)
- Waage-Symbol als Wortmarken-Perle — steht für die Balance zwischen Hunger und
  Sättigung
- Glas-Karten, Pill-Buttons und Chips nach den Original-Tokens

## Wissenschaftliche Grundlage
Hunger-Sättigungs-Skala &amp; Intuitive Eating (Tribole &amp; Resch), Interozeptions-Training,
sensorspezifische Sättigung (Geschmack wird neutral = körperliches „genug"), das
~20-Minuten-Sättigungsfenster (CCK/PYY), Unterscheidung körperlicher vs. emotionaler
Hunger (Ghrelin, Apfel-Test).

## Struktur
```
index.html                     komplette App (ein eigenständiges File)
manifest.webmanifest           Web-App-Manifest (Homescreen-Installation)
assets/
  bg-water.jpg                 Hintergrundbild (rosa-türkises Glitzerwasser)
  app-icon-180/192/512.png     Homescreen-Icons (Waage-Glasperle, rosé)
  textures/                    Calma-Perlmutt-Texturen (Reserve)
```

## Öffnen
`index.html` in jedem Browser öffnen — eigenständige Datei, keine Installation, kein
Build-Schritt nötig.
