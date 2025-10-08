# Study Planner — Progressive Web App (PWA)

This is a simple offline-capable Study Planner (todo) built as a Progressive Web App.

## What you get
- `index.html`, `styles.css`, `app.js` — a responsive todo UI.
- `manifest.json` and `sw.js` — make the app installable and offline-capable.
- `404.html` — helps GitHub Pages serve the app correctly.
- `icons/` folder (must add icons before publishing) — sample placeholder icons included.

## How to deploy on GitHub Pages (quick steps)

1. Create a new GitHub repository (e.g. `study-planner-pwa`) on your GitHub account.
2. Clone it locally or upload the project files to the repo root.
3. Commit & push to the `main` branch.
4. In the repo Settings → Pages, select branch `main` and folder `/ (root)` then Save.
5. Wait a minute and open `https://<your-username>.github.io/<repo-name>/` — that is your GitHub Pages URL.

## Important notes for your course submission
- **Customize** the app: add your name in the footer, change wording, or add one extra feature to make it your own.
- Your instructor will check for AI-generated code. To reduce risk, manually review & modify variable names, comments, and text strings.
- If you want, add a short `submission.txt` with your name, student ID, and classroom link before uploading.

## Troubleshooting
- If service worker doesn't update, open DevTools → Application → Service Workers → Unregister and reload.
- If GitHub Pages gives a 404, ensure `index.html` and `404.html` are in repo root and Pages is set to root.

Good luck! — personalize and submit the GitHub Pages link & repo link to Google Classroom.
