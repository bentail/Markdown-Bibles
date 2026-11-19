# Farsi — Today's Persian Version (TPV)

- Full Bible: [tpv.md](tpv.md)
- Verification: [audit_report.json](audit_report.json)
- Edition: Bible.com version 181 — 2023 Revision
- Rights: copyrighted; existing corpus text, deterministic local repair

## Reconstruction and verification

Edition resolved: `TPV_raw.json` == Bible.com v181 (Today's Persian Version, 2023 Revision), proven by an independent HTML oracle on 6/6 witness chapters. The legacy per-book files + backup were a systematically reworded, structurally corrupted older-revision rendition; both FULL and per-book were rebuilt from the authoritative raw v181.

**Fixes applied.** Collapsed 1,197 cloned range keys into 393 combined ranges rendered once (390 label-confirmed; 3 label-less NEH 10 ranges confirmed against fresh source data-usfm — zero heuristic-only merges); stripped 1,171 glued in-body range labels; removed 342 duplicate chapter headings; discarded legacy tail-losses; FULL == per-book.

**Verification.** 26 regression checks pass; independent separate-parser all-chapter comparison 1189/1189 exact; 6/6 source-witness chapters match; CommonMark clean on every chapter + FULL; idempotent; 70 originals unchanged.

## Residual gaps (honest)

Headings / Psalm superscriptions / footnotes are absent from the cached raw (apparatus gap, **no verse-text impact**); restoration needs per-chapter publisher HTML (bulk acquisition prohibited, not performed). **EZR 10:23 is absent in v181 itself** — documented, not synthesized. This rebuild updates TPV to its acquisition-source edition (v181, 2023 Revision); the prior corrupted older-revision wording is replaced.

These checks establish source-fidelity of the verse text, not infallibility or an independent scholarly collation. Originals were preserved with backups before replacement.
