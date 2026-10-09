# PAT Berth Window — Daily History

Running log of each day's ship movement sheet. Each dated folder contains the source PDF
and a snapshot of `pat_berth.html` as published that day. The live dashboard's day picker
(dropdown + ‹ › buttons) lets you browse these same days interactively.

## Vessel continuity across sheets

Tracks every vessel that appeared on any of the three sheets so far, across berths and days.
"→ 20X" marks a berth reassignment from the previous sheet; "sailed" means it no longer
appears on the next day's sheet.

| Vessel | 28 Sep | 29 Sep | 30 Sep | 01 Oct | 02 Oct | 03 Oct | 04 Oct | 05 Oct | 06 Oct | 07 Oct | 08 Oct | 09 Oct |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| INFINITY | alongside · 20AB | alongside · 20AB (ETD 29/15) | sailed | — | — | — | — | — | — | — | — | — |
| SKY CHALLENGE | expected · 20AB | alongside · 20AB | alongside · 20AB | sailed (01/04) | — | — | — | — | — | — | — | — |
| KMTC GWANGYANG | alongside · 20B | sailed (29/05) | — | — | — | — | — | — | — | — | — | — |
| MILLENNIUM BRIGHT | at anchorage · 20B | alongside · 20B | sailed (30/04) | — | — | — | — | — | — | — | — | — |
| BANGKOK | alongside · 20D | alongside · 20D | sailed (29/14) | — | — | — | — | — | — | — | — | — |
| TS CHIBA | alongside · 20E | sailed (29/04) | — | — | — | — | — | — | — | — | — | — |
| HOPE C | expected · 20E | alongside · **→ 20F** | alongside · 20F | sailed (30/16) | — | — | — | — | — | — | — | — |
| JARU BHUM | alongside · 20F (7B) | sailed (29/04) | — | — | — | — | — | — | — | — | — | — |
| MITRA BHUM | expected · 20F | alongside · **→ 20E** | alongside · 20E | sailed (30/18) | — | — | — | — | — | — | — | — |
| CAPE FAWLEY | expected · 20AB | expected · **→ 20C** | alongside · **→ 20AB** | alongside · 20AB | alongside · 20AB (ETD now 02/15, was 02/06) | sailed (02/15) | — | — | — | — | — | — |
| M ODYSSEY | expected · 20B (4A) | alongside · 20B | alongside · 20B | sailed (01/05) | — | — | — | — | — | — | — | — |
| KHARIS HERITAGE | — | expected · 20AB | alongside · **→ 20B** (marked) | alongside · 20B (marked) | alongside · 20B (marked) | sailed (02/17) | — | — | — | — | — | — |
| ALS SUMIRE | — | expected · 20F (1C) | alongside · **→ 20D** (marked, 1C) | expected · 20D (marked, 1C) | alongside · 20D (marked, 1C) | sailed (02/17) | — | — | — | — | — | expected · **→ 20C** (returns for a new call, ETA 12/18, shift 1C) |
| KMTC BANGKOK | — | — | expected · 20AB (new) | expected · 20AB | alongside · **→ 20F** | alongside · 20F (D&T 02/11) | sailed (03/17) | — | — | — | — | — |
| WAN HAI 278 | — | — | expected · 20F (new) | expected · 20F | expected · 20E (**→ 20E**, ETA/P.B pushed later) | at anchorage · 20E (ETA 02/22, P.B 03/10) | alongside · 20E (P.B 03/10) | alongside · 20E (ETD 05/11) | sailed (05/11) | — | — | — |
| ZHONG GU BEI HAI | — | — | — | expected · 20B (new) | expected · **→ 20AB** | expected · 20AB (marked, P.B slipped 04/11→04/15) | at anchorage · 20AB (ETA 04/09, P.B 04/15) | alongside · 20AB (ETD slipped 06/10→06/11) | alongside · 20AB (ETD 06/11) | sailed (06/11) | — | — |
| YM IMPROVEMENT | — | — | — | expected · 20C (new) | expected · **→ 20B** | expected · 20B (P.B slipped 03/20→04/10) | alongside · 20B (P.B 04/10) | alongside · 20B (ETD 05/12) | sailed (05/12) | — | — | — |
| RESURGENCE | — | — | — | expected · 20E (new) | expected · **→ 20AB** (ETA/P.B pulled earlier) | expected · 20AB (ETD now 04/17) | alongside · 20AB (ETD 04/17) | sailed (04/17) | — | — | — | — |
| JOSCO LUCKY | — | — | — | — | expected · 20B (new) | expected · **→ 20B** (back from 20AB) | expected · **→ 20AB** (flip-flopped back) | expected · **→ 20D** (P.B 06/18) | expected · **→ 20C** (P.B 07/13) | at anchorage · 20C (P.B 07/13, ETD 08/12→08/13) | alongside · 20C (ETD 08/13) | sailed (08/13) |
| SAWASDEE DENEB | — | — | — | — | expected · 20C (new, first since reopening) | expected · 20C | expected · 20C | at anchorage · 20C (P.B 05/12) | alongside · 20C (ETD 07/12→07/11) | alongside · 20C (ETD 07/11) | sailed (07/11) | — |
| HARI BHUM (Barge) | — | — | — | — | expected · 20D (new, barge) | alongside · 20D (D&T 03/07) | sailed (03/16) | — | — | — | — | — |
| XIN MING ZHOU 98 | — | — | — | — | expected · 20F (new) | expected · 20F | alongside · 20F (P.B 04/09) | sailed (05/09) | — | — | — | — |
| SAWASDEE SPICA | — | — | — | — | — | feeder sheet only · 20B (not on berthing sheet) | expected · 20B (P.B 06/13, ETD 08/13) | expected · 20B | expected · 20B (P.B 06/13) | alongside · 20B (ETD 08/13) | alongside · 20B (ETD 08/13) | sailed (08/13) |
| KMTC TOKYO | — | — | — | — | — | — | expected · 20F (new) | expected · **→ 20AB** (ETA 06/13) | expected · 20AB (P.B 06/13) | alongside · 20AB (ETD 08/12) | alongside · 20AB (ETD 08/12) | sailed (08/12) |
| GREEN PARK | — | — | — | — | — | — | — | expected · 20AB (new, marked) | expected · **→ 20B** | expected · **→ 20AB** (P.B 08/15→08/13) | at anchorage · 20AB (ETA 07/11→07/10, P.B 08/13) | alongside · 20AB (P.B 08/13→08/14, ETD 09/14→09/16) |
| SAWASDEE ATLANTIC | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C (P.B 08/15→09/15, ETD 10/13→11/03) | expected · **→ 20D** | at anchorage · **→ 20F** (ETA 07/22→07/20) | at anchorage · 20F (P.B 09/15) |
| MTT BANGKOK | — | — | — | — | — | — | — | expected · 20D (new, marked) | expected · 20D (P.B 07/17→07/14) | expected · 20D (ETA 07/12) | alongside · 20D (ETD 09/13→09/02) | sailed (09/02) |
| XIN AN | — | — | — | — | — | — | — | expected · 20F (new, marked) | expected · 20F (P.B 07/17→07/14) | expected · 20F (ETA 07/13) | alongside · 20F (ETD 09/13) | alongside · 20F (ETD 09/13) |
| SITC HOCHIMINH | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · **→ 20B** (ETA 07/19→07/18) | at anchorage · 20B (ETA 07/18→07/15) | alongside · 20B (ETD 09/17) |
| YM INCEPTION | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · **→ 20C** (P.B 09/15→09/13, ETD 10/16→11/01) | expected · 20C | at anchorage · 20C (ETD 11/01→10/16) |
| HE JIN | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · **→ 20AB** | at anchorage · **→ 22A** (shifts to 20D 09/02, ETD 10/13) | alongside · 20D (shifted in from 22A, P.B 09/02→08/24) |
| ZHONG GU DONG HAI | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C (ETA 07/16→07/13) | at anchorage · 20C (ETA 07/13→07/14) | alongside · 20C (ETD 09/14) |
| KANWAY FORTUNE | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · **→ 20F** (P.B 09/15→09/14, ETD 11/03→10/15) | expected · **→ 20AB** | at anchorage · 20AB (ETA 08/18→08/16) |
| CNC MARS | — | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · 20AB (ETA 09/10→09/22, ETD 12/04→11/15) | expected · 20AB |
| INDURO | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · 20B (P.B 09/15→09/16, ETD 11/03→11/14) | at anchorage · 20B (ETA 09/09→09/06) |
| CUL HAIPHONG | — | — | — | — | — | — | — | — | — | expected · 20B (new, shift 4A) | expected · **→ 20D** (shift 4A, ETA 09/20) | expected · 20D (ETA 09/20) |
| XIN MING ZHOU 102 | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · 20F (ETA 09/13→10/21, ETD 11/03→12/02) | expected · 20F |
| STARSHIP AQUILA | — | — | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C (P.B 11/04→10/16, ETD 12/13→12/05) |
| INCEDA | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · 20D |
| SAMAL | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB (new) |
| JOSCO SHINE | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) |
| KMTC TAIPEIS | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) |
| SAWASDEE SUNRISE | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) |

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

### 04-10-2026
- **20AB**: RESURGENCE (alongside, ETD 04/17), ZHONG GU BEI HAI (at anchorage, P.B 04/15), JOSCO LUCKY (**back at 20AB** after being listed at 20B on the 03 Oct berthing sheet)
- **20B**: YM IMPROVEMENT (alongside since 04/10), SAWASDEE SPICA (back on the sheet; P.B 06/13, ETD 08/13)
- **20C**: SAWASDEE DENEB — reopening still **5 Oct** (sheet prints 2027, treated as a typo)
- **20D**: empty — closure shown as **4–24 Oct** (the 03 Oct berthing sheet said 4–25)
- **20E**: WAN HAI 278 (alongside since 03/10) — G.25 stoppage **5–18 Oct** unchanged
- **20F**: XIN MING ZHOU 98 (alongside), KMTC TOKYO (new, ETA/P.B 06/14)
- Sailed since previous sheet: HARI BHUM (03/16), KMTC BANGKOK (03/17)
- Folder: [`04-10-2026/`](04-10-2026)

### 05-10-2026
- **20AB**: ZHONG GU BEI HAI (alongside, ETD slipped 06/10→06/11), KMTC TOKYO (**← moved from 20F**), GREEN PARK (new, marked)
- **20B**: YM IMPROVEMENT (sails 05/12), SAWASDEE SPICA
- **20C**: SAWASDEE DENEB (at anchorage, P.B 05/12), SAWASDEE ATLANTIC (new) — no reopening notice any more, the wharf is open as announced
- **20D**: JOSCO LUCKY (**← moved from 20AB**, P.B 06/18), MTT BANGKOK (new, marked) — closure still printed as **4–24 Oct**, yet vessels are booked from 6 Oct; to be confirmed
- **20E**: WAN HAI 278 (sails 05/11) — G.25 stoppage **5–18 Oct** unchanged
- **20F**: XIN AN (new, marked)
- New berth rows on the sheet: 22F, 20G (both empty)
- Sailed since previous sheet: RESURGENCE (04/17), XIN MING ZHOU 98 (05/09)
- Window extended to 27 Sep – 11 Oct to fit SAWASDEE ATLANTIC's ETD (10/13)
- Folder: [`05-10-2026/`](05-10-2026)

### 06-10-2026
- **20AB**: ZHONG GU BEI HAI (alongside, sails 06/11), KMTC TOKYO (P.B 06/13), SITC HOCHIMINH and YM INCEPTION (new)
- **20B**: SAWASDEE SPICA, GREEN PARK (**← moved from 20AB**), HE JIN (new)
- **20C**: SAWASDEE DENEB (alongside, ETD 07/12→07/11), JOSCO LUCKY (**← moved from 20D**), ZHONG GU DONG HAI (new), SAWASDEE ATLANTIC (P.B pushed 08/15→09/15, ETD 10/13→11/03)
- **20D**: MTT BANGKOK (P.B 07/17→07/14), KANWAY FORTUNE (new) — closure still printed as **4–24 Oct**, yet vessels are booked from 7 Oct; still to be confirmed
- **20E**: empty (WAN HAI 278 sailed 05/11) — G.25 stoppage **5–18 Oct** in progress
- **20F**: XIN AN (P.B 07/17→07/14)
- Sailed since previous sheet: YM IMPROVEMENT (05/12), WAN HAI 278 (05/11)
- Five new vessels appear on this sheet, and most of the 20C/20D bookings moved by a few hours
- Folder: [`06-10-2026/`](06-10-2026)

### 07-10-2026
- **20AB**: KMTC TOKYO (alongside), GREEN PARK (**← back from 20B**, P.B 08/15→08/13), HE JIN (**← moved from 20B**), CNC MARS (new, ETD 12/04)
- **20B**: SAWASDEE SPICA (alongside), SITC HOCHIMINH (**← moved from 20AB**), INDURO (new), CUL HAIPHONG (new, shift 4A, ETD 12/05)
- **20C**: SAWASDEE DENEB (alongside, sails 07/11), JOSCO LUCKY (at anchorage, P.B 07/13), ZHONG GU DONG HAI (ETA 07/16→07/13), YM INCEPTION (**← moved from 20AB**, P.B 09/15→09/13, ETD 10/16→11/01)
- **20D**: MTT BANGKOK, SAWASDEE ATLANTIC (**← moved from 20C**) — closure still printed as **4–24 Oct**, yet vessels are booked from 7 Oct; still to be confirmed
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: XIN AN, KANWAY FORTUNE (**← moved from 20D**, P.B 09/15→09/14, ETD 11/03→10/15), XIN MING ZHOU 102 (new)
- Sailed since previous sheet: ZHONG GU BEI HAI (06/11)
- Six vessels changed berth this day; 4 new vessels appear
- Window extended to 27 Sep – 13 Oct to fit CNC MARS (ETD 12/04) and CUL HAIPHONG (ETD 12/05)
- Folder: [`07-10-2026/`](07-10-2026)

### 08-10-2026
- **20AB**: KMTC TOKYO (alongside, sails 08/12), GREEN PARK (at anchorage), KANWAY FORTUNE (**← moved from 20F**), CNC MARS (ETA 09/10→09/22, ETD 12/04→11/15)
- **20B**: SAWASDEE SPICA (alongside), SITC HOCHIMINH (at anchorage, ETA 07/18→07/15), INDURO (P.B 09/15→09/16, ETD 11/03→11/14)
- **20C**: JOSCO LUCKY (alongside), ZHONG GU DONG HAI (at anchorage), YM INCEPTION, STARSHIP AQUILA (new)
- **20D**: MTT BANGKOK (alongside since 07/14, ETD 09/13→09/02), HE JIN (shifts in from 22A on 09/02), CUL HAIPHONG (**← moved from 20B**, shift 4A), INCEDA (new) — closure still printed as **4–24 Oct**, although MTT BANGKOK is already alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: XIN AN (alongside), SAWASDEE ATLANTIC (**← moved from 20D**, ETA 07/22→07/20), XIN MING ZHOU 102 (ETA 09/13→10/21, ETD 11/03→12/02)
- **22A**: HE JIN waits here (ETA 07/19, P.B 08/16, ETD 09/02) before shifting to 20D
- Sailed since previous sheet: SAWASDEE DENEB (07/11)
- Two new vessels (STARSHIP AQUILA, INCEDA); the first time a vessel is listed on a 22x berth
- Folder: [`08-10-2026/`](08-10-2026)

### 09-10-2026
- **20AB**: GREEN PARK (alongside, P.B 08/13→08/14, ETD 09/14→09/16), KANWAY FORTUNE (at anchorage, ETA 08/18→08/16), CNC MARS, SAMAL (new, ETD 13/14)
- **20B**: SITC HOCHIMINH (alongside), INDURO (at anchorage, ETA 09/09→09/06), JOSCO SHINE (new)
- **20C**: ZHONG GU DONG HAI (alongside), YM INCEPTION (ETD 11/01→10/16), STARSHIP AQUILA (P.B 11/04→10/16, ETD 12/13→12/05), **ALS SUMIRE returns** for a new call (ETA 12/18, ETD 14/05, shift 1C)
- **20D**: HE JIN (**shifted in from 22A**, P.B 09/02→08/24), CUL HAIPHONG, INCEDA, KMTC TAIPEIS (new, ETD 14/15) — closure still printed as **4–24 Oct**, yet HE JIN is already alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: XIN AN (alongside), SAWASDEE ATLANTIC (at anchorage), XIN MING ZHOU 102, SAWASDEE SUNRISE (new)
- **22A**: empty again (HE JIN completed its shift to 20D)
- Sailed since previous sheet: KMTC TOKYO (08/12), SAWASDEE SPICA (08/13), JOSCO LUCKY (08/13), MTT BANGKOK (09/02)
- Four new vessels; window extended to 27 Sep – 15 Oct to fit KMTC TAIPEIS (ETD 14/15) and ALS SUMIRE (ETD 14/05)
- Folder: [`09-10-2026/`](09-10-2026)

---
**Process for the next sheet:** add a dated folder with the source PDF and a copy of
`pat_berth.html`; add a new dataset entry to `DATASETS`/`DAY_ORDER` in the live
`pat_berth.html`/`index.html`; update the vessel continuity table above (carry forward
each vessel still on the sheet, mark newly-sailed vessels, flag any berth reassignment
or slipped closure date); then append a new per-day snapshot section; rebuild
`PAT_Berth_Window.xlsx` at the repo root (cumulative: continuity, all-days notices log and one
sheet per day), then save a per-day copy into each dated folder containing only that day's sheet
(vessel list + that day's notices).
