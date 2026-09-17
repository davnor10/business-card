# Player Card · Digital Business Card

A retro-arcade digital business card built with **HTML and CSS only** (no JavaScript).

- **Day / Night mode**: a hidden checkbox (`#theme-switch`) sits before `.page`, and `#theme-switch:checked ~ .page` swaps every CSS custom property. Day mode has a chunky sticker look with hard shadows. Night mode is synthwave neon with a striped sun and a moving grid floor.
- **Responsive**: built mobile-first, with breakpoints at 560px, 760px, 960px and 1200px.
- **Sections**: hero (photo, name, role, GitHub/LinkedIn), bio and character sheet, skills and tools, projects, timeline, and contact (email, phone, GitHub, LinkedIn).

## Files

```
index.html        page markup
style.css         all styles
images/avatar.svg pixel-art profile picture
```

## Run locally

Open `index.html` in a browser.

## Deploy to GitHub Pages

1. Create a **public** repository and push these files to the `main` branch.
2. Go to **Settings → Pages → Build and deployment**, choose *Deploy from a branch*, pick `main` / `root`, and save.
3. The site will be live at `https://<username>.github.io/<repo-name>/`.
