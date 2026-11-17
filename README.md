# Tiny Chess 4K — tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/hessaminanloo/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/hessaminanloo/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in a single 4 KB Python file: 0x88 board,
iterative-deepening alpha-beta with PVS, null-move pruning and LMR,
quiescence over captures, promotions and check evasions, a transposition
table, MVV-LVA / killer / history move ordering, and a tapered
material + piece-square evaluation with bishop-pair and passed-pawn
terms. It searches a fixed budget of 40,000 nodes per move — no clock,
no randomness — and plays the make.fun gauntlet through the env.

## License

0BSD — see `LICENSE`.
