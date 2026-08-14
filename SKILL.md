---
name: proof-post-typesetting-review
description: Compare an approved manuscript and production package with typeset proofs and final digital or print outputs. Use for proof baselines, fixity, visible differences, production-introduced errors, text and symbol integrity, navigation, visual objects, references, correction logs, reproof, accessibility signals, post-publication records, and human-owned release decisions. Do not use for developmental editing, substantive rewriting, routine copyediting, legal permission decisions, accessibility conformance certification, scholarly integrity adjudication, or silent changes to the version of record.
---

# Proof & Post-Typesetting Review

Use this family as a controlled comparison and correction process. Start with an approved baseline, stable file/output identity, fixity/provenance, proofing scope, approved variation log, and authorized channel. A difference is not automatically a defect: consult approved design and production decisions first. Keep `approved_variation`, `typesetter_error`, `factual_or_meaning_error`, `author_alteration`, `query_open`, `source_unavailable`, `asset_issue`, `accessibility_signal`, `status_issue`, `resolved`, and `blocked` distinct.

## Executable workflow

1. Initialize `MWM-PPR-SPEC`, rule version, baseline/proof/output IDs, stage, format, reviewer, correction limit, deadline, escalation path, and signatory.
2. Validate preconditions. If baseline, proof identity, authorized channel, output target, approved variations, upstream statuses, or signatory is missing, stop as `blocked` or `source_unavailable`; do not infer from filename, timestamp, visual similarity, or memory.
3. Capture baseline and fixity records for approved manuscript/copyedited version, proof, final candidates, assets, correction grid, and variation log. Preserve superseded and prior proof events.
4. Build stable comparison objects for text, names, numbers, symbols, equations, code, headings, pages, navigation, figures, tables, captions, notes, references, cross-references, metadata, and output formats.
5. Compare text, symbols, metadata, layout/navigation, visual objects, references, digital output features, and correction incorporation. Classify each difference only after checking approved variation/design authority.
6. Record exact current state, expected state, locator, evidence, authority, defect class, impact, confidence, minimal correction or query, owner, release effect, and closure condition. Vague instructions such as ?make better? do not authorize a change.
7. Process correction decisions as accept, reject, defer, or refer. Preserve rejected/deferred queries and rationale. Do not accept substantive author alterations as routine proof corrections.
8. Verify accepted corrections in a new proof/output. A correction is not resolved until incorporation evidence and affected-scope reproof pass; recheck TOC, index, pagination, cross-references, and format-specific effects when relevant.
9. For PDF/e-book/HTML outputs, record format-specific reading order, headings/bookmarks, links, tables, alt text, language, page navigation, text extraction, and other applicable checks. Route conformance to the specialist; do not overclaim.
10. For post-publication cases, preserve the original record/fixity, create linked correction/version/status records, and communicate only an authorized decision. Do not decide retraction, removal, or expression-of-concern status.
11. Produce a baseline/fixity report, difference and correction ledger, open-query list, reproof results, output checks, upstream dependency refresh, recommendation, release event, and human sign-off: `ready`, `ready_with_tracked_items`, `hold`, `blocked`, or `post_publication_case`.

## Skill routing

- `PPR-01`: baseline, proof/output identity, fixity, provenance, and corruption gate.
- `PPR-02`: difference review across content, objects, layout, metadata, and formats; approved variations first.
- `PPR-03`: exact text, names, numbers, symbols, equations, code, glyph, and special-character comparison; minimal correction only.
- `PPR-04`: TOC, headings, running elements, pagination, breaks, footnotes, index, and navigation; production owns design choices.
- `PPR-05`: figure/table/caption/note/asset identity, placement, crop, source, permission, and format presence; route technical/rights decisions.
- `PPR-06`: visible references and cross-reference survival; consume RCI/TE and do not duplicate their substantive checks.
- `PPR-07`: exact correction records and state machine through incorporation and reproof.
- `PPR-08`: digital/output evidence and accessibility signals; no conformance claim without specialist evidence.
- `PPR-09`: post-publication correction/version/status records; preserve original and authorized links.
- `PPR-10`: human-owned proof release gate with no unresolved material issue.

## Boundaries and safety

Do not rewrite passages, normalize whole sections, infer missing words or symbols, select a final file, silently overwrite the record, certify legal permissions, accessibility conformance, source validity, or scholarly integrity, or close a correction from the correction log alone. Treat confidential proof sharing as an incident. Protect unpublished proofs, correspondence, correction files, sensitive data, and rights documents. Use intervention values `AUTO_RECORD`, `NO_ACTION`, `CORRECT`, `QUERY`, `REPLACE_ASSET`, `REPROOF`, `HOLD`, `BLOCK`, and `REFER`.

Invocation: $proof-post-typesetting-review