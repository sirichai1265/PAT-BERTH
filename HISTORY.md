# PAT Berth Window — Daily History

Running log of each day's ship movement sheet. Each dated folder contains the source PDF
and a snapshot of `pat_berth.html` as published that day. The live dashboard's day picker
(dropdown + ‹ › buttons) lets you browse these same three days interactively.

## Vessel continuity across sheets

Tracks every vessel that appeared on any of the three sheets so far, across berths and days.
"→ 20X" marks a berth reassignment from the previous sheet; "sailed" means it no longer
appears on the next day's sheet.

| Vessel | 28 Sep | 29 Sep | 30 Sep |
|---|---|---|---|
| INFINITY | alongside · 20AB | alongside · 20AB (ETD 29/15) | sailed |
| SKY CHALLENGE | expected · 20AB | alongside · 20AB | alongside · 20AB |
| KMTC GWANGYANG | alongside · 20B | sailed (29/05) | — |
| MILLENNIUM BRIGHT | at anchorage · 20B | alongside · 20B | sailed (30/04) |
| BANGKOK | alongside · 20D | alongside · 20D | sailed (29/14) |
| TS CHIBA | alongside · 20E | sailed (29/04) | — |
| HOPE C | expected · 20E | alongside · **→ 20F** | alongside · 20F |
| JARU BHUM | alongside · 20F (7B) | sailed (29/04) | — |
| MITRA BHUM | expected · 20F | alongside · **→ 20E** | alongside · 20E |
| CAPE FAWLEY | expected · 20AB | expected · **→ 20C** | alongside · **→ 20AB** |
| M ODYSSEY | expected · 20B (4A) | alongside · 20B | alongside · 20B |
| KHARIS HERITAGE | — | expected · 20AB | alongside · **→ 20B** (marked) |
| ALS SUMIRE | — | expected · 20F (1C) | alongside · **→ 20D** (marked, 1C) |
| KMTC BANGKOK | — | — | expected · 20AB (new) |
| WAN HAI 278 | — | — | expected · 20F (new) |

Notable reassignments: HOPE C and MITRA BHUM swapped their originally-planned berths (20E/20F)
once actually scheduled; CAPE FAWLEY was provisionally booked at 20C then moved to 20AB once
20C's closure was confirmed; KHARIS HERITAGE and ALS SUMIRE both moved berths between their
first appearance and their actual berthing day.

## Berth closures & gate stoppages (as announced, by sheet date)

| Berth/Gate | First announced | Period (as of latest sheet) | Status |
|---|---|---|---|
| 20AB / G.29 | 29 Sep sheet | 29–30 Sep 2026 | spreader repair, gate only |
| 20C | 29 Sep sheet | closed until **3 Oct** (was 1 Oct on the 29 Sep sheet) | full berth closure |
| 20D | 29 Sep sheet | **3–24 Oct** (was 1–21 Oct on the 29 Sep sheet) | full berth closure, electric channel |
| 20E / G.25 | 29 Sep sheet | **3–18 Oct** (was 1–15 Oct on the 29 Sep sheet) | trolley rail, gate only |

Both the 20D closure and the 20E gate stoppage slipped by two days between the 29 Sep and
30 Sep sheets — worth watching on the next sheet to see if they slip again.

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

---
**Process for the next sheet:** add a dated folder with the source PDF and a copy of
`pat_berth.html`; add a new dataset entry to `DATASETS`/`DAY_ORDER` in the live
`pat_berth.html`/`index.html`; update the vessel continuity table above (carry forward
each vessel still on the sheet, mark newly-sailed vessels, flag any berth reassignment
or slipped closure date); then append a new per-day snapshot section.
