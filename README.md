# tiny-chess-01 entry

A chess engine in a single `main.py` under 4 KB (the engine source is
lzma-packed into the file, a form the rules explicitly allow).
Negamax alpha-beta with quiescence, transposition table, null-move
pruning, late move reductions, piece-square tables, and threefold
repetition avoidance. Deterministic: fixed node budget, no clock.
Python 3 standard library only.
