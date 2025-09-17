# Uwe Müller GmbH – Satellitenseite „Bagger mieten in Aachen, Heinsberg & Düren“

**Live-URL:** https://uwe-muller-gmbh.github.io/bagger-mieten/  
**Zweck:** Kleine, schnelle Satellitenseite für das Thema **Bagger mieten** in der Region Aachen · Heinsberg · Düren – mit klarem Hero, starken CTAs und sauberem SEO-Grundsetup.

---

## Highlights

- **DSGVO-freundlich**: keine externen Schriften/Tracker, alles lokal.
- **Klarer Hero**: großes lokales Bild (`images/Desk.jpg`), **kein** globales Overlay; nur der **Content-Block** ist halbtransparent.
- **Starke Copy + CTAs**: „Faires Angebot · Persönlicher Kontakt · Familienunternehmen · Individuelle Beratung“ + direkte Verlinkung zur Hauptseite.
- **Mobil & schnell**: `min-height: 100svh`, `preload` fürs Hero-Bild, system fonts.
- **SEO-Setup**: konsistenter Title/Description, Canonical, OG/Twitter, JSON-LD (WebSite, Organization, Service, FAQ, Breadcrumb).
- **Rechtliches**: Links zu **Impressum** und **Datenschutz** der Hauptseite.

---

## Projektstruktur

bagger-mieten/
├─ images/
│ └─ Desk.jpg # Hero-Bild (lokal, groß & scharf)
├─ index.html # komplette Seite inkl. CSS
└─ README.md # diese Datei



> Optional: zusätzlich `Desk.webp` / `Desk.avif` in `images/` ablegen (siehe Performance-Tipp).

---

## Lokale Vorschau

Ohne Build-Tool, rein statisch:

```bash
# im Projektordner
python -m http.server 8000
# dann im Browser öffnen:
# http://localhost:8000/
