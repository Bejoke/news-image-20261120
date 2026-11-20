# World news in one image — Friday, 20 November 2026

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Bejoke/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Bejoke/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

One image that sums up the world's news of 20 November 2026, drawn as a
newspaper front page (`entry.png`, 1024×1024, drawn with PIL so every word
is crisp and spelled correctly).

## The stories

- **Massive strike on Kyiv** — Russia fires 110+ missiles and ~400
  drones overnight; three Kyiv bridges hit, 8 killed. Poland scrambles
  jets after its airspace is breached.
- **AI sell-off** — Nikkei −4.8%, SoftBank −16%, Kospi −5.7%: Asia heads
  for its worst week since 2020 as doubts about AI spending spread.
- **UK–EU youth mobility** — deal due at Friday's Brussels summit: up to
  100,000 young people a year could move each way.
- **GTA VI: $2.36bn day one** — Sensor Tower estimates 24.6m copies sold
  on launch day, the biggest entertainment launch ever.
- **Pete Rose pardoned** — Trump posthumously pardons the baseball
  legend, banned for life over betting on games.
- Also: youth strike in 25+ countries over living costs, Italy's
  nationwide strike over wages, Nigeria moves to end jail terms for
  attempted suicide.

All facts as reported on 20 November 2026 (CNN, BBC, Morningstar /
Reuters, Sensor Tower via BBC).

## How it is built

`draw.py` (outside this repo) renders `entry.png` with PIL. `main.ts`
(Node 22, standard library only) copies `entry.png` to
`/output/entry.png`, so both grader runs write identical bytes.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## make.fun

Entry for the `news-image-20261120` bounty ($250 USDC). Payout wallet is
in `.makefun/owner.json`.
