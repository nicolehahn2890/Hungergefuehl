# Regeln für dieses Repo

## Git — WICHTIG
- **Alle Änderungen werden IMMER direkt auf `main` gepusht.** Keine Feature-Branches,
  keine Pull Requests — auch wenn die Session mit einem anderen Arbeitsbranch
  gestartet wurde. Die Live-App (GitHub Pages) läuft von `main`; nur dort
  ankommende Commits gehen live.
- Falls die Session einen Arbeitsbranch vorgibt: dort committen ist ok, aber am
  Ende immer per Fast-Forward nach `main` bringen und `main` pushen.

## Projekt
- Die komplette App lebt in **einer Datei**: `index.html` (HTML + CSS + JS inline).
  Kein Build-Schritt, keine Abhängigkeiten.
- Sprache: komplett Deutsch, Du-Form, warmer, nicht wertender Ton (siehe README,
  Abschnitt „Sprache").
- Design: Calma „Luminous / Perla" — bestehende CSS-Tokens und Klassen
  (`.glass`, `.bead`, `.chip`, `.btn`, Farbvariablen) wiederverwenden, keine
  neuen Stile erfinden, wenn ein bestehender passt.
- Speicherung: localStorage, Schlüssel `intuition.entries.v1`. Beim Ändern der
  Datenstruktur auf Rückwärtskompatibilität mit Alt-Einträgen achten
  (fehlende Felder dürfen Auswertungen nicht verfälschen).
- Eintragstypen: Mahlzeiten (Vorher/Nachher) und Zwischendurch-Momente
  (`type:'zwischen'`). Zwischendurch-Einträge zählen nie als Mahlzeit und
  dürfen nie vom Nachher-Check als „offene Mahlzeit" aufgegriffen werden.
- Übergang Zwischendurch → Mahlzeit: Bei Antwort „Ich esse jetzt etwas" führt
  ein Button in den kompletten Vor-der-Mahlzeit-Check; `startBefore(initVal)`
  übernimmt dabei den Hungerwert als Startwert (Regler bleibt anpassbar).
  Der Zwischendurch-Eintrag bleibt zusätzlich bestehen.
