# Students — POINT_OF_SALE

**Project:** POINT_OF_SALE  
**Category:** SUPERMARKETS  
**Upstream:** see BENCH.json  
**Pinned commit:** `01e14682f2d567ccc7b53d603e8aeb161ee31feb`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7cb036761f59b0ce859ad1f34d5ca7067b4df3b1854b02776b5c5856cf63a105`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `01e14682f2d567ccc7b53d603e8aeb161ee31feb`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `7cb036761f59b0ce859ad1f34d5ca7067b4df3b1854b02776b5c5856cf63a105`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
