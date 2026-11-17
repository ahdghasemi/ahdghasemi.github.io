# Website revisions — 17 November 2026

This branch preserves portable source and assets for the Google Sites V2 research showcase. It does not deploy or replace the existing GitHub Pages site.

## Versions

- **V1 Preserved Baseline — 2026-11-17:** the complete original Google Sites draft remains separate. The `v1/` directory records the original paper viewer and introduction; it is not a complete Google Sites export.
- **V2 Research Showcase — 2026-11-17:** separate draft with a shorter introduction, the five-paper viewer immediately after the introduction and before the evidence cards, updated research headings, and prepared carousel assets.

The current Google Sites native layout remains maintained in Google Sites. These files are a source checkpoint, not automatic two-way synchronization.

## Paper viewer

`v2/paper-viewer.html` is self-contained HTML/CSS/JavaScript for Google Sites Embed code or later use in GitHub Pages. It includes Tiny Flow Matching, CGES, the ICLR 2026 GNN sample-complexity paper, Ergodic Trajectory Design, and Tiny Graph Neural Networks. Controls support scrolling, previous/next buttons, optional autoplay, keyboard arrows, and reduced-motion preferences. Tiny Flow Matching uses a paper-request link because a verified public full-text URL was not available.

Keep the Google Sites iframe in a portrait proportion (approximately 420 × 600 in the editor). The embed's height scales on mobile; making it very wide and short can truncate the content.

## Image provenance

- `graph-foundations.png`, `efficient-reasoning.png`, `generative-autonomy.png`, and `compact-wireless.png`: explanatory diagrams adapted from the existing viewer. They are labeled concept illustrations, not experimental observations.
- `tiny-flow-milano.png`: a visual redraw of Table 1 from the supplied *Tiny Flow Matching: Constrained Low-Rank OT-CFM for Deployable Ergodic UAV Coverage* manuscript, headed IEEE MLSP 2026. Error bars are standard deviations over ten seeds. Selected-layer parameter ratios must not be described as whole-model parameter ratios.
- `tiny-flow-original-rank-sweep.png`: original Figure 1 asset from that manuscript's source archive.
- `tiny-flow-cross-dataset.png`: original Figure 2 rendered from its vector PDF. Milano uses ten seeds; other datasets use three.

For Milano rank 4: retained dense-model coverage correlation 99.45%; selected-layer parameter ratio 3.77%; FP32 size 0.7588 → 0.0323 MB; MACs per velocity evaluation 197,888 → 7,437. Arithmetic reductions do not imply equal latency reductions. The manuscript reports more modest end-to-end latency improvements.

## Pending content reconciliation

The newly mentioned CV was not available as an attachment or among the accessible source files. No claim is made that V2 has been reconciled against that new CV. Teaching remains 258 UMass + 77 Florida Polytechnic course enrollments (335), separately from research mentorship.
