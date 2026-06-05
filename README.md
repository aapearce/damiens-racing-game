# 🏎️ Damien's Racing Game

A neon-arcade go-kart **time trial**. One self-contained `index.html` (inline
CSS + Canvas, no build step, no dependencies) — deploys instantly on GitHub
Pages, part of [Damien's Arcade](https://aapearce.github.io/damiens-arcade/).

## How to play

- Wait for the **five red lights** above to go out, then race.
- **Desktop:** `↑` gas · `↓` brake · `← →` steer (WASD also works).
- **Phone / tablet:** on-screen pedals (⛽ gas, ⛔ brake) and ◀ ▶ steering.
- Get the fastest time from the **chequered start line** to the **chequered
  finish**. Keep all four wheels on the tarmac — the grass slows you down.

## The track (~90 seconds)

A pseudo-3D (OutRun-style) course through three environments, each about 30s:

1. 🌲 **Forest** — pine-lined country road.
2. 🏖️ **Beach** — sandy shoulders, palm trees, and **grandstands packed with a
   cheering crowd**.
3. 🌆 **Neon Strip** — a synthwave night straight glowing pink & cyan, matching
   the arcade theme, up to the finish flag.

## Leaderboard

Your time is recorded at the finish. Top-10 times are saved **locally in your
browser** (`localStorage`) — enter 3 initials to add yours. A new best lights up
the board. "Clear scores" wipes it.

## Run it locally

```bash
node server.cjs 8015      # then open http://localhost:8015
```
…or just open `index.html` in a browser.

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
