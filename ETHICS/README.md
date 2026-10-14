# Ethics — VSCODE_PRIOR_DOCS

**Project:** VSCODE_PRIOR_DOCS  
**Category:** SOFTWARE_DEVELOPMENT  
**Upstream:** https://github.com/microsoft/vscode  
**Pinned commit:** `1f1f69adfdcfd63f0888cab5af5518a913fb779e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `52b39c4244cda6b585ff259c05e0bd943ca2de55b0ccabd02f117b1744ed0e34`  
**Date:** October 2026

## Position

VSCODE_PRIOR_DOCS is packaged for offline deployment with a verifiable audit trail. The
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
