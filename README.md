# Megan · Human — personal portfolio

A single hand-written page (HTML, CSS and a little JavaScript, no framework and no build step).

## What's in here
| File | What it is |
|---|---|
| `index.html` | The whole site: styles at the top, page content in the middle, script at the bottom |
| `certs/` | Certificates (PDF) and the preview images (WebP) shown when someone clicks a certificate link |
| `favicon.svg` | The little lightbulb in the browser tab |
| `og.jpg` | The preview picture shown when the link is shared |

## How to see it on your computer
Open `index.html` in a browser. That's it.

## How it gets online
This repository is connected to Vercel. Every push to `main` redeploys the site automatically.

## Where to change things
- **Colours that change as you scroll:** search `var pal` in `index.html`; each line is one chapter (red, green, blue numbers).
- **Text:** search for the sentence you want to change and edit it in place.
- **Cord sensitivity:** search `dy > 56`; a smaller number means a shorter pull turns the light on.
- **The entrance plays again:** use "turn the lights off again" in the footer (it otherwise plays once per browser session).
