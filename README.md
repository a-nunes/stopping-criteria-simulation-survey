# Stopping Criteria in Simulation — Survey Data and Supplementary Material

This repository accompanies the manuscript **“Stopping Criteria in Simulation: A Survey of Methods, Applications, Challenges, and Future Directions.”**

The survey examines operational stopping criteria that use accumulating information to decide whether simulation, Monte Carlo, or sequential sampling effort should continue or terminate. It organizes the retained contributions by the purpose of termination and compares their reported evidence, assumptions, guarantees, implementation support, and limitations.

## Supplementary materials

### Operational Contributions and Evidence Profiles

The principal supplement reports 95 operational contributions from the survey's 54 primary studies, with contribution-level descriptions, conditions for use, family and subfamily classifications, and five evidence dimensions. It is available in three equivalent formats:

- [CSV — canonical machine-readable data](supplementary-materials/operational-contributions-and-evidence-profiles/Operational_Contributions_and_Evidence_Profiles.csv)
- [Markdown — readable directly on GitHub](supplementary-materials/operational-contributions-and-evidence-profiles/Operational_Contributions_and_Evidence_Profiles.md)
- [PDF — stable landscape rendering](supplementary-materials/operational-contributions-and-evidence-profiles/Operational_Contributions_and_Evidence_Profiles.pdf)

The filterable **Consider when** column provides short target-and-condition phrases for locating contributions. These phrases are entry points, not recommendations or a new taxonomy. Evidence states describe what the source studies reported and must not be combined into a readiness score, ranking, certification, or universal recommendation.

Symbols are **✓** demonstrated evidence, **~** limited or partial evidence, and **—** evidence not reported. Robustness is assessed for non-normality, autocorrelation/dependence, nonstationarity, and model misspecification. Family 1 subfamilies follow the inferential-target partition used in the manuscript: mean estimation, other scalar-parameter estimation, quantile estimation, and joint parameter estimation. **Cross-cutting** identifies contributions spanning multiple targets.

### Forward-Citation Candidates

This artifact lists 33 citing documents retained after title/abstract screening and the final authorship-overlap audit. It is available in three equivalent formats:

- [CSV — canonical machine-readable data](supplementary-materials/forward-citation-candidates/Forward_Citation_Candidates.csv)
- [Markdown — readable directly on GitHub](supplementary-materials/forward-citation-candidates/Forward_Citation_Candidates.md)
- [PDF — stable landscape rendering](supplementary-materials/forward-citation-candidates/Forward_Citation_Candidates.pdf)

The list contains title, authors, year, journal, DOI, link, and one screening flag for each document:

- **Specific indication** — five documents with at least one target-specific signal in title/abstract screening;
- **Potentially relevant** — 28 documents with a plausible but unresolved relationship.

Neither flag represents full-text confirmation, independent validation, or cross-domain transfer. The 33 documents are follow-up candidates, not additions to the survey's 54-study focal corpus.

## Scope and interpretation

Files in this repository should be interpreted within the scope and limitations stated in the manuscript. In particular:

- contribution-level entries remain linked to their source studies;
- family membership denotes a shared terminal rationale, not equivalence of assumptions, guarantees, or empirical support;
- evidence profiles describe what the source studies reported and are not readiness scores, rankings, deployment certifications, or universal recommendations;
- forward-citation candidates are screening signals for follow-up assessment, not confirmed independent validation.

## Citation

Citation metadata for the manuscript will be added after publication details become available.

## Contact

For questions about the repository or its supplementary material, please use the GitHub issue tracker.
