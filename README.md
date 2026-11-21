# Rezki — Security Researcher

Personal portfolio of **Rezki** — security researcher & bug bounty hunter (Jakarta, ID).

Single self-contained `index.html`. No build step, no dependencies, no external
requests: hand-written CSS, vanilla JS, zero network calls at runtime.

## Deploy

Static site — any host works. Deployed on Vercel (team **Rezki's projects**, project `rezki-portfolio`):

- Live URL: **https://rezki-portfolio.vercel.app**
- Vercel API: `POST /v13/deployments` with `files:[{file:"/index.html", data:<raw>}]` and `projectSettings:{outputDirectory:"."}` (raw text, NOT base64)

## Contents

- `index.html` — the entire site (markup, styles, script)

QA screenshots are kept out of version control (see `.gitignore`).
