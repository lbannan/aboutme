# Personal website

A plain HTML and CSS site with five pages, hosted free on GitHub Pages.

## Put it online

1. Create a GitHub account if you do not have one.
2. Make a new public repository named `yourusername.github.io` (use your exact username).
3. Open the repository, choose Add file then Upload files, and drag in everything from this folder.
4. Go to Settings then Pages. Under Source pick Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. After a minute or two the site is live at `https://yourusername.github.io`.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page with photo and bio |
| `research.html` | Publications, theses and projects |
| `gis.html` | Story maps, embedded web maps and map images |
| `writing.html` | Poetry and essays |
| `events.html` | Talks and guest appearances |
| `style.css` | All the colours, fonts and layout |
| `images/` | Your photo goes here as `profile.jpg`, map images go in `images/maps/` |
| `maps/` | Optional folder for your own HTML web maps |

## Editing

Each page has comments marked `<!-- -->` showing which block to copy for a new entry. Edit files on github.com with the pencil icon and the site updates within a minute or two.

To change colours, edit the values at the top of `style.css`.

## Embedding maps

ArcGIS StoryMaps and web maps must be shared publicly (Everyone) or they will show a sign-in box to visitors. QGIS maps can be exported as HTML with the qgis2web plugin and placed in the `maps/` folder.
