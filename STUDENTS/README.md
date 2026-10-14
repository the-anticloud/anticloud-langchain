# Students — LANGCHAIN

**Project:** LANGCHAIN  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `2baf2f33c72cf027383a0b123e9be5077eb483d5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `952b23cadf054964ed0eef1fd537090b51244076fa4f6678eeae790e6d53787c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2baf2f33c72cf027383a0b123e9be5077eb483d5`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `952b23cadf054964ed0eef1fd537090b51244076fa4f6678eeae790e6d53787c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
