# nerf-war-operator-select

The operator selection page for a private party. One file: `index.html`.

This repository holds only the page that gets served, because GitHub Pages
needs a public repository. The project source, the Apps Script backend and the
setup notes live in a separate private repository.

## Publishing an update

Replace `index.html`, commit, and push. The live URL never changes.

```bash
git add index.html && git commit -m "Update the board" && git push
```

GitHub Pages rebuilds in a minute or two.
