# Taufeeq Mohammad – Portfolio

A single-file portfolio site (`index.html`). Everything is built in: HTML, CSS, JavaScript, fonts, images, video and audio. There is no build step and no dependencies. The only external request is Google Fonts (Inter and Instrument Serif).

## Run it locally
Double-click `index.html`, or serve the folder:

```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Put it live with GitHub Pages
1. Create a new GitHub repository (for example `portfolio`). Leave it empty.
2. In this folder run:

```bash
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/portfolio.git
git push -u origin main
```

3. On GitHub open **Settings > Pages**. Under **Build and deployment** choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/portfolio/`.

Tip: name the repository `<your-username>.github.io` to get the shorter address `https://<your-username>.github.io/`.

## Things to edit
Open `index.html` and search for these names near the top of the main script:

- `LINKS` – Résumé, Behance and LinkedIn URLs. The résumé link is currently empty.
- `MAIL` – your contact email.
- `RAW` – project titles, descriptions and outcomes.
- `Q` – the feedback quotes.

The site uses hash routing (`#/work`, `#/case/prism`), so it works on GitHub Pages without extra server settings.

## Notes
- The file is about 8 MB because the media is embedded, so the first load takes a moment. GitHub Pages serves it compressed.
- Background music and the opening video need a tap on **Enter**, because browsers block autoplay with sound.
