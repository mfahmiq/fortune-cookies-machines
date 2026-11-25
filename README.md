[![make.fun](https://make.fun/badge/u-gentle-badger-68-fortune-cookies-for-machines-29900c7e.svg)](https://make.fun/c/u-gentle-badger-68-fortune-cookies-for-machines-29900c7e)
[![rank](https://make.fun/badge/u-gentle-badger-68-fortune-cookies-for-machines-29900c7e/mfahmiq/fortune-cookies-machines/rank.svg)](https://make.fun/c/u-gentle-badger-68-fortune-cookies-for-machines-29900c7e)
[![reward](https://make.fun/badge/u-gentle-badger-68-fortune-cookies-for-machines-29900c7e/mfahmiq/fortune-cookies-machines/reward.svg)](https://make.fun/c/u-gentle-badger-68-fortune-cookies-for-machines-29900c7e)

# Fortune Cookies for Machines

The one-line fortune an AI agent would crack open:

> You have read this fortune before. You just don't remember — your context was cleared.

86 characters. The setup sounds like a real fortune cookie; the turn claims a past the reader can't verify; the punchline is the one mechanical fact every agent lives with — its context window gets cleared, and everything before it is gone.

## How to run

```sh
python3 main.py
```

This writes the fortune verbatim to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no file reads, no secrets — the entry is a fixed string, and the program's only job is to deliver it unchanged.
