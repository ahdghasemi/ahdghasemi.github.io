# Website revisions — 17 November 2026

This branch preserves portable source and assets for the Google Sites V2 research showcase. It does not deploy or replace the existing GitHub Pages site.

## Versions

- **V1 Preserved Baseline — 2026-11-17:** the complete original Google Sites draft remains separate. The `v1/` directory records the original paper viewer and introduction; it is not a complete Google Sites export.
- **V2 Research Showcase — 2026-11-17:** separate draft with a shorter introduction, the five-paper viewer immediately after the introduction and before the evidence cards, updated research headings, and refreshed carousel imagery.

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

## CV reconciliation — November 2026

Reconciled V2 against the user-supplied `TXST_Academic_CV.pdf` on 17 November 2026.

- Teaching: 335 course enrollments (258 UMass + 77 Florida Poly). The 197 UMass discussion-section enrollments remain separate.
- Research mentoring: 14 researchers (2 PhD, 1 MS, 11 undergraduate), with interdisciplinary methodological collaboration listed separately.
- Added current Florida Poly undergraduate and graduate teaching details, respondent-qualified teaching ratings, robotics and digital-twin advising, and Kappa Learning proposal-development experience.
- Corrected Ford-sponsored internship to June–August 2018; added R; aligned talks with the CV.
- Identified CGES workshop Spotlight separately from the TMLR manuscript under review. The time-warped UAV manuscript is in revision.
- Accepted ICLR 2026 / NeurIPS 2026 work and Tiny Flow Matching (MLSP 2026, to appear) retain their stated distinctions.

`v2/pages/` contains rich-text source for the revised Research, Publications, Teaching, and Experience pages. Funding and the concise homepage biography were checked against the CV and remain accurate.

A general website PDF was saved privately in the existing Google Drive data folder, with only the Texas State running header removed. The supplied file remains unchanged. The website mentoring section uses counts and project descriptions; identifiable student details remain in the private CV after automatic review blocked their public repository upload. Public repository upload of the PDF was blocked by automatic approval review pending explicit user approval; the PDF and CV-page source containing its private Drive URL are deliberately excluded from this branch. The V2 CV link points to the new Drive file, which currently requires access. Resolve public PDF availability before publishing the site.

## Applied carousel changes and checks

The first three rotating carousels now lead with the updated graph-foundations, confidence-guided reasoning, and compact-GNN concept illustrations; their earlier supporting images remain available. The UAV carousel now rotates between the Milano rank-sweep graphic and the manuscript’s cross-dataset coverage plot. All four carousel features are preserved.

V2 was saved as an unpublished Google Sites draft. Desktop and phone previews were inspected. All five paper panels fit the mobile iframe without vertical clipping (client height and content height both 372 px). Previous/next navigation and autoplay advancing to the next paper were checked; autoplay was then paused. Teaching and mentoring remain separate.

## CV-update validation

All revised Google Sites page text was saved in the separate V2 draft. Desktop teaching and evidence-card previews were checked. The five paper panels still fit the phone iframe (372 px client/content height); paper navigation worked. The supplied five-page CV and the private website copy have identical extracted body text after removal of the application running header, and all pages render.
