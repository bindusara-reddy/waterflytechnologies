# waterflytechnologies.com

Experimental website for **Waterfly Technologies** — an IIT Madras incubated startup building Wing-In-Ground (WIG) craft for high-speed, low-cost marine transportation.

> *As Fast as a Plane, As Cheap as a Ship*

Content is drawn from [waterfly.info](https://waterfly.info). This repo is a sandbox for experimenting with the `waterflytechnologies.com` domain.

## Structure

- `index.html` — the whole site: a single self-contained page (inline CSS/JS, hand-drawn SVG artwork, no build step, no dependencies)
- `404.html` — on-brand not-found page

## Local preview

No tooling needed — just open `index.html` in a browser, or:

```sh
python -m http.server 8000
```

## Deployment

**Production — Vercel.** `waterflytechnologies.com` uses Vercel nameservers, so the domain is served by importing this repo as a Vercel project (no build command, root output) and attaching the domain in the project's Domains tab. Every push to `main` auto-deploys. `404.html` at the root doubles as Vercel's custom not-found page.

**Preview mirror — GitHub Pages.** The same branch is also published at <https://bindusara-reddy.github.io/waterflytechnologies/> (no custom domain, no redirect) as a zero-setup staging mirror.

## Contact

Waterfly Technologies — fly@waterfly.blue · [LinkedIn](https://www.linkedin.com/company/waterfly)
