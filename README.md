# Shakespeare Play Quiz

A zero-dependency static personality quiz designed for GitHub Pages.

## Test locally
Open `index.html` in a browser. No build step is required.

For a local HTTP server (optional):

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a repository and add `index.html`, `style.css`, and `script.js` to its root.
2. In GitHub: **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your main branch and `/ (root)`, then save.

## Structure
- `index.html` — page shell
- `style.css` — responsive styling
- `script.js` — 15 questions, scoring, play profiles, and results

The quiz stores no answers and uses no external libraries, fonts, analytics, cookies, or APIs.
