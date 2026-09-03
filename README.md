# christophorusalfa

Personal portfolio site for Christophorus Alfa — a virtual assistant offering
data management and administrative support.

## Stack

A single self-contained static page: `index.html`. All CSS and JavaScript are
inline, the favicon is an inline SVG data URI, and the only external
dependencies are Google Fonts. There is no build step and no framework.

## Local preview

Open `index.html` directly in a browser, or serve it:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Deployed on Vercel as a zero-config static site: Vercel serves `index.html`
at `/` with no build command or output directory to configure. Pushing to
`main` triggers a production deploy.

## Follow-ups

- Add `og:url`, `og:image`, and a canonical link tag to `index.html` once the
  final production domain is known (see the TODO comment in the file's
  `<head>`).
