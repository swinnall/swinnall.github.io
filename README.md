# Biology will underpin the next generation of hardware

Investment thesis page for Samuel Winnall, PhD (Future Planet Capital, UKI2S).

A single self-contained `index.html`: no build step and no dependencies apart from the Inter Tight font from Google Fonts.

## Publish with GitHub Pages

1. Put `index.html` at the root of a public repository named `<your-username>.github.io`.
2. Go to **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
3. The site goes live at `https://<your-username>.github.io` within a minute or two.

To use a custom domain, add it under **Settings → Pages → Custom domain**, create the DNS records GitHub lists, then tick **Enforce HTTPS**.

## Editing

- **Graph nodes:** the `leaves` array in the script at the bottom of the file. Each entry is `[branch, label, x, y]`, where x and y are percentages of the graph's width.
- **"Why now?" lines:** the `lines` array in the same script.
- **Path stages and brackets:** plain HTML inside `<section id="path">`.
