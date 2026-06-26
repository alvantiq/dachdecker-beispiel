# BERGHOFF Bedachungen — DeinWebPilot Beispiel-Website (Dachdecker / Bedachungen)

Statische Demo-/Beispiel-Website für die Branche **Dachdecker / Bedachungen**,
gebaut von [DeinWebPilot](https://deinwebpilot.de). Vorzeige-Beispiel für Akquise
und Pitch — eine fiktive Beispielfirma ("BERGHOFF Bedachungen", Hofheim am Taunus),
keine echten Kundendaten.

## Stack
- Reine statische Single-Page (`index.html`), keine Build-Steps.
- Self-contained: lokale Assets unter `assets/dach/` + Webfonts unter `assets/fonts/`, kein externes CDN.
- Inline CSS + inline JS.

## Deploy
- Hosting: Vercel (Static), Region `fra1`.
- Ziel-Domain (Produktion): `deinwebpilot.dachdeckerbeispiel.de`.

## Lokal ansehen
```bash
python3 -m http.server 4321
# http://localhost:4321
```

## Workflow
`feat/*` Branch → PR → Review → Merge nach `main` → Vercel Production-Deploy.
