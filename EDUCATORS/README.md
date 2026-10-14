# Educators — POINT_OF_SALE

**Project:** POINT_OF_SALE  
**Category:** SUPERMARKETS  
**Upstream:** see BENCH.json  
**Pinned commit:** `01e14682f2d567ccc7b53d603e8aeb161ee31feb`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7cb036761f59b0ce859ad1f34d5ca7067b4df3b1854b02776b5c5856cf63a105`  
**Date:** October 2026

## Teaching with POINT_OF_SALE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7cb036761f59b0ce859ad1f34d5ca7067b4df3b1854b02776b5c5856cf63a105` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
