# IEB Project Assistant — GitHub Pages site

Static landing page for downloads and project overview.

## GitHub Pages setup

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Source: **Deploy from a branch**
4. Branch: `main` (or `master`) · Folder: **`/docs`**
5. Save — site will be at `https://<username>.github.io/<repo>/`

## Set your download link

Open `index.html` and replace every `YOUR_DOWNLOAD_LINK_HERE` with your release URL, for example:

```html
href="https://github.com/your-user/IEB-Project-Helper/releases/download/v1.0.0/IEB-Project-Assistant.zip"
```

There are **3** download buttons (nav, hero, footer CTA). Update all of them.

Also update the **View on GitHub** links if needed (`href="https://github.com/your-user/your-repo"`).

## Preview locally

Open `docs/index.html` in a browser, or:

```bash
npx serve docs
```
