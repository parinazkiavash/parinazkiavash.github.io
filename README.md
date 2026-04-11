# Parinaz Kiavash Personal Website

A static personal website designed for GitHub Pages deployment.

## Folder structure

```text
parinaz-kiavash-website/
├── index.html
├── .nojekyll
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    ├── img/
    │   ├── favicon.svg
    │   └── profile-placeholder.svg
    └── js/
        └── main.js
```

## Before deploying

1. Add your portrait as:
   `assets/img/parinaz-headshot.jpg`

   If you do not add a photo, the website automatically falls back to the included placeholder.

2. Open the folder in VS Code.
3. Preview locally by using a simple live server extension or by opening `index.html` in the browser.

## Deploy to GitHub Pages

### Option 1: deploy from the repository root

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

Then in GitHub:

- Go to **Settings** → **Pages**
- Under **Build and deployment**, choose **Deploy from a branch**
- Select **main** and **/(root)**
- Save

Your site will be available at:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

### Option 2: personal GitHub Pages site

If the repository is named exactly:

```text
YOUR-USERNAME.github.io
```

then the site will be served directly at:

```text
https://YOUR-USERNAME.github.io/
```

## Easy edits

- Main content: `index.html`
- Visual design: `assets/css/styles.css`
- Small interactions: `assets/js/main.js`

## Notes

- The site is fully static and compatible with GitHub Pages.
- Fonts are loaded from Google Fonts.
- The publication section currently includes selected publications and can be expanded easily later.
