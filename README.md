# Die Freie Liste – Website

Inoffizielle Prototyp-Website für die **Freie Liste** – einer Initiative engagierter Kundinnen und Kunden zur Vertreterwahl 2026 der Sparda-Bank München eG. **Vibe-coded mit MistralAI**

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

## Design

- **Farben:** Blau `#2563eb` (Vertrauen, Bank) und Orange `#f97316` (Akzent, Wahljahr-Hervorhebung)
- **Logo:** Drei gleich lange Balken – stehen für die Liste und für Chancengleichheit
- **Features:** Dark Mode (folgt Systemeinstellung, umschaltbar, wird gespeichert), responsives Layout (Desktop/Tablet/Smartphone), sanfte Scroll-Animationen mit `prefers-reduced-motion`-Fallback, automatische Jahreszahl im Footer
- **Barrierefreiheit:** ARIA-Labels, Tastatur-navigierbares Menü, Kontrastwerte nach WCAG AA
