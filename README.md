# Coachly – Support & Rechtliches

Öffentliche Webseite der App **Coachly – Training & Community** (GitHub Pages), zweisprachig Deutsch/Englisch.

| Seite | Pfad |
|---|---|
| Support (Support-URL für App Store Connect) | `/` |
| Datenschutzerklärung (Datenschutz-URL) | `/datenschutz/` (Englisch: `/privacy/`) |
| Nutzungsbedingungen | `/nutzungsbedingungen/` (Englisch: `/terms/`) |
| Impressum | `/impressum/` (Englisch: `/legal-notice/`) |

Sprache: `?lang=de` oder `?lang=en`, sonst die Browsersprache.

Die Seiten werden erzeugt, nicht von Hand bearbeitet: Die Rechtstexte kommen aus der App (`src/data/legal.ts` im Coachly-Repo), damit App und Webseite denselben Stand haben. Generator: `coachly/support-seite/_werkzeug/build.cjs` in den Projektdateien.

```bash
node build.cjs <Coachly>/src/data/legal.ts <Coachly>/assets <dieser Ordner>
```
