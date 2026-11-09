# Artemis Defense Group

Faction site for Artemis Defense Group (BRM5). Single-page static site, no build step.

## Files
- `index.html` - the whole site (HTML, CSS and JS in one file)
- `404.html` - page shown for broken links
- `.nojekyll` - tells GitHub Pages to serve files as-is

## Edit
- Discord invite: `DISCORD` near the bottom of `index.html`
- TAK links: `TAK` and `OVERLAY` near the bottom of `index.html`
- Colors and fonts: the `:root` block at the top of the `<style>`

## Preview locally
Open the folder in VS Code, install the Live Server extension, right-click `index.html` and choose "Open with Live Server".

## Publish (GitHub Pages)
1. Push this folder to a public GitHub repository.
2. Repo Settings > Pages > Deploy from a branch > `main` / `(root)` > Save.
3. The live link appears at the top of that page after a minute or two.

## Custom domain (optional)
Add a file named `CNAME` containing just your domain (for example `artemis.example.com`), or set it under Settings > Pages > Custom domain.
