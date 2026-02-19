# metar

Airport weather (METAR) mini-site.

This repository contains a set of static HTML pages for viewing airport weather information. The main entry point is `index.html`, and there are several alternative/iterative versions of the airport page included for comparison/testing.

## Live site (GitHub Pages)

If GitHub Pages is enabled for this repo, the site will be available at:

- https://mishagl.github.io/metar/

(Or check **Settings → Pages** in the repo to see the exact URL and which branch/folder is being served.)

## Project structure

- `index.html` — main page / current version
- `airport.html` — airport page (version/variant)
- `airport2.html` — airport page (version/variant)
- `airport3.html` — airport page (version/variant)
- `airport4.html` — airport page (version/variant)
- `airport4.1.html` — airport page (version/variant)
- `airport4.2.html` — airport page (version/variant)

## How to run locally

Because this is a static site, you can open the HTML files directly, but using a small local web server is recommended.

### Option A: Python (quick)

```bash
python3 -m http.server 8000
