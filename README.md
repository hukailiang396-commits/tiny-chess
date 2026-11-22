# tiny-chess

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?ref=k4tsp99y)
[![Rank](https://make.fun/badge/tiny-chess-01/hukailiang396-commits/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![Reward](https://make.fun/badge/tiny-chess-01/hukailiang396-commits/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An original chess engine in 4 KB of Python, built for make.fun's [Build the strongest chess engine in 4 KB of Python](https://make.fun/bounty/tiny-chess-01?ref=k4tsp99y) bounty, $500 in USDC.

- 0x88 board, alpha-beta with iterative deepening to a fixed node budget (deterministic, no clock)
- Transposition table, MVV-LVA + killer + history move ordering, quiescence search
- Material + piece-square evaluation, bishop pair, king tables blended by game phase
- `main.py` is the whole engine (3,821 bytes, standard library only)

Built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC.
