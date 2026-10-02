# Website Template 5

A responsive, multi-page HTML/CSS website template — template #5 in the LadeStack website-template series. Built with Bootstrap, custom CSS, and FontAwesome icon webfonts. Zero build step required: serve the folder statically and it's live.

## ✨ Features

- 5 ready-to-customize pages: Home, About Us, Services, Our Gallery, Contact Us
- Bootstrap-grid layout for responsive behaviour on mobile, tablet, and desktop
- Modular CSS split: `default.css` (theme) + `custom.css` (overrides) + `combined.min.css` (production)
- Icon set: full FontAwesome webfont (`.eot`, `.svg`, `.ttf`, `.woff`, `.woff2`) + `.otf`
- `bootstrap.min.js` for off-the-shelf interactive components
- `wow.js` scroll-reveal animation helper
- SEO-friendly `sitemap.xml` included
- `index.html` entry page (redirects to `home.html`) so static hosts serve the site from `/`
- No build pipeline, no bundler — any static server works

## 📄 Pages included

| Page | File |
|------|------|
| Home | `home.html` |
| About Us | `about-us.html` |
| Services | `services.html` |
| Our Gallery | `our-gallery.html` |
| Contact Us | `contact-us.html` |

## 🛠️ Tech stack

- HTML5
- CSS3 (`css/default.css`, `css/custom.css`, `css/combined.min.css`)
- Bootstrap 3 grid + `js/bootstrap.min.js`
- FontAwesome icon webfont (self-hosted in `fonts/`)
- `js/wow.js` scroll animations

## 🚀 Getting started

```bash
# any static server — pick one:
python3 -m http.server 8080
# or
npx http-server -p 8080
```

Then open <http://localhost:8080/> — the entry page loads the Home page.

## 📁 Project structure

```
.
├── index.html          # entry page -> loads home.html
├── home.html
├── about-us.html
├── contact-us.html
├── services.html
├── our-gallery.html
├── css/
│   ├── default.css
│   ├── custom.css
│   └── combined.min.css
├── js/
│   ├── bootstrap.min.js
│   └── wow.js
├── fonts/              # FontAwesome webfont files
└── sitemap.xml
```

## 🎨 Customization

1. Replace placeholder text inside each HTML file directly.
2. Tweak theme colours in `css/default.css` — variables are at the top.
3. Add per-section overrides in `css/custom.css`.

## 🌐 Deploy

Static hosting only — no server required:

- **GitHub Pages**: Settings → Pages → deploy from branch `/` (root). Live at `https://<owner>.github.io/Website-template-5/`
- **Cloudflare Pages / Netlify**: point the build output at the repo root; no build command needed.

## 📜 License

Released for personal and commercial use. Attribution appreciated but not required.

---

Built by Girish Lade — [https://ladestack.in](https://ladestack.in)

Part of the **Website-template** series — explore templates 1–7 for layout alternatives.
