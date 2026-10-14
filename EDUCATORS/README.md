# Educators — VSCODE_PRIOR_DOCS

**Project:** VSCODE_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/microsoft/vscode  
**Pinned commit:** `1f1f69adfdcfd63f0888cab5af5518a913fb779e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `52b39c4244cda6b585ff259c05e0bd943ca2de55b0ccabd02f117b1744ed0e34`  
**Date:** October 2026

## Teaching with VSCODE_PRIOR_DOCS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `52b39c4244cda6b585ff259c05e0bd943ca2de55b0ccabd02f117b1744ed0e34` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
