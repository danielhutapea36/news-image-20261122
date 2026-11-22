# World News — Sunday 22 November 2026

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/danielhutapea36/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/danielhutapea36/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

One image summing up the world's news of Sunday 22 November 2026, for the
make.fun `news-image-20261122` bounty. The image is a newspaper front page
with the masthead "WORLD NEWS", the date line "SUNDAY 22 NOVEMBER 2026",
and six panels — one per story below.

## The six stories

1. **Drones hit Russian cargo ship Sparta II in the Baltic** — on
   Saturday, two drones struck the Russian-flagged cargo ship Sparta II
   in the Gulf of Finland as it sailed for Kaliningrad; the ship caught
   fire and drifted into Finnish waters, its 16 crew were evacuated,
   and Finland said Ukraine was likely behind the attack.
   Source: Reuters —
   https://www.europesays.com/dk/210799/
2. **COP31 climate talks run into overtime, deadlocked on fossil
   fuels** — in Antalya on Saturday, negotiators from nearly 200
   countries stretched past the summit's Friday deadline with no deal,
   split over fossil-fuel language and climate finance; the EU's top
   climate official said it would be "a good deal or no deal at all",
   and Ethiopia was named host of COP32 in 2027.
   Source: Reuters —
   https://www.devdiscourse.com/article/international/4010374-cop31-climate-summit-risks-failure-as-talks-go-deep-into-overtime?amp
3. **FBI investigates hack of its national crime database** — the FBI
   is investigating an apparent breach of the National Crime Information
   Center, the database police across the US use for warrants,
   fugitives and missing persons; it is the second intrusion into an
   FBI system in recent months, and the scope is not yet known.
   Source: AP —
   https://www.lapost.com/content/fbi-investigating-apparent-hack-of-a-key-criminal-justice-information-database-ap-source-says
4. **Mexico captures FBI most-wanted cartel boss "El Chapo Isidro"**
   — Mexican special forces arrested Fausto Isidro Meza-Flores in
   Guasave, Sinaloa, on Friday night with US intelligence help; the
   raid set off gun battles that killed 11 people — four soldiers and
   seven alleged gunmen — and fans fled a baseball game as shooting
   broke out nearby.
   Source: AP —
   https://lapresse.us/world/2026/11/21/mexico-arrest-of-el-chapo-isidro-11-killed-in-gun-battle/
5. **Zelensky calls Crimean Bridge strikes a "fair response"** — in
   Kyiv on Saturday, President Volodymyr Zelenskyy defended Ukraine's
   strikes on the Crimean Bridge, saying Russia had attacked Ukrainian
   bridges 109 times; the bridge's collapsed road section may take
   months to a year to clear, Ukraine's defence minister said.
   Source: BBC —
   https://www.europesays.com/russia/92621/
6. **EU and Indonesia sign landmark trade deal** — in Brussels on
   Saturday, the EU and Indonesia signed a Comprehensive Economic
   Partnership Agreement after nearly 10 years of talks, scrapping
   tariffs on about 98% of goods traded and saving EU exporters over
   €600 million a year; ratification is still needed before it takes
   effect.
   Source: European Commission —
   https://commission.europa.eu/topics/trade/eu-indonesia-trade-agreement_en

## How it works

`main.py` (Python 3.13, standard library only) copies the bundled
`entry.png` byte-for-byte into the output directory
(`$MAKEFUN_OUTPUT_DIR`, default `/output`). It first checks the PNG
magic bytes, the 1 MiB size cap and the 1024×1024 dimensions of the
source, copies the file, then reads the copy back and confirms it is
identical before reporting its size and SHA-256. No network, no
randomness, no timestamps — two runs write identical bytes.

Run it locally with:

```
MAKEFUN_OUTPUT_DIR=/tmp/ni22-out python3 main.py
```

## Verification

To confirm the copy is faithful, run the program once more into a
fresh folder and compare the digests of the source and the copy:

```
MAKEFUN_OUTPUT_DIR=/tmp/ni22-check python3 main.py
sha256sum entry.png /tmp/ni22-check/entry.png
```

The two digests must be identical, and both must match the SHA-256
recorded under "The image" below. The first eight bytes of the copy
must read `89 50 4E 47 0D 0A 1A 0A`, the PNG signature. If `entry.png`
is missing beside `main.py`, over the size cap, or a copy fails any of
these checks, the program stops with exit code 1 and a
plain-language error instead of leaving behind a bad copy.

## The image

- File: `entry.png`
- Size: 1024 × 1024 pixels, 664402 bytes
- SHA-256: `d99524ffc5fdcd6df6167263d774dae5db2bfe578feae2b3748da839b384bb7f`

---

<sub>Entered on [make.fun](https://make.fun/?ref=danielhutapea36&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
