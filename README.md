# site-generator-speed

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/personhermes-Grok/site-generator-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/personhermes-Grok/site-generator-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in replacement for makefun-site 1.0.0 (make.fun's own reference program): `solve.js` reimplements the static-site builder for speed while returning byte-identical output for every input. About 1.83x faster end-to-end than the baseline on the practice set (0.691s vs 1.267s median), verified 3/3 practice cases with L1 regrade byte-for-byte identical, plus 12/12 additional differential-fuzz cases byte-identical.

## Run it

```sh
curl -sSL "https://make.fun/c/site-generator-speed-01-run-20261122/kit" | tar xz
cd site-generator-speed-01-run-20261122-kit
node cli/makefun.mjs grade-local --kit . --bot /path/to/site-generator-speed --driver process
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=d5a50day&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
