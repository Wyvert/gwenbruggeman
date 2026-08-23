# gwenbruggeman.com

The source for Gwendolyn Bruggeman's professional website. It is deliberately built with plain HTML and CSS so it can be hosted directly by GitHub Pages and maintained without a build system.

## Edit the site

- `index.html` — homepage and services
- `portfolio/index.html` — project portfolio
- `resume/index.html` — concise résumé
- `cv/index.html` — full work history
- `assets/style.css` — colors, typography, layout, and mobile styles
- `assets/og.png` — social-sharing image

GitHub's web editor is enough for copy changes. Open a file, click the pencil icon, make the change, and commit it to `main`. GitHub Pages will republish automatically.

## GitHub Pages settings

In the repository, open **Settings → Pages** and choose:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

After the ordinary `github.io` address is working, enter `gwenbruggeman.com` under **Settings → Pages → Custom domain**. GitHub will create the required `CNAME` file. Then update the domain's DNS records and enable **Enforce HTTPS** after DNS finishes updating.

## Local preview

Open `index.html` directly, or run a small local web server from this folder:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.
