# georgephotos.org (staticsite1)

> A visually elegant and static photography site showcasing George’s work, designed for ease of use and aesthetic appeal.

---

##  Overview

**georgephotos.org** is a fully static photography gallery built using plain HTML, CSS, and optimized assets. It serves as a beautiful, fast-loading platform for showcasing photographic content without the need for backend services or complicated build tools.

---

##  Project Structure

staticsite1/
├── index.html
├── logo.png (and variants: logo-400, logo-800, logo-1200)
├── apple-touch-icon.png
├── favicon.svg, favicon.ico, favicon-96x96.png
├── site.webmanifest
├── web-app-manifest-192x192.png, web-app-manifest-512x512.png
├── (other assets as needed)
└── README.md ← (this file)

- **index.html** – The main landing page of your site.
- **logo-*.png** – Scaled logo files for various resolutions (400px, 800px, 1200px).
- **Favicon and icons** – Files to ensure consistency across browsers and devices.
- **site.webmanifest & web-app-manifest-*.png** – Support PWA features (installability, icons on home screens, etc.).

---

##  Features

- **Purely Static** – No dependencies or backend; easy to deploy anywhere (e.g., GitHub Pages, Netlify, Vercel).
- **Multiple Icon Sizes** – Ensures crisp visuals across devices and use cases.
- **PWA-Ready** – Includes manifest and icons to allow optional installation as an app.
- **Minimal & Fast** – Lightweight and optimized for speed.
- **Easy to Customize** – Tweak visuals, layout, and content to reflect your style.

---

##  Usage & Deployment

### Local Preview
Simply open `index.html` in your browser to see your portfolio in action.

### Deploying to GitHub Pages
1. Verify you're on the `main` branch.
2. Enable GitHub Pages in repository settings, choosing `main` (or `/docs`) as the source.
3. Visit `https://<username>.github.io/<repo>/`—or if you've set up a custom domain like georgephotos.org, update DNS and configure the domain there.

---

##  Customization Ideas

- **Content Updates** – Add more photos, change titles/descriptions directly in `index.html`.
- **Styling Tweaks** – Customize fonts, colors, or layout using inline or external CSS.
- **Add PWA Capabilities** – Include a service worker for offline support, leveraging existing manifest and icon files.

---

##  Credits

- **Repository**: N0v4ont0p/staticsite1 on GitHub :contentReference[oaicite:0]{index=0}.
- **Language**: Simple, clean static site built entirely with HTML.

---

##  License
MIT License
—or mark as proprietary if it’s for personal use only.

---

##  Summary

This static site is designed to showcase your photography—you just drop images and tweak the HTML/CSS. Deployment is as simple as pushing to GitHub and enabling Pages.

Let me know if you'd like help refining visuals, adding features like lightboxes, or setting up live deployment workflows!
::contentReference[oaicite:1]{index=1}
