# PAT Berth Window — Daily History

Running log of each day's ship movement sheet. Each dated folder contains the source PDF
and a snapshot of `pat_berth.html` as published that day. The live dashboard's day picker
(dropdown + ‹ › buttons) lets you browse these same days interactively.

## Vessel continuity across sheets

Tracks every vessel that appeared on any of the three sheets so far, across berths and days.
"→ 20X" marks a berth reassignment from the previous sheet; "sailed" means it no longer
appears on the next day's sheet.

| Vessel | 28 Sep | 29 Sep | 30 Sep | 01 Oct | 02 Oct | 03 Oct | 04 Oct | 05 Oct | 06 Oct | 07 Oct | 08 Oct | 09 Oct | 10 Oct | 11 Oct | 12 Oct | 13 Oct | 14 Oct | 15 Oct | 16 Oct | 17 Oct | 18 Oct | 19 Oct | 20 Oct | 21 Oct | 22 Oct | 23 Oct | 24 Oct | 25 Oct |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| INFINITY | alongside · 20AB | alongside · 20AB (ETD 29/15) | sailed | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20C** (returns for a new call, ETA 18/06) | expected · **→ 20D** (was 20C) | expected · 20D (ETA 18/06→17/24) | alongside · 20D (ETD 19/10→19/09) | sailed (19/09) | — | — | — | — | — | — |
| SKY CHALLENGE | expected · 20AB | alongside · 20AB | alongside · 20AB | sailed (01/04) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| KMTC GWANGYANG | alongside · 20B | sailed (29/05) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20B** (returns for a new call, ETA 22/13) | expected · **→ 20AB** (ETA 22/13→22/14) | expected · 20AB (ETA 22/14→22/13) | expected · 20AB | expected · 20AB (ETD 25/02→25/01) | sailed (25/01) |
| MILLENNIUM BRIGHT | at anchorage · 20B | alongside · 20B | sailed (30/04) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20C** (returns for a new call, ETA 19/14) | alongside · 20C (ETD 20/12) | sailed (20/12) | — | — | — | — |
| BANGKOK | alongside · 20D | alongside · 20D | sailed (29/14) | — | — | — | — | — | — | — | — | — | — | — | — | — | listed at 20B without times (returns, schedule TBA) | expected · **→ 20AB** (times now announced: ETA 16/21, P.B 17/09, ETD 18/16) | expected · 20AB | alongside · 20AB (actual ETA 16/15, P.B 17/09) | alongside · 20AB (ETD 18/16→19/08) | sailed (19/08) | — | — | — | — | — | — |
| TS CHIBA | alongside · 20E | sailed (29/04) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20C** (returns for a new call, ETA 17/02) | expected · **→ 20B** (ETA 17/02→16/14, P.B 17/08→16/14, ETD 18/07→17/12) | alongside · 20B (ETD 17/12→17/11) | sailed (17/11) | — | — | — | — | — | — | — |
| HOPE C | expected · 20E | alongside · **→ 20F** | alongside · 20F | sailed (30/16) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20AB** (returns for a new call, shift 4A, ETA 20/24) | expected · 20AB (shift 4A) | alongside · 20AB (marked, ETA 20/24→21/02, 4A) | sailed (21/22) | — | — | — |
| JARU BHUM | alongside · 20F (7B) | sailed (29/04) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20D** (returns for a new call, shift 7B, ETA 17/18) | expected · **→ 20B** (shift 7B, ETA/P.B 17/18→17/16) | expected · 20B (shift 7B) | alongside · 20B (ETD 18/11→18/10, 7B) | sailed (18/10) | — | — | — | — | — | — |
| MITRA BHUM | expected · 20F | alongside · **→ 20E** | alongside · 20E | sailed (30/18) | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20D** (returns for a new call, ETA 19/23) | expected · **→ 20AB** (was 20D) | no longer listed (dropped from the sheet) | expected · **→ 20C** (listed again; ETA 19/23→20/17, P.B 20/09→20/17, ETD 21/08→21/13) | expected · **→ 20B** (ETA/P.B 20/17→21/13, ETD 21/13→22/05) | expected · 20B | expected · 20B | sailed (22/05) | — | — | — |
| CAPE FAWLEY | expected · 20AB | expected · **→ 20C** | alongside · **→ 20AB** | alongside · 20AB | alongside · 20AB (ETD now 02/15, was 02/06) | sailed (02/15) | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20AB** (returns for a new call, ETA 19/18) | expected · **→ 20C** (was 20AB) | 20C row with only LOA 558 m printed (no name or times) | no longer listed (the unnamed LOA 558 m row is gone) | expected · **→ 20C** (listed again with times: ETA 21/11, P.B 21/12, ETD 23/12) | expected · 20C | expected · 20C | expected · 20C | expected · 20C | sailed (23/12) | — |
| M ODYSSEY | expected · 20B (4A) | alongside · 20B | alongside · 20B | sailed (01/05) | — | — | — | — | — | — | — | — | — | — | expected · **→ 20C** (returns for a new call, shift 4A) | expected · 20C (shift 4A no longer shown) | at anchorage · **→ 20B** (shift 4A, ETA 14/03→14/01, P.B 14/14→14/15) | sailed (15/05) | — | — | — | — | — | — | — | — | — | expected · 20C (new call: ETA 28/03, ETD 29/06) |
| KHARIS HERITAGE | — | expected · 20AB | alongside · **→ 20B** (marked) | alongside · 20B (marked) | alongside · 20B (marked) | sailed (02/17) | — | — | — | — | — | — | — | — | — | expected · **→ 20C** (returns for a new call, ETA 15/01) | expected · **→ 20B** | alongside · 20B (P.B 15/07→15/06) | sailed (16/07) | — | — | — | — | — | — | — | — | — |
| ALS SUMIRE | — | expected · 20F (1C) | alongside · **→ 20D** (marked, 1C) | expected · 20D (marked, 1C) | alongside · 20D (marked, 1C) | sailed (02/17) | — | — | — | — | — | expected · **→ 20C** (returns for a new call, ETA 12/18, shift 1C) | expected · **→ 20B** (marked, 1C; ETA 12/18→12/22, ETD 14/05→14/06) | expected · **→ 20F** (1C) | expected · 20F (1C) | alongside · 20F (P.B 13/06, ETD 14/06, 1C) | sailed (14/06) | — | — | — | — | expected · **→ 20E** (returns for another call, 1C, ETA 21/17) | expected · **→ 20AB** (1C; ETA 21/17→21/22, P.B 21/17→22/13, ETD 22/17→23/16) | expected · 20AB (1C) | expected · 20AB (1C) | expected · 20AB (1C) | sailed (23/16) | — |
| KMTC BANGKOK | — | — | expected · 20AB (new) | expected · 20AB | alongside · **→ 20F** | alongside · 20F (D&T 02/11) | sailed (03/17) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (ETA 25/02→25/06, P.B 25/04→25/06) | expected · 20D | expected · 20D (ETD 26/12→26/13) |
| WAN HAI 278 | — | — | expected · 20F (new) | expected · 20F | expected · 20E (**→ 20E**, ETA/P.B pushed later) | at anchorage · 20E (ETA 02/22, P.B 03/10) | alongside · 20E (P.B 03/10) | alongside · 20E (ETD 05/11) | sailed (05/11) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| ZHONG GU BEI HAI | — | — | — | expected · 20B (new) | expected · **→ 20AB** | expected · 20AB (marked, P.B slipped 04/11→04/15) | at anchorage · 20AB (ETA 04/09, P.B 04/15) | alongside · 20AB (ETD slipped 06/10→06/11) | alongside · 20AB (ETD 06/11) | sailed (06/11) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20B | expected · 20B (ETA 26/14→26/20, P.B 26/14→27/05, ETD 28/03→28/14) | expected · **→ 20C** (moved from 20B; ETA 26/20→26/15, P.B 27/05→26/15, ETD 28/14→28/03) |
| YM IMPROVEMENT | — | — | — | expected · 20C (new) | expected · **→ 20B** | expected · 20B (P.B slipped 03/20→04/10) | alongside · 20B (P.B 04/10) | alongside · 20B (ETD 05/12) | sailed (05/12) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| RESURGENCE | — | — | — | expected · 20E (new) | expected · **→ 20AB** (ETA/P.B pulled earlier) | expected · 20AB (ETD now 04/17) | alongside · 20AB (ETD 04/17) | sailed (04/17) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| JOSCO LUCKY | — | — | — | — | expected · 20B (new) | expected · **→ 20B** (back from 20AB) | expected · **→ 20AB** (flip-flopped back) | expected · **→ 20D** (P.B 06/18) | expected · **→ 20C** (P.B 07/13) | at anchorage · 20C (P.B 07/13, ETD 08/12→08/13) | alongside · 20C (ETD 08/13) | sailed (08/13) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| SAWASDEE DENEB | — | — | — | — | expected · 20C (new, first since reopening) | expected · 20C | expected · 20C | at anchorage · 20C (P.B 05/12) | alongside · 20C (ETD 07/12→07/11) | alongside · 20C (ETD 07/11) | sailed (07/11) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| HARI BHUM (Barge) | — | — | — | — | expected · 20D (new, barge) | alongside · 20D (D&T 03/07) | sailed (03/16) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| XIN MING ZHOU 98 | — | — | — | — | expected · 20F (new) | expected · 20F | alongside · 20F (P.B 04/09) | sailed (05/09) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| SAWASDEE SPICA | — | — | — | — | — | feeder sheet only · 20B (not on berthing sheet) | expected · 20B (P.B 06/13, ETD 08/13) | expected · 20B | expected · 20B (P.B 06/13) | alongside · 20B (ETD 08/13) | alongside · 20B (ETD 08/13) | sailed (08/13) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| KMTC TOKYO | — | — | — | — | — | — | expected · 20F (new) | expected · **→ 20AB** (ETA 06/13) | expected · 20AB (P.B 06/13) | alongside · 20AB (ETD 08/12) | alongside · 20AB (ETD 08/12) | sailed (08/12) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB (new call: ETA 27/05, ETD 28/13) |
| GREEN PARK | — | — | — | — | — | — | — | expected · 20AB (new, marked) | expected · **→ 20B** | expected · **→ 20AB** (P.B 08/15→08/13) | at anchorage · 20AB (ETA 07/11→07/10, P.B 08/13) | alongside · 20AB (P.B 08/13→08/14, ETD 09/14→09/16) | sailed (09/16) | — | — | — | — | — | — | — | — | expected · **→ 20F** (returns for a new call, ETA 21/17) | expected · **→ 20B** | expected · 20B (ETA 21/17→21/14) | expected · 20B (ETA 21/14→21/16) | expected · 20B | sailed (23/13) | — |
| SAWASDEE ATLANTIC | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C (P.B 08/15→09/15, ETD 10/13→11/03) | expected · **→ 20D** | at anchorage · **→ 20F** (ETA 07/22→07/20) | at anchorage · 20F (P.B 09/15) | alongside · 20F (ETD 11/03→11/13) | alongside · 20F (ETD 11/13→11/12) | sailed (11/12) | — | — | — | — | — | — | — | — | — | — | — | — | — |
| MTT BANGKOK | — | — | — | — | — | — | — | expected · 20D (new, marked) | expected · 20D (P.B 07/17→07/14) | expected · 20D (ETA 07/12) | alongside · 20D (ETD 09/13→09/02) | sailed (09/02) | — | — | — | — | — | — | — | — | expected · **→ 20B** (returns for a new call, ETA 20/15) | expected · **→ 20E** | expected · 20E | alongside · 20E (marked, P.B 20/15→20/18, ETD 21/13→21/20) | sailed (21/20) | — | — | — |
| XIN AN | — | — | — | — | — | — | — | expected · 20F (new, marked) | expected · 20F (P.B 07/17→07/14) | expected · 20F (ETA 07/13) | alongside · 20F (ETD 09/13) | alongside · 20F (ETD 09/13) | sailed (09/13) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · **→ 20B** (moved from 20C) |
| SITC HOCHIMINH | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · **→ 20B** (ETA 07/19→07/18) | at anchorage · 20B (ETA 07/18→07/15) | alongside · 20B (ETD 09/17) | sailed (09/17) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| YM INCEPTION | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · **→ 20C** (P.B 09/15→09/13, ETD 10/16→11/01) | expected · 20C | at anchorage · 20C (ETD 11/01→10/16) | alongside · 20C (marked, ETD 10/16→10/14) | sailed (10/14) | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| HE JIN | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · **→ 20AB** | at anchorage · **→ 22A** (shifts to 20D 09/02, ETD 10/13) | alongside · 20D (shifted in from 22A, P.B 09/02→08/24) | alongside · 20D (ETD 10/13) | sailed (10/13) | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| ZHONG GU DONG HAI | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C (ETA 07/16→07/13) | at anchorage · 20C (ETA 07/13→07/14) | alongside · 20C (ETD 09/14) | sailed (09/14) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| KANWAY FORTUNE | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · **→ 20F** (P.B 09/15→09/14, ETD 11/03→10/15) | expected · **→ 20AB** | at anchorage · 20AB (ETA 08/18→08/16) | alongside · 20AB (ETD 10/15) | sailed (10/15) | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB | expected · 20AB (ETD 27/03→26/16) | expected · 20AB (ETA 25/05→25/06) |
| CNC MARS | — | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · 20AB (ETA 09/10→09/22, ETD 12/04→11/15) | expected · 20AB | at anchorage · 20AB (P.B 10/15) | alongside · 20AB (ETD 11/15) | sailed (11/15) | — | — | — | — | — | — | — | — | — | — | — | — | — |
| INDURO | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · 20B (P.B 09/15→09/16, ETD 11/03→11/14) | at anchorage · 20B (ETA 09/09→09/06) | alongside · 20B (ETD 11/14→11/04) | sailed (11/04) | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| CUL HAIPHONG | — | — | — | — | — | — | — | — | — | expected · 20B (new, shift 4A) | expected · **→ 20D** (shift 4A, ETA 09/20) | expected · 20D (ETA 09/20) | at anchorage · 20D (P.B 10/16) | sailed (11/06) | — | — | — | — | — | — | — | — | — | — | — | — | — | — |
| XIN MING ZHOU 102 | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · 20F (ETA 09/13→10/21, ETD 11/03→12/02) | expected · 20F | expected · **→ 20B** (marked) | alongside · 20B (ETD 12/02) | sailed (12/02) | — | — | — | — | — | — | — | — | — | — | — | — | — |
| STARSHIP AQUILA | — | — | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C (P.B 11/04→10/16, ETD 12/13→12/05) | at anchorage · 20C (marked, P.B 10/16→10/14, ETD 12/05→12/02) | alongside · 20C (ETD 12/02) | sailed (12/02) | — | — | — | — | — | — | — | — | — | — | — | — | — |
| INCEDA | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · 20D | expected · 20D | alongside · 20D (P.B 11/05→11/06) | alongside · 20D (ETD 12/14) | sailed (12/14) | — | — | — | — | — | — | — | — | — | — | — | — |
| SAMAL | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB (new) | expected · **→ 20F** (marked, ETA 12/04→12/01, P.B 12/05→12/06) | expected · **→ 20AB** (ETA 12/01→12/09, P.B 12/06→12/16, ETD 13/14→14/05) | at anchorage · 20AB (ETA 12/09→12/08) | alongside · 20AB (ETA 12/08→12/09, ETD 14/05) | sailed (14/05) | — | — | — | — | — | — | — | — | — | — | — |
| JOSCO SHINE | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · **→ 20AB** (ETA 11/17→12/13, P.B 11/17→12/16) | expected · **→ 20F** (marked, ETA 12/13→12/09, P.B 12/16→12/15, ETD 13/14→13/06) | expected · 20F (ETA 12/09→12/11) | sailed (13/06) | — | — | — | — | — | — | — | — | — | — | — | — |
| KMTC TAIPEIS | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · **→ 20C** | expected · 20C (ETA 12/23→13/01) | expected · **→ 20AB** (P.B 13/05→14/05, ETD 14/15→15/15) | at anchorage · 20AB (ETA 13/01→13/02) | alongside · 20AB (P.B 14/05, ETD 15/15→15/08) | sailed (15/08) | — | — | — | — | — | — | — | — | — | — |
| SAWASDEE SUNRISE | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · **→ 20D** (ETA 12/05→12/09, P.B 12/05→12/16, ETD 13/15→14/05) | expected · 20D | at anchorage · 20D (ETA 12/09→12/04) | alongside · 20D (P.B 12/16, ETD 14/05) | sailed (14/05) | — | — | — | — | — | — | — | — | — | — | — |
| KHUNA BHUM | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB (new, shift 7B) | expected · **→ 20D** (marked, shift 7B; P.B 13/13→14/05, ETD 14/07→14/22) | expected · 20D (shift 7B) | expected · 20D (ETA 13/07→13/11, shift 7B) | alongside · 20D (7B) | sailed (14/22) | — | — | — | — | — | — | — | — | — | — |
| WAN HAI 277 | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new, marked) | expected · **→ 20B** (marked, ETA 13/04→12/23, P.B 13/16→13/06, ETD 15/05→14/15) | expected · **→ 20C** (ETA 12/23→12/21) | alongside · 20C (P.B 13/06, ETD 14/15) | alongside · 20C (ETD 14/15→14/16) | sailed (14/16) | — | — | — | — | — | — | — | — | — | — |
| CEBU | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB (new, marked) | expected · **→ 20B** (ETA 12/24→12/22, P.B 14/06→13/06, ETD 15/16→14/16) | alongside · 20B (ETD 14/16) | alongside · 20B (ETD 14/16→14/13) | sailed (14/13) | — | — | — | — | — | — | — | — | — | — |
| WAN HAI 173 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · 20B (ETA 14/08→14/01) | at anchorage · **→ 20C** | sailed (15/07) | — | — | — | — | — | — | — | — | — | — |
| SAWASDEE INCHEON | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · 20F (ETA 13/15) | alongside · 20F (ETD 15/15→16/06) | alongside · 20F (ETD 16/06) | sailed (16/06) | — | — | — | — | — | — | — | — | — |
| WAN HAI 176 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · **→ 20AB** | alongside · 20AB (ETA 15/11→15/08, P.B 15/11→15/09) | alongside · 20AB (ETD 16/16) | sailed (16/16) | — | — | — | — | — | — | — | — |
| WAN HAI 175 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · **→ 20C** (ETA 15/01→14/23, ETD 16/17→16/15) | alongside · 20C (ETA 14/23→14/21) | alongside · 20C (ETD 16/15) | sailed (16/15) | — | — | — | — | — | — | — | — |
| SITC DALIAN | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | alongside · 20D (P.B 15/05) | sailed (16/06) | — | — | — | — | — | — | — | — | — |
| WAN HAI 172 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · 20D | alongside · 20D (ETD 17/15→17/08) | sailed (17/08) | — | — | — | — | — | — | — | — |
| LITTLE DOLPHIN | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | listed at 20F without times (new, schedule TBA) | expected · **→ 20B** (times announced: ETA 16/17, ETD 18/07; was 20F) | expected · **→ 20C** (ETA 16/17→16/19, P.B 16/17→17/08, ETD 18/07→18/16) | alongside · 20C (actual ETA 17/01) | alongside · 20C (ETD 18/16) | sailed (18/16) | — | — | — | — | — | — |
| XIN MING ZHOU 108 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · **→ 20F** (ETA 17/22→17/10) | expected · 20F | alongside · 20F (ETD 19/07) | alongside · 20F (ETD 19/07→19/12) | sailed (19/12) | — | — | — | — | — |
| INGENUITY | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · 20F | alongside · 20F (actual ETA 16/23) | sailed (18/07) | — | — | — | — | — | — | — |
| KMTC JAKARTA | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · 20F (ETA 18/20→19/07, P.B 18/20→19/09, ETD 20/08→20/17) | expected · 20F (ETA 19/07→19/08) | expected · 20F (marked, ETA 19/08→19/12, P.B 19/09→19/12, ETD 20/17) | expected · **→ 20B** (ETA/P.B 19/12→19/10) | alongside · 20B (ETD 20/17) | sailed (20/17) | — | — | — | — |
| PUNNYA NAVEE | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new, LOA 304 m) | alongside · **→ 20D** (ETA 16/15→16/18, P.B 16/15→17/03, ETD 17/06→17/15) | sailed (17/15) | — | — | — | — | — | — | — |
| SKY ORION | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | listed at 20AB without times (new, schedule TBA) | expected · **→ 20E** (times announced: ETA 21/20, P.B 22/13, ETD 24/01) | expected · 20E (ETA 21/20→21/22) | expected · 20E | expected · 20E | sailed (24/01) | — |
| SAWASDEE MIMOSA | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | listed at 20B without times (new, schedule TBA) | no longer listed (was listed without times) | listed at 20E with ETA 23/22 only (listed again) | expected · **→ 20C** (full schedule now listed: P.B 24/15, ETD 26/03) | expected · 20C (ETA 23/22→23/17) | expected · 20C | expected · 20C |
| CA MANILA | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · **→ 20B** (ETA 22/16→22/17) | expected · 20B | expected · 20B (ETA 22/17→22/18) | expected · 20B | sailed (24/24) |
| RENOWN | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) | at anchorage · 20F (ETA 20/22→20/18) | at anchorage · 20F (ETD 23/10→23/09) | sailed (23/09) | — | — |
| WAN HAI 272 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 22A, then shifts to 20F (new) | expected · 22A, then shifts to 20F | expected · 22A, then shifts to 20F (ETD 23/10→23/09) | expected · **→ 20F only** (no longer listed at 22A; P.B 23/09) | expected · 20F (ETA shown as "22A", P.B 23/09) | sailed (24/14) |
| HORAI BRIDGE | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · 20C | expected · 20C | expected · 20C | sailed (24/15) |
| YM IMAGE | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | listed at 20C without times (new, schedule TBA) | expected · **→ 20E** (schedule now listed: ETA 23/06, P.B 24/03, ETD 25/01) | expected · 20E (ETA 23/06→23/10) | expected · 20E (ETA 23/10→23/06) | sailed (25/01) |
| KANWAY FORTUNE | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20AB (new call) | expected · 20AB | expected · 20AB (ETD 27/03→26/16) | expected · 20AB (ETA 25/05→25/06) |
| ASL TAIPEIS | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · 20B | expected · 20B | expected · 20B (ETA 24/24→25/06, P.B 25/04→25/14, ETD 26/03→26/12) |
| ZHONG GU BEI HAI | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20B (new) | expected · 20B | expected · 20B (ETA 26/14→26/20, P.B 26/14→27/05, ETD 28/03→28/14) | expected · **→ 20C** (moved from 20B; ETA 26/20→26/15, P.B 27/05→26/15, ETD 28/14→28/03) |
| KMTC BANGKOK | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) | expected · 20D (ETA 25/02→25/06, P.B 25/04→25/06) | expected · 20D | expected · 20D (ETD 26/12→26/13) |
| HEUNG A HOCHIMINH | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20E (new) | expected · 20E | expected · **→ 20F** (moved from 20E; ETA 25/22→25/14, P.B 26/06→25/15, ETD 27/14→27/04) | expected · 20F |
| XIN MING ZHOU 106 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) | expected · 20F | expected · **→ 20E** (moved from 20F) | expected · 20E |
| XIN AN | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20C (new) | expected · **→ 20B** (moved from 20C) |
| PUNNYA NAVEE (barge) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new, barge) | sailed (24/23) |
| HARI BHUM (barge) | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new, barge) | sailed (25/07) |
| SAWASDEE VEGA | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20D (new) |
| KUO LONG | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20E (new) |
| WAN HAI 276 | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | — | expected · 20F (new) |

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

### 10-10-2026
- **20AB**: KANWAY FORTUNE (alongside, sails 10/15), CNC MARS (at anchorage), JOSCO SHINE (**← moved from 20B**, ETA 11/17→12/13), KHUNA BHUM (new, shift 7B)
- **20B**: INDURO (alongside, ETD 11/14→11/04), XIN MING ZHOU 102 (**← moved from 20F**, marked), ALS SUMIRE (**← moved from 20C**, marked, ETA 12/18→12/22)
- **20C**: YM INCEPTION (alongside, ETD 10/16→10/14, marked), STARSHIP AQUILA (at anchorage, P.B 10/16→10/14, ETD 12/05→12/02, marked), KMTC TAIPEIS (**← moved from 20D**)
- **20D**: HE JIN (alongside, sails 10/13), CUL HAIPHONG (at anchorage), INCEDA, SAWASDEE SUNRISE (**← moved from 20F**, ETA 12/05→12/09) — closure still printed as **4–24 Oct**, yet HE JIN is alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: SAWASDEE ATLANTIC (alongside, ETD 11/03→11/13), SAMAL (**← moved from 20AB**, marked), WAN HAI 277 (new, marked)
- Sailed since previous sheet: GREEN PARK (09/16), SITC HOCHIMINH (09/17), ZHONG GU DONG HAI (09/14), XIN AN (09/13)
- Sheet highlights (yellow): XIN MING ZHOU 102, ALS SUMIRE, SAMAL, WAN HAI 277, plus the changed YM INCEPTION and STARSHIP AQUILA times
- Seven vessels changed berth this day; two new vessels (KHUNA BHUM, WAN HAI 277)
- Folder: [`10-10-2026/`](10-10-2026)

### 11-10-2026
- **20AB**: CNC MARS (alongside, sails 11/15), SAMAL (**← moved from 20F**, ETA 12/01→12/09, ETD 13/14→14/05), CEBU (new, marked, ETD 15/16)
- **20B**: XIN MING ZHOU 102 (alongside), WAN HAI 277 (**← moved from 20F**, marked, ETA 13/04→12/23)
- **20C**: STARSHIP AQUILA (alongside), KMTC TAIPEIS (ETA 12/23→13/01)
- **20D**: INCEDA (alongside, P.B 11/05→11/06), SAWASDEE SUNRISE, KHUNA BHUM (**← moved from 20AB**, marked, shift 7B, P.B 13/13→14/05, ETD 14/07→14/22) — closure still printed as **4–24 Oct**, yet INCEDA is alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: SAWASDEE ATLANTIC (alongside, ETD 11/13→11/12), JOSCO SHINE (**← moved from 20AB**, marked, ETA 12/13→12/09), ALS SUMIRE (**← moved from 20B**, 1C)
- Sailed since previous sheet: KANWAY FORTUNE (10/15), INDURO (11/04), YM INCEPTION (10/14), HE JIN (10/13), CUL HAIPHONG (11/06)
- Sheet highlights (orange): CEBU, WAN HAI 277, KHUNA BHUM and JOSCO SHINE's new ETA
- Six vessels changed berth; one new vessel (CEBU); five sailed
- Folder: [`11-10-2026/`](11-10-2026)

### 12-10-2026
- **20AB**: SAMAL (at anchorage, ETA 12/09→12/08), KMTC TAIPEIS (**← moved from 20C**, P.B 13/05→14/05, ETD 14/15→15/15)
- **20B**: CEBU (**← moved from 20AB**, ETA 12/24→12/22, P.B 14/06→13/06, ETD 15/16→14/16), WAN HAI 173 (new)
- **20C**: WAN HAI 277 (**← moved from 20B**, ETA 12/23→12/21), **M ODYSSEY returns** for a new call (ETA 14/03, shift 4A)
- **20D**: INCEDA (alongside), SAWASDEE SUNRISE (at anchorage, ETA 12/09→12/04), KHUNA BHUM (shift 7B) — closure still printed as **4–24 Oct**, yet INCEDA is alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: JOSCO SHINE (ETA 12/09→12/11), ALS SUMIRE (1C), SAWASDEE INCHEON (new)
- Sailed since previous sheet: CNC MARS (11/15), XIN MING ZHOU 102 (12/02), STARSHIP AQUILA (12/02), SAWASDEE ATLANTIC (11/12)
- No sheet highlights on this day; three vessels changed berth, two new vessels (WAN HAI 173, SAWASDEE INCHEON)
- Folder: [`12-10-2026/`](12-10-2026)

### 13-10-2026
- **20AB**: SAMAL (alongside, ETA 12/08→12/09), KMTC TAIPEIS (at anchorage, ETA 13/01→13/02)
- **20B**: CEBU (alongside), WAN HAI 173 (ETA 14/08→14/01), WAN HAI 176 (new)
- **20C**: WAN HAI 277 (alongside), M ODYSSEY (shift 4A no longer shown), **KHARIS HERITAGE returns** for a new call (ETA 15/01, ETD 16/07)
- **20D**: SAWASDEE SUNRISE (alongside), KHUNA BHUM (ETA 13/07→13/11, shift 7B), WAN HAI 175 (new) — closure still printed as **4–24 Oct**, yet SAWASDEE SUNRISE is alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: ALS SUMIRE (alongside, 1C), SAWASDEE INCHEON
- Sailed since previous sheet: INCEDA (12/14), JOSCO SHINE (13/06)
- No sheet highlights; no berth changes today (a first since 7 Oct); two new vessels (WAN HAI 176, WAN HAI 175) and one return call (KHARIS HERITAGE)
- Folder: [`13-10-2026/`](13-10-2026)

### 14-10-2026
- **20AB**: KMTC TAIPEIS (alongside, ETD 15/15→15/08), WAN HAI 176 (**← moved from 20B**)
- **20B**: CEBU (alongside, ETD 14/16→14/13), M ODYSSEY (**← moved from 20C**, at anchorage, shift 4A back), KHARIS HERITAGE (**← moved from 20C**), **BANGKOK listed with no ETA / P.B / ETD** (returns, schedule TBA)
- **20C**: WAN HAI 277 (alongside, ETD 14/15→14/16), WAN HAI 173 (**← moved from 20B**, at anchorage), WAN HAI 175 (**← moved from 20D**, ETA 15/01→14/23)
- **20D**: KHUNA BHUM (alongside, 7B), SITC DALIAN and WAN HAI 172 (new) — closure still printed as **4–24 Oct**, yet KHUNA BHUM is alongside
- **20E**: empty — G.25 stoppage **5–18 Oct** in progress
- **20F**: SAWASDEE INCHEON (alongside, ETD 15/15→16/06), **LITTLE DOLPHIN listed with no times** (new, schedule TBA)
- Sailed since previous sheet: SAMAL (14/05), SAWASDEE SUNRISE (14/05), ALS SUMIRE (14/06)
- The two vessels without times (BANGKOK, LITTLE DOLPHIN) appear on the dashboard as "Schedule TBA" but are not in the Excel day sheet or the timeline
- Five vessels changed berth; three new vessels (SITC DALIAN, WAN HAI 172, LITTLE DOLPHIN); no highlights on the sheet
- Folder: [`14-10-2026/`](14-10-2026)

### 15-10-2026
The sheet layout changed today: a new berth **20A (Gate 19, 20)** appears (empty), 22C is no longer listed, and times are printed as DD.HHMM (e.g. 15.0800 = 15/08).
- **20AB**: WAN HAI 176 (alongside, ETA 15/11→15/08, P.B 15/11→15/09), BANGKOK (**← moved from 20B**, times now announced: 16/21 → 18/16), CAPE FAWLEY (returns, ETA 19/18)
- **20B**: KHARIS HERITAGE (alongside), LITTLE DOLPHIN (**← moved from 20F**, times now announced), XIN MING ZHOU 108 (new)
- **20C**: WAN HAI 175 (alongside, ETA 14/23→14/21), TS CHIBA and INFINITY (both return for new calls)
- **20D**: SITC DALIAN (alongside), WAN HAI 172, JARU BHUM (returns, shift 7B), MITRA BHUM (returns) — the **4–24 Oct closure notice is gone**, which resolves the booking conflict seen since 7 Oct
- **20E**: empty — now printed as **CLOSE (Oct 5–20 2026)** (earlier sheets: G.25 gate stop 5–18 Oct)
- **20F**: SAWASDEE INCHEON (alongside), INGENUITY and KMTC JAKARTA (new)
- Sailed since previous sheet: KMTC TAIPEIS (15/08), CEBU (14/13), M ODYSSEY (15/05), WAN HAI 277 (14/16), WAN HAI 173 (15/07), KHUNA BHUM (14/22)
- Five vessels return for new calls (CAPE FAWLEY, TS CHIBA, INFINITY, JARU BHUM, MITRA BHUM); three new vessels; BANGKOK and LITTLE DOLPHIN now have times
- Folder: [`15-10-2026/`](15-10-2026)

### 16-10-2026
- **20AB**: WAN HAI 176 (alongside, sails 16/16), BANGKOK, MITRA BHUM (**← moved from 20D**); CAPE FAWLEY moved out to 20C
- **20B**: TS CHIBA (**← moved from 20C**, ETA/P.B 17/02, 17/08 → 16/14, ETD 18/07→17/12), JARU BHUM (**← moved from 20D**, shift 7B, 17/18 → 17/16)
- **20C**: WAN HAI 175 (alongside, sails 16/15), LITTLE DOLPHIN (**← moved from 20B**, P.B 16/17→17/08, ETD 18/07→18/16), CAPE FAWLEY (**← moved from 20AB**)
- **20D**: WAN HAI 172 (alongside, ETD 17/15→17/08), INFINITY (**← moved from 20C**)
- **20E**: empty — CLOSE (Oct 5–20 2026) unchanged
- **20F**: PUNNYA NAVEE (new, LOA 304 m), INGENUITY, XIN MING ZHOU 108 (**← moved from 20B**, ETA 17/22→17/10), KMTC JAKARTA (ETA 18/20→19/07, ETD 20/08→20/17)
- Sailed since previous sheet: KHARIS HERITAGE (16/07), SITC DALIAN (16/06), SAWASDEE INCHEON (16/06)
- Eight vessels changed berth; one new vessel; no sheet highlights
- Folder: [`16-10-2026/`](16-10-2026)

### 17-10-2026
Bold ETAs on this sheet (BANGKOK, LITTLE DOLPHIN, INGENUITY) are actual arrival times, entered as DD.HHMM with minutes (e.g. 16.1504 = arrived 16 Oct 15:04).
- **20AB**: BANGKOK (alongside, actual ETA 16/15, P.B 17/09) — WAN HAI 176 sailed, MITRA BHUM no longer listed
- **20B**: TS CHIBA (alongside, ETD 17/12→17/11), JARU BHUM (shift 7B)
- **20C**: LITTLE DOLPHIN (alongside, actual ETA 17/01); a second row shows only **LOA 558 m with no name or times** (probably CAPE FAWLEY, which was on 20C yesterday) — shown as Schedule TBA
- **20D**: PUNNYA NAVEE (**← moved from 20F**, alongside, ETD 17/06→17/15), INFINITY (ETA 18/06→17/24)
- **20E**: empty — CLOSE (Oct 5–20 2026) unchanged
- **20F**: INGENUITY (alongside, actual ETA 16/23), XIN MING ZHOU 108, KMTC JAKARTA (ETA 19/07→19/08)
- Sailed since previous sheet: WAN HAI 176 (16/16), WAN HAI 175 (16/15), WAN HAI 172 (17/08)
- Dropped without sailing: MITRA BHUM (was expected 20/09 at 20AB); no new vessels; no sheet highlights
- Folder: [`17-10-2026/`](17-10-2026)

### 18-10-2026
- **20AB**: BANGKOK (alongside, ETD 18/16→19/08)
- **20B**: JARU BHUM (alongside, ETD 18/11→18/10, shift 7B), **MTT BANGKOK returns** for a new call (ETA 20/15, ETD 21/13)
- **20C**: LITTLE DOLPHIN (alongside), MITRA BHUM (**listed again** after vanishing on 17 Oct; ETA/P.B 20/17, ETD 21/13); the unnamed LOA 558 m row is gone
- **20D**: INFINITY (alongside, ETD 19/10→19/09) — new notice **CLOSE from Oct 19 2026** (end date not printed)
- **20E**: empty — the CLOSE (Oct 5–20 2026) line is **no longer printed**
- **20F**: XIN MING ZHOU 108 (alongside), KMTC JAKARTA (highlighted yellow: ETA 19/08→19/12, P.B 19/09→19/12, ETD 20/17)
- Sailed since previous sheet: TS CHIBA (17/11), PUNNYA NAVEE (17/15), INGENUITY (18/07)
- No new vessels; one return call (MTT BANGKOK); sheet highlight: KMTC JAKARTA's three times
- Folder: [`18-10-2026/`](18-10-2026)

### 19-10-2026
- **20AB**: **HOPE C returns** for a new call (shift 4A, ETA 20/24, ETD 21/22), **SKY ORION listed with no times** (new, schedule TBA); BANGKOK sailed
- **20B**: KMTC JAKARTA (**← moved from 20F**, ETA/P.B 19/12→19/10), MITRA BHUM (**← moved from 20C**, now 21/13 → 22/05), **SAWASDEE MIMOSA listed with no times** (new, schedule TBA)
- **20C**: MILLENNIUM BRIGHT (returns, ETA 19/14), CAPE FAWLEY (listed again with times 21/11 → 23/12)
- **20D**: empty — the "CLOSE from Oct 19" notice is no longer printed
- **20E**: MTT BANGKOK (**← moved from 20B**), ALS SUMIRE (returns, 1C); no closure text printed
- **20F**: XIN MING ZHOU 108 (alongside, ETD 19/07→19/12), GREEN PARK (returns, ETA 21/17)
- Sailed since previous sheet: BANGKOK (19/08), INFINITY (19/09), LITTLE DOLPHIN (18/16), JARU BHUM (18/10)
- No berth notices on this sheet at all; the 20A row is not printed; two new vessels without times (SKY ORION, SAWASDEE MIMOSA); five return calls
- Folder: [`19-10-2026/`](19-10-2026)

### 20-10-2026
- **20AB**: HOPE C (shift 4A, ETA 20/24), ALS SUMIRE (**← moved from 20E**, 1C, ETA 21/17→21/22, P.B 22/13, ETD 23/16)
- **20B**: KMTC JAKARTA (alongside, sails 20/17), MITRA BHUM, GREEN PARK (**← moved from 20F**), **KMTC GWANGYANG returns** for a new call (ETA 22/13, ETD 25/02)
- **20C**: MILLENNIUM BRIGHT (alongside, sails 20/12), CAPE FAWLEY, CA MANILA (new, ETD 24/24)
- **20D**: empty
- **20E**: MTT BANGKOK, SKY ORION (**← moved from 20AB**, times now announced: 21/20 → 24/01)
- **20F**: RENOWN (new), WAN HAI 272 (new; waits at **22A** 22/07 → 23/10, then shifts to 20F 23/10 → 24/14)
- Sailed since previous sheet: XIN MING ZHOU 108 (19/12); SAWASDEE MIMOSA (listed without times yesterday) is no longer listed
- No berth notices on this sheet; no highlights; three new vessels (CA MANILA, RENOWN, WAN HAI 272) and one return call (KMTC GWANGYANG)
- Folder: [`20-10-2026/`](20-10-2026)

### 21-10-2026
- **20AB**: HOPE C (alongside, highlighted ETA 20/24→21/02, 4A), ALS SUMIRE (1C), KMTC GWANGYANG (**← moved from 20B**, ETA 22/13→22/14)
- **20B**: MITRA BHUM, GREEN PARK (ETA 21/17→21/14), CA MANILA (**← moved from 20C**)
- **20C**: CAPE FAWLEY, HORAI BRIDGE (new), **YM IMAGE listed with no times** (new, schedule TBA)
- **20D**: empty
- **20E**: MTT BANGKOK (alongside, highlighted P.B 20/15→20/18, ETD 21/13→21/20), SKY ORION (ETA 21/22), **SAWASDEE MIMOSA relisted with ETA 23/22 only**
- **20F**: RENOWN (at anchorage, ETA 20/22→20/18), WAN HAI 272 (waits at **22A** 22/07 → 23/10, then 20F)
- Sailed since previous sheet: KMTC JAKARTA (20/17), MILLENNIUM BRIGHT (20/12)
- No berth notices on this sheet; sheet highlights: HOPE C's ETA and MTT BANGKOK's P.B; one new vessel with times (HORAI BRIDGE), one without (YM IMAGE)
- An Outlook draft (original sheet attached, dashboard pasted in) was prepared for the daily "BKK BERTH LINE UP" email; it is kept outside this repo because it contains internal addresses
- Folder: [`21-10-2026/`](21-10-2026)

### 22-10-2026
- **20AB**: ALS SUMIRE (1C), KMTC GWANGYANG (ETA 22/14→22/13), KANWAY FORTUNE (new call)
- **20B**: GREEN PARK (ETA 21/14→21/16), CA MANILA, ASL TAIPEIS (new), ZHONG GU BEI HAI (new)
- **20C**: CAPE FAWLEY, HORAI BRIDGE, **SAWASDEE MIMOSA moved from 20E** (schedule now complete: ETA 23/22, P.B 24/15, ETD 26/03)
- **20D**: KMTC BANGKOK (new, ETA 25/02)
- **20E**: SKY ORION, **YM IMAGE moved from 20C** (schedule now listed: 23/06, 24/03, 25/01), HEUNG A HOCHIMINH (new)
- **20F**: RENOWN (at anchorage, ETD 23/10→23/09), WAN HAI 272 (waits at **22A** 22/07 → 23/09, then 20F; ETD 24/14), XIN MING ZHOU 106 (new)
- Sailed since previous sheet: HOPE C (21/22), MITRA BHUM (22/05), MTT BANGKOK (21/20)
- No berth notices and no highlights on this sheet; six new vessels
- Original sheet saved as JPG + PDF; a ready-to-send Outlook draft is kept outside the repo
- Dashboard fix: times written DD/HH no longer assume 27-31 = September; each time is tagged with the month nearest to its sheet date (27-28 Oct on this sheet are October)
- Folder: [`22-10-2026/`](22-10-2026)

### 23-10-2026
- **20AB**: ALS SUMIRE (1C), KMTC GWANGYANG, KANWAY FORTUNE (unchanged)
- **20B**: GREEN PARK, CA MANILA (ETA 22/17→22/18), ASL TAIPEIS, ZHONG GU BEI HAI
- **20C**: CAPE FAWLEY, HORAI BRIDGE (sheet spells it BRUDGE), SAWASDEE MIMOSA (ETA 23/22→23/17)
- **20D**: KMTC BANGKOK (ETA 25/02→25/06, P.B 25/04→25/06)
- **20E**: SKY ORION, YM IMAGE (ETA 23/06→23/10), HEUNG A HOCHIMINH
- **20F**: WAN HAI 272 (ETA shown as "22A", P.B 23/09, ETD 24/14; **no longer listed at 22A**), XIN MING ZHOU 106
- Berth blocks on this sheet: 22A, 22B, 22D, 22E (22C no longer printed; 22E new) – all empty
- Sailed since previous sheet: RENOWN (ETD 23/09)
- No berth notices and no highlights; no new vessels
- Original sheet saved as JPG + PDF
- Folder: [`23-10-2026/`](23-10-2026)

### 24-10-2026
- **20AB**: KMTC GWANGYANG (ETD 25/02→25/01), KANWAY FORTUNE (ETD 27/03→26/16)
- **20B**: CA MANILA, ASL TAIPEIS, ZHONG GU BEI HAI (ETA 26/14→26/20, P.B 26/14→27/05, ETD 28/03→28/14)
- **20C**: HORAI BRIDGE, SAWASDEE MIMOSA, **XIN AN** (new)
- **20D**: **PUNNYA NAVEE (barge)** and **HARI BHUM (barge)** (new, short same-day calls), KMTC BANGKOK
- **20E**: YM IMAGE (ETA 23/10→23/06), **XIN MING ZHOU 106 moved from 20F**
- **20F**: WAN HAI 272 (ETA shown as "22A", P.B 23/09), **HEUNG A HOCHIMINH moved from 20E** (ETA 25/22→25/14, P.B 26/06→25/15, ETD 27/14→27/04)
- 22A–22D printed again (22E gone), all empty
- Sailed since previous sheet: ALS SUMIRE (23/16), GREEN PARK (23/13), CAPE FAWLEY (23/12), SKY ORION (24/01)
- No berth notices and no highlights; three new vessels (two barges)
- Original sheet saved as JPG + PDF
- Folder: [`24-10-2026/`](24-10-2026)

### 25-10-2026
- **20AB**: KANWAY FORTUNE (ETA 25/05→25/06), **KMTC TOKYO** (new call: ETA 27/05, ETD 28/13)
- **20B**: ASL TAIPEIS (ETA 24/24→25/06, P.B 25/04→25/14, ETD 26/03→26/12), **XIN AN moved from 20C**
- **20C**: SAWASDEE MIMOSA, **ZHONG GU BEI HAI moved from 20B** (ETA 26/20→26/15, P.B 27/05→26/15, ETD 28/14→28/03), **M ODYSSEY** (new call: 28/03, 28/05, 29/06)
- **20D**: KMTC BANGKOK (ETD 26/12→26/13), **SAWASDEE VEGA** (new, 27/15, ETD 29/04)
- **20E**: XIN MING ZHOU 106, **KUO LONG** (new, 27/03, ETD 28/14)
- **20F**: HEUNG A HOCHIMINH, **WAN HAI 276** (new, 27/16, ETD 29/04)
- 22A, 22B, 22D, 22E printed, all empty
- Sailed since previous sheet: KMTC GWANGYANG (25/01), YM IMAGE (25/01), CA MANILA (24/24), HORAI BRIDGE (24/15), WAN HAI 272 (24/14), PUNNYA NAVEE barge (24/23), HARI BHUM barge (25/07)
- No berth notices and no highlights; three new vessels plus two returning (KMTC TOKYO, M ODYSSEY)
- Original sheet saved as JPG + PDF
- Dashboard: "Berth & gate notices" renamed "Berth notices". The separate changes table was removed; the comparison with the previous sheet now sits in "Vessel list by berth": old time struck through → new in ETA / P.B / ETD, plus a "Change vs previous sheet" column (BERTH MOVED, ETA|P.B|ETD ADVANCED -Nh / DELAYED +Nh, NEW). The list shows only the vessel(s) alongside and the next vessel to berth for each berth, as at the sheet date (the timeline still shows every vessel)
- Dashboard: Calendar tab removed; the sheet date's day summary (Berthing P.B / Sailing ETD / Notices, as the old calendar day detail) now sits above the Berth timeline; "Next berthing" tile shows the vessel name, berth and P.B (or "No vessel scheduled"); "Vessel list by berth" is one box per berth
- Dashboard: standing box "20A === Awaiting handover ===" added to Vessel list by berth; it stays on every sheet until told otherwise (HOLD constant in the dashboard script)
- Dashboard: Vessel list by berth now sits before Berth timeline; the daily email no longer pastes the Berth timeline (header, summary, notices, day summary and vessel list only)
- Dashboard: vessel status for the sheet date ("today"): ETA = ARRIVAL, P.B = PILOT ON BOARD, ETB = P.B + 3 HOURS = BERTH, ETD = DEPARTURE. The day summary has one column per status and each vessel box has a BERTH (ETB) row (the per-vessel TODAY tags were removed on request)
- Dashboard: Vessel list by berth grouped under headings PAT TERMINAL 1 (20A, 20AB, 20B, 20C), PAT TERMINAL 2 (20D, 20E, 20F) and BULK BERTH (22A (OB), 22B, 22D, 22E)
- Dashboard: the day summary above Vessel list by berth now shows only the vessels that BERTH (ETB = P.B + 3 h) on the sheet date, sorted by berth 20A, 20AB, 20B, 20C, 20D, 20E, 20F
- Dashboard: day berthing cards show ETB and ETD; a berth (20A-20F) with no vessel berthing on the sheet date shows its latest vessel that already berthed, tagged "last vessel in" (20A shows Awaiting handover)
- Dashboard: vessels that have already sailed (ETD passed) are not shown in the day berthing cards
- Dashboard: berth 20A (not in use yet) is not shown in the day berthing cards; its standing Awaiting handover box stays in Vessel list by berth
- Dashboard: summary cards are now Berth notices, At anchorage, Alongside now and Coming soon (count of vessels not yet at anchorage); Next berthing and Next sailing removed; the status word "Expected" is now "Upcoming"
- Folder: [`25-10-2026/`](25-10-2026)

---
**Process for the next sheet:** add a dated folder with the source PDF and a copy of
`pat_berth.html`; add a new dataset entry to `DATASETS`/`DAY_ORDER` in the live
`pat_berth.html`/`index.html`; update the vessel continuity table above (carry forward
each vessel still on the sheet, mark newly-sailed vessels, flag any berth reassignment
or slipped closure date); then append a new per-day snapshot section; rebuild
`PAT_Berth_Window.xlsx` at the repo root (cumulative: continuity, all-days notices log and one
sheet per day), then save a per-day copy into each dated folder containing only that day's sheet
(vessel list + that day's notices).
