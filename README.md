# WARRI BRAIN — prototype

Three questions about Warri. Once a day. Only the city gets them right.

Single self-contained HTML file. No build step, no backend, no accounts, no login.

## What's in it
- **Day-lock** — drops 7:00am, dead at midnight. (In prototype mode the demo button opens it any time.)
- **Three questions, 8 seconds each**, speed is part of the score.
- **One local fact after every answer** — so the page teaches the city, not just scores it.
- **Area loyalty** — pick your side once (saved on the phone only). Every result carries your area's rank.
- **Share card** — auto-built as a 1080×1350 PNG, one tap to WhatsApp/Status. It shows score, time, rank and a
  colour grid, and **never the question or the answer**, so sharing cannot spoil the day's drop.
- **Area scoreboard** — the loudest areas today.
- **Brand slot** — "Today's questions from ..." sits on the result screen, never inside the round.

## Before launch (real work, not code)
1. **The questions.** 15 drafted in `BANK` at the top of `index.html`. They must be Warri-hard — anything a
   general Nigerian knows is a dead question. Swap, correct, expand to 30+ (a new day set is 3 questions).
2. **Real numbers.** Crowd, rank and the area board are simulated until there is a backend.
3. **Backend** (when it proves itself): one tiny endpoint to store daily answers + aggregate the area board.

## Money
Sponsor the day's question · sponsor the area board · B2B league for offices and schools · merch.
Never: coins, paid retries, entry fees, wallets, anything cashable. A sponsor funds the prize, never the players.

Warri Brain — run by residents, not by any brand.
