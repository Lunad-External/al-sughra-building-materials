# Al Sughra Building Materials (ASBM) – Website

Static website for Al Sughra Building Materials Trading LLC, Sharjah, UAE.

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `asbm-website`).
2. Upload **all files and folders in this folder** to the root of the repository
   (keep the folder structure and the hidden files `.nojekyll` and `.image-slots.state.json`).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*,
   branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two the site is live at
   `https://<your-username>.github.io/<repository-name>/`.

To use your own domain (e.g. www.asbmuae.net), add it under **Settings → Pages → Custom domain**
and point the domain's DNS to GitHub Pages.

## Structure

- `index.html` – the whole site (Home, About, Products, categories, product pages, Gallery, Contact)
- `support.js`, `image-slot.js` – page runtime
- `vendor/` – React 18.3.1 (bundled so the site has no CDN dependency)
- `assets/` – logo, page images, category images, product photos and gallery photos

## Notes

- The contact and quote forms are not connected yet. To receive messages, link them to a form
  service (e.g. Formspree) or your email.
- The search bar is visual only.
