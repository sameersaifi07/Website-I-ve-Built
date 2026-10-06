# Sameer Saifi — Website Showcase

Websites designed and developed by **Sameer Saifi**, Shopify developer and website developer.

Open the live showcase and click through each project one by one.

## Projects

| Project | Folder | Built with |
|---|---|---|
| **Shopify Developer Portfolio** — blue & white portfolio with services, projects and contact form | [`portfolio-light/`](portfolio-light/) | HTML, CSS, JavaScript |
| **Dark Motion Portfolio** — scroll marquee, text reveal, stacking project cards | [`portfolio-dark/`](portfolio-dark/) | React, TypeScript, Tailwind CSS, Framer Motion |
| **India — Parallax Hero** — cinematic scroll story through Ladakh, India | [`india/`](india/) | HTML, CSS, vanilla JavaScript |
| **VEX — Video Hero** — full-screen video, liquid-glass navigation, letter-by-letter headline | [`vex/`](vex/) | React, TypeScript, Tailwind CSS |
| **Planet Jumping** — space portal with a video preloader and canvas 3D window | [`planet-jumping/`](planet-jumping/) | HTML, CSS, vanilla JavaScript, Canvas |

React source code: the dark portfolio is in [`source/portfolio-dark-react/`](source/portfolio-dark-react/) (built into `portfolio-dark/`), and VEX is in [`source/vex-hero/`](source/vex-hero/) (built into `vex/`).

## Publish with GitHub Pages

1. Upload everything in this folder to a GitHub repository (keep the folder structure).
2. Go to **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then click **Save**.
4. After a minute or two the showcase is live at `https://<your-username>.github.io/<repository-name>/`.

Each project then has its own link:

- `…/portfolio-light/`
- `…/portfolio-dark/`
- `…/india/`
- `…/vex/`
- `…/planet-jumping/`

## Run the React source locally

```bash
cd source/portfolio-dark-react
npm install
npm run dev
```
