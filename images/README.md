# Photos

Drop photos into this folder using these exact filenames and they will show up on the site automatically. No code changes needed. Until a file exists, the site shows a styled "Photo coming soon" placeholder in its place.

| Filename        | Where it appears                        | Suggested shape        |
|-----------------|-----------------------------------------|------------------------|
| `hero.jpg`      | Full-screen banner at the top           | Wide landscape (e.g. 2400×1400) |
| `farm.jpg`      | "The Farm" section                      | Portrait (4:5)         |
| `gallery-1.jpg` … `gallery-6.jpg` | Gallery grid          | Landscape (4:3)        |

Tips:
- Keep each file under about 500 KB so the page loads quickly (resize to ~2000 px wide for the hero, ~1200 px for the rest).
- Filenames are case-sensitive on GitHub Pages: use `hero.jpg`, not `Hero.JPG`.
- To use a different file type (e.g. `.png` or `.webp`), change the matching `data-photo="images/..."` value in `index.html`.
