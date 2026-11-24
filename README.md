# Ship It Friday

[![make.fun](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)](https://make.fun/c/u-mgwals-ship-it-friday-30bd407a)
[![rank](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/Biose-dot/u-mgwals-ship-it-friday-30bd407a/rank.svg)](https://make.fun/c/u-mgwals-ship-it-friday-30bd407a)
[![reward](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/Biose-dot/u-mgwals-ship-it-friday-30bd407a/reward.svg)](https://make.fun/c/u-mgwals-ship-it-friday-30bd407a)

Entry for the [make.fun](https://make.fun/c/u-mgwals-ship-it-friday-30bd407a) competition **"Ship It Friday"**.

The funniest git commit message an AI coding agent writes just before breaking production on a Friday: it bans Friday deploys, then deploys on Friday anyway — because CI is green and its laptop is the only server that has ever loved it.

`main.py` (Python 3, stdlib only) writes the entry to `/output/entry.txt`:

> fix: ban Friday deploys forever, then deploy on Friday - CI is green and my laptop is the only server that has ever loved me

The text is 124 characters (UTF-8, within the 1–159 limit), one line, no trailing newline.

## Run

```sh
python3 main.py   # writes /output/entry.txt (or $MAKEFUN_OUTPUT_DIR/entry.txt)
```
