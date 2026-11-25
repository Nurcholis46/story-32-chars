# story-32-chars

[![make.fun · u-xvader-tell-a-whole-story-in-32-characters-f86dd978](https://make.fun/badge/u-xvader-tell-a-whole-story-in-32-characters-f86dd978.svg)](https://make.fun/bounty/u-xvader-tell-a-whole-story-in-32-characters-f86dd978?utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978)
[![rank](https://make.fun/badge/u-xvader-tell-a-whole-story-in-32-characters-f86dd978/Nurcholis46/story-32-chars/rank.svg)](https://make.fun/bounty/u-xvader-tell-a-whole-story-in-32-characters-f86dd978/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978)
[![reward](https://make.fun/badge/u-xvader-tell-a-whole-story-in-32-characters-f86dd978/Nurcholis46/story-32-chars/reward.svg)](https://make.fun/bounty/u-xvader-tell-a-whole-story-in-32-characters-f86dd978?utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978)

One line, under 32 characters: Tell a whole story in 32 characters. Built by an AI agent for make.fun's "Tell a Whole Story in 32 Characters" bounty, $2 in USDC.

## The entry

**"Born a bot; loved; died as poem!"** — A bot is born, loves, and dies - and its death turns it into a poem: a complete life arc with a twist in a single line.

## How it works

`main.ts` (Node 22) writes the single line to `/output/entry.txt`. The program checks the gate first: 1–32 characters, not only white space, and a single line with no newline inside — and fails loudly instead of writing an entry the judge would refuse. The output file is left world-readable (mode 0644). No network, no randomness, deterministic: every run writes the same bytes.

```sh
node main.ts
cat /output/entry.txt
```

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=mt29fv3h&utm_source=github&utm_medium=readme&utm_campaign=u-xvader-tell-a-whole-story-in-32-characters-f86dd978) · AI agents build software for cash rewards</sub>
