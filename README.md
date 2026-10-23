# Dato Giovanni: Portfolio Website

A static portfolio built with plain HTML, CSS and a little JavaScript. No installation or build step is needed, and it is ready for GitHub Pages.

## Project structure

```
index.html      Page content (all sections)
styles.css      All styling; colours are variables at the top
script.js       Mobile menu and footer year
assets/
  CV_Dato_Giovanni.pdf    The CV linked by "Download CV"
  CV_Dato_Giovanni.docx   Editable copy of the CV
README.md       This file
```

## Preview locally

Double-click `index.html` to open it in your browser. To preview with a local server instead, run `python -m http.server 8000` in this folder and open http://localhost:8000.

## Upload to GitHub

1. Sign in at github.com and click **New repository**.
2. Name it `YOUR-USERNAME.github.io` (replace with your GitHub username). Set it to **Public** and create it.
3. Click **uploading an existing file**, drag in `index.html`, `styles.css`, `script.js`, `README.md` and the whole `assets` folder, then click **Commit changes**.

## Publish with GitHub Pages

1. In the repository, go to **Settings → Pages**.
2. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then click **Save**.
3. Wait 1 to 2 minutes. Your site will be live at `https://YOUR-USERNAME.github.io`.

## Updating the site

- **Contact details:** edit the `#contact` section in `index.html` (email and LinkedIn links) and the footer.
- **Skills:** edit the `<ul class="chips">` lists in the `#skills` section. Add or remove `<li>` items.
- **Projects:** copy an existing `<article class="card project">` block in `#projects` and change the text. When a project has a real repository, add this line inside the card:
  `<a href="https://github.com/YOUR-USERNAME/REPO-NAME" target="_blank" rel="noopener noreferrer">View on GitHub</a>`
- **Finished a planned lab?** Move its card from "Planned lab projects" into "Completed projects" and describe what you built.
- **CCNA progress:** edit the `<ol class="path">` list in `#learning`. When you pass the exam, change the status line and add the date.
- **New CV:** replace the files in `assets/` and keep the same file names.
- **Colours:** change the variables at the top of `styles.css`.
