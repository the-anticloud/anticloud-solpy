# Educators — SOLPY

**Project:** SOLPY  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7d65b66c123f83f51d410416c46c424790389c48`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3e5101a853c153245892a118c05e8a3add8c55816ffd973ab11e00a75b4eafd9`  
**Date:** October 2026

## Teaching with SOLPY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3e5101a853c153245892a118c05e8a3add8c55816ffd973ab11e00a75b4eafd9` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
