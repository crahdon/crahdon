# crahdon.github.io

Personal engineering portfolio for Charlie Rahdon — mechanical engineering student at Harvard University.

Live at: https://crahdon.github.io

## Structure

```
.
├── index.html              Homepage — hero, about, project grid, contact
├── css/
│   └── style.css           Site-wide styling
├── projects/
│   ├── pressure-vessel-fabrication.html
│   ├── turf-wars-robot.html
│   └── electro-pneumatic-organ.html
└── images/
    └── <project-name>/web/ Resized JPGs used on each project page
```

## Tech

Plain HTML/CSS, no build step or framework. Deployed via GitHub Pages directly from this repo.

## Local preview

Open `index.html` in a browser, or serve the folder locally:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Adding a project

1. Add resized images under `images/<project-name>/web/`.
2. Copy an existing file in `projects/` as a template for the new page.
3. Link the new page from the project grid in `index.html`.
