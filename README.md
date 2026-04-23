# Farzat CV Website

Moderne, responsive Portfolio- und CV-Website mit HTML und CSS.

## Uebersicht

Diese Website stellt ein persoenliches Profil mit folgenden Bereichen dar:
- Profilbild in einer rechten Spalte
- Fixierte Detailkarte unter dem Profilbild (Name, Beruf, Kontakt)
- Hauptinhalt mit Kurzvorstellung
- Services-Bereich mit professionellen Bildern
- Kontaktformular mit Web3Forms-Integration

## Projektstruktur

- Farzat.html: Hauptseite mit kompletter Struktur
- style.css: Design, Layout, Responsiveness und Animationen
- Image/: Alle verwendeten Bilder und Icons
- Browser-Testplan.md: Checkliste fuer Cross-Browser-Tests

## Features

- Responsives Layout fuer Desktop, Tablet und Mobile
- Moderne Kartenoptik mit Schatten und sanften Farbverlaeufen
- Rechte Profilspalte mit fixierter Bild- und Detaildarstellung
- Service-Karten mit professionellen Fotos
- Kontaktformular via Web3Forms (ohne eigenes Backend)

## Web3Forms konfigurieren

Das Formular ist bereits mit Web3Forms vorbereitet.

1. Oeffne Farzat.html.
2. Suche im Formular das Feld:
   <input type="hidden" name="access_key" value="DEIN_WEB3FORMS_ACCESS_KEY_HIER">
3. Ersetze den Platzhalter mit deinem echten Access Key.
4. Speichern und Website neu laden.
5. Testnachricht ueber das Formular senden.

Optional:
- subject-Feld anpassen fuer eigenen E-Mail-Betreff.
- Success/Error-Anzeige per JavaScript ergaenzen.

## Lokal starten

Da es eine statische Website ist, reicht eine der folgenden Methoden:

- Datei Farzat.html direkt im Browser oeffnen
- Oder mit VS Code Live Server starten

## Anpassungstipps

- Farben: In style.css unter :root (CSS-Variablen)
- Spaltenlayout: .page, .profile, .profile-info, .profile-details
- Service-Bilder: Image/service-*-pro.jpg austauschen
- Kontakttexte: In Farzat.html im Bereich Contact Me

## Browser-Kompatibilitaet

Die Website wurde so gebaut, dass sie in modernen Browsern stabil laeuft:
- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Fuer strukturierte Tests siehe Browser-Testplan.md.

## Lizenz

Dieses Projekt ist fuer den persoenlichen Einsatz als Portfolio/CV gedacht.
Bitte pruefe die Lizenzbedingungen externer Bilder, Icons und Dienste (z. B. Unsplash, Web3Forms).
