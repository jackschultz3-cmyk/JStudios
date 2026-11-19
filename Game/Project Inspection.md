---
tags: [game, inspection]
date: 2026-11-18
---
# Project Inspection — 2026-11-18

Prompt: [[Game Prompt]] · Back to [[Start Here]]

## What was inspected
- **Roblox Studio:** one open place, `Place1`, Edit mode, **not saved to Roblox cloud or to a file**.
- **Vault files:** `Export.gltf`, `Test`.

## Findings
| Area | State |
|---|---|
| Workspace | Default Baseplate + SpawnLocation only. No terrain (0 cells). |
| Scripts | **0** scripts anywhere (ServerScriptService, ReplicatedStorage, StarterPlayer all empty). |
| UI | StarterGui empty — no HUD. |
| NPCs / combat / flight / forms / techniques / quests / data saving | None exist. |
| Lighting | Template defaults: Sky, Atmosphere, Bloom, SunRays, DepthOfField. |
| StreamingEnabled | On (template default) — good for the large world. |
| `Export.gltf` | A Roblox glTF export of the same empty Baseplate scene (generator "Roblox Export"). No game assets. |
| `Test` | Empty file. |

## Conclusion
This is the **default Roblox Baseplate template**: there is no existing game to preserve yet. Section 24 ("inspect and preserve") is satisfied trivially; development starts from the foundation.

If the real project lives in another place file or on Roblox, open it in Studio and re-run the inspection.

## Suggested first release (foundation)
1. Rojo-style code layout: `ReplicatedStorage/Shared` (registries, config), `ServerScriptService` (services), `StarterPlayerScripts` (controllers).
2. Core services: player data + saving, stats/progression, Ki/stamina.
3. Controllers: flight (hover/fly/boost/banking), melee combo + block/dodge, Ki Bolt + Radiant Lance via a technique registry.
4. Form registry with **Ember Surge** as the first working form.
5. HUD v1: health/Ki/stamina bars, technique hotbar with cooldowns, menu shell, UI scale slider.
6. Mount Tenrai starter region (terrain + Tenrai Dojo blockout) and Master Hoshigane's first quest.
7. Save the place to a file inside the vault so it is versioned on GitHub.
