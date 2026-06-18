# Ratchet

**The Body Fights Back** — a data essay on weight, willpower, and biology.

A single self-contained HTML page (inline CSS, hand-built SVG charts, no build step,
no dependencies beyond Google Fonts loaded at runtime).

## Local preview
Just open `index.html` in a browser, or serve it:

    python3 -m http.server 8080
    # then visit http://localhost:8080

## Deploy
Static site hosted on Cloudflare Pages at https://ratchet.doyled-it.com

There is no build command and no build output directory to configure — the repo root
*is* the site. The optional `_headers` file adds a few baseline security headers
(Cloudflare Pages reads it automatically).

## Sources
All research citations are listed at the bottom of the page (DIETFITS, POUNDS LOST,
Hall et al. on ultra-processed food, Fothergill et al. on metabolic adaptation,
Sumithran et al. on hunger hormones, Spalding et al. on fat-cell number, the STEP and
SURMOUNT GLP-1 trials, and set-point literature).
