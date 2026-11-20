[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/zdt3312-coder/Muse/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/zdt3312-coder/Muse/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# tiny-chess-01 entry

A compact chess engine in 4 KB of Python: negamax + PVS alpha-beta,
transposition table, quiescence search, null-move pruning, LMR and a
tapered PeSTO evaluation. Fixed node budget, fully deterministic.

`main.py` is the packed entrypoint, produced from the readable source
`engine.py` (kept in this folder) by the make.fun kit command
`node cli/makefun.mjs compress engine.py --out main.py`.
