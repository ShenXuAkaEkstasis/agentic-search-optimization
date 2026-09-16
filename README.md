# Agentic Search Optimization (ASO) Framework

An **open-source framework and evaluation tool** for Agentic Search Optimization (ASO), developed by **Shen Xu**.

ASO evaluates whether AI agents can move an entity through six decision stages:

**Discover → Understand → Verify → Qualify → Select → Act**

The project is designed to make agentic selection readiness measurable, auditable, and easier to compare across entities, brands, products, and services.

## What is included

- Six-stage ASO Framework v1.0
- 24 scored criteria with weighted ASO Score
- Baseline vs. current scoring and Selection Lift
- Criterion-level evidence provenance, source type, note, and URL
- Evidence Confidence calculation
- Evaluation Lab with:
  - built-in demo engine
  - optional BYO OpenAI-compatible endpoint, model, and API key
  - repeatable decision-query probes
  - Discover / Verify / Qualify / Select / Act signals
- Competitive benchmark and six-stage radar visualization
- Judge-ready report view
- JSON import/export
- CSV evidence export
- Print / Save PDF
- Local browser persistence
- Responsive single-file front end
- Static deployment support for Vercel

## Methodology

The framework uses six weighted stages:

| Stage | Weight |
|---|---:|
| Discover | 15% |
| Understand | 15% |
| Verify | 20% |
| Qualify | 15% |
| Select | 25% |
| Act | 10% |

Each stage contains four criteria scored from 0–5. Scores are normalized to 100 and combined using the stage weights above.

The framework score and live model-run signals are intentionally kept separate. The framework score is evidence-based; Evaluation Lab results are probe outputs from the selected model endpoint.

## Open source

This project is released as open-source software under the **MIT License**. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software subject to the terms of the license.

See [`LICENSE`](LICENSE).

## Run locally

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deploy to Vercel

No build step is required. Import this repository into Vercel and deploy it as a static site. `index.html` is the entry point.

## Citation

If you reference the framework in research, analysis, documentation, or a publication, please cite:

> Xu, Shen. *Agentic Search Optimization (ASO) Framework v1.0*. 2026.

A machine-readable citation file is included as [`CITATION.cff`](CITATION.cff).

## Framework status

**Version:** 1.0 prototype  
**Author:** Shen Xu  
**Year:** 2026  
**License:** MIT  

The framework is an original applied methodology and evaluation model. It should not be represented as an externally standardized scientific or regulatory benchmark.
