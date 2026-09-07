# Roadmap

## Phase 0 — Preserve upstream

- Keep the original 2024 Workshop release archived unchanged outside active development.
- Preserve upstream attribution and source notes.
- Track all redux changes through Git.

## Phase 1 — Modernization

Goal: reach a reliable current-HOI4 boot and playable 99 AG campaign.

### P0 — Startup blockers
- Fix `descriptor.mod` mistakes and obsolete declarations.
- Audit `replace_path` entries.
- Audit changed engine schemas since HOI4 1.14.
- Resolve parser/runtime errors from `error.log` and `game.log`.
- Validate map startup, bookmarks, states, supply, units, technologies, characters, abilities, and interface.

### P1 — Broken gameplay/content
- Fix missing dynamic-country definitions.
- Fix empty active country definition files.
- Repair broken event/decision references.
- Clean duplicate and malformed localisation keys.
- Remove or replace visible TODO localisation.
- Verify AI can use the major systems.

### P2 — Cleanup
- Remove unnecessary vanilla residue where safe.
- Standardize naming and folder organization.
- Document non-obvious scripted systems.
- Add repeatable validation checks.

## Phase 2 — Core gameplay rework

### Naval warfare
- Fire Nation: blue-water dominance, imperial logistics, convoy escort, amphibious operations.
- Earth Kingdom: sea denial, submarines, mines, coastal defense, raiding.
- Northern Water Tribe: polar/littoral warfare and defensive naval superiority.
- Southern Water Tribe: small-unit raiding and asymmetric maritime warfare.
- Pirates: meaningful convoy-raiding and trade disruption.
- Make ports, convoy routes, colonial supply, and overseas resources strategically important.

### Air warfare
- Progression from reconnaissance/balloons to military airships.
- Useful air missions even before conventional fighter-vs-fighter warfare exists.
- Ground-based counters and anti-air options for nations without major air forces.
- Strategic/narrative technology acquisition where appropriate.

## Phase 3 — Narrative systems

- Avatar world mechanic.
- White Lotus network.
- Dai Li influence/subversion.
- Fire Nation royal-family politics.
- Resistance and occupation systems.
- Day of Black Sun.
- Sozin's Comet.

## Phase 4 — Additional bookmarks

After the existing 99 AG start is stable:

- Siege of Ba Sing Se era.
- Fall of Ba Sing Se.
- Day of Black Sun.
- Sozin's Comet.
- Other starts only when they offer meaningfully different strategic gameplay.

## Release principle

Prefer a smaller number of polished, distinct scenarios and mechanics over a large number of shallow bookmarks or unfinished systems.
