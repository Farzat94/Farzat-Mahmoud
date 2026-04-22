# Browser-Testplan fuer CV Webseite

Projektdateien:
- Farzat.html
- style.css

## 1) Testumgebung

Desktop Browser:
- Chrome (aktuelle Version)
- Firefox (aktuelle Version)
- Edge (aktuelle Version)
- Safari (aktuelle Version, falls verfuegbar)

Mobile Browser:
- Chrome Android
- Samsung Internet (optional)
- Safari iOS

Bildschirmgroessen:
- 320x568 (kleines Smartphone)
- 390x844 (modernes Smartphone)
- 768x1024 (Tablet)
- 1366x768 (Laptop)
- 1920x1080 (Desktop)

## 2) Schnell-Check pro Browser/Geraet

- Seite laedt ohne Layout-Bruch
- Bildspalte ist rechts auf Desktop
- Bild hat ovale Raender
- Hauptspalte ist breiter als Bildspalte
- Auf Mobilgeraeten stapelt sich das Layout sinnvoll
- Keine abgeschnittenen Inhalte
- Keine horizontalen Scrollbalken
- Formulareingaben sind klickbar und gut lesbar

## 3) Detaillierte Testfaelle

### A. Layout und Responsiveness

1. Desktop (1366x768 oder groesser):
- Erwartung: Zwei Spalten, Inhalt links, Bild rechts.
- Erwartung: Beide Spalten fuellen die Seitenbreite.
- Erwartung: Abstaende, Karten und Text wirken symmetrisch.

2. Tablet (768x1024):
- Erwartung: Kein Ueberlappen von Text, Bild oder Karten.
- Erwartung: Projekte bleiben ordentlich in mehreren Spalten.

3. Smartphone (390x844 und 320x568):
- Erwartung: Einspaltige Darstellung.
- Erwartung: Services untereinander.
- Erwartung: Formularfelder untereinander.
- Erwartung: Kein horizontaler Scroll.

### B. Bilddarstellung

1. Profilbild:
- Erwartung: Ovale Randform sichtbar.
- Erwartung: Bild bleibt scharf und wird nicht verzerrt.

2. Projektbilder:
- Erwartung: Bilder haben saubere Abstaende.
- Erwartung: Hover-Effekt nur auf Desktop mit Maus relevant.

### C. Typografie und Lesbarkeit

1. Schrift:
- Erwartung: Fallback-Schriften funktionieren, falls Webfonts blockiert sind.
- Erwartung: Textgroesse bleibt auf Mobil gut lesbar.

2. Kontrast:
- Erwartung: Ueberschriften und Text sind gut lesbar.
- Erwartung: Buttons sind klar erkennbar.

### D. Form und Interaktion

1. Eingabefelder:
- Erwartung: Fokusrahmen sichtbar (Tastatur und Touch).
- Erwartung: Kein abgeschnittener Placeholder-Text.

2. Button:
- Erwartung: Button ist klickbar und zeigt Hover/Fokus-Zustand.

### E. Browser-spezifische Punkte

1. Safari iOS:
- Erwartung: Kein Fehler durch Sticky/Viewport-Hoehe.
- Erwartung: Karten bleiben stabil, auch ohne Blur-Unterstuetzung.

2. Firefox:
- Erwartung: Grid/Flex-Fallback ohne Layout-Bruch.

3. Edge/Chrome:
- Erwartung: Animationen laufen weich, ohne Layout-Spruenge.

## 4) Performance Kurztest

- Seite laedt in unter 2 Sekunden im lokalen Test.
- Keine grossen Layout-Spruenge waehrend des Ladens.
- Scrollen auf Mobile bleibt fluessig.

## 5) Barrierefreiheit Kurztest

- Tab-Navigation erreicht alle Formfelder und Button.
- Fokuszustand ist sichtbar.
- Bilder haben Alt-Texte.
- Zoom auf 200 Prozent: Inhalt bleibt nutzbar.

## 6) Fehlerprotokoll Vorlage

Fuer jeden gefundenen Fehler festhalten:
- Browser + Version:
- Geraet + Aufloesung:
- Schritte zur Reproduktion:
- Ist-Zustand:
- Soll-Zustand:
- Screenshot:
- Prioritaet (hoch/mittel/niedrig):

## 7) Abnahmekriterien

Freigabe nur wenn:
- Alle Tests aus Abschnitt 2 ohne Fehler bestanden.
- Keine kritischen oder hohen Fehler offen.
- Mobile Darstellung auf mindestens iOS und Android geprueft.
