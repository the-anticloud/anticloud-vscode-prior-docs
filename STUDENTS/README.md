# Students — VSCODE_PRIOR_DOCS

**Project:** VSCODE_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/microsoft/vscode  
**Pinned commit:** `1f1f69adfdcfd63f0888cab5af5518a913fb779e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `52b39c4244cda6b585ff259c05e0bd943ca2de55b0ccabd02f117b1744ed0e34`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1f1f69adfdcfd63f0888cab5af5518a913fb779e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `52b39c4244cda6b585ff259c05e0bd943ca2de55b0ccabd02f117b1744ed0e34`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
