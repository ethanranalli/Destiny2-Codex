# Build Validation

Reviewed: 2026-09-06. Run mentally against the completed card. Fix failures before calling a setup complete. Do not print this entire checklist in every response.

## Legality

- Correct class and exact subclass; abilities, Super, aspects, and fragments belong to that subclass.
- Fragment count fits the current selected aspects. No automatic assumption of four, five, or six slots.
- Prismatic abilities come from the Prismatic pool; Super-element dependencies and Transcendence are accounted for.
- At most one exotic armor piece and one exotic weapon; both slots can be used together.
- Exotic class item perks are legal for the class and both perk columns, with Prismatic active. Spirit perks need not reproduce the full exotic's behavior.
- Every weapon fits its inventory slot. Its perks, catalyst, origin trait, enhancement, and mod actually exist on that version.
- Each armor piece fits the mod slots and energy available, including stat mods. Apply artifact discounts only when that artifact is active.
- Set-piece count accounts for the exotic slot and real equipped items. Armor ornaments do not imply functional set bonuses.
- Current artifact tier limits, mutually exclusive picks, and total allocation are respected; no mixing perks from different artifact items.
- Locked loadouts, swap penalties, disabled items, and playlist artifact rules are respected.

## Function

- Every central perk has an actual trigger in the loadout.
- Armor Charge generation, consumption/decay, and upkeep are compatible. Do not rely on two spending loops without an uptime plan.
- Survival works during boss downtime and after a failed ability/kill.
- Champion effects and activation are verified for exact weapons/verbs, with ammo and recovery windows.
- Buff/debuff stacking categories and target restrictions are checked; no duplicate benefit is counted twice.
- Damage and ability energy account for patch, artifact, range, enemy rank, cooldown scalar, and activation timing.
- Reserves and orb/kill requirements are attainable in the encounter; no free ammo, free reloads, or infinite uptime assumptions.
- Both ordinary play and emergency recovery are explainable in a few steps.

## Feasibility and evidence

- All six stat targets include fragment adjustments and distinguish permanent from conditional values.
- Unknown armor does not support a claim that exact targets are equip-ready. Give target ranges and minimum energy/tier assumptions.
- Required exotics, catalysts, class item rolls, unlocks, DLC, and mods are supported by personal data or labeled as assumptions with alternatives.
- Current sources were actually read, not merely found. Record date checked separately from the author's date.
- A theoretical ranking is not presented as in-game-tested by this helper.
- PvP TTK gives target Health/overshield assumption, crit/body requirement, range, and perk uptime; omit an unverified breakpoint.
- Damage comparison uses matching windows and conditions; uncertainty that could change the winner is visible.
- The card includes exact artifact selections for non-PvP combat, or explicitly explains the missing evidence and marks it provisional.

## Output decision

**Complete:** legal, internally consistent, sufficiently supported, with clear equipment assumptions.
**Provisional:** still useful, but a required live mechanic, modifier, or owned item is unknown. State exactly what prevents final validation.
**Needs clarification:** unknown mode/encounter or a hard user constraint prevents a defensible choice. Ask only that missing question.

Do not silently drop artifact, armor mods, or substitutions to make a build look finished.
