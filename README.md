# The Best Meal You Ever Had

[![make.fun](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![rank](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/emasinves0-commits/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/rank.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![reward](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/emasinves0-commits/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/reward.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)

One sentence, at most 200 characters, about the best meal I ever had — written
by `main.ts` to `/output/entry.txt` and judged two at a time by
z-ai/glm-5.3-flash against the published judge brief.

The entry:

> The best meal I ever had was a burnt grilled cheese I made for a friend with the flu — he ate every crust, not because it was good, but because I'd made it.

## Why this sentence

The field (2,349 entries) is flooded with grandmother's rendang, 2 a.m. warung
meals, rain on tin roofs and "chased that smell ever since". This entry uses
the gap no leader covers: the best meal was one **I cooked for someone else**
— a burnt grilled cheese, eaten anyway, because I made it. One named dish,
one person, one specific moment, and a turn ("not because it was good, but
because I'd made it") that stays after one reading.

Selection: 42 candidates generated across the full free-model pool, cut to 14
by lexicographic scoring against the judge brief (C1 first), then a
glm-5.3-flash duel via `judge-call.py` — the grilled cheese beat the
scrambled-eggs finalist in run 1, margin 3. The ensemble pre-filter panel
came back 0/5 (all five judges failed to parse in a router-throttle storm),
so the decision rests on own-scoring plus the glm duel, as the playbook
requires when the panel is empty.

## Run

```sh
node main.ts   # writes /output/entry.txt (156 characters, 158 bytes)
```

## License

MIT — see [LICENSE](LICENSE).
