**English** | [Русский](README.ru.md)

# Arkships for Settled Empires

This mod expands the role of Arkships and allows empires to continue using them after adopting a settled way of life.

## Requirements

- Stellaris version **4.4**.
- The expansion that adds Nomadic empires and Arkships.

## Arkship Technologies for Settled Empires

Settled empires gain access to **Arkship Construction** and its related technology tree after meeting both requirements:

- **Mega-Engineering** has been researched;
- the **Adaptability** tradition tree, or its Gestalt equivalent **Versatility**, has been completed.

The normal prerequisite technologies for each Arkship tier and specialization are still required.

After researching the appropriate technologies, regular construction ships belonging to settled empires can construct:

- Civilian Arkships;
- Science Arkships;
- Military Arkships;
- advanced Arkship tiers and specialized systems.

Nomadic empires retain their vanilla technology requirements and continue constructing new Arkships from existing Arkships.

## Becoming a Settled Empire

When a Nomadic empire has multiple Arkships and has completed **Adaptability** or **Versatility**, an additional choice becomes available in the **Settlement Complete** event:

> We shall make our home here, but our Arkships will sail on.

This choice:

- turns the selected Arkship into a regular planetary colony;
- changes the empire from Nomadic to Settled;
- keeps all remaining Arkships under the player's direct control;
- converts Nomadic waystations into regular starbases;
- does not scuttle the remaining Arkships or transfer them to a separate subject.

When only one Arkship remains, the normal vanilla settlement choice is used.

## Colonizing with Settled Arkships

Arkships controlled by a settled empire retain access to the **Settle** order.

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
- `tech_arkship_exodus_jump`.

It also overrides the vanilla scripted action `arkship_settle`.

Because these objects deliberately retain their vanilla IDs, Stellaris writes the following expected messages to `error.log`:

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
[game_singleobjectdatabase.h:170]: Object with key: arkship_settle already exists, using the one at  file: common/scripted_actions/afse_arkship_settle.txt line: 1
```

These messages are harmless, do not affect gameplay and can be ignored.

## Compatibility and Saved Games

The mod can be added to an existing saved game. New technologies may not appear immediately and can require the available research alternatives to refresh.

A full game restart is recommended after installing or updating the mod.

Mods that also replace Arkship technologies, the **Settle** order or Nomadic settlement rules may be incompatible.
