# lindseylab-site

Proof-of-concept website for the [Lindsey Lab](https://github.com/LindseyLab-umich) at the University of Michigan,
built from the content of https://lindseylab.engin.umich.edu/.

Plain HTML + CSS, no build step. All links are relative, so the site works both as a
project page (`https://laubachb.github.io/lindseylab-site/`) and, once moved, as the org
page (`https://lindseylab-umich.github.io/`).

## Pages

| File | Content |
|---|---|
| `index.html` | Research overview, three research thrusts, recent publications |
| `people.html` | PI bio/CV, postdocs, students, alumni |
| `publications.html` | Full publication list with TOC thumbnails |
| `software.html` | ChIMES suite and group repositories |
| `news.html` | Awards, talks, conferences, press |
| `join.html` | Openings and contact |
| `css/style.css` | All styling (U-M blue/maize, automatic dark mode) |

Images live in `img/{people,pubs,news,research,software,group}/` as WebP (~1 MB total).

## Common edits

- **New member:** copy a `<div class="card member">` block in `people.html`, add a square-ish photo to `img/people/`.
- **New paper:** copy an `<li>` in `publications.html` (wrap lab members in `<u>`), optional thumbnail in `img/pubs/`.
- **News item:** copy an `<li>` in `news.html`.

Preview locally with `python3 -m http.server` and open http://localhost:8000.

## Moving to the org

Transfer this repo to `LindseyLab-umich` (Settings → Transfer ownership), rename it to
`LindseyLab-umich.github.io`, and enable Pages from `main` / root.
