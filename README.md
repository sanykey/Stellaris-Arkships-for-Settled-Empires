**English** | [Русский](README.ru.md)

# Arkships for Settled Empires

This mod expands the role of Arkships and allows empires to continue using them after adopting a settled way of life.

## Requirements

- Stellaris version **4.4**.
- The expansion that adds Nomadic empires and Arkships.

## Arkship Technologies for Settled Empires

Settled empires gain access to **Arkship Construction** and its related technology tree through the new **Two Paths, One Destiny** Ascension Perk.

**Two Paths, One Destiny** requires three other Ascension Perks and completion of the **Adaptability** tradition tree, or its Gestalt equivalent **Versatility**. A formerly Nomadic empire must also have this perk to continue researching Arkship technologies after settling.

The normal prerequisite technologies for each Arkship tier and specialization are still required.

After researching the appropriate technologies, regular construction ships belonging to settled empires can construct:

- Civilian Arkships;
- Science Arkships;
- Military Arkships;
- advanced Arkship tiers and specialized systems.

Nomadic empires retain their vanilla technology requirements and continue constructing new Arkships from existing Arkships.

## Waystations for Settled Empires

**Two Paths, One Destiny** grants the foundational **Waystation** technology and allows regular construction ships belonging to Settled empires to construct Waystations. The second- and third-tier Waystation technologies can then be researched normally.

Settled empires receive Waystation tier upgrades and stockpile improvements. These technologies do not increase their Starbase Capacity, so each Waystation uses the empire's existing capacity. They do, however, retain the vanilla Logistics Ship limit progression described below. Nomadic empires retain all vanilla technology effects.

## Logistics Ships for Settled Empires

**Two Paths, One Destiny** allows a Settled empire to build **Logistics Ships** at ordinary starbase shipyards and grants a base limit of **2** ships. Eager Explorer empires use the **Logistics Vessel** variant. Both variants share the same limit.

Logistics Ships can harvest resources, perform construction tasks and interact with Waystation stockpiles. The normal FTL technology requirement still applies and is already fulfilled by ordinary spacefaring Settled empires.

The limit progresses as follows:

- **Two Paths, One Destiny: +2**;
- **Waystation II: +2**;
- **Waystation III: +2**;
- each **Logistics Hub** module on a Waystation: **+1**.

**Zero-G Engineering** is not a separate researchable technology. It is the Nomadic version of the starting `tech_space_construction` technology. The mod therefore applies its **+2 Logistics Ship limit** directly through **Two Paths, One Destiny**. The perk also automatically grants `tech_waystation_1` if necessary.

## Two Paths, One Destiny and Ascension Perks

**Two Paths, One Destiny** allows a Settled empire to research, construct and colonize with Arkships. It also grants access to the mod's settlement option and allows affected Ascension Perks to retain their Nomadic effects.

Settled empires with **Two Paths, One Destiny** receive the Nomadic bonuses of the following Ascension Perks in addition to their regular settled bonuses:

- **Imperial Prerogative**:
  - **Ruler Pop Output: +15%**.
- **Eternal Vigilance**:
  - **Waystation Armor Hardening: +25%**;
  - **Waystation Shield Hardening: +15%**;
  - **Waystation Hull Points: +25%**;
  - **Waystation Alloy Cost: -25%**;
  - **Arkship Fire Rate: +25%**;
  - **Ship Hull Points: +25%**.

- **Interstellar Dominion**:
  - **Waystation Influence Cost: -20%**;
  - **Starbase Stockpile Capacity: +15%**;
  - **Nomadic Construction Ship Stockpile Capacity: +15%**;
  - **Engineer Vessel Stockpile Capacity: +15%** for Eager Explorers.
- **Mastery of Nature**:
  - **Arkship Harvested Resources: +50%**;
  - **Ship and Starbase Stockpile Collection Rate: +10%**.
- **Voidborne**:
  - **Arkship Max Districts: +2**;
  - **Arkship Construction Cost: -10%**;
  - **Arkship Upgrade Cost: -15%**;
  - **Arkship Habitability: +20%**.

These bonuses remain active without requiring the empire to own an Arkship.

Settled empires with **Two Paths, One Destiny** may also select **Wanderlust**. Existing and newly selected Wanderlust perks retain their normal bonuses, and Arkships controlled by settled empires continue progressing the Nomadic Wanderlust exploration chain when they visit remarkable systems.

## Two Paths, One Destiny and Traditions

The regular Settled effects of these traditions remain intact. With **Two Paths, One Destiny**, the following Nomadic effects are added:

- **Adaptability**:
  - **Survival of the Fittest**: Arkship Hull Points **+25%**;
  - **Adaptive Ecology**: Max Districts on Artificial Worlds **+1**;
  - **Appropriation**: Starbase Module Cost **-30%**.
- **Diplomacy — Entente Coordination**: Nomadic Contract Value **+25%**.
- **Discovery — Databank Uplinks**: Physics, Society and Engineering Research collected from systems by starbases **+20%**.
- **Domestication — Bio-Repurposing**:
  - Tiyanki and Amoeba Food production **+1**;
  - Crystalline Entity and Cutholoid Mineral production **+1**;
  - Voidworm Energy production **+1**.
- **Enmity adoption**: Logistic Growth and Pop Assembly Speed **+3% per rival**.
- **Expansion**:
  - adoption: Megastructure Build Speed **+25%**, Waystation and Waystation Module Upkeep **-20%**;
  - **Colonization Fever**: Empire Size from Colonies **-25%**, Arkship Cost **-5%**, Arkship Upgrade Cost **-10%**;
  - **Courier Network**: Starbase Stockpile Capacity **+25%**, Ship and Starbase Stockpile Collection Rate **+25%**;
  - **Reach for the Stars**: Waystation Cost **-10%**;
  - finisher: Max Districts on Artificial Worlds **+1**.
- **Commerce adoption**: Nomadic Contract Value **+15%**.
- **Prosperity**:
  - adoption: Arkship Harvested Resources **+10%**, Starbase and Logistics Ship Stockpile Capacity **+25%**;
  - **Public Works Division**: Max Districts on Artificial Worlds **+1**, and every Arkship city district provides **+250 Housing**;
  - finisher: Arkship Harvested Resources **+15%**.

## Becoming a Settled Empire

When a Nomadic empire has multiple Arkships, an additional choice is displayed in the **Settlement Complete** event:

> We shall make our home here, but our Arkships will sail on.

Selecting this choice requires **Two Paths, One Destiny**. Without the perk, it remains visible but disabled; the normal vanilla settlement choices remain available.

This choice:

- turns the selected Arkship into a regular planetary colony;
- changes the empire from Nomadic to Settled;
- keeps all remaining Arkships under the player's direct control;
- converts Nomadic waystations into regular starbases;
- does not scuttle the remaining Arkships or transfer them to a separate subject.

When only one Arkship remains, the normal vanilla settlement choice is used.

## Colonizing with Settled Arkships

Arkships controlled by a settled empire with **Two Paths, One Destiny** retain access to the **Settle** order.

To establish a colony:

1. Select an Arkship.
2. Right-click a suitable uncolonized planet.
3. Select **Settle**.

A settled empire does not receive the settlement choice event. Once preparations are complete, the Arkship immediately becomes a colony.

This process:

- transfers the Arkship's population and infrastructure to the planet;
- dismantles the Arkship used for settlement;
- leaves all other Arkships untouched;
- establishes a starbase and resource stations in the new system;
- adds the vanilla **Arkship Remains** modifier to the planet.

**Arkship Remains** provides:

- **Habitability: +60%**;
- **Max Districts: +2**.

The usual Arkship restrictions still apply. The planet must be surveyed, colonizable and not owned by another empire. Subject empires cannot use the order.

## Empire Size from Settled Arkships

Arkships belonging to settled empires retain the increased administrative burden of Nomadic colonies.

Each Arkship contributes additional Empire Size:

- **+20** for the Arkship colony itself;
- **+0.5** for every district built aboard it.

Unused district capacity does not increase Empire Size. Upgrading an Arkship therefore has no immediate administrative cost, but it allows more districts to be constructed.

The **Settled Arkships** modifier tooltip separately displays:

- total additional Empire Size;
- the number of Arkships and their contribution;
- the number of Arkship districts and their contribution.

The calculation accounts for:

- the Ascension Tier of each Arkship colony;
- Empire Size reductions from colonies;
- Empire Size reductions from districts;
- general Empire Size reductions;
- bonuses to Colony Ascension effects.

This means that **Imperial Prerogative**, traditions, civics and other Empire Size bonuses apply to settled Arkships. Ascension bonuses from **Harmony**, **Synchronicity**, **Ascensionists**, federations and other sources are also included automatically.

By default, each Ascension Tier reduces the additional contribution of an Arkship and its districts by **5%**. Bonuses to Colony Ascension effects improve this reduction in the same way as they do for regular planets.

Values are refreshed after ascending a colony and during the monthly recalculation.

## Expected Error Log Messages

This mod overrides the following vanilla technology IDs:

- `tech_planetary_engineering`;
- `tech_arkship_construction`;
- `tech_arkship_tier_2`;
- `tech_arkship_tier_3`;
- `tech_civilian_arkship`;
- `tech_science_arkship`;
- `tech_military_arkship`;
- `tech_arkship_planetary_refinery`;
- `tech_arkship_stellar_igniter`;
- `tech_arkship_system_scanner`;
- `tech_arkship_exodus_jump`;
- `tech_waystation_1`;
- `tech_waystation_2`;
- `tech_waystation_3`.

It also overrides the six Ascension Perks and sixteen tradition objects listed in the compatibility section, the two Logistics Ship sizes, their shared limit, the Arkship city district, the `nomads.4720` Wanderlust exploration event, and the scripted action `arkship_settle`.

Because these objects deliberately retain their vanilla IDs, Stellaris can write expected messages such as the following to `error.log` (the complete object list is in the compatibility section):

```text
[game_singleobjectdatabase.h:170]: Object with key: tech_planetary_engineering already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 4
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_construction already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 50
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_tier_2 already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 87
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_tier_3 already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 128
[game_singleobjectdatabase.h:170]: Object with key: tech_civilian_arkship already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 173
[game_singleobjectdatabase.h:170]: Object with key: tech_science_arkship already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 219
[game_singleobjectdatabase.h:170]: Object with key: tech_military_arkship already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 265
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_planetary_refinery already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 314
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_stellar_igniter already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 366
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_system_scanner already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 413
[game_singleobjectdatabase.h:170]: Object with key: tech_arkship_exodus_jump already exists, using the one at  file: common/technology/afse_arkship_technologies.txt line: 473
[game_singleobjectdatabase.h:170]: Object with key: tech_waystation_1 already exists, using the one at  file: common/technology/afse_waystation_technologies.txt line: 3
[game_singleobjectdatabase.h:170]: Object with key: tech_waystation_2 already exists, using the one at  file: common/technology/afse_waystation_technologies.txt line: 48
[game_singleobjectdatabase.h:170]: Object with key: tech_waystation_3 already exists, using the one at  file: common/technology/afse_waystation_technologies.txt line: 147
[game_singleobjectdatabase.h:170]: Object with key: ap_wanderlust already exists, using the one at  file: common/ascension_perks/afse_ascension_perks.txt line: 39
[game_singleobjectdatabase.h:170]: Object with key: ap_interstellar_dominion already exists, using the one at  file: common/ascension_perks/afse_ascension_perks.txt line: 137
[game_singleobjectdatabase.h:170]: Object with key: ap_mastery_of_nature already exists, using the one at  file: common/ascension_perks/afse_ascension_perks.txt line: 223
[game_singleobjectdatabase.h:170]: Object with key: ap_voidborn already exists, using the one at  file: common/ascension_perks/afse_ascension_perks.txt line: 290
[game_singleobjectdatabase.h:170]: Object with key: arkship_settle already exists, using the one at  file: common/scripted_actions/afse_arkship_settle.txt line: 1
```

These messages are harmless, do not affect gameplay and can be ignored.

## Compatibility and Saved Games

The mod can be added to an existing saved game. New technologies may not appear immediately and can require the available research alternatives to refresh.

A full game restart is recommended after installing or updating the mod.

The mod changes definitions originating from the following vanilla files:

- `common/technology/00_nomads_dlc_tech.txt`: `tech_planetary_engineering`, the Arkship technology chain and `tech_waystation_1` through `tech_waystation_3`;
- `common/ascension_perks/00_ascension_perks.txt`: `ap_imperial_prerogative`, `ap_eternal_vigilance`, `ap_wanderlust`, `ap_interstellar_dominion`, `ap_mastery_of_nature` and `ap_voidborn`;
- `common/traditions/00_adaptability.txt`: `tr_adaptability_survival_fittest`, `tr_adaptability_adaptive_ecology`, `tr_adaptability_appropriation`;
- `common/traditions/00_diplomacy.txt`: `tr_diplomacy_entente_coordination`;
- `common/traditions/00_discovery.txt`: `tr_discovery_databank_uplinks`;
- `common/traditions/00_domestication.txt`: `tr_domestication_bio_repurposing`;
- `common/traditions/00_enmity.txt`: `tr_enmity_adopt`;
- `common/traditions/00_expansion.txt`: `tr_expansion_adopt`, `tr_expansion_finish`, `tr_expansion_colonization_fever`, `tr_expansion_courier_network`, `tr_expansion_reach_for_the_stars`;
- `common/traditions/00_mercantile.txt`: `tr_mercantile_adopt`;
- `common/traditions/00_prosperity.txt`: `tr_prosperity_adopt`, `tr_prosperity_finish`, `tr_prosperity_public_works`;
- `common/ship_sizes/29_nomads_dlc_ships.txt`: `nomads_constructor`, `nomads_engineer_vessel`;
- `common/country_limits/ship_of_size_limits/00_ship_of_size_limits.txt`: `nomadic_constructor_limit`;
- `common/districts/07_ark_districts.txt`: `district_ark_city`;
- `common/scripted_actions/03_arkships.txt`: `arkship_settle`;
- `common/game_rules/00_rules.txt`: `can_nomad_settle`;
- `common/inline_scripts/megastructures/arkship.txt`: full relative-path override;
- `common/megastructures/30_nomad_waystation.txt`: full relative-path override of `waystation_megastructure`;
- `events/nomads_events_1.txt`: `nomads.4720`.

Objects with vanilla IDs are overridden by identifier. The Arkship inline script and Waystation megastructure file are full overrides at their original relative paths. The mod also adds `afse` events, triggers, effects, values, modifiers and on-actions for settlement, colonization, migration and Settled Arkship Empire Size accounting.

Mods that replace any listed technology, Ascension Perk, tradition, ship size, ship limit, Arkship district, Waystation construction, the **Settle** order or Nomadic settlement rules may be incompatible. For identifier overrides, whichever definition loads last wins.
