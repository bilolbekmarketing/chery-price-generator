# Chery Price Generator

Static Chery dealer price-list generator for Netlify.

## Deploy Model

Use one GitHub repository connected to one Netlify site.

After the first Netlify setup, the production URL stays the same. Future updates are:

```bash
git add .
git commit -m "Update generator"
git push
```

Netlify will rebuild and publish the same site URL automatically.

## Netlify Settings

- Build command: leave empty
- Publish directory: `.`
- Production branch: `main`

