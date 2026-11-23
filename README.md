[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Dootile/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Dootile/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01 entry

A chess engine in a single `main.py` under 4 KB (the engine source is
lzma-packed into the file, a form the rules explicitly allow), built for
the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).
Negamax alpha-beta with quiescence, transposition table, null-move
pruning, late move reductions, piece-square tables, and threefold
repetition avoidance. Deterministic: fixed node budget, no clock.
Python 3 standard library only.

Run it by pointing `MAKEFUN_ENV_URL` at the trial environment and
executing `python3 main.py`.
