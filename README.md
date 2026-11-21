# GLOBAL HERALD — Friday 20 November 2026

One-page vintage newspaper in colour, summing up Friday 20 November 2026
in five verified stories. Entry for make.fun `news-image-20261120`
($250, closes 22 Nov 2026 07:00 WIB).

## The five stories (all verified against live reporting, 21 Nov 2026)

1. **THREE POWERS, ONE TABLE — Shenzhen, Thursday.** Trump, Xi and Putin
   met for 90 minutes at Kylin Villa, the first-ever trilateral of the
   leaders of the US, China and Russia. Joint statement: a nuclear war
   "cannot be won and must never be fought." (WSJ, CNN)
2. **COURT: MYANMAR COMMITTED GENOCIDE — The Hague, Thursday.** The ICJ
   ruled 9–6, the first time it has held a state responsible for genocide:
   the Rohingya in northern Rakhine in 2017. Reparations ordered.
   (CNN, ICJ reporting)
3. **IRAN DECISION PUSHED TO 2027 — Washington, Thursday.** Trump: "We
   will see what happens after the beginning of the year." The Senate
   rejected a war-powers resolution, 51–48. (Reuters, Axios via Particle)
4. **ANTHROPIC'S $81.3BN RECORD IPO — Wall Street, Thursday.** 980 million
   shares at $83, the largest IPO ever, past SpaceX's $75bn. Trading on
   Nasdaq as ANT; shares opened at $111.50. (CNN, WSJ, NPR)
5. **AKVAN HITS ODISHA; 300,000 SAFE — Odisha, Friday morning.** Cyclone
   Akvan crossed the coast near Gopalpur, winds 70–80 km/h gusting to 90.
   More than 300,000 people were moved to shelters. (IMD via The Watchers)

Dates are written as reported: the first four stories happened on Thursday
19 November; only the cyclone made landfall on Friday 20 November, the day
this front page is dated.

## How it is made

`entry.png` (1024×1024, ~109 KB) is drawn programmatically with Pillow:
flat-colour illustrations (Shenzhen skyline, The Hague courthouse, a stock
chart, the Capitol, a cyclone spiral) plus real typeset text. No AI image
generator was used for the text, so every headline is crisp and legible at
~300 px. The drawing script lives outside this repo in the build workspace;
the repo holds only the finished image and this program.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
# writes out/entry.png, byte-identical on every run
```

## License

MIT — see `LICENSE`.
