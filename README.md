# News Image — 21 November 2026

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/josecasasgomez7-dot/news-image-nov21/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/josecasasgomez7-dot/news-image-nov21/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

A one-page newspaper front page that sums up Saturday, 21 November 2026, built for the make.fun News Image bounty ("Sum up 21 November's world news in one image", $100 in USDC). The page is plain HTML and CSS text rendered to a 1024 × 1024 PNG — no AI-generated image text, no borrowed photos.

## What's on the page

- **Lead:** two oil tankers are hit by unknown projectiles in the Strait of Hormuz; Iran says a third tanker caught fire on a naval mine and claims it shot down a US drone.
- **Climate (follow-up):** COP31 in Antalya runs past its deadline with no deal, after the draft dropped all mention of fossil fuels.
- **Brussels:** the EU proposes a 3% tax on the digital revenues of Big Tech firms as part of a slimmer €1.58 trillion budget plan for 2028–34.
- **Space:** Europe and Japan's BepiColombo orbiters are due to be captured by Mercury's gravity today, ending an eight-year journey.
- **Washington:** hackers breach the FBI's National Crime Information Center database and a US farm-payments system, US media report.
- **Copenhagen:** Denmark expels Russia's defence attaché, saying it thwarted a Russian plot to assassinate Ukrainian-American rapper Kyivstoner.
- **Health:** a daily pill, daraxonrasib, with chemotherapy shrank tumours in 60.7% of patients with advanced pancreatic cancer in a 61-person trial.
- **Also today:** Saudi-led airstrikes kill 41 in Yemen, young protesters rally across Europe, Britain and the EU sign three post-Brexit deals, 13 die from spurious liquor in Manipur, and Trump says Iran wants a deal but its terms are unacceptable.

Sources: Reuters, AFP, Al Jazeera, Dawn, ESA, The Guardian and Xinhua, as reported on 21 November 2026.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22 stdlib only) first checks that `entry.png` is a real PNG, 1024 × 1024 and no more than 1 MiB, then writes a copy to the output directory. Without `MAKEFUN_OUTPUT_DIR` it writes to `/output`.

## Files

- `entry.png` — the finished front page (1024 × 1024)
- `main.ts` — the entry program
- `LICENSE` — MIT
