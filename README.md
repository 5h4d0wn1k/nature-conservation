# Nature Conservation Awareness Website

[![last commit](https://img.shields.io/github/last-commit/5h4d0wn1k/nature-conservation)](https://github.com/5h4d0wn1k/nature-conservation)

A responsive nature conservation awareness website built with HTML, CSS, and
Bootstrap — environmental education, tree planting, and eco-friendly resources
served live from GitHub Pages at `nature.shadownik.online`.

## Why

Most conservation messaging struggles to reach people where they already
browse. This project is a fast, static, mobile-first awareness site designed to
educate visitors about protecting nature and to make participation easy (forms,
thank-you flow, and contact paths). Because it is plain HTML/CSS, it loads
quickly, costs nothing to host, and stays accessible — the right tool for a
community education page.

## Features

- **Responsive landing page** (`index.html`) — Bootstrap-based layout with
  content sections, jarallax visual blocks, and an SEO-friendly meta
  description targeting "nature conservation" and "environment".
- **Thank-you flow** (`thankyou.html`) — post-submission confirmation page for
  forms.
- **Resources & contact page** (`ads.html`) — additional contact and outreach
  content.
- **Language support** — embedded Google Translate widget for multilingual
  readers.
- **Consent & notifications** — cookie directive and notification handling
  built into the page.
- **GitHub Pages + custom domain** — deployed via the `CNAME`
  (`nature.shadownik.online`) with a security policy (`SECURITY.md`) and
  automated dependency updates (`dependabot.yml`).

## Quickstart

No build step — it is static HTML.

### Open locally

Open `index.html` in any browser, or serve the directory with any static
server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

### Deploy to GitHub Pages

Push to `main` and point the Pages custom domain to the `CNAME` value
(`nature.shadownik.online`), or add your own `CNAME` with your domain.

## Project structure

```
index.html                        Main landing page
thankyou.html                     Form thank-you confirmation
ads.html                          Contact / outreach content
Nature Conservation Website_files/  Static assets (CSS, JS, images)
CNAME                             Custom domain for GitHub Pages
SECURITY.md                       Security policy
```

## Contributing

Content and styling contributions for environmental education are welcome.
Keep the site static and dependency-light.

## License

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

