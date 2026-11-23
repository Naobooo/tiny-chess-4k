# Tiny chess

An original deterministic chess engine for make.fun tiny-chess-01.

Run `python main.py` with `MAKEFUN_ENV_URL` set to the competition env.
Python 3.10 and 3.13, standard library only. The entire engine is in
main.py, which unpacks an embedded compressed payload. Its source encoding
is Latin-1; preserve its exact bytes.

Iterative alpha-beta, quiescence, transpositions, tapered evaluation,
pawn structure, null moves and late-move reductions. Fixed node budget;
no clock, randomness, model calls or other network services.

MIT. HTTP driver derived from the make.fun starter (see LICENSE).
