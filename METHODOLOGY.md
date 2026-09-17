# ASO Framework v1.0 — Methodology

Author: Shen Xu  
Status: Research Preview / Prototype  
Year: 2026

## Core question

Can an AI-mediated decision process reliably discover, understand, verify, qualify, select, and act on an entity for a defined task?

## Six stages and 24 criteria

### 1. Discover — 15%
1. Task-query presence
2. Source coverage
3. Entity resolution
4. Freshness

### 2. Understand — 15%
1. Category clarity
2. Attribute clarity
3. Semantic consistency
4. Entity relationships

### 3. Verify — 20%
1. Claim-to-evidence mapping
2. Third-party corroboration
3. Citation quality
4. Provenance clarity

### 4. Qualify — 15%
1. Requirement coverage
2. Constraint transparency
3. Comparison readiness
4. Risk reduction

### 5. Select — 25%
1. Decision-relevant differentiation
2. Proof strength
3. Evidence consensus
4. Preference fit

### 6. Act — 10%
1. Action path clarity
2. Machine-action readiness
3. Transaction information
4. Handoff readiness

## Scoring

Each criterion is scored from 0–5. A stage score is the arithmetic mean of its four criteria, normalized to 0–100. The overall ASO Score is the weighted sum of the six stage scores using the v1.0 heuristic weights above.

The **Readiness Delta** is the current ASO Score minus the baseline ASO Score. It is a framework-score change, not a causal claim that real-world selection probability increased by the same amount.

## Evidence Coverage

Evidence Coverage is a transparent documentation-completeness metric:

- one evidence-note slot per criterion;
- one traceable-URL slot per criterion;
- coverage = completed slots / all available slots.

It does not estimate truth, authority, or source quality. Those properties are assessed separately by criteria such as Third-party corroboration, Citation quality, Provenance clarity, Proof strength, and Evidence consensus.

## Decision-query probes

Decision-query probes are an experimental layer. They can record whether an entity is surfaced, verified, qualified, selected, and actionable for representative tasks. Probe results are reported separately and do not automatically overwrite the framework score.

## Validation status

This v1.0 implementation is a research preview. Stage definitions, criteria, weights, thresholds, and benchmark procedures should be calibrated using repeated cross-model experiments, real cases, and external review before any claim of scientific or industry-standard validation.
