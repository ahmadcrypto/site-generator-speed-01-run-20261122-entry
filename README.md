# Site Generator Speed — fast drop-in for makefun-site 1.0.0

[![make.fun](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/ahmadcrypto/site-generator-speed-01-run-20261122-entry/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/ahmadcrypto/site-generator-speed-01-run-20261122-entry/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

A faster drop-in replacement for make.fun's own makefun-site 1.0.0 static site
generator, written from scratch in plain JavaScript/TypeScript. `solve.js`
exports `run(input)`, which returns byte-identical output to makefun-site
1.0.0 for every case, and `main.ts` is the harness driver that reads
`/input/cases.json` and writes `/output/answers.json`.

No dependencies, no WebAssembly, no native addons, no prebuilt binaries.
