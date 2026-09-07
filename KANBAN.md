# Avatar HOI4 Redux — Kanban

This file mirrors the current development backlog. GitHub Issues are the source of truth for individual tasks.

## Backlog — P0: Make it boot

- [ ] #1 Port defines to HOI4 1.19
- [ ] #2 Port units and interface to HOI4 1.19
- [ ] #3 Clean and modernize descriptor.mod

**Exit condition:** the 99 AG bookmark reaches gameplay on the current HOI4 version without critical startup/runtime failures.

## Backlog — P1: Make it work

- [ ] #4 Fix Air Council mission ID mismatch
- [ ] #5 Fix Fire Nation royal family character effects
- [ ] #6 Fix broken flags in Swamp and Kyoshi events
- [ ] #7 Repair dynamic country definitions D51-D75
- [ ] #8 Fill zero-byte Avatar country definition files
- [ ] #9 Add missing generic characters for active countries
- [ ] #10 Repair broken technology IDs and unlock chains

**Exit condition:** core systems run without known broken IDs, invalid scopes, dead country definitions or broken technology chains.

## Backlog — P2: Make it feel finished

- [ ] #11 Complete Gaoling Castle content
- [ ] #12 Repair missing and duplicate localisation
- [ ] #13 Complete missing news and event content

**Exit condition:** core playable content no longer exposes obvious TODOs, raw localisation keys or unfinished event branches.

## Planned — Redux systems

- [ ] #14 Rebalance 99-100 AG campaign pacing
- [ ] #15 Redesign naval warfare and logistics
- [ ] #16 Build meaningful air warfare progression

Future Redux systems to break into cards after modernization:

- Avatar world mechanic
- Day of Black Sun system
- Sozin's Comet system
- Dai Li / Ba Sing Se political mechanics
- White Lotus network
- Fire Nation political/narrative content
- AI strategy overhaul
- Additional bookmarks/scenarios

## In progress

_None yet. Start with P0 after the original 1.0 source is imported into `upstream-1.0` and copied into `modernization`._

## Review / Test

_None yet._

## Done

- [x] Initial repository created
- [x] `main`, `upstream-1.0`, `modernization`, and `content` branches created
- [x] Initial static audit of the 1.0 Workshop release completed
- [x] Map/state/supply structural integrity checked
- [x] Initial roadmap and credits documentation added

## Workflow

1. Move one task from **Backlog** to **In progress**.
2. Implement it on `modernization` (compatibility/bugfix) or `content` (new Redux content).
3. Test in HOI4 and inspect `error.log` / `game.log`.
4. Move it to **Review / Test** until the fix survives a real campaign test.
5. Close the GitHub Issue and move it to **Done**.

Avoid mixing unrelated fixes into the same commit. The original `upstream-1.0` branch should remain untouched as the historical baseline.
