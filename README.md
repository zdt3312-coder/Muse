# tiny-chess-01 entry

A compact chess engine in 4 KB of Python: negamax + PVS alpha-beta,
transposition table, quiescence search, null-move pruning, LMR and a
tapered PeSTO evaluation. Fixed node budget, fully deterministic.

`main.py` is the packed entrypoint, produced from the readable source
`engine.py` (kept in this folder) by the make.fun kit command
`node cli/makefun.mjs compress engine.py --out main.py`.
