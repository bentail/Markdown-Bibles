# Dari — Today's Dari Version (TDV)

- Full Bible: [tdv.md](tdv.md)
- Verification: [audit_report.json](audit_report.json)
- Publisher source: <https://afghanbibles.org/eng/dari-bible/>

## Reconstruction and verification

Rebuilt all 66 books and 1,189 chapters from cached publisher-served HTML. The compilation preserves the publisher's chapter-specific variants: 682 chapters served as `tdv08`, and 507 as `tdv`. It is **not described as a uniform historical edition**.

All 30,009 verse entries, covering 31,104 verse numbers, were compared with source data using a separate extraction implementation. The 598 combined ranges appear once each, rather than duplicating their text under each constituent verse number. Headings, superscriptions, prologues and speaker labels are retained separately. Full-Bible and per-book outputs agree. Twenty regression tests and all-chapter Markdown-rendering checks passed.

These checks establish fidelity to the cached publisher pages, not an independent collation against another edition or a guarantee that the publisher's own text is error-free. Additional model-assisted reviews may continue; they are supplementary to the complete deterministic comparisons.

## Rights

This translation retains its publisher's applicable copyright and usage terms. Formatting and verification do not grant new rights to the underlying translation; the repository's software license does not override those terms.
