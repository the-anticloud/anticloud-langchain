# Educators — LANGCHAIN

**Project:** LANGCHAIN  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `2baf2f33c72cf027383a0b123e9be5077eb483d5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `952b23cadf054964ed0eef1fd537090b51244076fa4f6678eeae790e6d53787c`  
**Date:** October 2026

## Teaching with LANGCHAIN

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `952b23cadf054964ed0eef1fd537090b51244076fa4f6678eeae790e6d53787c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
