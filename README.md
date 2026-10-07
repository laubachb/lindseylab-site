# lindseylab-site

Proof-of-concept website for the [Lindsey Lab](https://github.com/LindseyLab-umich) at the University of Michigan.

Plain HTML + CSS, no build step. All links are relative, so the site works both as a
project page (`https://laubachb.github.io/lindseylab-site/`) and, once moved, as the org
page (`https://lindseylab-umich.github.io/`).

## Editing

- `index.html` — research overview and recent work
- `people.html` — PI bio and members (copy a `card member` block per person; photos go in `img/people/`)
- `publications.html` — selected publications
- `software.html` — ChIMES and related tools
- `css/style.css` — all styling (U-M blue/maize, automatic dark mode)

Preview locally with `python3 -m http.server` and open http://localhost:8000.

## Moving to the org

Transfer this repo to `LindseyLab-umich` (Settings → Transfer ownership), rename it to
`LindseyLab-umich.github.io`, and enable Pages from `main` / root.
