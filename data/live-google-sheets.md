# Live Google Sheets

Access and targeted freshness review: **2026-09-06**. Public read-only browser access worked for the three core workbooks after the web text reader failed. No full workbook was downloaded or copied.

## Core sources

| Source | Canonical link | Best use | Observed access/freshness |
|---|---|---|---|
| Destiny Data Compendium | [Open](https://docs.google.com/spreadsheets/d/1WaxvbLx7UoSZaBqdFr1u32F2uWVLo-CJunJB4nlGUE4/edit#gid=1038486120) | Exact mechanic definitions | Public browser; current and OLD tabs visibly separate; not every value audited |
| Aegis: Boss Damage | [Open](https://docs.google.com/spreadsheets/d/1_5wtBjRYHHxuF4oJKDb_iOGZs-wTkzB6RYbnyNLbuz4/edit#gid=1313551887) | Measured damage and rotations | Changelog first visible entry 2026-08-28; June snapshot is outdated for current rankings |
| Aegis: Endgame Analysis | [Status](https://docs.google.com/spreadsheets/d/1JM-0SlxVDAi-C6rGVlLxa-J1WGewEeL8Qvq4htWZHhY/edit#gid=346832350) | Chase/keep priority, perks, subclass/role comparison | Status shows per-tab dates; Shopping List 2026-08-19, Snipers 2026-08-30 in checked rows |

For Compendium lookups, search **D:/Coding/DestinyDataCompendium/Destiny_Data_Compendium.txt** first. See [section index](compendium-index.md). Check live only for missing, changed, stale, contested, or explicitly current details. Do not recreate the file.

## Verified tab routing

| Workbook | Current visible tabs / handling |
|---|---|
| Compendium | Landing; Weapon Perks; Armor Perks; Artifact Perks; Armor Mods; Arc; Solar; Void; Stasis; Strand; Prismatic; Exotic Class; Class Abilities; Exotic Weapons; Exotic Armors; Game Mechanics |
| Compendium archives | OLD Episodic Artifact Perks; OLD Seasonal Artifact Perks; OLD Nether Mechanics; OLD Armor Mods; OLD Game Mechanics. Historical only. |
| Boss Damage | Home; Changelog; Weapons; ability tab (resolve current spelling; accessibility exposed "Abilties"); Sustained; Swap; Bosses; Pack Hunter; Bolt Charge; Testing |
| Boss Damage dated tabs | Scaling (old), Fireteam (S28), Graphing (S28), Historical. Check scope/date before using; don't route every DPS question to S28. |
| Endgame Analysis | Status; Changelog; Shopping List; Archetypes; exact weapon-family tab; Exotic Weapons; Perks; Origin Traits; Set Bonuses; Artifact Mods; Fragments; Aspects; Subclasses; Encounters |
| Endgame Analysis exclusions | "Exotic Armor (ignore)" and "Builds (ignore)" are explicitly labeled ignore. Experimental is not an established ranking. |

Visible tab names can change. Get current metadata or UI labels before selecting a range; do not repeat the old "Gear Perks," "Ranking," "Super (WIP)," or "Ergo Sum" assumptions without checking.

The checked Boss Damage Changelog says recent work covered artifact values and Sustained/Swap tables. That does not validate every conditional or bug-based entry. Inspect the chosen row's methodology and restrictions.

## Specialist sources

Links are preserved from [Destiny Science](https://www.destiny2.science/). The hub's displayed July 29, 2025 update date is older than several linked sheets.

| Resource | Link | Audit result / use |
|---|---|---|
| Court: damage stacking, Champions, catalysts, Banes | [Sheet](https://docs.google.com/spreadsheets/d/1i1KUwgVkd8qhwYj481gkV9sZNJQCE-C3Q-dpQutPCi4/edit) | Public page read; title says JUNE UPDATE. Inspect relevant tab before exact values. |
| Magazine and Reserve Database | [Source](https://destiny2.science/reserves) | Signed-out browser redirected to sign-in; values not refreshed |
| Outgoing Damage Scaling | [Sheet](https://docs.google.com/spreadsheets/d/1b57Hb8m1L3daFfUckQQqvvN6VOpD03KEssvQLMFpC5I/edit) | Public document title says v1.9.2 / Edge of Fate in Progress; check unfinished scope |
| Quantum Damage-ics | [Source](https://destiny2.science/quantum-damage-ics) | Sign-in redirect; no current values verified |
| Damage Generator | [Sheet](https://docs.google.com/spreadsheets/d/1rY_iChu08CVnIMfHliZQwup10-GnmPtEu5FG0DNy8VM/edit) | Document identity resolved; calculations not validated |
| Glaive Compendium | [Source](https://destiny2.science/glaive-compendium) | Sign-in redirect; use local exact glaive entries first |
| Flat Gain Factors / Active Super Regen | [Source](https://destiny2.science/flat-gain-factors) | Sign-in redirect; [Clarity explanation](https://www.d2clarity.com/blog/destiny-science-6/chunk-energy-scalars-breakdown-12) is readable |
| Armor 3.0 Stat Planner | [Source](https://destiny2.science/armor-stat-planner) | Template preview redirects to sign-in; do not claim live calculation access |
| Exotic Class Item Planner | [Source](https://destiny2.science/exotic-class-item-planner) | Template preview redirects to sign-in |
| Prismatic Build Planner | [Source](https://destiny2.science/prismatic-build-planner) | Sign-in redirect in this audit; earlier "gone" claim is not confirmed current |

Do not remove a source just because this session is signed out. Do not label gated values current or copy a template into the user's Drive without authorization.

## Bounded lookup procedure

1. Identify the specific question, exact item, and appropriate workbook.
2. Inspect Status/Changelog or relevant update note.
3. Get current tab names, then read only the needed rows/columns through an available connector or public browser.
4. In Sheets, the name box and formula bar can inspect a selected cell/range without modifying it. Use a small visible section when text extraction is unavailable.
5. Record workbook, tab, range/entry, date checked, source update/test date, and conditions.
6. If blocked, use a labeled local/reference fallback; do not imply a live read.

No connector was used or authenticated in this audit. Historical claims that a Google Drive connector worked do not establish current access.

## Snapshot policy

The eight existing workbooks under [June 16 archive](snapshots/public-sheets/2026-06-16/destiny-science/README.md) are historical reference files. Their archive structure was checked; formulas and current numerical accuracy were not revalidated.

Keep public sheets live by default. Do not delete/redownload weekly, create full snapshots for routine analysis, or use public workbooks as personal inventory. If the user explicitly requests a bounded or full snapshot, record source, scope, date, purpose, and access method; preserve older files unless removal is requested.
