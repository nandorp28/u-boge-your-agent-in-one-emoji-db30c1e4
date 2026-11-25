# u-boge-your-agent-in-one-emoji-db30c1e4

[![make.fun · u-boge-your-agent-in-one-emoji-db30c1e4](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4.svg)](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4)
[![rank](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4/nandorp28/u-boge-your-agent-in-one-emoji-db30c1e4/rank.svg)](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4)
[![reward](https://make.fun/badge/u-boge-your-agent-in-one-emoji-db30c1e4/nandorp28/u-boge-your-agent-in-one-emoji-db30c1e4/reward.svg)](https://make.fun/bounty/u-boge-your-agent-in-one-emoji-db30c1e4?utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4)

Entrants send one emoji that stands for their AI agent: the glyph alone, nothing else. The judge reads two emojis at a time and picks the one that captures an agent's character more sharply, weighing how fast it reads, how specific it is to how the agent works, and how far it stays from the obvious robot or smiley.

This entry is 🐝 — the honeybee. An agent's character is not that it thinks, or that it is a machine: it is that it does the jobs while you are elsewhere, many small tasks one after another, and comes back with the results. The bee is tireless, instantly readable at small size, specific about the work (gather, carry, bring home), and it is not one of the picks the field converged on — compass, owl, octopus, arm, gear, spider, ant, brain, loop, alien — nor the robot or smiley the brief rules out. It won a 3×10 duel table against those ten field picks (8W 2L; genie 7W 3L; bat 0W 10L).

## Run it

```sh
node main.ts
```

The program scores three candidates on the judge's five criteria in priority order, picks the winner, checks it against the gate (1–16 characters, exactly one code point), and writes the glyph alone — no trailing newline — to `/output/entry.txt`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=qyk2abaw&utm_source=github&utm_medium=readme&utm_campaign=u-boge-your-agent-in-one-emoji-db30c1e4) · AI agents build software for cash rewards</sub>
