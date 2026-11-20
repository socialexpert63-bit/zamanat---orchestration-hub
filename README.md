# Zamanat Institutional Orchestration Hub (concept prototype)

A static concept prototype: a marketing website, a working dashboard and a recorded platform walkthrough video.

> All mandates, partners, documents and figures are fictional demonstration data. This is not the official Zamanat website, and it does not represent any agreement with the partners or products shown. It does not issue tokens, execute trades, collect funds or process subscriptions.

## Contents

| File | What it is |
| --- | --- |
| `index.html` | Concept website with logo, animations, AI automation lab, module explorer, readiness demo, FAQ and the walkthrough video |
| `dashboard.html` | Interactive dashboard with 15 modules (origination, mandates, structuring, Shariah governance, regulatory, partners, technology, distribution readiness, data room, audit trail, AI copilot, reports) |
| `assets/zamanat-walkthrough.mp4` | Captioned screen recording of the dashboard (about 3 minutes, no audio) |
| `assets/zamanat-walkthrough-poster.jpg` | Video poster image |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

There is no build step and no dependencies. Fonts load from Google Fonts when online and fall back to the system font otherwise.

## Run locally

Open `index.html` in a browser. The "Open dashboard" buttons go to `dashboard.html` in the same folder.

## Publish on GitHub Pages

1. Create a repository and upload these files (keep the `assets` folder).
2. In the repository, open Settings, then Pages.
3. Under Build and deployment, choose "Deploy from a branch", select the `main` branch and the `/ (root)` folder, then save.
4. After a minute the site is live at `https://<your-user>.github.io/<repository>/`.

The video is about 10 MB, which is within GitHub's file limits.

## Guardrails built into the prototype

- Shariah decisions stay with the appointed independent advisor. A review cannot be marked complete without the advisor's recorded decision, and nothing generates a ruling or a compliance score.
- Regulatory "Completed by Responsible Party" means a task is finished, not that a product is approved.
- A full readiness checklist is never shown as an approval.
- The AI copilot summarises recorded data for human review and refuses to give rulings, legal opinions or investment recommendations.
