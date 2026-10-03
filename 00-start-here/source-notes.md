# Current Baseline and Source Notes

Checked: **2026-09-06**. This is the canonical game-state note. Dates below are evidence dates, not a claim that the user's installed game or every mechanic was tested.

## Patch evidence

| Version / source | Published or displayed date | What was established |
|---|---|---|
| [9.7.0](https://www.bungie.net/7/en/News/Article/destiny_update_9_7_0) | 2026-06-09 | Monument baseline; substantial sandbox, artifact, reward, and armor changes |
| [9.7.0.1](https://www.bungie.net/7/en/News/Article/destiny_update_9_7_0_1) | 2026-06-16 | Fixes include exotic armor energy eligibility, frozen-boss Nighthawk interaction, Wish-Ender catalyst drop, and reward issues |
| [9.7.0.2](https://www.bungie.net/7/en/News/Article/destiny_update_9_7_0_2) | 2026-06-23 | Later fixes to activities, loot, armor interactions, and artifact selections |
| [9.7.0.3](https://www.bungie.net/7/en/News/Article/destiny_2_update_9_7_0_3) | 2026-07-07 | Later fixes including Pack Tactics performance and Pantheon Insurrection Prime/Divinity behavior |
| [Server/update status: 9.7.0.4](https://help.bungie.net/hc/en-us/articles/360049199271-Destiny-Server-and-Update-Status) | 2026-07-28 scheduled update | Highest official version reference found in this audit; a standalone official changelog was not located |
| [Known issues](https://help.bungie.net/hc/en-us/articles/39007140765204-Destiny-2-Known-Issues-and-Vital-Information) | Monument section says 2026-07-07 | Read with later fixes; this is not a fresh September test of every listed issue |

Do not call 9.7.0 the latest patch, claim 9.7.0.4's full changes are known, or infer the user's installed build from these pages. Check relevant later evidence for a current recommendation.

## Confirmed baseline

Bungie's [Monument support guide](https://help.bungie.net/hc/en-us/articles/49848696022548-Destiny-2-Monument-of-Triumph-and-Update-9-7-0-Support-Guide) confirms the June 9 launch and cessation of planned live-service content updates, with possible health/stability hotfixes. Monument, Pantheon, and SRL are continuing additions. Legacy activity nodes were reorganized into Ops and the appropriate activity destinations. Retired seasonal events should not be scheduled from old calendars.

The [Monument FAQ](https://help.bungie.net/hc/en-us/articles/50100493304468--13-Monument-of-Triumph-FAQ) provides the Tower on-ramp and returning-player guidance, including the 550 Power cap in its checked baseline. Verify target activity Power rules and ownership separately.

Armor 3.0, gear tiers, set bonuses, Artifacts 2.0, and intrinsic weapon Champion effects are central to buildcrafting. The [9.7.0 patch](https://www.bungie.net/7/en/News/Article/destiny_update_9_7_0) adds six armor archetypes, bringing the total to 12, and makes 20 in-game loadout slots available on login. Do not send players through an old Guardian Rank loadout-slot unlock route. Use [armor](../gear/armor.md) and [artifacts](../builds/artifacts.md) for details.

## Build-impact corrections

- [9.7.0.1](https://www.bungie.net/7/en/News/Article/destiny_update_9_7_0_1) fixes an inflated frozen-boss Celestial Nighthawk interaction. Old exploit damage is not a current benchmark.
- [9.7.0.3](https://www.bungie.net/7/en/News/Article/destiny_2_update_9_7_0_3) states that Divinity and damage to its cage do not damage Insurrection Prime in that Pantheon encounter. Do not recommend the old cage strategy there.
- The current known-issues page names artifact problems involving Argent Blade, Argent Quiver, Creeping Chill, Debilitating Wave, and Horde Shuttle, among others. Read the selected perk's issue and later fixes before relying on it.
- The external Compendium text file is dated June 26 by filesystem metadata and contains question-mark values. That date predates July fixes and August testing; use it as the first lookup, not unquestioned current truth.
- Live Boss Damage's visible Changelog begins with 2026-08-28 in the checked view. Endgame Analysis's Status tab lists Shopping List updated 2026-08-19 and Snipers 2026-08-30. These dates apply to those entries, not every sheet value. See [live sheet notes](../data/live-google-sheets.md).

## Official historical references

Use these to interpret origins of systems, then apply later patches:
- [Every End is a New Beginning — 2026-05-21](https://www.bungie.net/7/en/News/article/d2_may_21_2026)
- [TWID 2026-06-11](https://www.bungie.net/7/en/News/Article/twid_06_11_2026); the main URL rendered blank during the audit; the [official static mirror](https://origin-static01.bungie.net/7/en/News/Article/twid_06_11_2026) is a fallback.
- [Armor 3.0 launch: 9.0.0.1](https://www.bungie.net/7/en/News/article/destiny_update_9_0_0_1)
- [Armor archetypes/tiering: TWID 2025-06-26](https://www.bungie.net/7/en/News/Article/twid_06_26_2025)
- [Weapon tiering](https://www.bungie.net/7/en/News/Article/dev_insights_weapon_gear_tier)
- [Weapons, artifacts, focusing, Anti-Champion 2.0](https://www.bungie.net/7/en/News/article/dev_insights_weapons_artifacts_focusing_preview)
- [Buildcrafting Evolved](https://www.bungie.net/7/en/News/article/buildcrafting) — older mod-system background, not present slot/energy authority.
- [A Path for New Players](https://help.bungie.net/hc/en-us/articles/45297505570580--4-A-Path-for-New-Players)
- [Activities guide](https://help.bungie.net/hc/en-us/articles/46668136913172--10-Activities)

For live state use [research rules](research-protocol.md), [public registry](public-source-registry.md), and the dated [source audit](../maintenance/source-audit-2026-09-06.md).
