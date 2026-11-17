# Chloe Hung · Portfolio

A UX/UI portfolio set up as a personal digital archive: glossy jelly objects lead to three case studies (Missing Wealth, St. Joseph's Life Care Centre, DFO), a personal collection (music, photography, Japan, the cat) and a one-page resume.

It is a single static file, `index.html`, with no build step.

## Run locally

Open `index.html` in a browser.

## Edit content

All text lives in the `DATA` object near the top of the `<script>` in `index.html`. Items marked `sample: true` show a small "sample" tag until you replace them.

- Photos: add `src: "images/your-photo.jpg"` to an entry in `DATA.photos`.
- Resume PDF: add the file to the repo and set `resumeUrl: "resume.pdf"`.

## Publish with GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`.
