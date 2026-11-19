# Farsi — Persian Contemporary Bible (PCB)

- Full Bible: [pcb.md](pcb.md)
- Verification: [audit_report.json](audit_report.json)
- Edition: Bible.com version 1619 (Biblica)
- Rights: copyrighted (Biblica); existing corpus text, deterministic local repair

## Reconstruction and verification

Rebuilt all 66 books / 1,189 chapters from the cached `PCB_raw.json` (Bible.com v1619, Persian Contemporary Bible). Language confirmed Farsi; 111 verse rows source-compared against 3 cached publisher HTML chapters.

**Fixes applied.** Removed 1,634 duplicated combined-range clones (913 ranges now rendered once); stripped 2,546 glued in-body range labels; restored truncated leading verse text (e.g. PSA 37:28); corrected scrambled per-book chapter sequences (37/66 books were mis-ordered); preserved 757 inline-footnote verses verbatim.

**Verification.** 22 regression tests pass; independent separate-parser comparison of every chapter against raw (1189/1189); CommonMark render of all chapters + FULL; FULL == per-book byte equality (canonical order); idempotent rebuild; 70 original files hash-verified unchanged.

## Residual gaps (honest)

The cached raw is a verse-text-only flatten: **section headings are absent from the source cache** (not dropped by this rebuild) and **footnotes are preserved inline verbatim** (the source has no end delimiter). Corpus-wide heading restoration / footnote separation would require per-chapter publisher HTML — bulk acquisition from a permission-restricted source, which was not performed. Verse text is complete and source-verified for all 1,189 chapters.

These checks establish source-fidelity of the verse text, not infallibility or an independent scholarly collation. Originals were preserved with backups before replacement.
