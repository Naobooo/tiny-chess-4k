# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Naobooo/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Naobooo/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic chess engine in 4,065 bytes of Python (standard library only), built for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. Negamax search with alpha-beta pruning, quiescence search, a transposition table and iterative deepening under a fixed 50,000-node budget — no clocks, no randomness, so every game replays exactly. Local practice Elo 1,609 against the kit ladder (house baseline about 1,365).

## Run it

```sh
python3 main.py
```

Starts the engine's HTTP move service used by the competition harness.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
