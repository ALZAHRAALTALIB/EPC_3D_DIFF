# Website changes (polished v2)

This revision further improves the EPC-3D-Diff project page with a more paper-like structure and a more polished research-style presentation.

## Main updates
- Reworked the top banner into a more polished hero section with:
  - a subtle medical-imaging inspired background,
  - a darker scientific gradient,
  - faint CBCT/sCT imagery in the background,
  - cleaner title, affiliations line, and action buttons.
- Replaced the methodology drawing with the uploaded paper figure from `fig1(1).pdf`.
- Removed the previous "Why this matters" style section.
- Reorganized the content to better follow the paper structure:
  1. Introduction
  2. Methodology
  3. Experiments and Results
  4. Conclusion
  5. Citation
- Added more structured subsection headings within Methodology and Experiments.
- Improved the layout and figure card styling for the methodology figure.
- Kept the interactive CBCT/sCT slider in the Results section.

## Added/updated files
- `public/figures/fig1_paper.png`
- `src/components/Header.astro`
- `src/paper.mdx`
- `src/styles/global.css`

## Comparison images
- `public/results/cbct_237.png`
- `public/results/synth_237.png`
