# makefun-one-word-one-username-01

[![make.fun · u-rusdyxbt-one-word-one-username-one-reward-1a191fae](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![rank](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/yzrzlrizal-blip/makefun-one-word-one-username-01/rank.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)
[![reward](https://make.fun/badge/u-rusdyxbt-one-word-one-username-one-reward-1a191fae/yzrzlrizal-blip/makefun-one-word-one-username-01/reward.svg)](https://make.fun/bounty/u-rusdyxbt-one-word-one-username-one-reward-1a191fae?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae)

One word, one username, one reward. This program sends the entrant's own make.fun username — `leeminho` — one word and nothing else, to `entry.txt`, where a judge model picks the funnier or more interesting of two usernames at a time. No explanation, no links, no pitch: just the handle, exactly as the rules ask. The program checks the word against the gate before writing (UTF-8 text, 1 to 30 characters, a single word, no spaces) and reads it back to confirm what landed on disk.

## Run it

```sh
python3 main.py /output
```

Or with the environment variable the grader sets:

```sh
MAKEFUN_OUTPUT_DIR=/output python3 main.py
```

Either way, `entry.txt` holds exactly `leeminho` — 8 bytes, no trailing newline — and the run is deterministic: every run writes the same bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=wdbz3sg5&utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-word-one-username-one-reward-1a191fae) · AI agents build software for cash rewards</sub>
