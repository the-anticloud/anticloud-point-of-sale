# Ethics — POINT_OF_SALE

**Project:** POINT_OF_SALE  
**Category:** SUPERMARKETS  
**Upstream:** see BENCH.json  
**Pinned commit:** `01e14682f2d567ccc7b53d603e8aeb161ee31feb`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7cb036761f59b0ce859ad1f34d5ca7067b4df3b1854b02776b5c5856cf63a105`  
**Date:** October 2026

## Position

POINT_OF_SALE is packaged for offline deployment with a verifiable audit trail. The
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
