# REALITY FUSION — SCREENPLAY PACKAGE BUILD VERIFICATION

Version: 1.0  
Build date: 2026-08-06  
Branch: `main`

## Purpose

This document records the automated formatting build for the current active screenplay set. It does not constitute production lock, runtime validation, or external specialist approval.

## Active Sources

- `screenplays/EP1/Reality_Fusion_EP1_Master_Draft_v2.1.md`
- `screenplays/EP2/Reality_Fusion_EP2_Master_Draft_v2.1.md`
- `screenplays/EP3/Reality_Fusion_EP3_Master_Draft_v2.2.md`
- `screenplays/EP4/Reality_Fusion_EP4_Master_Draft_v2.1.md`
- `screenplays/EP5/Reality_Fusion_EP5_Master_Draft_v2.1.md`

## Build System

- Generator: `tools/build_screenplay_package.py`
- Workflow: `.github/workflows/build-screenplay-package.yml`
- Workflow run: `31104128736`
- Source commit: `d1bab09b3cec6682b6e1159023864d4db49a4a19`
- Workflow conclusion: `success`

## Verified Outputs

The workflow produced five DOCX files, five PDF files, a package README, and a combined ZIP archive.

Rendered DOCX page counts observed during post-build visual QA:

| Episode | Active Draft | Rendered Pages |
|---|---|---:|
| EP1 | v2.1 | 18 |
| EP2 | v2.1 | 18 |
| EP3 | v2.2 | 33 |
| EP4 | v2.1 | 19 |
| EP5 | v2.1 | 21 |
| **Total** |  | **109** |

These are formatting page counts, not runtime estimates.

## Artifact Record

- Artifact name: `reality-fusion-current-screenplays-docx-pdf`
- Artifact ID: `8968778734`
- Artifact size: `1,781,461 bytes`
- Artifact digest: `sha256:14e5d32319c4dae20d2c892c330abf3a6fa4056340a725898a9d4f78d03d4dab`
- Retention expiry: 2026-09-05

## QA Performed

- all five DOCX files rendered successfully;
- all five PDFs were generated and were non-empty;
- expected output count verified: five DOCX and five PDF files;
- Thai glyphs rendered in the inspected pages;
- no dark content was detected within the clipping-risk edge bands across 109 rendered pages;
- no runtime, spoken duration, or production-duration claim was inferred from page count.

## Limitations

- page layout is a controlled internal screenplay format, not a claim of compliance with a specific studio house template;
- human line-by-line proofing remains required before production lock;
- timed Thai table reads remain `PENDING EXTERNAL PROCESS`;
- medical, Buddhist practice, safeguarding, privacy, technology, and governance reviews remain `PENDING EXTERNAL REVIEW`.

## Status

- automated package build: `VERIFIED COMPLETE`
- DOCX/PDF files: `VERIFIED PRESENT`
- visual edge-clipping check: `PASS`
- production lock: not reached
- submission readiness: not claimed
