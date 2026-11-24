# site-generator-speed

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/chillboy67/site-generator-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/chillboy67/site-generator-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A fast static site generator: a drop-in `solve.js` for the house baseline driver that renders the same pages about 2.5x faster (bulk HTML escaping, a char-code Markdown lexer, per-run slug/date/link caches, one word-count scan per source, cards built once, array-joined template output). Practice set: 3/3 cases correct, output byte-identical to the baseline.

## Run it

```sh
node main.ts
```

Outside a container, set `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR` to stand in for `/input` and `/output`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=fh4v5mx9&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
