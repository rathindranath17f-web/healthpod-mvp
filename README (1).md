# Health Pod — Investor Demo

An interactive, single-file demo of Health Pod, the full-commode health diagnostic platform. Everything runs in the browser: an investor pitch, plain-language technology, a labeled 3D product navigator, a step-by-step live simulator, cost and revenue models, competition, innovation and patents, and a validation tab.

BPP Group 8 · Section F · EPGP Batch 17

## What to upload

Upload all of these to the repository:

- `index.html` — the demo (open this / it is the site homepage)
- `three.min.js` — the 3D library, bundled locally so the 3D navigator works even on weak wifi
- `README.md` — this file
- `.nojekyll` — tells GitHub to serve the files as-is (optional but recommended)

## View it online (GitHub Pages)

1. Create a new repository on GitHub and upload the files above.
2. In the repository, go to **Settings** then **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose the **main** branch and the **/ (root)** folder, then click **Save**.
5. Wait about a minute. The page goes live at:
   `https://<your-username>.github.io/<your-repo-name>/`

That link opens the demo directly, because the file is named `index.html`. Share that link with your professor and team.

## View it locally

Just open `index.html` in any modern browser (double-click it). No install, no build step. Keep `three.min.js` in the same folder so the 3D loads.

If your browser blocks anything when opened as a file, serve it locally instead:

```
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## What is in it

The demo is a set of tabs across the top:

- **The Health Pod — Intro:** what it is, the purpose, the motivation, the research it stands on, and a technical "under the hood" section explaining the full signal chain.
- **Why invest:** the case in six points, plus an honest feasibility table.
- **3D Navigator:** rotate the product, explode the parts, and tap any component to read its role.
- **Architecture:** plain-language "how it works", then the four technical layers, with a feasibility check.
- **Biomarkers:** the ten-marker MVP panel.
- **Simulator:** a step-by-step walkthrough of a real morning with five people, showing who is tested and who is not.
- **Survey, Team feedback, Professor feedback:** findings and how each was addressed.
- **Cost model, Revenue model:** granular costs and the three-layer revenue model.
- **Competition, Innovation and Patents, Validation.**

## Notes

- The demo is `index.html`. The 3D library `three.min.js` sits next to it and loads locally, so the 3D navigator works even if the room wifi is weak. If the local copy is missing, it falls back to loading from a public CDN.
- The web fonts load from Google Fonts when online; if offline, the page falls back to your system fonts and still looks clean.
- The 3D model and the simulator are made-for-demo representations, not a built product or filmed footage.
- All prices and accuracy figures are design targets pending real quotes and clinical validation. Nothing here is a filed patent.

## Ownership

This is proprietary work for the Health Pod project. All rights reserved. Please do not redistribute without permission.
