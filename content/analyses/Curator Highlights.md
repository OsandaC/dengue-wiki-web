---
type: analysis
tags: [curator-notes, highlights, annotations]
created: 2026-04-18
updated: 2026-04-19
---

# Curator Highlights

*Last updated: 2026-04-19 | 13 active highlights across 1 page*

> **How this works:**
> - Add highlights in Obsidian using `==text==` on any wiki page (standard highlight, no colour)
> - For **colour-coded verification highlights**, use Obsidian's `<mark style="background: #COLOUR;">text</mark>` syntax
> - Add a comment by placing `%%your comment%%` immediately after the highlight on the same line: `==text== %%comment%%`
> - To resolve: remove the `==...==` or `<mark>` markers from the source page
> - This page is auto-regenerated during lint and on "update highlights" — do not edit manually

## Colour Code Legend

| Colour | Hex | Meaning |
|---|---|---|
| 🟢 Green | `#BBFABBA6` | Verified against raw source file — claim confirmed correct |
| 🔴 Red | `#FF5582A6` | Could not verify in raw source file — claim absent, modified, or misstated |

---

## [[Antinuclear Antibodies]]

*All highlights below are `<mark>` colour-coded verification annotations (2026-04-18 to 2026-04-19)*

### 🟢 Green — Verified correct

- `11.0% (1988–91) → 11.4% (1999–2004) → 16.1% (2011–12; P<0.0001)` — Dinse2022 temporal trend figures; confirmed in source
- `Adolescents 12–19 years: 5.0% → 9.7% → 12.4% (OR 2.77 by 2011–12 vs. 1988–91)` — Dinse2022; confirmed in source
- `ANA ≥1:80 on HEp-2 cells as the mandatory entry criterion for SLE` — Aringer2019; confirmed in source
- `Meta-regression of 13,080 patients across 64 studies` — Aringer2019 Phase I results; confirmed in source
- `sensitivity 97.8% (95% CI 96.8–98.5%) for SLE` — Aringer2019 Phase I meta-regression; confirmed in source
- `Most common specific autoantibodies: anti-Ro (3.9% of ANA+ subjects)` — Satoh2012; confirmed in source
- `anti-Su (2.4%)` — Satoh2012; confirmed in source
- `Disease-specific autoantibodies (anti-Sm, anti-topoisomerase I, anti-RNA pol I/III, anti-Jo-1) are extremely rare in healthy populations, confirming their disease specificity` — Satoh2012; confirmed in source
- `top 3 in high-titer (>1:320) ANA+ individuals were anti-Ro-52, AMA-M2, and anti-SSA` — Li2019; confirmed in source
- `Viral infections (HAV, HBV, HCV): **21.7%** ANA positive (ELISA, ANA 8 Pro 8-antigen panel, 1:100; P<0.013 vs. controls)` — Berlin2007 Table 1; confirmed in source
- `Bacterial infections: **20.0%** ANA positive (P<0.006 vs. controls)` — Berlin2007 Table 1; confirmed in source
- `Healthy blood donor controls: **3.8%** ANA positive` — Berlin2007 Table 1; confirmed in source
- `ANA in 20.5% of acute viral hepatitis patients (IIF homogeneous ≥1:40, n=156 prospective, Salvador Brazil) dropping to 6.4% in convalescence` — Codes2002 as cited by Berlin2007; confirmed in Berlin2007 Discussion

### 🔴 Red — Could not verify (resolved 2026-04-19)

The following two red highlights were investigated against the raw source PDFs and corrected:

1. **Original claim:** `~86% of individuals who test ANA-positive at 1:80 in the general population do not have SLE or another defined autoimmune disease.`
   - **Finding:** No such percentage appears in Aringer2019 or any other cited source. The paper reports ANA sensitivity (97.8%) but not this derived population-level specificity figure.
   - **Resolution:** Replaced with an accurate statement grounded in Satoh2012/Dinse2022 prevalence data (~14% population ANA+ at 1:80 vs ~0.1% SLE prevalence). Now verified green.

2. **Original claim:** `HAV patients were positive for all 8 tested ANA specificities`
   - **Finding:** Berlin2007 **Results** section states "Three patients with HAV and one with HBV were positive for all eight antigens" — only 3/10 HAV patients. Berlin2007's own **Discussion** section incorrectly overstates this as "all patients with HAV." The wiki followed the Discussion error.
   - **Resolution:** Corrected to "three of ten HAV patients (and one HBV patient)." Berlin2007 source page updated with ⚠ internal discrepancy note. Now verified green.
