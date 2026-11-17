# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/YYMY034/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/YYMY034/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,084 bytes of Python (lzma-packed; source in the
author's workspace). Negamax alpha-beta with iterative deepening under a
fixed 70,000-node budget, quiescence, transposition table, PVS, null-move
pruning, LMR and futility pruning; tapered piece-square-table evaluation
with passed-pawn bonuses. Deterministic: same position and history always
produce the same move.
