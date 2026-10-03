# Damage, Survival, and Rotation Reasoning

Reviewed: 2026-09-06. These are calculation rules; no example below is a measured Destiny result.

## Compare the right quantity

- Phase damage = all damage delivered before immunity returns.
- Sustained DPS = damage divided by the full repeating cycle, including required reloads, swaps, casts, and pauses.
- Full-run speed includes mechanics, traversal, ammo preparation, deaths, and resets.
- Team DPS includes support's effect on teammates and its opportunity cost.
- Reserves determine total damage; a high first-magazine ranking does not prove a solo boss setup is best.

Use [Boss Damage](../data/live-google-sheets.md) for measured inputs. Record encounter/test target, power normalization, window, range, accuracy, ammo, artifact, armor, and team effects. Do not combine differently normalized tables.

## Stacking

Build a ledger before multiplying:
| Effect | Source | Category | Value | Trigger / duration | Target restriction |
|---|---|---|---|---|---|

Determine whether each effect stacks, adds within a pool, uses only the strongest effect, or has a special exception. Empowering buffs, surges, weapon traits, debuffs, artifact effects, encounter modifiers, and additive melee pools must be classified using current data.

For independent multipliers only, 1.20 × 1.10 = 1.32, a 32% gain. Two descriptions that say "+20%" do not establish independence.

Use [Court's sheet](https://docs.google.com/spreadsheets/d/1i1KUwgVkd8qhwYj481gkV9sZNJQCE-C3Q-dpQutPCi4/edit) and the exact Compendium entries for classification. A weaken/debuff family can override another; suppression and scorch are not general vulnerability multipliers.

## Survival

For applicable independent damage reductions:
- Remaining incoming damage fraction = product of (1 - each DR).
- Total DR = 1 - that product.
- Effective health under those same conditions = usable health/shields divided by remaining damage fraction.

Arithmetic example: 20% DR with an independent 30% DR gives 44% total DR, not 50%. This is an illustration, not a recommended mod combination.

Separate resistance, health/shields, restoration/healing rate, overshields, immunity, crowd control, and avoiding shots. Conditional defenses need realistic uptime. An on-kill heal does not protect the player before the first kill or during an add-free damage phase.

## Ability economy

Distinguish passive cooldown, additional base recharge, flat percentage energy, instant refreshes, charges, and energy-source scalars. A perk described as returning energy can be affected by the chosen ability's scalar. [Clarity's chunk-energy explanation](https://www.d2clarity.com/blog/destiny-science-6/chunk-energy-scalars-breakdown-12) explains why nominal refunds may differ; check current values in the exact ability entry.

## PvP

Use a current weapon calculation and target conditions. For N required shots at constant RPM, a simple hitscan firing interval is (N - 1) × 60 / RPM. Burst spacing, charge/draw time, damage ramps, projectiles, pellets, overshields, falloff, and rounding may require another model.

Record Health and temporary defenses, crit/body mix, kill-activated perks, mode-specific bonuses, range, and accuracy. Do not treat low-Health or fully buffed TTK as the neutral duel.

## Rotations

Specify setup, initial ammo/charges, actions in order, refresh triggers, phase end, and recovery. Respect loadout locks and costs of exotic/ability swaps. For solo/duo, include a lower-risk rotation when lost uptime or a death would erase the theoretical advantage.
