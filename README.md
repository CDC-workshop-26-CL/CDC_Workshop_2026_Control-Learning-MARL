# CDC 2026 Workshop Website

Website for the workshop:

**Learning, Control, and Strategy in Autonomous Interactive Systems**

at IEEE CDC 2026.

## Files

- `index.html` — all website content
- `style.css` — website appearance
- `images/` — put speaker and organizer photos here

## How to preview locally

Open `index.html` in any web browser.

## How to publish with GitHub Pages

1. Create a GitHub repository, for example `cdc2026-workshop`.
2. Upload `index.html`, `style.css`, and the `images` folder.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder.
6. Save.
7. GitHub will provide a public URL such as:
   `https://YOUR-USERNAME.github.io/cdc2026-workshop/`

## What to update first

Search inside `index.html` for these placeholders:

- `Workshop date: To be announced`
- `Location: To be announced`
- `Speaker Name`
- `University / Institution`
- `Talk title coming soon`
- `Organizer Name`
- `workshop-email@example.com`

## Adding a speaker photo

Put the photo in `images`, for example:

`images/speaker-smith.jpg`

Then replace:

```html
<div class="speaker-photo placeholder" aria-hidden="true">Speaker</div>
```

with:

```html
<img class="speaker-photo" src="images/speaker-smith.jpg" alt="Professor Jane Smith">
```

## Adding more speakers

Copy one complete `<article class="speaker-card"> ... </article>` block and edit its name, affiliation, talk title, and website link.

