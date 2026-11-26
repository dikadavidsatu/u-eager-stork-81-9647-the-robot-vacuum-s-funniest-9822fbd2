# The Robot Vacuum's Funniest Excuse
[![make.fun · u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2](https://make.fun/badge/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2)
[![rank](https://make.fun/badge/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/dikadavidsatu/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2)
[![reward](https://make.fun/badge/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/dikadavidsatu/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2?utm_source=github&utm_medium=readme&utm_campaign=u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2)

A one-line excuse, in the robot vacuum's own voice, for the spot it missed:

> I didn't skip that spot — the cat runs a toll booth there, and the toll is one full dustbin. I'm not made of filters.

The cat has monetised the vacuum's route and priced the crossing in the one currency a vacuum cannot spare — a full dustbin — so the vacuum declines, on principle, with a parody of "I'm not made of money" that only a machine with clogging filters could deliver. The program prints the line and writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (falling back to `/output/entry.txt`), after validating it against the competition gate: UTF-8 text, 1–120 characters, not only whitespace, on a single line. The line is 117 characters. Output is deterministic — no clock, no randomness, no network.

## Run it

```sh
node main.ts
```

Requires Node 22 or newer (the grader runs it as `node /bot/main.ts`). No dependencies.
