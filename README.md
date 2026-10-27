# Pathfinder — Your future, your way

A responsive, interactive student career discovery and higher-education planning app. This project is a local prototype with sample career and study-route content, local persistence, reflection tools, comparison, pathway planning, Career Quest, and plan export.

## Run locally on macOS

1. Install Node.js 20 or later from https://nodejs.org/ if you do not already have it.
2. Open this folder in Antigravity.
3. Open Antigravity's terminal (**Terminal → New Terminal**).
4. Run:

```bash
npm install
npm run dev
```

5. Open the local URL Vite prints, usually `http://localhost:5173`.

To create a production build:

```bash
npm run build
npm run preview
```

## Features

- Distinctive navy / slate / off-white / coral / red visual identity.
- Cinematic hero with animated route illustration, scroll-reveal sections, a moving field ticker, and responsive layouts.
- Seven-question interest reflection with multi-theme results.
- Searchable career library, filters, career detail drawer, save and compare actions.
- Illustrative course/study-route catalogue with filters and verification notes.
- Compare up to three saved careers or routes, with user-selected priorities.
- Six-step visual pathway with persistent completion states and expandable guidance.
- Decision checklist, local notes, conversation starter, and downloadable text/JSON plan.
- Five-round Career Quest with replay and theme suggestions.
- Local-data reset with confirmation.
- Reduced-motion support and keyboard focus styling.

## Data and privacy

This prototype stores saved options, quiz answers, quest answers, pathway progress, checklist state, priority, and notes in the current browser's `localStorage`. It does not require an account or send these values to a server. Do not enter sensitive personal information. Use **Clear local data** in the sidebar or footer to reset Pathfinder's data in this browser.

## Content disclaimer

Career and study-route entries are illustrative sample content, not verified institution listings. Entry requirements, duration, fees, recognition, accreditation, and professional requirements vary by provider and region. Verify all real decisions with official sources. This tool supports exploration and does not diagnose aptitude or guarantee admissions, employment, salary, or success.
