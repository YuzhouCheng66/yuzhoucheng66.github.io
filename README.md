# Yuzhou Cheng — Academic Homepage

A compact, single-page academic website that follows the classic Jon Barron
computer-vision homepage structure: an 800 px table layout, 14 px Lato type,
160 × 160 publication media, and hover-to-video previews. It is plain HTML and
CSS, with no build step.

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

## Portrait

The square web-optimized portrait is stored at `assets/yuzhou-cheng.jpg` and
displayed with a circular mask by `styles.css`.
