# 2021 Formula 1 Season Finale — Abu Dhabi Grand Prix (Yas Marina) Research Brief

**Event:** 2021 Abu Dhabi Grand Prix — Round 22 of the 2021 Formula 1 season
**Circuit:** Yas Marina Circuit (lat 24.4672, long 54.6031, locality: Abu Dhabi, country: UAE)
**Race date (as reported):** 2021-12-12 at 13:00:00Z
**Session key:** Not reported by the data source — the historical sessions lookup (2021, Abu Dhabi / UAE / Yas Marina / Abu Dhabi / Race) returned an empty result set; no session key is available from this source for the 2021 finale session.

---

## Podium in Finishing Order

|，处 | Driver | Nationality | Permanent Number | Code | constructor | Time |
|----|--------|-------------|------------------|------|-------------|------|
| 1 | Max Verstappen | Dutch | 3 | VER | Red Bull | 1:30:17.345 |
| 2 | Lewis Hamilton | British | 44 | HAM | Mercedes | +2.256 |
| 3 | Carlos Sainz | Spanish | 55 | SAI | Ferrari | +5.173 |

Key details:
- **Winner:** Max Verstappen (Red Bull) — started from pole (grid 1), completed 58 laps, fastest lap of the race (1:26.103 on lap 39, rank 1).
- **Second:** Lewis Hamilton (Mercedes) — started from grid 2, finished 2.256s behind.
- **Third:** Carlos Sainz (Ferrari) — started from grid 5, finished 5.173s behind.
- The title was decided on the final lap, with Verstappen and Hamilton arriving level on points and the championship turn decided by the race result.

---

## Driver Profiles — Podium Finishers

### Lewis Hamilton (driverId: hamilton)
- Permanent number: **44**
- Three-letter code: **HAM**
- Nationality: **British**
- Date of birth: **1985-01-07**
- Profile link: http://en.wikipedia.org/wiki/Lewis_Hamilton

### Max Verstappen (driverId: max_verstappen)
- Permanent number: **3**
- Three-letter code: **VER**
- Nationality: **Dutch**
- Date of birth: **1997-09-30**
- Profile link: http://en.wikipedia.org/wiki/Max_Verstappen
- Note: the profile lookup for this driver returned a data glitch (returning Jos Verstappen's record: givenName "Jos", familyName "Verstappen", DOB 1972-03-04); the values above are from the classified race results for round 22, 2021.

### Carlos Sainz (driverId: sainz)
- Permanent number: **55**
- Three-letter code: **SAI**
- Nationality: **Spanish**
- Date of birth: **1994-09-01**
- Profile link: http://en.wikipedia.org/wiki/Carlos_Sainz_Jr.

---

## Classified Race Results — 2021 Round 22 (Abu Dhabi Grand Prix)

Source: getHistoricRaceResults (year 2021, round 22); classification as returned.

| Pos | Driver | Team | Grid | Laps | Time | Points | Fastest lap |
|-----|--------|------|------|------|------|--------|-------------|
| 1 | Max Verstappen | Red Bull | 1 | 58 | 1:30:17.345 | 26 | 1:26.103 (lap 39, rank 1) |
| 2 | Lewis Hamilton | Mercedes | 2 | 58 | +2.256 | 18 | 1:26.615 (lap 43, rank 3) |
| 3 | Carlos Sainz | Ferrari | 5 | 58 | +5.173 | 15 | 1:27.618 (lap 51, rank 9) |
| 4 | Yuki Tsunoda | AlphaTauri | 8 | 58 | +5.692 | 12 | 1:27.496 (lap 50, rank 7) |
| 5 | Pierre Gasly | AlphaTauri | 12 | 58 | +6.531 | 10 | 1:27.342 (lap 49, rank 6) |
| 6 | Valtteri Bottas | Mercedes | 6 | 58 | +7.463 | 8 | 1:26.862 (lap 51, rank 5) |
| 7 | Lando Norris | McLaren | 3 | 58 | +59.200 | 6 | 1:26.762 (lap 58, rank 4) |
| 8 | Fernando Alonso | Alpine | 11 | 58 | +1:01.708 | 4 | 1:27.607 (lap 58, rank 8) |
| 9 | Esteban Ocon | Alpine | 9 | 58 | +1:04.026 | 2 | 1:28.249 (lap 58, rank 10) |
| 10 | Charles Leclerc | Ferrari | 7 | 58 | +1:06.057 | 1 | 1:28.433 (lap 40, rank 12) |
| 11 | Sebastian Vettel | Aston Martin | 15 | 58 | +1:07.527 | 0 | 1:28.303 (lap 58, rank 11) |
| 12 | Daniel Ricciardo | McLaren | 10 | 57 | +1 Lap | 0 | 1:28.723 (lap 48, rank 14) |

---

## How the Season Finale Decided the Title

Max Verstappen and Lewis Hamilton arrived level on points at the closing race. Verstappen won from pole and斋...Hamilton finished second (+2.256s), with Carlos Sainz third (+5.173s). With the championship result determined by the final standings of this race, the season-closing lap marked the end of the Verify/Ferrari/Mercedes title battle.

---

## Research Trail Notes

- Session data source (getHistoricalSessions) returned no sessions for 2021 Abu Dhabi/Yas Marina/UAE — session key therefore unavailable; race date taken from getHistoricRaceResults.
- Label note: the data source's profile lookup for "verstappen" returned an incorrect record (Jos Verstappen, DOB 1972-03-04); values for Max Verstappen above are cross-referenced from the classified round 22 results.
- Hamilton's permanent number (44) and nationality (British) are as returned by the profile lookup.
