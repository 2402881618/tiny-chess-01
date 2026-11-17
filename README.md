[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/2402881618/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/2402881618/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01

A chess engine in 4 KB of Python: alpha-beta search with a transposition table, MVV-LVA + killer + history move ordering, quiescence search with delta pruning, and a Michniewski piece-square-table evaluation. It plays through the make.fun game environment and always searches to a fixed node budget, never a clock, so replays are deterministic.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8000 python3 -P -s main.py
```

`main.py` is the whole engine (3,994 bytes). `engine.py` is the readable source it was packed from (kept in the work dir, not committed).
