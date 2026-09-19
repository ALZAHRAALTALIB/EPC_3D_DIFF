# Current-code update

This package was created from the latest `EPC_3D_DIFF.zip` supplied by the authors.
All current text, styling, justified paragraphs, images, and previous project edits
were retained except for the requested changes below.

## Changes
1. Reduced hero/header height:
   - smaller top/bottom padding
   - slightly smaller title
   - tighter author/affiliation spacing
   - slightly smaller action buttons

2. Updated the qualitative comparison:
   - fixed paired reference CT panel on the left
   - CBCT ↔ EPC-3D-Diff sCT interactive slider on the right
   - both panels are substantially smaller than the previous single large slider
   - responsive stacking on mobile

3. Reference CT asset
   - the current uploaded package did not contain a paired reference CT image
   - add it as `public/results/ct_237.png`
   - until it is added, a clearly labelled placeholder is shown instead of
     misrepresenting CBCT or sCT as ground-truth CT
