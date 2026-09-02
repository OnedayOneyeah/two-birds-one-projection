# Two Birds, One Projection

Project page for *"Two Birds, One Projection: Harmonizing Safety and Utility in LVLMs via Inference-time Feature Projection"* ([arXiv:2603.14825](https://arxiv.org/abs/2603.14825)).

Live at: https://OnedayOneyeah.github.io/two-birds-one-projection/

## Editing

Everything is plain HTML/CSS, no build step needed.

- Content: [index.html](index.html)
- Styling: [static/css/style.css](static/css/style.css)
- Images: drop files into `static/images/` and reference them from `index.html`

## TODO before sharing widely

- [ ] Add a teaser figure (`static/images/teaser.png`) and replace the placeholder in the "teaser" section
- [ ] Add a method diagram and fill in the Method section text
- [ ] Add a results table/figure and fill in the Results section text
- [ ] Add the code link once the repository is public
- [ ] Double check author links (currently placeholder `#` hrefs)

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.

## Deployment

Plain GitHub Pages, no Actions build needed. Push to `main`, then in **Settings → Pages** set Source to "Deploy from a branch" → `main` / `/(root)`.
