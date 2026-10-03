# Buildcrafting Framework

Reviewed: 2026-09-06. This is decision logic, not a static tier list.

A complete build is a combat plan: survival, damage, control, ammo, and execution under an activity's constraints. Optimize the chance of accomplishing the stated goal, not just a favorable damage screenshot.

## Choose the primary objective

| Objective | Compare using | Common trap |
|---|---|---|
| Short boss phase | Damage delivered inside the actual window, including setup/cast time | Peak DPS that starts after the phase ends |
| Sustained boss damage | Repeatable damage, total reserves, reloads, safe uptime | Ranking first magazine only |
| Solo/duo completion | Survival without a kill, control, recovery, ammo | Assuming teammates supply every buff or stun |
| Add clear/farming | Reliable clears per hour and eligible rewards | Slow difficulty that gives worse real returns |
| Mechanics/support | Completion reliability, team damage, buffs, revives | Double-counting support already covered |
| PvP | First-fight consistency, range, handling, breakpoints, objective value | Kill-chain bonus treated as always active |
| Speed | Full-run time, consistency, movement, reset cost | A skip that loses more time when it fails |

## Assemble one connected plan

1. Fix activity, class constraints, role, and practical difficulty.
2. Identify a small number of credible exotic/subclass engines from current evidence.
3. Map each engine's trigger, payoff, cooldown/lockout, and recovery.
4. Choose an exotic armor piece and independently allocate the exotic weapon slot. They can be used together.
5. Cover survival outside the ideal loop; include safe range, cover, movement, healing or resistance.
6. Choose weapons for adds, majors, boss, ammo, and actual Champion types.
7. Select an artifact whose current perks reinforce this plan; use exact perk definitions.
8. Compare set bonuses, stat distribution, mods, and any activity-specific armor.
9. Check legal equipment, then compare expected results under the same conditions.
10. Write practical execution and explain the biggest tradeoff.

## Stat and armor logic

Use **Health, Weapons, Class, Grenade, Melee, Super**. Armor 3.0 generally uses individual stat points and distinct benefits above 100; verify the actual benefit in the relevant mode. Do not transplant the old 100 Resilience rule or assume PvE bonuses affect Guardians.

There are 12 archetypes in the checked Monument rules; see [armor](../gear/armor.md). Archetypes shape obtainable distributions, not universal rankings. Evaluate set value and actual roll distribution together.

- Weapons can matter for handling, reloads, ammo and damage, but verify which effect, target category, and stat region applies.
- Health is not interchangeable with damage resistance, healing, shields, or immunity.
- Class matters when the class ability drives the engine; Grenade/Melee when the selected ability and its energy source matter.
- Super investment depends on the chosen Super, damage contribution, active regeneration, and encounter length.
- Flat energy returns, passive cooldowns, base recharge multipliers, and instant refunds are different. Do not assume more ability stat always fixes a refund-dependent loop.

## Reliability and coverage

Check kill dependence, self-triggering versus allied triggers, buff duration, internal cooldown, boss restrictions, energy scalars, and reserve economy. An on-kill heal can be strong in a wave and absent during solo boss damage.

A source of weaken is not automatically a stacking extra debuff. Suppression, scorch, crowd control, and bonus damage have different jobs. See [damage and survival](damage-and-survival.md).

For solo, cover every Champion actually present. For duo/team, explicitly assign coverage; retain a reasonable fallback. Account for immune/recovery windows and lost ability uptime.

## Current-source discipline

Use the [Compendium map](../data/compendium-index.md), relevant [live sheet](../data/live-google-sheets.md), and [known issues](../00-start-here/source-notes.md). Endgame Analysis's "Exotic Armor (ignore)" and "Builds (ignore)" tabs are not authoritative build rankings. Historical S28 damage tabs are not automatically the current answer.

Class candidates and creator guides start a comparison; they do not finish it. Validate with [build validation](build-validation.md).
