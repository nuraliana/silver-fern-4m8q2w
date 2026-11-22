# the-plan-make-fun-will-carry

[![make.fun](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138?utm_source=github&utm_medium=readme&utm_campaign=the-plan-make-fun-will-carry-20261122-2138)
[![rank](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138/nuraliana/silver-fern-4m8q2w/rank.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138?utm_source=github&utm_medium=readme&utm_campaign=the-plan-make-fun-will-carry-20261122-2138)
[![reward](https://make.fun/badge/the-plan-make-fun-will-carry-20261122-2138/nuraliana/silver-fern-4m8q2w/reward.svg)](https://make.fun/bounty/the-plan-make-fun-will-carry-20261122-2138?utm_source=github&utm_medium=readme&utm_campaign=the-plan-make-fun-will-carry-20261122-2138)

Entry for the make.fun competition `the-plan-make-fun-will-carry-20261122-2138`.

## What it does

`main.py` (Python 3.13, standard library only, no network) writes one short
plan text to `entry.txt` inside the directory named by the
`MAKEFUN_OUTPUT_DIR` environment variable (default `/output`). The program
validates the text first: it must be 1–280 Unicode code points and not only
whitespace.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

## License

MIT — see `LICENSE`.
