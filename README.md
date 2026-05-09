# BOTWAVE PAPERWORK

**Kyle Jimenez — 2026**

---

Seven books. Three genres. One pipeline.

This is the proof that TELOS+PAI — a purpose-driven, automated-instruction architecture built on Daniel Miessler's PAI framework — can produce serious long-form journalism, sports narrative, and literary fiction at production quality. Same architecture. Different books. Every claim traceable to a filed document.

The pipeline:

```
Seed → News Cache (221 sources) → Claim Extractor → Prime Directive Gate
→ Substrate Write → Voice Pass → Humanizer → PDF Build
```

Every factual assertion passes the Prime Directive before it reaches the page:

> *A named, filed, publicly-verifiable primary source — court filing with case number, Federal Register volume and page, National Archives record group, signed memorandum with archive location, contemporary newspaper of record with date and page. No inference presented as fact. No "widely reported." No "many historians argue." The document is named, or the sentence does not appear.*

That is not a style guideline. It is a hard gate. Code enforces it. The substrate either accepts the claim with a primary-source citation or rejects it.

---

## The Books

### Nonfiction

**[Unwarranted Influence](books/unwarranted_influence/)** — 643 pages. A primary-source investigation tracing the same financial instruments and institutional actors from the Crusader states through DOGE. Every claim cites a filed document: Federal Register entries, National Archives record groups, court dockets, signed executive orders, peer-reviewed monographs. The substrate holds 1,100+ verified citations.

**[Did Not Step Forward](books/captain_and_champ/)** — Muhammad Ali. Kareem Abdul-Jabbar. Two men. One refusal. A Ledger of Resistance, 1960–2016. Every citation traces to a Selective Service System record, a court filing (*United States v. Clay*, S.D. Tex.), a Muhammad Ali Center contract, or a newspaper of record with date and page.

**[The Shield](books/the_shield/)** — MIC 2.0 and the Architecture of Impunity. The Epstein flight logs, the Palantir contracts, the defense revolving door — documented from primary sources and rebuilt as continuous narrative.

### Sports Narrative

**[Magic Hour](books/magic_hour/)** — A memoir of Showtime Lakers basketball, 1979–1991. The Forum. The fast break. The last night the lights were on. Written in a voice that earned the knowledge, not researched it.

**[Voice in the Transistor](books/blue_heaven/)** — Blue Heaven: A Dodger Memoir, 1947–2016. The transistor radio. Vin Scully. The move west. The long twilight. A fifty-year story told from the seat of a listener who was always late to the game.

### Fiction

**[SUDO_KINGDOM](books/sudo_kingdom/)** — Literary fiction. Root access to the system. A narrator who hasn't left the compound in twenty-three days, watching Camera 12, waiting for a crontab to fire. The meth is from a man in Boca. The access model the book describes is not fictional.

**[DOGE](books/doge/)** — The Efficiency Files. Fiction constructed from filed executive orders, Federal Register entries, and public contracting records. The documents are real. The narrator is not.

---

## For Editors

Each book directory contains:
- `full.pdf` — complete manuscript, print-ready, 6×9 trim
- `teaser.pdf` — first chapters, for review

Submission inquiries: Kyle Jimenez — lyfer1904@gmail.com

---

## The Pipeline

This imprint is built on [Daniel Miessler's PAI framework](https://github.com/danielmiessler/PAI). The journalism arm extends PAI with:

- **221-source news cache** — Western + adversarial + non-aligned sources, full-text extracted, source-fingerprinted
- **Claim extractor** — entity matching, indirect reference detection, propaganda pattern flagging
- **Prime Directive gate** — hard code, not a guideline; no claim reaches the substrate without a named filed primary source
- **Substrate** — immutable JSONL claims store; every assertion traceable to an audit log entry

The point is that the architecture is the moat, not the individual book. The same pipeline that produced a 643-page primary-source investigation can write a sports memoir and a piece of literary fiction. The substrate compounds. The books are the output. The pipeline is the product.

---

*BOTWAVE PAPERWORK — All rights reserved — © 2026 Kyle Jimenez*
