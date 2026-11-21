# DuoFramer Website

**Every photo has a story. Frame it.**

<img src="assets/icon.png" alt="DuoFramer app icon" width="128" height="128">

DuoFramer is a free iPhone app that reads the camera, settings, date and place from your photos and frames them: 55 camera, film, location, weather, holiday and iPhone Duo templates. It frames many photos at once with on-device smart cropping, turns collections into social media carousels, and on iPhone Duo plays your frames as a photo frame in tent mode.

This repository holds the DuoFramer landing page, privacy policy and support page.

## About this site

The site is three static pages that share one stylesheet. It has no build step and makes no requests to other sites. Light and dark mode follow the system.

- **Preview:** open `index.html` in a browser.
- **Publish:** GitHub Pages serves the repository root from `main`.

| Path | Contents |
| --- | --- |
| `index.html` | The landing page. |
| `privacy.html` | The privacy policy. |
| `support.html` | Frequently asked questions and how to get in touch. |
| `assets/site.css` | Styles shared by every page. |
| `assets/gallery/` | Frames rendered by the app's own templates from its sample photos. |
| `assets/icon.png` | App icon, 512 px. |
| `assets/og-image.png` | Social sharing preview, 1200 × 630 px. |
| `assets/apple-touch-icon.png` | Home Screen icon for the site, 180 px. |
| `assets/favicon.ico` | Browser tab icon, 16, 32 and 48 px. |
| `assets/favicon-192.png` | Browser tab icon for high-resolution displays, 192 px. |
| `assets/favicon.png` | The icon in the navigation bar, 64 px. |

When the app is live, replace the "Coming soon to the App Store" button in `index.html` with the App Store badge and link, and add `<meta name="apple-itunes-app" content="app-id=…">` to the page head.

iPhone and iPhone Duo are trademarks of Apple Inc.
