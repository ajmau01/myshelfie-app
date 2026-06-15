# myshelfie-app

Landing page, user guide, and privacy policy for **myShelfie** — the personal library for the way you actually read.

Static site served via **GitHub Pages** from `/docs` on `main`.

- **Live:** https://ajmau01.github.io/myshelfie-app/
- **Guide:** https://ajmau01.github.io/myshelfie-app/guide.html
- **Privacy:** https://ajmau01.github.io/myshelfie-app/privacy.html

## Structure
```
docs/
  index.html      — landing page + tester recruitment
  guide.html      — starter user guide (evolving)
  privacy.html    — privacy policy (canonical URL for App Store / Play)
  assets/icon.png — app icon
```

No build step — plain HTML/CSS, MCM design system (Playfair Display + DM Sans; cream/charcoal/terracotta/mustard/olive; zero border-radius; hard-offset shadows). Edit the files directly; GitHub Pages redeploys on push to `main`.

The myShelfie app itself lives in a separate private repo.
