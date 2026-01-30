# ResumeSense AI

A single-page, front-end resume analyzer that simulates ATS-style screening and delivers role-specific guidance. Designed as a lightweight demo with no backend requirements.

## Highlights
- Role-specific fit scoring with keyword matching
- ATS checklist (email, phone, links, summary, skills)
- Impact metrics (quantified wins, action verbs, bullet density)
- Job description parsing for missing keyword detection
- Exportable JSON report + copy-to-clipboard summary
- Local analysis history stored in `localStorage`
- Demo resume loader and `.txt` resume upload

## Run locally
Open `index.html` in a browser.

## GitHub Pages deploy (manual)
1. Create a GitHub repo and add it as `origin`.
2. Push to `main`.
3. In GitHub: **Settings → Pages → Build and deployment**
   - Source: `Deploy from a branch`
   - Branch: `main` / root
4. Save and wait for the deployment URL.

## Project structure
- `index.html` — application UI, styles, and logic

## Notes
This project is a front-end demo. API hooks (e.g., Gemini) are stubbed and ready for wiring.
