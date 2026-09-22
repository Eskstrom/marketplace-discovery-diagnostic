# Marketplace Discovery Diagnostic

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=product-service-design#library)

## Product brief

A catalog-quality tool that detects taxonomy gaps, missing attributes, duplicate categories, and poor filter coverage—then recommends changes that improve discoverability.

## Design focus

Find how categories, missing attributes, and filters hide relevant products.

## Proposed scope

- Public or synthetic product catalog.
- Quality checks for attributes, category depth, and duplicate labels.
- Search/filter coverage report.
- Prioritized remediation queue with expected impact assumptions.

## Validation targets

- Show a before/after browse or search experience.
- Make the ranking rationale clear and editable.

## Potential implementation

Python, DuckDB, Streamlit; optionally a small React catalog viewer.

## Guardrails

Do not scrape or reuse restricted marketplace data.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)
