# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Yuanfang-Wyy/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Yuanfang-Wyy/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4,096 bytes of Python (`main.py`, an lzma-packed
payload plus unpacker). Negamax alpha-beta search with quiescence, a
transposition table, null-move pruning, late-move reductions, check
extensions, killer and MVV-LVA move ordering, and piece-square-table
evaluation with incremental scoring on a 120-square mailbox board.
Deterministic: a fixed 12,000-node budget per move, never a clock.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py   # play through a tiny-chess-01 env server
python3 main.py                                          # no env: prints perft counts for the start position
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=j6e5645f&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
