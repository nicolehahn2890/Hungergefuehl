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
- **Vor der Mahlzeit** — Hungerskala 0–10, „Bauch oder Kopf?" + Apfel-Check, Merksatz
  für den Tisch
- **Nach der Mahlzeit** — Sättigungsskala 0–10, Geschmacks-Kipppunkt, Stopp-Punkt
  (aus der Erinnerung)
- **Muster** — wöchentliche Übersicht ohne Kalorien, nur Signaltreue
- **Merkmale** — Nachschlagewerk: Hungerverlauf, Bauch- vs. Kopf-Hunger,
  Geschmacks-Trick, Sättigungsverlauf

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
assets/textures/               Calma-Perlmutt-Texturen
  pearl-marble.png
  pearls.png
```

## Öffnen
`index.html` in jedem Browser öffnen — eigenständige Datei, keine Installation, kein
Build-Schritt nötig.
