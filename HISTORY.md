# PAT Berth Window — Daily History

Running log of each day's ship movement sheet. Each dated folder contains the source PDF
and a snapshot of `pat_berth.html` as published that day. The live dashboard's day picker
(dropdown + ‹ › buttons) lets you browse these same days interactively.

## Vessel continuity across sheets

Tracks every vessel that appeared on any of the three sheets so far, across berths and days.
"→ 20X" marks a berth reassignment from the previous sheet; "sailed" means it no longer
appears on the next day's sheet.

| Vessel | 28 Sep | 29 Sep | 30 Sep | 01 Oct |
|---|---|---|---|---|
| INFINITY | alongside · 20AB | alongside · 20AB (ETD 29/15) | sailed | — |
| SKY CHALLENGE | expected · 20AB | alongside · 20AB | alongside · 20AB | sailed (01/04) |
| KMTC GWANGYANG | alongside · 20B | sailed (29/05) | — | — |
| MILLENNIUM BRIGHT | at anchorage · 20B | alongside · 20B | sailed (30/04) | — |
| BANGKOK | alongside · 20D | alongside · 20D | sailed (29/14) | — |
| TS CHIBA | alongside · 20E | sailed (29/04) | — | — |
| HOPE C | expected · 20E | alongside · **→ 20F** | alongside · 20F | sailed (30/16) |
| JARU BHUM | alongside · 20F (7B) | sailed (29/04) | — | — |
| MITRA BHUM | expected · 20F | alongside · **→ 20E** | alongside · 20E | sailed (30/18) |
| CAPE FAWLEY | expected · 20AB | expected · **→ 20C** | alongside · **→ 20AB** | alongside · 20AB |
| M ODYSSEY | expected · 20B (4A) | alongside · 20B | alongside · 20B | sailed (01/05) |
| KHARIS HERITAGE | — | expected · 20AB | alongside · **→ 20B** (marked) | alongside · 20B (marked) |
| ALS SUMIRE | — | expected · 20F (1C) | alongside · **→ 20D** (marked, 1C) | expected · 20D (marked, 1C) |
| KMTC BANGKOK | — | — | expected · 20AB (new) | expected · 20AB |
| WAN HAI 278 | — | — | expected · 20F (new) | expected · 20F |
| ZHONG GU BEI HAI | — | — | — | expected · 20B (new) |
| YM IMPROVEMENT | — | — | — | expected · **20C** (new, first vessel since reopening) |
| RESURGENCE | — | — | — | expected · 20E (new) |

Notable reassignments: HOPE C and MITRA BHUM swapped their originally-planned berths (20E/20F)
once actually scheduled; CAPE FAWLEY was provisionally booked at 20C then moved to 20AB once
20C's closure was confirmed; KHARIS HERITAGE and ALS SUMIRE both moved berths between their
first appearance and their actual berthing day. On 01 Oct, ALS SUMIRE's status read back to
"expected" from "alongside" — its P.B (01/17) is still a few hours ahead of that sheet's
snapshot time (01/12), which is expected, not a data error.

## Berth closures & gate stoppages (as announced, by sheet date)

| Berth/Gate | First announced | Period (as of latest sheet) | Status |
|---|---|---|---|
| 20AB / G.29 | 29 Sep sheet | 29–30 Sep 2026 | spreader repair, gate only |
| 20C | 29 Sep sheet | closed until **3 Oct** (was 1 Oct on the 29 Sep sheet) | full berth closure |
| 20D | 29 Sep sheet | **3–24 Oct** (was 1–21 Oct on the 29 Sep sheet) | full berth closure, electric channel |
| 20E / G.25 | 29 Sep sheet | **3–18 Oct** (was 1–15 Oct on the 29 Sep sheet) | trolley rail, gate only |

Both the 20D closure and the 20E gate stoppage slipped by two days between the 29 Sep and
30 Sep sheets, then held steady (3–24 Oct / 3–18 Oct) on the 01 Oct sheet — no further
slippage so far. The 20AB / G.29 stoppage is no longer listed on the 01 Oct sheet (its
29–30 Sep window has passed). 20C reopened as announced: YM IMPROVEMENT is its first
booked vessel, berthing 03/20 — just after the 3 Oct opening.

## Per-day snapshots

### 28-09-2026
- **20AB**: INFINITY, SKY CHALLENGE
- **20B**: KMTC GWANGYANG, MILLENNIUM BRIGHT
- **20C**: closed (per sheet)
- **20D**: BANGKOK
- **20E**: TS CHIBA, HOPE C
- **20F**: JARU BHUM (7B), MITRA BHUM
- Folder: [`28-09-2026/`](28-09-2026)

### 29-09-2026
- **20AB**: INFINITY, SKY CHALLENGE, KHARIS HERITAGE — G.29 stopped (spreader repair) 29–30 Sep
- **20B**: MILLENNIUM BRIGHT, M ODYSSEY (4A)
- **20C**: closed until 1 Oct; CAPE FAWLEY booked in after
- **20D**: BANGKOK — closure 1–21 Oct announced (electric channel)
- **20E**: MITRA BHUM — G.25 stoppage 1–15 Oct announced (trolley rail)
- **20F**: HOPE C, ALS SUMIRE (1C)
- Folder: [`29-09-2026/`](29-09-2026)

### 30-09-2026
- **20AB**: SKY CHALLENGE, CAPE FAWLEY, KMTC BANGKOK — G.29 stoppage continues (spreader repair)
- **20B**: M ODYSSEY (4A), KHARIS HERITAGE (marked)
- **20C**: empty, closed until **3 Oct** (date slipped from 1 Oct)
- **20D**: ALS SUMIRE (1C, marked) — closure now **3–24 Oct** (slipped from 1–21 Oct)
- **20E**: MITRA BHUM — G.25 stoppage now **3–18 Oct** (slipped from 1–15 Oct)
- **20F**: HOPE C, WAN HAI 278
- Window extended to 27 Sep – 04 Oct to fit later ETDs (KMTC BANGKOK, WAN HAI 278)
- Folder: [`30-09-2026/`](30-09-2026)

### 01-10-2026
- **20AB**: CAPE FAWLEY, KMTC BANGKOK — G.29 stoppage no longer listed (29–30 Sep window passed)
- **20B**: KHARIS HERITAGE (marked), ZHONG GU BEI HAI (new)
- **20C**: reopened — YM IMPROVEMENT (new, first vessel since the 3 Oct reopening)
- **20D**: ALS SUMIRE (1C, marked) — closure holds at 3–24 Oct (no further slip)
- **20E**: RESURGENCE (new) — G.25 stoppage holds at 3–18 Oct (no further slip)
- **20F**: WAN HAI 278
- Window extended to 27 Sep – 06 Oct to fit ZHONG GU BEI HAI's ETD (05/16)
- Folder: [`01-10-2026/`](01-10-2026)

---
**Process for the next sheet:** add a dated folder with the source PDF and a copy of
`pat_berth.html`; add a new dataset entry to `DATASETS`/`DAY_ORDER` in the live
`pat_berth.html`/`index.html`; update the vessel continuity table above (carry forward
each vessel still on the sheet, mark newly-sailed vessels, flag any berth reassignment
or slipped closure date); then append a new per-day snapshot section.
