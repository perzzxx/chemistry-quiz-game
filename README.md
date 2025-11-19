# Chemistry Quiz Game (เกมเคมีสนุกๆ)

This is a single-file HTML/CSS/JS quiz game (Thai language) that can be hosted with GitHub Pages.

How to publish:
1. Create a GitHub repository (e.g. `chemistry-quiz-game`).
2. Add `index.html` (this file) to the repository root.
3. Optionally add this README and an empty `.nojekyll` if you want GitHub Pages to serve root files without Jekyll processing.
4. Enable GitHub Pages in repository Settings:
   - Source: Branch `main` (or `gh-pages`) and folder: `/ (root)`
   - Save and visit the provided URL (e.g. `https://<your-username>.github.io/<repo-name>/`).

Local preview:
- Just open `index.html` in your browser, or use a simple local static server:
  - Python 3: `python -m http.server 8000` then open `http://localhost:8000`
  - VS Code: Use Live Server extension

Notes:
- No backend required — purely static.
- If you want a user-page (URL `https://<your-username>.github.io`) name the repo `<your-username>.github.io`.
