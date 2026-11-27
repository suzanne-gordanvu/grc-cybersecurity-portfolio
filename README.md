# grc-cybersecurity-portfolio

GRC & compliance portfolio: risk register, security audit, vulnerability assessment, and incident response work samples.

**Live site:** https://suzanne-gordanvu.github.io/grc-cybersecurity-portfolio/ (once GitHub Pages is on)

## What's in here

| File | What it is |
|---|---|
| `index.html` | The whole page: text, links, and project rows |
| `styles.css` | Colors, fonts, and layout (matches the LinkedIn banner) |
| `assets/photo.jpg` | Profile photo |
| `assets/resume.pdf` | Resume (add this file) |

This is a plain HTML/CSS site. It has no build step, no template, and no JavaScript.

## How to edit common things

Everything you'll usually change is in `index.html`. Search the file for `EDIT` to find the spots that need your input.

- **Project text:** each project is a `<details class="project">` block with a comment header like `01 · Risk Register`. Replace the `[bracketed]` placeholders.
- **Document links:** in each project, replace `href="#"` on the "Open Google Doc/Sheet" button with the share link. Set each file to *Anyone with the link can view*.
- **Add a project:** copy a whole `<details>…</details>` block, paste it where you want it, and update the number, title, text, and link.
- **Resume:** upload your PDF as `assets/resume.pdf` (Add file → Upload files, inside the `assets` folder).
- **Photo:** replace `assets/photo.jpg` with a square image, at least 400×400px.

## Turning on GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → Branch: **main**, folder **/ (root)** → Save. The site goes live in about a minute.
