# French — Louis Segond 1910 (LSG)

- Full Bible: [lsg.md](lsg.md)
- Verification: [audit_report.json](audit_report.json)
- Source: eBible.org French Louis Segond 1910 (`fraLSG`), identified as public domain.
- USFX archive: <https://ebible.org/Scriptures/fraLSG_usfx.zip>
- HTML archive: <https://ebible.org/Scriptures/fraLSG_html.zip>

## Reconstruction and verification

Rebuilt 66 books, 1,189 chapters and 31,170 verse units. Missing continuation text was restored in 8,474 verses; two additional changes were spacing-only.

Every chapter's verse keys/text and headings were compared across the USFX and HTML renderings and the staged Markdown. Full-Bible and per-book outputs agree. Twelve regression tests passed. A separate parent-side HTML extractor also compared all 1,189 chapters against the final Markdown, ignoring only Unicode-normalization and whitespace differences, with no mismatches.

USFX and HTML are two formats of the same eBible publication, **not two independent textual witnesses**. Additional saved Bible.com comparisons cover three chapters. Qwen4-Max supplementary review is **complete: all 1,189 chapters reviewed at $0**. The final 31 Proverbs chapters were reviewed via per-chapter partitioning, which cleared an earlier whole-book provider content-filter block. Model-assisted review is supplementary to the deterministic comparisons. This is source-fidelity validation, not a claim of infallibility.

## Rights

The underlying Louis Segond 1910 translation is public domain. Retain source attribution and check the terms of any added third-party notes or other content separately.
