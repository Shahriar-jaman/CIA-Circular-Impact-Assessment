# The Circular Impact Assessment (CIA) Model

## Work Process

1. **Framing.** Built the four-layer CIA model around a hypothesized secondary delay intensification loop, and applied it to two Bangladeshi projects over 2012–2026: the Padma Multipurpose Bridge Project (PMBP) and Dhaka Mass Rapid Transit Line 6 (DMRP).
2. **Evidence base.** Identified 156 documents and included 147 (institutional reports, environmental records, 124 newspaper articles, peer-reviewed studies). Used secondary documentary data only.
3. **Phasing.** Divided 2012–2026 into four phases applied identically to both projects, giving a panel of eight project-phases.
4. **Coding.** Thematic coding in two stages (open, then axial). Built a Feedback Evidence Matrix with three pathways (economic, social, environmental), each coded strong, moderate, or weak.
5. **DAC.** Computed the Delay Amplification Coefficient as the number of pathways coded strong or moderate (0–3), for Phases 2–4 only (n = 6).
6. **Sentiment.** Scored all 124 newspaper articles with VADER and averaged by project and phase.
7. **Dual coding and validation.** Dual-coded all 18 DAC pathway codes and the 8 IGQ ratings. A provisional pass was checked with an AI cross-check layer, followed by an independent blind recoding by two coders. Reported Cohen's kappa and quadratic-weighted kappa.
8. **Statistics.** Ran Spearman correlations, bootstrap confidence intervals, exploratory OLS, and ordinal logit. Added GEE with small-cluster correction, a penalized ordinal logit, and Random Forest / Extra Trees for triangulation only. Reported every DAC statistic for both the full and corpus-strict series.
9. **Model run.** Ran a stylized phase-step system dynamics model, checked it against known outcomes, then ran four scenarios: S0 baseline, S1 high governance, S2 30% early delay cut, S3 combined.
10. **Cross-case comparison.** Compared the two projects on delay, economic, social, environmental, and feedback-evidence dimensions, and traced impacts to SDGs 8, 9, 11, 13, and 15.

## Findings

- Documented impacts largely intensified in later project phases, not at the onset of delay.
- The two projects differed in the pattern of their trajectories, not only in magnitude.
- The one association that survived every correction is delay duration vs. environmental impact intensity: Spearman ρ = 0.89, p = 0.003, n = 8.
- The DAC is sensitive to a disclosed three-cell coding decision, in magnitude and once in direction. Six to eight observations cannot support strong inference at that level.
- Coding reliability: pooled QWK = 0.71. The economic pathway and IGQ fell below the 0.60 threshold.
- The system dynamics model gave a model-derived, unvalidated hypothesis: a 30% early delay cut reduced terminal delay by about 26% (PMBP) and 22–29% (DMRP), while raising governance quality changed it by roughly 0–4%.
- Robustness corrections did not strengthen the delay-amplification claim at the DAC level (for example, the GEE p-value moved from 0.0005 to 0.937 after correction).
- Delay-induced impacts therefore look circular and cross-domain in this record, but the composite instrument needs a larger observation base.
