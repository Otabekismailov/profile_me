# Otabek Ismailov — Portfolio Site

Personal portfolio website for QA Engineer positioning.

## Quick start (local preview)

Open `index.html` in any browser — no build step needed.

## Add your photo

1. Save your professional photo as **`profile.jpg`** in this same folder (square or 4:5 portrait works best, ~800×1000px).
2. Open `index.html` in a text editor and find this block (around line ~580):

```html
<!-- TO ADD YOUR PHOTO: Replace the placeholder div below with:
     <img src="profile.jpg" alt="Otabek Ismailov"> -->
<div class="hero-photo-placeholder">
  ...
</div>
```

3. Replace the entire `<div class="hero-photo-placeholder">...</div>` block with:
```html
<img src="profile.jpg" alt="Otabek Ismailov">
```

That's it.

## Deploy to GitHub Pages (free hosting)

1. Create a new repository on GitHub: `otabekismailov.github.io` (must match your username exactly for a personal site).
2. Upload `index.html` and `profile.jpg` to the repo.
3. Go to **Settings → Pages → Source: Deploy from branch → main → /(root) → Save**.
4. Your site will be live in ~1 minute at: **`https://otabekismailov.github.io`**

Add this URL to your CV, LinkedIn, and Telegram bio.

## Deploy to Netlify (alternative — even easier)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this whole folder into the page.
3. Done. You'll get a free `*.netlify.app` URL.

## Add your CV download link

Place `Otabek_Ismailov_CV.pdf` in this same folder. The "Download CV" button on the site already points to `cv.pdf` — rename your CV to `cv.pdf` or update the link in `index.html`:

```html
<a href="Otabek_Ismailov_CV.pdf" class="btn btn-secondary" download>
```

## What's inside

- `index.html` — single-file portfolio site (HTML + CSS + JS, ready to deploy)
- `Otabek_Ismailov_CV.docx` — editable Word version of CV
- `Otabek_Ismailov_CV.pdf` — print/email-ready CV

## Customization tips

- **Color scheme:** edit the `:root` CSS variables at the top of `index.html` (line ~10).
- **Sections:** all section content is plain HTML, easy to edit directly.
- **New project?** Duplicate the `<article class="project-card">` block in the Projects section.

---

**Need help?** All the code is plain HTML/CSS — open it, change the text, refresh the browser.
