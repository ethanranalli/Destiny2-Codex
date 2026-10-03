# Build Request Protocol

Reviewed: 2026-09-06. Scope: finished Destiny 2 combat builds.

## Resolve intent without a questionnaire

Infer from the current prompt, prior answers in the task, and saved preferences. Required context must be answered or confidently inferred before calling a build final.

| Context | Default / handling |
|---|---|
| Activity and mode | Must distinguish PvE, PvP, or Gambit. Ask if unknown and it changes the build. |
| Encounter and difficulty | Infer from the request. Ask for the boss when its mechanics determine a DPS recommendation. |
| Class | Preserve a stated class; otherwise Hunter is the saved main, Warlock the secondary. For "best of either," compare the relevant candidates. |
| Goal | Infer from activity: damage phase, solo completion, farming speed, objective play, or dueling. State the assumption. |
| Fireteam | Solo/duo by default; raids imply a raid team unless the user requests a low-player-count challenge. |
| Gear access | Use newest personal data when present. Without data, do not claim ownership. Use an obtainable setup plus replacement; ask if an owned-only result is requested. |
| Complexity | Give a practical core loop and advanced optimization where useful. Do not ask whether optimal play is desired; it is the saved bias. |
| Platform/input | Epic PC, mouse and keyboard. |
| Fixed constraints | Keep named exotic, subclass, weapon, and roll. Explain tradeoffs if the constraint prevents the unrestricted optimum. |

Ask only the unresolved decision-changing questions, in one short batch. Do not ask for favorites, spoilers, platform, or fireteam again if already known. A gear-access uncertainty must not become an excuse to invent a perfect exotic class item roll or a 200-everything stat distribution.

While awaiting an essential answer, research known constraints and identify candidates. If the user asks to assume, state reasonable assumptions and proceed.

## Choose for the actual task

- **Boss DPS:** boss/window, range, crit access, movement, immunity, damage/health scaling, team buffs, reserves, swap restrictions, and setup time.
- **Solo/duo endgame:** self-contained survival, actual Champion types, safe setup/escape, revive responsibilities, and recovery after a missed kill.
- **PvP:** playlist, first-duel value, map/range, special-ammo economy, handling, current Health/Weapons breakpoints, objective and team-shot plan.
- **Farming:** target drop, eligibility, grade/difficulty, repeatability, clear consistency, loading/reset time, and fatigue.
- **Gambit:** combatant clear/boss role and Guardian invasion role; evaluate their rules separately.
- **Mechanics/support:** exact assignment, danger during mechanics, buff/debuff coverage, and safe damage contribution.

## Build and compare

1. Check local sources first, then current patch/known issues and exact relevant data.
2. Compare a small set of credible candidates; prefer measured evidence under matching conditions.
3. Select subclass and legal abilities/aspects/fragments.
4. Choose exotic armor and, independently, whether an exotic weapon beats legendary alternatives for its job.
5. Solve survival, range, Champion needs, damage, and ammo as a connected plan.
6. Add artifact, set bonuses, stats, and armor/weapon mods. Recheck interactions.
7. Write opening, sustained loop, failure recovery, and encounter rotation.
8. Include one easier/obtainable replacement and its dependent changes.
9. Run [validation](build-validation.md); repair contradictions before presenting.
10. Output the [copy card](build-output-template.md) and concise evidence.

For a small edit or lookup, answer only that request and mention any dependent changes. Do not force a full build intake onto a weapon verdict or a single perk question.
