# Salitha Sadalinda — Portfolio

Personal portfolio and blog, hosted on [GitHub Pages](https://salithasadalinda.github.io/).

## Stack

- Plain semantic HTML5, CSS and vanilla JavaScript — zero build step, zero dependencies
- Mobile-first responsive layout with automatic dark/light mode (`prefers-color-scheme`)
- SEO: meta tags, Open Graph, JSON-LD structured data, `sitemap.xml`, `robots.txt`, custom `404.html`

## Structure

```
├── index.html          # Single-page portfolio
├── 404.html            # Custom 404 page
├── favicon.svg
├── robots.txt
├── sitemap.xml
└── assets/
    ├── css/style.css
    └── js/main.js
```

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Any push to `main` rebuilds the site automatically via GitHub Pages.

## License

Content and source © Salitha Sadalinda.
