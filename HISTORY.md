# PAT Berth Window — Daily History

Running log of each day's ship movement sheet. Each dated folder contains the source PDF
and a snapshot of `pat_berth.html` as published that day. The live dashboard's day picker
(dropdown + ‹ › buttons) lets you browse these same days interactively.

## Vessel continuity across sheets

Tracks every vessel that appeared on any of the three sheets so far, across berths and days.
"→ 20X" marks a berth reassignment from the previous sheet; "sailed" means it no longer
appears on the next day's sheet.

| Vessel | 28 Sep | 29 Sep | 30 Sep | 01 Oct | 02 Oct | 03 Oct |
|---|---|---|---|---|---|---|
| INFINITY | alongside · 20AB | alongside · 20AB (ETD 29/15) | sailed | — | — | — |
| SKY CHALLENGE | expected · 20AB | alongside · 20AB | alongside · 20AB | sailed (01/04) | — | — |
| KMTC GWANGYANG | alongside · 20B | sailed (29/05) | — | — | — | — |
| MILLENNIUM BRIGHT | at anchorage · 20B | alongside · 20B | sailed (30/04) | — | — | — |
| BANGKOK | alongside · 20D | alongside · 20D | sailed (29/14) | — | — | — |
| TS CHIBA | alongside · 20E | sailed (29/04) | — | — | — | — |
| HOPE C | expected · 20E | alongside · **→ 20F** | alongside · 20F | sailed (30/16) | — | — |
| JARU BHUM | alongside · 20F (7B) | sailed (29/04) | — | — | — | — |
| MITRA BHUM | expected · 20F | alongside · **→ 20E** | alongside · 20E | sailed (30/18) | — | — |
| CAPE FAWLEY | expected · 20AB | expected · **→ 20C** | alongside · **→ 20AB** | alongside · 20AB | alongside · 20AB (ETD now 02/15, was 02/06) | sailed (02/15) |
| M ODYSSEY | expected · 20B (4A) | alongside · 20B | alongside · 20B | sailed (01/05) | — | — |
| KHARIS HERITAGE | — | expected · 20AB | alongside · **→ 20B** (marked) | alongside · 20B (marked) | alongside · 20B (marked) | sailed (02/17) |
| ALS SUMIRE | — | expected · 20F (1C) | alongside · **→ 20D** (marked, 1C) | expected · 20D (marked, 1C) | alongside · 20D (marked, 1C) | sailed (02/17) |
| KMTC BANGKOK | — | — | expected · 20AB (new) | expected · 20AB | alongside · **→ 20F** | alongside · 20F (D&T 02/11) |
| WAN HAI 278 | — | — | expected · 20F (new) | expected · 20F | expected · 20E (**→ 20E**, ETA/P.B pushed later) | at anchorage · 20E (ETA 02/22, P.B 03/10) |
| ZHONG GU BEI HAI | — | — | — | expected · 20B (new) | expected · **→ 20AB** | expected · 20AB (marked, P.B slipped 04/11→04/15) |
| YM IMPROVEMENT | — | — | — | expected · 20C (new) | expected · **→ 20B** | expected · 20B (P.B slipped 03/20→04/10) |
| RESURGENCE | — | — | — | expected · 20E (new) | expected · **→ 20AB** (ETA/P.B pulled earlier) | expected · 20AB (ETD now 04/17) |
| JOSCO LUCKY | — | — | — | — | expected · 20B (new) | expected · **→ 20B** (back from 20AB) |
| SAWASDEE DENEB | — | — | — | — | expected · 20C (new, first since reopening) | expected · 20C |
| HARI BHUM (Barge) | — | — | — | — | expected · 20D (new, barge) | alongside · 20D (D&T 03/07) |
| XIN MING ZHOU 98 | — | — | — | — | expected · 20F (new) | expected · 20F |
| SAWASDEE SPICA | — | — | — | — | — | feeder sheet only · 20B (not on berthing sheet) |

Notable reassignments: HOPE C and MITRA BHUM swapped their originally-planned berths (20E/20F)
once actually scheduled; CAPE FAWLEY was provisionally booked at 20C then moved to 20AB once
20C's closure was confirmed; KHARIS HERITAGE and ALS SUMIRE both moved berths between their
first appearance and their actual berthing day. On 01 Oct, ALS SUMIRE's status read back to
"expected" from "alongside" — its P.B (01/17) is still a few hours ahead of that sheet's
snapshot time (01/12), which is expected, not a data error. On 02 Oct, four vessels moved
berths at once (KMTC BANGKOK → 20F, ZHONG GU BEI HAI → 20AB, YM IMPROVEMENT → 20B,
RESURGENCE → 20AB) — 20C's reopening slipped to 5 Oct, so vessels originally slotted there or
near it kept getting reshuffled across 20AB/20B/20C right up to the day each one plans to berth.

## Berth closures & gate stoppages (as announced, by sheet date)

| Berth/Gate | First announced | Period (as of latest sheet) | Status |
|---|---|---|---|
| 20AB / G.29 | 29 Sep sheet | 29–30 Sep 2026 (ended) | spreader repair, gate only |
| 20C | 29 Sep sheet | closed until **5 Oct** (was 1 Oct → 3 Oct → 5 Oct) | full berth closure |
| 20D | 29 Sep sheet | **4–24 Oct** (was 1–21 Oct → 3–24 Oct → 4–24 Oct) | full berth closure, electric channel |
| 20E / G.25 | 29 Sep sheet | **5–18 Oct** (was 1→3→5 Oct start on earlier sheets) | trolley rail, gate only |

The 20D closure and the 20E gate stoppage both slipped by two days between the 29 Sep and
30 Sep sheets, then held steady through the 01 Oct sheet. On the 02 Oct sheet, 20D's start
slipped one more day (3 Oct → 4 Oct) and 20E / G.25's start slipped two more days (3 Oct →
5 Oct) — both keep slipping, worth checking again on every new sheet. The 20AB / G.29
stoppage is no longer listed (its 29–30 Sep window has passed). **20C's reopening itself
slipped from 3 Oct to 5 Oct** on the 02 Oct sheet — YM IMPROVEMENT, originally booked as its
first vessel, was reassigned to 20B instead, and SAWASDEE DENEB (new) is now the vessel
booked into 20C once it reopens.

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

### 02-10-2026
- **20AB**: CAPE FAWLEY (ETD pushed 02/06→02/15), RESURGENCE (**← moved from 20E**), ZHONG GU BEI HAI (**← moved from 20B**)
- **20B**: KHARIS HERITAGE (marked), YM IMPROVEMENT (**← moved from 20C**), JOSCO LUCKY (new)
- **20C**: empty — reopening slipped **1 Oct → 3 Oct → 5 Oct**; SAWASDEE DENEB (new) now booked in once it reopens
- **20D**: ALS SUMIRE (1C, marked), HARI BHUM (Barge, new) — closure start slipped to **4 Oct** (now 4–24 Oct)
- **20E**: empty — WAN HAI 278 moved out to 20F; G.25 stoppage start slipped to **5 Oct** (now 5–18 Oct)
- **20F**: KMTC BANGKOK (**← moved from 20AB**), XIN MING ZHOU 98 (new)
- Window extended to 27 Sep – 08 Oct to fit JOSCO LUCKY's ETD (07/13)
- Four vessels reassigned berths in a single day (see continuity table) as the 20C reopening keeps slipping
- Folder: [`02-10-2026/`](02-10-2026)

### 03-10-2026
Two sheets exist for this date. The berthing-section sheet (ETA / P.B / ETD for container ships plus
berth notices) is used as the source of truth; the feeder sheet (LOA / FEEDER NAME) is archived alongside it.
- **20AB**: RESURGENCE (ETD 04/12→04/17), ZHONG GU BEI HAI (P.B slipped 04/11→04/15)
- **20B**: YM IMPROVEMENT (P.B slipped 03/20→04/10), JOSCO LUCKY (back at 20B; feeder sheet had put it at 20AB)
- **20C**: SAWASDEE DENEB — reopening still **5 Oct**; new notice: cable splicing 4 Oct 09:00–12:00 (20C and 20D)
- **20D**: HARI BHUM (Barge, D&T 03/07) — closure now **4–25 Oct** (end moved 24→25 Oct)
- **20E**: WAN HAI 278 at anchorage since 02/22, P.B 03/10 — G.25 stops from **5 Oct 12:00** (end date cut off on this sheet; daily sheet says 18 Oct)
- **20F**: KMTC BANGKOK (alongside since 02/11, sails 03/17), XIN MING ZHOU 98
- Sailed since previous sheet: CAPE FAWLEY (02/15), KHARIS HERITAGE (02/17), ALS SUMIRE (02/17)
- Not on the berthing sheet: SAWASDEE SPICA (listed on the feeder sheet only)
- Other terminals on this sheet, not shown on the dashboard: MTT SANDAKAN (4A), KMTC PUSAN (2F)
- Folder: [`03-10-2026/`](03-10-2026)

---
**Process for the next sheet:** add a dated folder with the source PDF and a copy of
`pat_berth.html`; add a new dataset entry to `DATASETS`/`DAY_ORDER` in the live
`pat_berth.html`/`index.html`; update the vessel continuity table above (carry forward
each vessel still on the sheet, mark newly-sailed vessels, flag any berth reassignment
or slipped closure date); then append a new per-day snapshot section; rebuild
`PAT_Berth_Window.xlsx` at the repo root with the new day's data and copy it into every
dated folder (including the new one) so each day's archive carries the latest summary.
