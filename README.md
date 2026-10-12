# Websites I've Built — Sameer Saifi

Live: https://sameersaifi07.github.io/Website-I-ve-Built/

## Add a new website (the only step)

1. On GitHub, open this repository and click **Add file → Upload files**.
2. Drag in the **website's folder**. It must have an `index.html` directly inside it.
3. Click **Commit changes**.

That's all. In 1–2 minutes the gallery shows the new website as a card, newest first.
You do **not** need to change `index.html`, `sites.js` or any style.

## Optional extras

- **Thumbnail:** upload an image into the `thumbs` folder with the same name as the website folder,
  e.g. folder `my-site` → `thumbs/my-site.webp` (or `.jpg` / `.png`, 1200 × 750).
  Without one, the card shows the live website itself as its preview.
- **Name and categories:** add these lines inside the website's own `<head>`:

  ```html
  <meta name="gallery-title" content="My Site">
  <meta name="gallery-category" content="3D, Landing Page">
  ```

  Without them, the name comes from the page's `<title>` and the category is "Website".
- **Hide a folder** from the gallery: `<meta name="gallery-hide" content="true">` in its `<head>`.

## External websites (not in this repository)

Websites hosted elsewhere, such as the Shopify stores, are listed in `sites.js`.
Copy a block there, change the details, and upload `sites.js`.
