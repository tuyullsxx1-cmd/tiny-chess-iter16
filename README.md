# tiny-chess-iter16

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tuyullsxx1-cmd/tiny-chess-iter16/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tuyullsxx1-cmd/tiny-chess-iter16/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4 KB of Python (stdlib only), rebuilt from scratch — iteration 16. 0x88 board, incremental tapered PeSTO eval, Zobrist transposition table, PVS, null-move pruning (R=3), killer moves, MVV-LVA ordering, captures-only quiescence, iterative deepening with a fixed 80,000-node budget and late-move reduction. Deterministic: node budget only, never a wall clock. Local 6-game gauntlet mean 1451 Elo (vs 1367.7 for iteration 15).

## Run it

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=sjsshy4j&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
