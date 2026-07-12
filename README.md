# waterflytechnologies.com

Experimental website for **Waterfly Technologies** — an IIT Madras incubated startup building Wing-In-Ground (WIG) craft for high-speed, low-cost marine transportation.

> *As Fast as a Plane, As Cheap as a Ship*

Content is drawn from [waterfly.info](https://waterfly.info). This repo is a sandbox for experimenting with the `waterflytechnologies.com` domain.

## Structure

- `index.html` — the whole site: a single self-contained page (inline CSS/JS, hand-drawn SVG artwork, no build step, no dependencies)
- `404.html` — on-brand not-found page
- `CNAME` — custom domain for GitHub Pages

## Local preview

No tooling needed — just open `index.html` in a browser, or:

```sh
python -m http.server 8000
```

## Deployment

Served by **GitHub Pages** from the `main` branch root. Pushing to `main` deploys automatically.

To point `waterflytechnologies.com` at it, set these DNS records at the domain registrar:

| Type  | Host | Value                   |
|-------|------|-------------------------|
| A     | @    | 185.199.108.153         |
| A     | @    | 185.199.109.153         |
| A     | @    | 185.199.110.153         |
| A     | @    | 185.199.111.153         |
| CNAME | www  | bindusara-reddy.github.io |

Until DNS is set, the site is reachable at <https://bindusara-reddy.github.io/waterflytechnologies/>.

## Contact

Waterfly Technologies — fly@waterfly.blue · [LinkedIn](https://www.linkedin.com/company/waterfly)
