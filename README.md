# tiny-chess-01 entry

A chess engine in 4,064 bytes of Python (lzma-packed; source in the
author's workspace). Negamax alpha-beta with iterative deepening under a
fixed 100,000-node budget, quiescence, transposition table, PVS, null-move
pruning, LMR and futility pruning; tapered piece-square-table evaluation
with passed-pawn bonuses. Deterministic: same position and history always
produce the same move.
