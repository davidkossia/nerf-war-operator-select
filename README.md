# nerf-war-operator-select

The operator selection page for a private party: `index.html` and the `img/`
folder of operator portraits and badges that goes with it.

This repository holds only the page that gets served, because GitHub Pages
needs a public repository. The project source, the Apps Script backend and the
setup notes live in a separate private repository.

## Publishing an update

Replace `index.html` and `img/`, commit, and push. The live URL never changes.
The page works without `img/` but every operator loses their artwork, so copy
both every time.

```bash
git add index.html && git commit -m "Update the board" && git push
```

GitHub Pages rebuilds in a minute or two.
