---
type: source
tags: [epidemiology, case-control, matching, study-design, methods, biostatistics]
authors: [Pearce N]
year: 2016
journal: BMJ
doi: 10.1136/bmj.i969
citations_semantic_scholar: 684
citations_crossref: 575
citations_retrieved: 2026-05-24
created: 2026-05-24
updated: 2026-05-24
---

# Pearce2016 - Analysis of Matched Case-Control Studies

**Full citation:** Pearce N. Analysis of matched case-control studies. *BMJ* 2016;352:i969. doi:10.1136/bmj.i969

**Raw file:** `[[raw/Pearce2016.pdf]]`

## Summary

This paper addresses two widespread misconceptions about matched case-control studies: (1) that matching in itself eliminates confounding by the matching factors, and (2) that if matching has been performed, a "matched analysis" (conditional logistic regression) is required. Pearce demonstrates through a hypothetical age-matched population-based case-control study that matching does not remove confounding — it can actually introduce confounding by the matching factors even when none existed in the source population. Matching makes controls more similar to cases on both the matching factor and the exposure, creating a spurious association that must be analytically controlled.

The paper shows that a "standard" (unconditional) analysis adjusting for the matching factors is not only valid but may yield better statistical precision than a paired matched (conditional) analysis. Using worked examples with hypothetical data, Pearce demonstrates that unconditional logistic regression and the Mantel-Haenszel method produce identical adjusted odds ratios (2.00) to the conditional approach, but with narrower confidence intervals (1.42–2.81 vs 1.40–2.89). Conditional logistic regression is necessary only when strata are genuinely sparse (e.g., one case and one control per stratum, as in sibling or neighbourhood matching), where unconditional regression would be biased — producing an odds ratio that is the square of the true conditional estimate.

## Study Design
- **Type:** Methodological guidance paper (BMJ Research Methods and Reporting series)
- **Sample size:** Hypothetical data (390 cases, 390 controls in worked example; total population 200,000)
- **Setting:** N/A — general epidemiological methods guidance
- **Population:** Hypothetical population-based case-control study with age matching (five-year age groups, two sex groups)

## Key Findings

- Matching in a case-control study **does not control for confounding** by the matching factors; it requires analytical adjustment regardless of whether the analysis uses matched or unmatched methods.
- Matching can **introduce confounding** that did not exist in the source population: the matching process selects controls who are similar to cases on both the matching factor and the exposure, inflating the association between the matching factor and the exposure in the study sample.
- In the worked example, the crude odds ratio in the total population was 0.86 (95% CI 0.70–1.05); after age adjustment, the true odds ratio was 2.00 (1.59–2.51). The matched case-control study produced a crude OR of 1.68 (1.25–2.24) — neither the true crude nor the true adjusted value — demonstrating confounding introduced by matching.
- A **standard (unconditional) analysis** adjusting for the matching factors yields the correct adjusted OR (2.00) with 95% CI 1.42–2.81.
- A **pair-matched (conditional) analysis** yields the same adjusted OR (2.00) with a slightly wider 95% CI of 1.40–2.89.
- Unconditional analysis has advantages: (a) slightly better precision when multiple case-control pairs share identical matching-factor values; (b) easier to combine datasets with different matching schemes; (c) clearer presentation with standard 2x2 tables for subgroup analyses.
- **Conditional analysis is required** when strata are truly sparse — e.g., sibling controls (one case, one sibling control per family), neighbourhood matching, or matching on many factors simultaneously so that most strata have just one case and one control. In this situation, unconditional logistic regression is biased (the OR estimate becomes the square of the true conditional OR).
- The precision at which the matching factor is controlled in the analysis should match the precision of the original matching (e.g., if exact age in years was used for matching, exact age should be controlled in analysis — though five-year groups may suffice in practice).

## Methods Used

- [[Age-Matched Case-Control Analysis]]

## Entities Mentioned

None (general epidemiological methods paper — no disease-specific entities).

## Concepts Addressed

- [[Age-Matched Case-Control Analysis]]

## Relevance & Notes

This is not a dengue paper. It is ingested as a methodological reference for evaluating the validity of age-matched case-control designs used in dengue research and related immunological studies. The paper is directly relevant when assessing whether an age-matched case-control study has been correctly analysed — specifically, whether confounding introduced by matching was adequately controlled and whether the choice of unconditional vs. conditional analysis was appropriate for the study's matching structure.

Pearce is affiliated with the London School of Hygiene and Tropical Medicine and the Centre for Public Health Research, Massey University. The paper is part of BMJ's Research Methods and Reporting series and is highly cited (684 citations on Semantic Scholar), indicating it is a standard reference in epidemiological methodology.

**Limitations:** The paper uses hypothetical data throughout; no empirical dataset is analysed. The examples focus on age matching, which is the simplest case. The recommendations extend to multi-factor matching, but the worked examples do not demonstrate these more complex scenarios. The guidance on when conditional analysis is truly necessary (sparse strata) relies on a qualitative threshold rather than a formal rule.

## Questions Raised

- In dengue case-control studies using age-matching (e.g., Garcia2010), was the matching factor adequately controlled in the analysis? If not, the reported ORs may reflect confounding introduced by matching rather than a true exposure effect.
- For studies matching on multiple factors simultaneously (age + sex + hospital admission date), are the resulting strata sparse enough to require conditional logistic regression, or would unconditional analysis with covariate adjustment be equally valid and more precise?
- When combining dengue case-control data from multiple sites with different matching schemes (e.g., some matched on age, some on age+sex, some unmatched), Pearce's framework suggests unconditional analysis adjusting for all matching factors is the correct approach — is this being done in multi-centre dengue studies?
