# Farshad Rahmani — personal website

Professional portfolio for computational mechanics research and solver development.

## Edit each section independently

| File | Content |
| --- | --- |
| `index.html` | Homepage introduction, research focus overview, and links to full pages |
| `about.html` | Biography, education, awards, skills, and CV |
| `research.html` | Research descriptions and mechanics comparison table |
| `publications.html` | All publication records, DOI links, and year filter |
| `projects.html` | Projects page; intentionally empty until entries are added |
| `contact.html` | Email and professional profiles |
| `styles.css` | Shared appearance and responsive layouts |
| `site.js` | Publication year filtering |
| `mechanics-hero.webp` | Homepage illustration |
| `favicon.svg` | Browser icon |

All navigation opens separate HTML pages. The site does not use the bundled review preview or a JavaScript page router. No build step is required.

## Update publications

Edit `publications.html` only. Duplicate an `<article class="publication" data-year="YYYY">` block and replace the title, authors, journal, year and DOI. If adding a new year, add an option in the year selector. Update the initial publication count in `#count`. The homepage links to this page and does not duplicate paper records.

## Add a project

Add entries inside the commented project area in `projects.html`. The homepage links to this page.

## Navigation and styling

Navigation is plain HTML repeated on each page. If renaming a page or navigation label, update the header links in all six pages. Shared design changes belong in `styles.css`.

## Preview locally

Run `python3 -m http.server 8000` from this directory and open `http://localhost:8000`.

## Content notes

- Publication details were preserved from the original website and still require checking against the latest Google Scholar record.
- The hero is an AI-generated illustration, visibly labeled as not research results.
- The two Iranian institution names are retained in HTML comments in `about.html`, as requested.
- The Projects page is intentionally empty.
