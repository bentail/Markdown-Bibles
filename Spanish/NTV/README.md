# Spanish — Nueva Traducción Viviente (NTV)

- Full Bible: [ntv.md](ntv.md)
- Verification: [audit_report.json](audit_report.json)
- Edition: Tyndale / Bible.com v127
- Rights: copyrighted (Tyndale); existing corpus text, deterministic local repair

## Reconstruction and verification

**CRITICAL LANGUAGE FIX.** The previous `NTV_FULL.md`, all per-book files, `NTV_raw.json` and the published GitHub `ntv.md` were a **Sesotho (Southern Sotho) Bible — not Spanish NTV** (one bad fetch propagated to every artifact; the old audit falsely stamped PASS). Correct Spanish NTV was restored verbatim from `NTV_FULL.md.backup` (the correct May-27 witness): langdetect `es` 1189/1189, token recall 1.0 against fresh Bible.com NTV (v127).

**Fixes applied.** Rebuilt 66 books / 1,189 chapters / 31,040 verses verbatim from the correct Spanish backup (no text altered or substituted); added 66 book headings; FULL == per-book byte equality.

**Verification.** 17 independent separate-parser checks + 14 hardening checks pass: verse bodies byte-equal to the witness, raw verse-line byte multiset equality (31,040 == 31,040, 0 added/dropped), per-chapter sequence byte equality, CommonMark render, langdetect es 1189/1189, idempotent; originals re-hashed unchanged.

## Residual gaps (honest)

**KNOWN GAP — 48 verses missing:** the backup witness omits **NUM 1:20–43 (census) and the NUM 2 camp lists**. No local correct-language source can fill them (the raw is Sesotho; substituting another translation is forbidden). Completing these requires an **authorized Tyndale NTV source/permission** (bulk/AI restricted; no bulk fetch performed). Separately, 16 critical-text omissions (e.g. MAT 17:21, MRK 7:16, JHN 5:4, ACT 8:37) are **legitimate NTV versification**, preserved intentionally.

These checks establish source-fidelity of the verse text, not infallibility or an independent scholarly collation. Originals were preserved with backups before replacement.
