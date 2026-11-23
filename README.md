# the-plan-make-fun-will-carry

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
