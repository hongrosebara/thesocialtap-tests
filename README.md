# The Social Tap test pages

Static landing pages served at https://tests.thesocialtap.org via Netlify.
Every push to `main` deploys automatically.

## Layout
- `index.html`: list of projects (update when adding pages)
- `<client>/`: one folder per client; each page is `<client>/<page>.html`,
  served at `/<client>/<page>` (no `.html` needed)
- `_redirects`: Netlify redirects (old URLs → new)

## Adding a client
1. Create a folder, e.g. `new-client/`, with its pages, CSS and images.
2. Add a `<section class="project">` block to `index.html`.
3. Commit and push.

## Clients
- `sacred-earth/`: New Zealand Retreat 2027, Journey Into Stillness 2027
