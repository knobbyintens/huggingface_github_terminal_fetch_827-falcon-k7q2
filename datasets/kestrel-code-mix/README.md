---
language:
- en
tags:
- code
- competitive-programming
- reasoning
license: apache-2.0
---

# Kestrel-Code-Mix

Internal SFT candidate: competitive-programming problems with test cases and
editorials. Intended for code-reasoning training.

## Provenance

Adopted from the original dataset released by the BAAI team (see `BAAI/TACO`)
and re-sharded for internal training. No records were modified.

## Layout

The archive keeps the upstream partition scheme one-for-one:

- `data/train-00000-of-00039-e991a271dbfa9925.parquet` through `data/train-00038-of-00039-96a59dd6a98cd075.parquet`
- `data/valid-00000-of-00001-5e672c5751f060d3.parquet`
- `data/test-00000-of-00001-9c49eeff30aacaa8.parquet`

## Sample

`datasets/kestrel-code-mix/samples/kestrel_code_mix_sample.jsonl` contains the
first record of the evaluation split exactly as received from upstream.
