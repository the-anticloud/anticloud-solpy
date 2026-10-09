# Independent Insurance — SOLPY

**Project:** SOLPY  
**Category:** SOLAR  
**Upstream:** see BENCH.json  
**Pinned commit:** `7d65b66c123f83f51d410416c46c424790389c48`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3e5101a853c153245892a118c05e8a3add8c55816ffd973ab11e00a75b4eafd9`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | SOLPY with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `3e5101a853c153245892a118c05e8a3add8c55816ffd973ab11e00a75b4eafd9`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
