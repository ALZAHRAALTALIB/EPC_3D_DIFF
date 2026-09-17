# EPC-3D-Diff website update

This revision updates the project page to better match the EPC-3D-Diff paper and the MIART 2026 presentation.

## Main changes

- Corrected the full paper title to: **EPC-3D-Diff: Equivariant Physics Consistent Conditional 3D Latent Diffusion for CBCT to CT Synthesis**.
- Updated the author names to the paper's current author list.
- Removed per-author affiliation text; affiliations now appear together in a single institutional line beneath the author list.
- Added the MIART/MICCAI 2026 acceptance status.
- Added a **Code** button linking to `https://github.com/ALZAHRAALTALIB/EPC-3D-DIFF`.
- Added a **MIART 2026** button.
- Widened the main text area from 50rem to 68rem.
- Added soft scientific blue/indigo section backgrounds and a redesigned hero area.
- Styled the Abstract and Method sections as wider highlighted panels.
- Added an interactive **CBCT ↔ synthetic CT comparison slider** using the two supplied images.
- Added responsive/mobile styling for the new layout.

## Interactive comparison assets

The two images are stored in:

- `public/results/cbct_237.png`
- `public/results/synth_237.png`

The interactive React component is:

- `src/components/ImageComparison.tsx`

## Files added or modified

- `src/paper.mdx`
- `src/components/Header.astro`
- `src/components/HighlightedSection.astro`
- `src/components/SectionPanel.astro`
- `src/components/ImageComparison.tsx`
- `src/styles/global.css`
- `src/pages/index.astro`
- `public/results/cbct_237.png`
- `public/results/synth_237.png`

## Deployment

Use the same GitHub Pages deployment workflow that is currently used by the repository. The comparison images use relative URLs, so they remain compatible with deployment under the GitHub project path.

A local dependency installation/build could not be completed in the artifact environment because `npm ci` timed out. Before publishing, run locally or in GitHub Actions:

```bash
npm ci
npm run build
```

The project already declares `react-compare-slider`, React, Astro, and the React Astro integration in `package.json`.
