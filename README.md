# ASO Framework — Agentic Search Optimization Evaluator

**Version:** v1.0 Research Preview
**Author:** Shen Xu
**Purpose:** Framework validation, case-study evidence collection, and reproducible ASO assessment.

This repository is a public research-preview implementation of an **Agentic Search Optimization (ASO)** evaluation framework.

## Framework

**Discover → Understand → Verify → Qualify → Select → Act**

The framework contains **24 criteria**, four per stage, scored from 0–5 and normalized into a 0–100 readiness score.

### Heuristic v1.0 stage weights

* Discover — 15%
* Understand — 15%
* Verify — 20%
* Qualify — 15%
* Select — 25%
* Act — 10%

These weights are **heuristic research-preview weights**. They are intended for validation through real cases and benchmark experiments and are not presented as an externally validated scientific or industry standard.

## What the tool includes

* 24-criterion ASO assessment workspace
* Baseline vs current **Readiness Delta**
* Criterion-level evidence notes and traceable URLs
* **Evidence Coverage** based on completion of evidence notes and URLs
* Manual competitor benchmark
* Illustrative decision-query probes
* Experimental BYO endpoint mode
* JSON import/export
* CSV evidence export
* Print / Save PDF report
* Local browser persistence

## Important methodology note

The framework score and the decision-query probe layer are deliberately separated. Probe outputs do **not** automatically overwrite the 24 criterion scores. This keeps model-run signals distinct from evidence-based assessment.

Evidence Coverage measures documentation completeness, not source quality or truth. Third-party corroboration and source quality are assessed separately inside the framework criteria.

## Privacy

The static app stores assessment state in your browser local storage. The experimental endpoint mode does not store API keys in local storage, but users should use test credentials only and confirm the endpoint permits browser requests.

## Status

**v1.0 — Research Preview / Prototype.**

Planned validation work includes URL-based evidence capture, repeated cross-model decision probes, real client before/after cases, benchmark datasets, and methodology calibration.

## Citation

Xu, Shen. *ASO Framework — Agentic Search Optimization Evaluator*, v1.0 Research Preview, 2026.
