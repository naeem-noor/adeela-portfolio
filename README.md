# Adeela Noor | DPT Portfolio

A single-page portfolio website for **Adeela Noor**, a Doctor of Physical Therapy (DPT) student at the University of Sargodha, Pakistan.

Built with plain HTML, CSS and a little JavaScript. There is no framework and no build step.

## Features

- Clean, clinical teal-and-navy design with automatic light and dark mode
- Interactive **goniometer** in the hero that measures a joint angle as you drag the slider
- **Explore the body in motion**: tap a joint on the diagram to see what it does and where physiotherapy helps
- Education timeline, areas of interest, core strengths and care approach
- Navbar that highlights the section you are currently viewing
- Fully responsive and keyboard accessible, and it respects reduced-motion settings

## Project structure

```
.
├── index.html   # the whole website (HTML, CSS and JS in one file)
└── README.md
```

## Run locally

Open `index.html` in any browser. No installation is needed.

To use a local server instead:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customize

All content lives in `index.html`.

| What to change | Where to look |
| --- | --- |
| Name, headline, about text | The `hero` and `#about` sections |
| Colours | The CSS variables at the top of the `<style>` block (`--brand`, `--hero`, `--bg`) |
| Education entries | The `<ol class="tl">` list in `#education` |
| Areas of interest | The `.areas` cards in `#focus` |
| Joint descriptions | The `J` object in the `<script>` at the bottom |
| LinkedIn link | The button in `#contact` |

### Adding a photo

Place `photo.jpg` next to `index.html`, then add this where you want it to appear:

```html
<img src="photo.jpg" alt="Adeela Noor" width="320" height="400">
```

## Deploy to Netlify

1. Push this repository to GitHub.
2. In Netlify, choose **Add new site → Import an existing project** and connect the GitHub repo.
3. Leave the build command empty and set the publish directory to `.` (or leave it blank).
4. Click **Deploy**. Every push to the `main` branch redeploys automatically.

## Credits

Design and content: Adeela Noor.
Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) and [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts.
