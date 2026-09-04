# South America Methane — Grid Explorer

Interactive per-element explorer of the **production** analytical Bayesian inversion of TROPOMI
XCH₄ over South America (2019–2025): emission and scale-factor maps, TROPOMI fit, sector totals,
and trends. The inversion uses the softplus solver with a two-component prior error Sₐ (continental
+ grid-cell, BTR-calibrated); the one selector that varies is the observation error Sₒ — the
production **off-diagonal Sₒ** (well-calibrated, Ja/DOFS≈1.1) versus a **diagonal Sₒ** (over-fits,
Ja/DOFS≈3.9). Single self-contained HTML page — no build step, no dependencies.

**Live:** enable GitHub Pages on this repo, then open `index.html`.
