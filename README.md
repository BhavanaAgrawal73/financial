# Quarterly Earnings – Reveal.js (index.html)

An interactive **Reveal.js** presentation for a financial institution’s quarterly earnings report. The deck is a single, self‑contained `index.html` that includes:

* **Email in deck:** `21f2000670@ds.study.iitm.ac.in` (title slide)
* **Markdown slide:** Revenue table via `data-markdown`
* **Animated fragments:** Progressive bullets on the Agenda slide
* **Code highlighting:** Python EPS example with line numbers (Highlight.js)
* **Math:** ROE formula rendered with MathJax (TeX)
* **Speaker notes:** Presenter guidance in `<aside class="notes">` (press **S**)

---

## Live site (GitHub Pages)

Once Pages is enabled, your site will be here:

```
https://<username>.github.io/<reponame>/
```

For this repo: `https://BhavanaAgrawal73.github.io/financial/`

**Enable Pages:** Repo **Settings → Pages → Build and deployment**

* **Source:** Deploy from a branch
* **Branch:** `main`
* **Folder:** `/ (root)`
* **Save**

> Since your entry file is `index.html`, it will load automatically at the URL above.

---

## Repo layout

```
.
├─ index.html            # Reveal.js deck (entry file)
└─ README.md             # This file
```

*(Add an `assets/` folder for images/logos if needed and reference them relatively.)*

---

## Local preview

Use any static file server and open `http://localhost:8000/`.

**Python (3.x) built‑in:**

```bash
python -m http.server 8000
```

**Node (http-server):**

```bash
npx http-server -p 8000
```

**Reveal CLI (optional):**

```bash
npx reveal-md index.html --port 8000
```

---

## Editing the slides

Each slide is a `<section>` inside `.slides`. The curre
