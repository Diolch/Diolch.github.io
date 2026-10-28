# github_homepage

Source for my personal homepage at https://diolch.github.io/

## Preview locally

No build step, no dependencies. Open the file directly:

```
index.html
```

Double-click it, or drag it into a browser. Everything required to render the
page is in this folder.

If you prefer to serve it over HTTP instead of opening the file directly:

```
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Dependencies

None. Plain HTML and CSS in a single file, with inline styles. No JavaScript,
no frameworks, no package manager, so there is no manifest or lockfile.

## Files

```
index.html    the entire site - markup, styles and content
README.md     this file
```

## Deployment

The live site is published with GitHub Pages from the `main` branch of the
repository `Diolch/Diolch.github.io`, at the repository root. GitHub Pages
serves `index.html` automatically, so no build or CI configuration is needed.
