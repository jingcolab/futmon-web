# Futmon — US equity research

English-language AI-assisted research workspace for futmon.com.

## Real features
- Research memo CRUD, ticker/company search, dated evidence, risks and next questions.
- Session-only by default; opt-in local browser storage, Markdown backup export, confirmed deletion and unsaved-change protection.
- Hypothetical EPS × P/E valuation scenarios with explicit limits and no live quotes.
- Local AI research prompt builder and clipboard copy. No AI model inference or paid API.
- Official SEC EDGAR, FRED and Investor.gov links; no implied affiliation.
- Responsive light/dark design and a clearly labeled AI-generated editorial skyline.

## Run
Use any static HTTP server. For example: `python -m http.server 8000` then open http://localhost:8000.
Run tests with Node 20+: `npm test`. No dependency install is needed.

## Deploy
Static deploy files: index.html, desk.html, privacy.html, style.css, desk.js, core.mjs, favicon.svg, assets/financial-district.webp and _headers. Use correct MIME types and apply _headers on Cloudflare static hosting. No database, secrets or runtime bindings are needed.

## Boundaries
No stock prices, current financial statements, AI model calls, personalized financial advice, bank connections, cloud accounts, trade execution or guaranteed returns. User input is not sent to a server by this app. Optional local storage is not encrypted or synced. Export a backup; avoid shared devices and confidential data. Hosting providers may process standard request metadata.
