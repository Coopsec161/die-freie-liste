# Die Freie Liste – Website

Website der **Freien Liste** – einer Initiative engagierter Kundinnen und Kunden zur Vertreterwahl 2026 der Sparda-Bank München eG.

> Chancengleichheit und Transparenz

## Projektstruktur

```
├── index.html        Komplette One-Page-Website (Prototyp, fertig zur Veröffentlichung)
├── assets/
│   └── logo.svg      Logo der Freien Liste als eigenständige SVG-Datei
└── README.md         Diese Datei
```

## Inhalte bearbeiten

Die Seite ist eine einzige HTML-Datei ohne Build-Schritt. Einfach `index.html` öffnen und die Texte direkt anpassen.

**Noch auszufüllen (Platzhalter sind mit `[ … ]` markiert):**

- Kandidatinnen und Kandidaten (Abschnitt „Kandidaten“): Namen, Kurzprofile, Fotos
- Kontakt: E-Mail-Adresse, Postanschrift, Erreichbarkeit
- Impressum: Name und Anschrift des Verantwortlichen (§ 18 Abs. 2 MStV)
- Termine 2026: Wahlzeitraum und Fristen, sobald bekannt

## Vorschau

`index.html` einfach im Browser öffnen – die Seite läuft ohne Server, ohne Build und ohne Abhängigkeiten (außer der Google-Font „Inter“, der per CDN geladen wird).

## Veröffentlichen mit GitHub Pages

1. Repo öffnen → **Settings** → **Pages**
2. Unter **Source** den Branch **main** wählen → **Save**
3. Nach ca. 1 Minute ist die Seite unter `https://<nutzername>.github.io/die-freie-liste/` erreichbar

**Hinweis:** Bei privaten Repositorys ist GitHub Pages nur mit einem kostenpflichtigen Plan verfügbar. Alternativ: Repo auf öffentlich stellen (der Code enthält nur Platzhalter, keine sensiblen Daten) oder die Dateien auf den bestehenden Webserver bei die-freie-liste.org hochladen.

## Design

- **Farben:** Blau `#2563eb` (Vertrauen, Bank) und Orange `#f97316` (Akzent, Wahljahr-Hervorhebung)
- **Logo:** Drei gleich lange Balken – stehen für die Liste und für Chancengleichheit
- **Features:** Dark Mode (folgt Systemeinstellung, umschaltbar, wird gespeichert), responsives Layout (Desktop/Tablet/Smartphone), sanfte Scroll-Animationen mit `prefers-reduced-motion`-Fallback, automatische Jahreszahl im Footer
- **Barrierefreiheit:** ARIA-Labels, Tastatur-navigierbares Menü, Kontrastwerte nach WCAG AA
