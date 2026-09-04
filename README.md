# South America Methane — Grid Explorer

Interactive per-element explorer of an analytical Bayesian inversion of TROPOMI XCH₄ over South
America (2019–2025): emission and scale-factor maps, TROPOMI fit, sector totals, and trends. It
walks from a **standard IMI inversion** to our **production** setup one change at a time — three
independent toggles: **solver** (normal → lognormal → softplus positivity), prior error **Sₐ**
(uniform diagonal 50% → two-component continental + grid-cell), and observation error **Sₒ**
(diagonal → off-diagonal with a one-day temporal correlation, no cutoff). The standard-IMI corner
over-fits (Ja/DOFS ≈ 9, hundreds of negative cells); production is well-calibrated (Ja/DOFS ≈ 1.1,
zero negatives). 12 configurations (3 × 2 × 2). Single self-contained HTML page — no build step,
no dependencies.

**Live:** enable GitHub Pages on this repo, then open `index.html`.
