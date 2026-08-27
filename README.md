# devinpbrown.github.io

Personal academic website for Devin P. Brown, built as a static site for GitHub Pages
(no build step — plain HTML/CSS).

## Structure

- `index.html` — home / bio
- `research.html` — working papers and projects
- `teaching.html` — teaching philosophy, courses, syllabus
- `cv.html` — CV summary + link to full PDF
- `assets/css/style.css` — shared styles
- `assets/img/` — optimized images used on the site
- `assets/pdf/` — CV, papers, and syllabus PDFs served for download

## Updating content

Edit the relevant `.html` file directly. To update the CV or add a paper, drop the
new PDF into `assets/pdf/` and update the link in `cv.html` or `research.html`.

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser.
