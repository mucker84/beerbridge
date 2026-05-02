# BeerBridge — CLAUDE.md

## Projekt

Komunitní projekt spojující české místní a expaty v Praze přes setkání v hospodách.
URL: beerbridge.com | Status: v0.1 coming soon

## Stack

- Frontend: Vanilla HTML/CSS/JS — žádný framework, žádný build tool
- Backend: Firebase (Firestore + Google Auth)
- Analytics: Google Analytics (G-QQTD6TPJ7R)
- Hosting: není definováno (lokální XAMPP dev)

## Soubory

- `index.html` — hlavní landing page, registrační formulář, Firebase integrace
- `admin.html` — admin panel, Google OAuth, seznam registrací
- `beer_bridge_landing.html` — starší/alternativní verze bez Firebase (archiv)

## Styl a konvence

- Barvy: primary #B87333 (měď), bg #f5f5f3, text #1a1a1a
- Fonty: DM Serif Display (display), DM Sans (body)
- Max-width obsahu: 680px
- Žádné závislosti mimo Firebase SDK a Google Fonts (CDN)

## Přístupy

- Jednoduché PHP? Ne — Firebase je záměrná volba (zero server maintenance)
- Žádný npm, žádný Vite, žádné frameworky — projekt záměrně minimalistický
- Jazyková mutace: anglicky pro expaty, česky v admin panelu

## Model pro subagenty

- Průzkum souborů, grep, čtení struktury → Haiku
- Implementace nových sekcí, refaktoring HTML/CSS → Sonnet nebo aktuální model
- Architektonická rozhodnutí, nové features → aktuální model
