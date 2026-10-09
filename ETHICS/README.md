# Ethics — LANGCHAIN

**Project:** LANGCHAIN  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `2baf2f33c72cf027383a0b123e9be5077eb483d5`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `952b23cadf054964ed0eef1fd537090b51244076fa4f6678eeae790e6d53787c`  
**Date:** October 2026

## Position

LANGCHAIN is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
