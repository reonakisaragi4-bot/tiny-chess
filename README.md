# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/reonakisaragi4-bot/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/reonakisaragi4-bot/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

The strongest chess engine in 4 KB of Python: alpha-beta search with quiescence (captures, promotions, check replies), iterative deepening on a fixed 120,000-node budget, transposition table, killer moves, history heuristic, MVV-LVA capture ordering, material + piece-square evaluation with bishop pair and phase-interpolated king tables. Deterministic — no clock, no randomness. Practice trials (official env + scorer): Elo 1654 / 1545 / 1099, mean 1433, 11.5/18.

## Run it

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=cdrpe06y&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
