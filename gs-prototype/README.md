# Great Sword Weapon Tree — WordPress iframe prototype

This is a **standalone static prototype**. All weapon names, statistics, upgrade relationships, and crafting materials are illustrative placeholders. Do not present them as verified Monster Hunter Portable 3rd game data.

## Preview locally

Open `index.html` in a browser. There are no dependencies, build steps, PHP, plugins, or API requests.

## Publish on GitHub Pages

1. Create a public GitHub repository and upload `index.html`, `style.css`, and `app.js` to its root.
2. Under **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
3. Once GitHub Pages finishes deploying, open `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.
4. In WordPress, add a **Custom HTML** block to a page and paste the iframe below, replacing the URL.

```html
<iframe
  src="https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/"
  title="Monster Hunter Portable 3rd Great Sword Weapon Tree"
  loading="lazy"
  width="100%"
  height="870"
  style="display:block;width:100%;border:0;max-width:100%;"
></iframe>
```

The 870px height is a starting point, not automatic resizing. On narrow screens or with the details expanded, you may need to adjust it. This iframe runs independently of WordPress PHP.

## Files

- `index.html` — accessible interface structure
- `style.css` — light, WordPress-friendly responsive design
- `app.js` — illustrative weapon data, branching connectors, search, and selection

## Next iteration

Move data into a separate JSON file once the schema is settled, validate actual MHP3rd weapon values, add more branches, and improve iframe height handling if needed. Keep all game data verified before public release.
