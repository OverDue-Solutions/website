# OverDue Solutions website

Simple static landing page (HTML + CSS only) for GitHub Pages.

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Images

Put logo and other assets in the `images/` folder. The page expects `images/logo.png` by default.

## Enable GitHub Pages

1. Push this repo to `main`.
2. On GitHub: **Settings → Pages**.
3. Set source to **Deploy from a branch**.
4. Choose branch **`main`** and folder **`/ (root)`**.
5. Save, then wait a minute for the site at:

   `https://overdue-solutions.github.io/website/`
