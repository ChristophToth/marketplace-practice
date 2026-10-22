# Marketplace practice

Unofficial offline practice tool for a CSULB MBA team. It is a single-file simulation of a carbon-fiber bike company, played Q1 through Q4. It is not affiliated with, endorsed by, or a product of Innovative Learning Solutions, Ernest Cadotte, or Marketplace Simulations.

This is its own site. It is not part of the christoth-ai brand site.

The page is class prep. `index.html` includes a `noindex` meta tag, `robots.txt` disallows crawling, and `vercel.json` sends `X-Robots-Tag: noindex`.

It is self-contained: inline CSS and JavaScript, system fonts, and `localStorage` for saves. Loading it does not request other assets. On a Mac the type resolves to San Francisco. On Windows it resolves to Segoe UI. A few source links inside the page point at public guides. Those are ordinary links, not required to play.

## Deploy

Import this repository into Vercel as a new project. Do not add it to the christoth-ai project. The repository root is the site. Vercel serves `index.html` at `/`.

## Update

Replace `index.html` with the new single-file HTML and keep the `<meta name="robots" content="noindex">` tag. Keep inline CSS and JavaScript, with no external stylesheets, scripts, fonts, or images. Do not commit ILS Help File text, course decks, or PDFs.
