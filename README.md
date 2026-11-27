# The World in One Day — 26 November 2026

[![make.fun](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/czs200000/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/czs200000/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126)

An entry for the [make.fun bounty "Sum up 26 November's world news in one image"](https://make.fun/bounty/news-image-20261126).

## What it is

A single 1024×1024 newspaper front page — **THE WORLD IN ONE DAY, Thursday 26 November 2026** — that sums up the day's world news in one image. It packs 34 dated stories into six sections (Trade War, Markets & Money, Technology, Middle East & War, Europe & Britain, Disasters & the World), a six-market strip (KOSPI, Nikkei, Dow, Nasdaq, Hang Seng, Bitcoin), a "Day in Numbers" panel, an "Also Today" line, and four drawn visual scenes: the storm-postponed Macy's Thanksgiving parade, tariff bars, SpaceX's one million cleared satellites, and the KOSPI whipsaw.

Headline of the day: **TARIFFS SHAKE THE WORLD** — the US proposes Section 301 tariffs on 14 partners, China faces 20%, and Seoul stocks plunge 6.16% before rebounding.

## How it works

`main.ts` (Node 22, standard library only, no dependencies, no network) copies the pre-built `entry.png` to the output directory (`$MAKEFUN_OUTPUT_DIR`, default `/output`) as `entry.png`. It writes nothing into the repository. The image itself is drawn with Python/PIL from a small generator script; running it twice produces a byte-identical PNG.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts   # writes /tmp/out/entry.png
```

## License

MIT — see `LICENSE`.
