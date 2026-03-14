# Astrops Inc. — Security Research

We identify and responsibly disclose security vulnerabilities across open source projects and bug bounty programs.

---

## Security Contributions

### Acknowledged by Elastic — Path Traversal in docs-builder
**Date:** March 2026  
**Project:** [elastic/docs-builder](https://github.com/elastic/docs-builder)  
**Type:** Path Traversal (CWE-22)

Reported a path traversal vulnerability in the `literalinclude` directive of `docs-builder`, Elastic's documentation build system. The include processor failed to validate that resolved paths remained within the documentation source directory, allowing traversal to arbitrary filesystem locations.

**Fix:** [PR #2887 — Extend path sanitization to literal includes](https://github.com/elastic/docs-builder/pull/2887)  
**Acknowledgement:** Credited by the Elastic team in the PR description.

---

*More disclosures coming soon.*
