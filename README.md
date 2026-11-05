![Format](https://img.shields.io/badge/format-HTML-blue)
![Release](https://img.shields.io/github/v/release/Chrisp-Codes/swot-tows-analyse)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![English](https://img.shields.io/badge/README-English-informational?style=flat-square)

Ziel
Viele SWOT-Vorlagen sind statisch, an Konten gebunden oder kostenpflichtig. Dieses Tool ist eine einzelne HTML-Datei: interaktiv, ohne Anmeldung und ohne Server.  
Die SWOT-Analyse wird mit der TOWS-Matrix verbunden. So lassen sich aus Stärken, Schwächen, Chancen und Risiken konkrete Strategien ableiten.
Funktionen
SWOT-Matrix mit Stärken, Schwächen, Chancen und Risiken
TOWS-Matrix (SO, WO, ST, WT) mit Leitfragen
Beispiel laden zum Ausprobieren
Speichern und Laden als JSON-Datei
PDF-Export (A4 quer)
Automatische Sicherung des Entwurfs im eigenen Browser
Nutzung
Online: https://chrisp-codes.github.io/swot-tows-analyse/
Offline: `index.html` herunterladen und im Browser öffnen. Eine Installation ist nicht nötig.
Aufbau
```
index.html   → komplette Anwendung (HTML, CSS, JavaScript)
LICENSE      → MIT-Lizenz
README.md
```
Es gibt keine Build-Schritte und keine Abhängigkeiten. Die einzige externe Bibliothek ist jsPDF. Sie wird nur beim PDF-Export geladen.
Datenschutz
Kein Server, kein Konto, kein Tracking, keine Cookies.
Eingaben bleiben im eigenen Browser bzw. in der exportierten JSON-Datei.
Beim PDF-Export wird jsPDF von `cdnjs.cloudflare.com` geladen. Dabei wird die IP-Adresse an den CDN-Anbieter übermittelt. Wer das vermeiden möchte, nutzt den Druckdialog des Browsers.
Methodik
SWOT-Analyse: Gegenüberstellung interner Stärken und Schwächen mit externen Chancen und Risiken.
TOWS-Matrix: von Heinz Weihrich (1982) entwickelt. Sie leitet aus den Kombinationen der SWOT-Faktoren Strategien ab (SO, WO, ST, WT).
Mitmachen
Fehler und Verbesserungsvorschläge sind willkommen, am besten über Issues. Eine Bearbeitung oder Antwort wird nicht garantiert.
Haftungsausschluss
Die Software wird ohne jede Gewähr bereitgestellt. Die Nutzung erfolgt auf eigene Verantwortung. Die Ergebnisse ersetzen keine professionelle Beratung.
Lizenz
MIT License – freie Nutzung, Veränderung und Weitergabe erlaubt. Siehe LICENSE.
