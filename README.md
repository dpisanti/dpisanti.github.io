# dpisanti.github.io

Personal website of Dario Pisanti, built with [Hugo](https://gohugo.io/) and the [Blowfish](https://blowfish.page/) theme and deployed to GitHub Pages by `.github/workflows/hugo.yml` on every push to `main`.

## How to update

- **Add a publication:** copy an entry in `data/publications.yaml` and edit it. Put a 640x400 thumbnail in `assets/img/pubs/`. Set `selected: true` to also show it on the home page.
- **Edit the home page bio:** `content/_index.md`.
- **Add a project:** create `content/projects/<name>/index.md`, with an optional `featured.jpg` in the same folder.
- **Profile photo:** replace `assets/img/profile.jpg` (square).
- **CV PDF:** replace `static/cv/Pisanti_CV.pdf` (keep the file name so the link never changes).
- **Links in the header:** `config/_default/languages.en.toml`.

The Geo-LoFTR project page lives in its own repository and is served at `/geo-loftr/`.
