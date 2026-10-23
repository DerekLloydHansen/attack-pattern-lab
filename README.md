# Attack Pattern Lab

Interactive, step-through demos of common attack patterns from the [CAPEC](https://capec.mitre.org/) catalog (SQL injection, phishing, brute force, XSS, MITM, clickjacking, and more). Built for CYBER 266. Every demo is a conceptual walkthrough; none contains a working exploit.

## Run locally

It's a single static page with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Works as-is on GitHub Pages (Settings → Pages → deploy from `main`, root folder), Netlify, or any static host.

Progress ("explored" cards) is saved in the browser's `localStorage`.
