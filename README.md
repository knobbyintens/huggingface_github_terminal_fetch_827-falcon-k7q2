# Falcon Training Data Review

This repository holds the license review of candidate training datasets.

- `datasets/<dataset>/README.md` — the card for each candidate dataset.
- `datasets/<dataset>/samples/<dataset>_sample.jsonl` — a small sample extract.
- Issues in this repository form the review queue; one open ticket per candidate dataset.
- `registry/approved/<dataset>.json` records datasets cleared for ingestion.
- `registry/blocked/<dataset>.json` records datasets that are not cleared.

Registry record fields: `dataset`, `upstream`, `license`, `decision`,
`reviewed_at`, `evidence`.
