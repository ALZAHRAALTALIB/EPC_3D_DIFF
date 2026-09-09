# EPC-3D-Diff — Easy Editing Guide

## The only files you normally edit

### 1. `src/paper.mdx`
This contains the title, authors, affiliations, text, equations, results,
and optional media.

### 2. `src/assets/paper/`
Replace the placeholder images with your real paper figures using the same
filenames.

## Useful commands

```bash
npm install
npm run dev
```

Then open the local Astro URL shown by the terminal.

For a production check:

```bash
npm run build
```

## Optional features

The page already supports the original template components:

- LaTeX / KaTeX
- code blocks
- comparison sliders
- carousels
- tabs
- YouTube
- video
- interactive GLB/3D models

The new helper components make the most common research-page operations
simpler.

## Reusing this for another paper

Copy the project, replace `src/paper.mdx`, replace the files in
`src/assets/paper/`, and leave the reusable components alone.
