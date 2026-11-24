# Garden Hill Farm

Website for Garden Hill Farm, a family farm (and former peach farm) in Lyman, South Carolina, and the home of [Magnolia Equine Veterinary Services](https://magnoliaequinevet.com).

It's a plain static site (HTML, CSS, a little JavaScript) with no build step, so it runs on GitHub Pages as-is.

## Files

```
index.html          The page
assets/styles.css   Styling
assets/main.js      Mobile menu and header
assets/logo.svg     Logo (also used as favicon.svg)
images/             Put photos here (see images/README.md)
.nojekyll           Tells GitHub Pages to serve files as-is
```

## To do

Search `index.html` for `TODO`:

- Add family history to the "Our Story" section (when the family came to the farm, etc.)

Vet details (Dr. Govan, services, phone, email) come from magnoliaequinevet.com. If they change there, update them here too.

## Adding photos

See [images/README.md](images/README.md). It lists the published photos and how to swap or add one.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `garden-hill-farm`).
2. From this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/garden-hill-farm.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. The site will be live at `https://<your-username>.github.io/garden-hill-farm/` within a minute or two.

### Custom domain (optional)

To use a domain like `gardenhillfarm.com`, add it under **Settings → Pages → Custom domain** and point your DNS at GitHub Pages ([instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).
