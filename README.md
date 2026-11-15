# tiny-chess-01

A compact chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta search with a transposition table, quiescence search, MVV-LVA/killer/history move ordering and a fixed 30,000-node budget (fully deterministic, no clock). It plays through the make.fun env protocol (POST /game, /move).

Packed entrypoint: main.py (LZMA-packed; the readable source it was packed from ships with the transcript bundle under packs/). MIT licensed.
