# Mohamed Elnabarawi — Portfolio

Official personal project portfolio: **https://mohammednabarawy.github.io/**

This static, bilingual (English / Arabic with real RTL) GitHub Pages website highlights work connecting accounting-domain expertise with business applications, financial-document workflows, website operations, and AI-assisted product development.

## Selected projects

- **Invoices Reader** — invoice-document workflows: https://invoicesreader.com/
- **Rakha Center** — corporate site with tenant meeting-room booking: https://rakha.net/
- **Aghna Real Estate** — corporate website: https://aghna.com.sa/
- **Arab Tech Trends** — site migration, content operations, SEO: https://www.arabtechtrends.com/
- **RUSHVANE** — browser game: https://riyadh-ring-game.pages.dev/

## Technical notes

- Homepage is a standalone `index.html` with embedded CSS and small plain-JavaScript interactions; no build step or API key required.
- Language toggle supports `lang=ar`, native `dir=rtl`, and saves the selection in browser storage.
- Project filters are client-side and do not collect visitor data.
- Contact is handled via `mailto:` (no form or user-data collection).
- `cv.html` and other pages are preserved alongside the main portfolio landing page.

## Local preview

```sh
python -m http.server 8000
```

Then open http://localhost:8000/

## Deployment

Uses the existing GitHub Pages configuration for the `mohammednabarawy.github.io` repository. The website's entry point is `index.html` on the default `master` branch.

## Professional background

See [GitHub profile](https://github.com/mohammednabarawy) or [LinkedIn](https://www.linkedin.com/in/mnabarawi).
