# Yuzhou Cheng — Academic Homepage

A compact, single-page academic website inspired by Jon Barron's homepage. It is plain HTML and CSS, with no build step or external dependencies.

## Preview locally

From this directory, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

The MLP Splatting and LoGS preview videos are stored locally under `assets/`,
along with poster frames extracted from those videos. The belief propagation
preview is cropped from Figure 1 of the paper. The page does not depend on
cross-site media loading.

See `MEDIA_FILES.txt` for the exact media filenames included in this package.

## Publish with GitHub Pages

1. Create a public repository named `YuzhouCheng66.github.io`.
2. Copy the contents of this directory to the repository root.
3. Push to the repository's default branch.
4. In **Settings → Pages**, select **Deploy from a branch**, then choose the default branch and `/ (root)`.

The site will be available at `https://yuzhoucheng66.github.io/`.

## Replace the portrait

Replace `assets/avatar-placeholder.svg` with a portrait image and update the `src` in `index.html`. A roughly 4:5 portrait crop works best.
