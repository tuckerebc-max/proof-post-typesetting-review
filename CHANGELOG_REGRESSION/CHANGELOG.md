# Change Log ? Proof & Post-Typesetting Review

## 0.1.0 ? 2026-08-14

Status: draft for editorial-owner review.

- Bound `01_SPECIFICATION.md` to `MWM-PPR-SPEC` v0.1.0-draft; source hash is recorded in `package_manifest.json`.
- Added 31 machine-readable rules for baseline/fixity, approved variations, exact differences, text and symbols, navigation, visual objects, references, correction/reproof state, output formats, accessibility boundaries, post-publication lineage, protection, minimum change, and human release.
- Added 10 explicit MWM decision hooks for proof protocols, correction limits, variation ownership, formats, reproof scope, status taxonomy, fixity retention, and confidentiality incidents.
- Added schemas for run manifests, baselines, findings, corrections, fixity events, upstream results, ledgers, decisions, outputs, and cross-family contracts.
- Added a 45-fixture synthetic evaluation set with rule crosswalk, adversarial/negative controls, integration cases, and deterministic scorer.
- Added regression intake and production-failure capture for false ready, baseline ambiguity, silent overwrite, missing reproof, status overreach, accessibility overclaim, rights boundary, and confidentiality incidents.

## Change policy

Behavior changes identify specification/rule IDs, baseline/proof examples, authority, correction-limit decision, fixtures, regression results, owner approval, and migration treatment. Preserve every proof/correction/final-output event needed to reconstruct what was reviewed and released.

## 2026-08-14 packaging update

- Added `01_SPECIFICATION.docx` as a source-preserving Word version of the governing specification. The Markdown specification remains the design authority; no editorial rule or open MWM decision was changed.
