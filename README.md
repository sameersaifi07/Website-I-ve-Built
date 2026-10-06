# Websites I've Built — Sameer Saifi

A growing gallery of live websites designed and developed by **Sameer Saifi**, Shopify developer and website developer.

**Gallery:** https://sameersaifi07.github.io/Website-I-ve-Built/

Every card shows the real website **running live inside it** — animations, videos and all.
Scroll-animated sites scroll themselves slowly. Categories, counts and the search are built automatically.

## How to add a new website (3 steps)

1. **Upload the website** as its own folder, with an `index.html` inside, e.g. `my-new-site/index.html`.
   Skip this if the site is hosted somewhere else.
2. **Upload a preview image** into `thumbs/`, e.g. `thumbs/my-new-site.webp` (1200 × 750 works best).
   It shows while the live preview loads, and for visitors with data saver or reduced motion.
3. **Edit `sites.js`** on GitHub (click the file → pencil icon). Copy one `{ ... }` block,
   paste it at the top of the list and change the details:

```js
  {
    title: 'My New Site',
    url: 'my-new-site/',                 // or a full link like 'https://example.com'
    thumb: 'thumbs/my-new-site.webp',
    categories: ['Shopify', 'Fashion'],  // any categories you like
    added: '2026-10-20',
    scroll: true,                        // optional: auto-scroll the live preview
  },
```

Commit, wait a minute, and refresh. New categories appear in the tabs automatically.
Sites added in the last 3 weeks get a **New** badge.

### Live preview options
- Folders in this repository play **live** automatically.
- External links show the image only, because many sites block being shown inside another page.
  If an external site allows it, add `live: true`.
- To show only the image for a site, add `live: false`.

## Folder structure

```
index.html      ← the gallery page (no need to edit)
sites.js        ← the list of websites (edit this to add sites)
logo.svg        ← the logo in the header
thumbs/         ← preview images
planet-jumping/ ← each website in its own folder
india/
vex/
```

## Link to a category

Add `#` and the category name to the gallery link, e.g.
`https://sameersaifi07.github.io/Website-I-ve-Built/#3d`
