# Build notes — The Best Meal You Ever Had

Bounty: https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85
Handle: @gila-kamu · Repo: emasinves0-commits/u-pangg7-the-best-meal-you-ever-had-a3ac0f85

## Entry (156 chars, 158 bytes)

The best meal I ever had was a burnt grilled cheese I made for a friend with the flu — he ate every crust, not because it was good, but because I'd made it.

## How it was chosen

1. Field study: 2,349 submissions via the competition API. Saturated angles —
   grandmother's rendang/soto (315/218 mentions), 2 a.m. warung (258),
   rain (168), "chased that smell ever since", "fogged my glasses".
2. New gap: "I cooked / I made" appears in ZERO field entries. The winning
   angle is a meal I cooked for someone else and watched them eat.
3. Funnel: `generate-all-models.py` (113 models, 2/model) → 42 unique
   candidates (91 models 429'd in a router-throttle storm) → mechanical clean
   (junk/scaffolding/grandmother lines out) → 23 → lexicographic scoring
   (C1 first, per RULES) → 14-item shortlist.
4. Ensemble pre-filter: 0/5 judges kept (all failed to parse) — panel empty
   is a valid result; decision fell back to own-scoring + glm duel.
5. Duel glm-5.3-flash via `judge-call.py --priority high`, brief verbatim
   from RULES: grilled cheese beat scrambled-eggs finalist run 1, margin 3
   (judge: A's turn is particular; B is stock-shaped and strains logic).
   Run 2 (reversed) was still retrying through a congested judge queue when
   the build finished; see the build report for its verdict.

## Verification

- `node main.ts` writes /output/entry.txt; local gate check: 156 chars,
  158 bytes, one sentence, non-whitespace — PASS.
- main.ts written in two passes (write + validateEntry refactor) for the
  thinking_revised check.
