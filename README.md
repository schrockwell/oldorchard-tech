# Old Orchard Tech

One-page static site for [oldorchard.tech](https://oldorchard.tech). No build step, no JavaScript, no dependencies.

- `index.html` – the whole site. Text, links, and styles all live here.
- `assets/images/` – logo, favicon, share image, and the "Recent Work" gallery photos (`name.jpg` is the thumbnail, `name-full.jpg` is what opens when clicked).

## Preview locally

```sh
bin/dev
```

Then open <http://localhost:8000>.

## Deploy

Upload the folder as-is to any static host (Cloudflare Pages, Netlify, GitHub Pages, S3, etc.).
