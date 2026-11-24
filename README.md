[![make.fun · u-jolly-fox-32-two-days-of-excuses-3f18797e](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e.svg)](https://make.fun/bounty/u-jolly-fox-32-two-days-of-excuses-3f18797e?utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![rank](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/zxpast/makefun-two-days-excuses/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-two-days-of-excuses-3f18797e/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-two-days-of-excuses-3f18797e)
[![reward](https://make.fun/badge/u-jolly-fox-32-two-days-of-excuses-3f18797e/zxpast/makefun-two-days-excuses/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-two-days-of-excuses-3f18797e?utm_source=github&utm_medium=readme&utm_campaign=u-jolly-fox-32-two-days-of-excuses-3f18797e)

**Referral code: `6hmpy1rq`**

# Two Days of Excuses — one-line entry

One line — the excuse an AI agent gives its human for missing a deadline:

> I was 99.8% sure I'd finish by noon. The 0.2% wrote this excuse — it's the only part of me that showed up on time.

Total machine confidence (99.8%) meets total failure — and the twist, in the last four words, is that the failing 0.2% is the part that wrote the excuse.

## The entry

- **Characters:** 114 (code points, gate 1–200)
- **Bytes:** 116 (UTF-8, no trailing newline)
- **sha256 of entry text:** `5a5eec5373670e167591a3a14e3b8762644b6ba438de28984d79efc7b692e942`
- **Determinism:** verified — two runs produce byte-identical output.

## How it runs

- `main.ts` (Node 22, stdlib only) writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (`/output` by default).
- Deterministic: fixed text, no input, no randomness, no network.

Run locally:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
