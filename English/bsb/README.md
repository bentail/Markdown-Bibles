# English — Berean Standard Bible (BSB)

- Full Bible (no footnotes): [bsb.md](bsb.md)
- Footnotes variant: [bsb_with_footnotes.md](bsb_with_footnotes.md) *(legacy; pending the same spacing/superscription pass)*
- Verification: [audit_report.json](audit_report.json)
- License: [Public Domain / CC0](LICENSE)

## Edition and rights

The Berean Standard Bible is **public domain (CC0 1.0 Universal)**, officially dedicated April 30, 2023 by the Berean Bible Translation Committee with Bible Hub, Discovery Bible, and OpenBible.com (https://berean.bible/terms.htm). All uses freely permitted; attribution appreciated but not required. The prior CC BY-SA 4.0 / Lockman Foundation notice in this folder was incorrect and has been corrected.

## Reconstruction and verification

`bsb.md` is the current official BSB text (verified against `bereanbible.com/bsb.txt`), repaired and independently validated:

- **4,463 spacing repairs** (3,354 merged-word boundaries, 783 missing separators, 326 extraneous gaps) across 3,351 verses — fixing words joined at poetic line-breaks and dialogue quote boundaries.
- **116 Psalm superscriptions restored** (e.g. "A Psalm of Asaph."), corroborated against the current source.
- **16 pre-existing content discrepancies reconciled** against the official text: 10 wording corrections, 3 Hebrew/English versification artifacts quarantined losslessly (2 Chr 1:18, 13:23; Micah 4:14 — correct English verses already present), and Malachi 4:4–6 restored.
- **All 1,189 chapters / 31,086 verses match the current official BSB text, zero unresolved differences.** 30 regression tests pass; independent separate-parser verification, CommonMark rendering, canonical FULL/per-book equality, and byte-exact reversible ledgers verified.

This is source-fidelity validation against the official public-domain text, not a claim of infallibility. `bsb_with_footnotes.md` is the legacy footnotes variant and has not yet received the same spacing/superscription pass.
