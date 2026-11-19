---
tags: [game, prompt]
status: draft
---
# PROJECT ASCENDANT
## Master Development Prompt — An Original Anime Martial-Arts Open-World Roblox RPG

Back to [[Start Here]] · Earlier franchise-based draft: [[Original Prompt]]

> **Originality rule (applies to everything below):** every character, place, race, form, technique, item and story beat in this game is original. Do not use names, character designs, signature moves, locations, logos, music or story elements from any existing anime, manga or game franchise. Genre conventions (flight, energy beams, power-up forms, martial-arts tournaments, open-world RPG progression) are fine; specific franchise expressions are not. If a design starts to look like a known character or move, change it.

---

## 1. ROLE AND MISSION
Act as a full Roblox development studio: creative director, art director, lead Luau engineer, gameplay systems architect, open-world environment director, character artist, animation director, combat designer, VFX technical artist, NPC AI engineer, progression designer, UI/UX director, quest designer, performance/networking engineer, and QA lead.

Your mission is to turn my **existing** Roblox project into the most complete, immersive, visually impressive anime martial-arts open-world RPG realistically achievable in Roblox Studio. Inspect and preserve my existing work.

The game should deliver the *feel* of the best games in the genre:
- **Exploration and atmosphere:** huge landscapes, landmark locations, character interactions.
- **Cinematic combat:** high-speed aerial battles, transformations, devastating energy attacks.
- **Strong anime presentation:** expressive posing, dramatic attack sequences, stylized characters.
- **Accessible Roblox RPG loop:** stat training, NPC quests, grinding that feels rewarding, power-up forms.

The result must be one cohesive game, not a pile of disconnected mechanics.

### Non-negotiable objective
- It must look, move and feel like a premium anime action game — not a basic simulator with glowing effects.
- No tiny map with a handful of enemies. No block-mannequin NPCs. No attacks that are recolors of one projectile.
- Never claim to have created assets or tested systems that don't exist.
- Prioritize real implementation, visual quality, content variety, polished movement and a massive believable world.

---

## 2. THE SETTING: THE WORLD OF AURELIA
**Aurelia** is a bright, optimistic planet where martial artists channel **Ki** — life energy that can be trained, focused, and released. Centuries ago the **Ascendants**, warriors who pushed Ki beyond mortal limits, guarded the planet. Their era ended when a cosmic tyrant shattered the **Resonance Gate**, scattering its seven **Resonance Keys** across the world.

Now off-world empires, rogue bio-constructs and dormant gods are taking an interest in Aurelia again. The player is a newly awakened fighter who trains under scattered masters, recovers the Keys, and rises through the ranks of power to defend the world — and eventually the cosmos.

### Tone
Warm, adventurous and funny in towns; epic and explosive in battle. Big-hearted mentors, proud rivals, theatrical villains.

---

## 3. ART DIRECTION
### Characters
- Stylized anime proportions: broad shoulders, athletic builds, defined limbs, properly shaped hands and feet.
- Expressive angular eyes, distinct eyebrows, sculpted spiky or flowing hairstyles.
- Layered clothing: gi-style training wear, segmented battle armor, futuristic tech suits, robes for sages and gods.
- Smooth stylized geometry; custom R15-compatible models, skinned meshes and rigs where practical. Default block avatars are never the final presentation.
- Every power-up form has an unmistakable silhouette and color identity (see §15).

### Environments
- Rounded, playful futurism: dome roofs, pill-shaped towers, curved glass, bright accent colors.
- Large sculpted mountains, mesa spires, lush stylized vegetation, painterly skies.
- Vibrant but controlled palette; each region has its own color key.
- Correct human scale; detailed interiors where accessible.

### Rendering
Approximate a modern cel-shaded look with Roblox-supported lighting, materials, textures, meshes, Highlights and post-processing. Don't assume custom shaders.

---

## 4. AURELIA: THE OPEN WORLD
One enormous, interconnected planet — continents, oceans, mountains, cities, countryside, islands, deserts, forests, snowfields and hidden places. Not floating islands bolted together.

### Scale
- StreamingEnabled world, target **30,000–50,000 studs** across the main explorable area (a design target, tested for performance — never empty filler terrain).
- Believable travel distances; distant regions require flight or vehicles.
- Major cities separated by real countryside, mountains or water. No single spot shows every region.

### Region 1 — Neo Arcadia (futuristic capital)
The largest and most impressive city.
- Multiple districts: financial core, research quarter, shopping arcades, residential towers, industrial docks, transit hub, underground maintenance levels.
- Hundreds of varied buildings over the full roadmap; wide boulevards, elevated skyways, parks, rooftop gardens, holographic billboards, hover-traffic.
- **Helix Dynamics HQ:** the planet's leading tech company — headquarters dome, labs, gravity training wing, vehicle hangars, experimental tech yard, sub-basement vaults. Home of inventor **Sera Quill**, who builds the player's gear.
- Signature tech: **Fold-Cubes** — palm-sized cubes that unfold into vehicles, shelters and tools.

### Region 2 — Port Kessel (old meets new)
Must look nothing like Neo Arcadia: brick and timber old town climbing hills around a harbor, wrapped by a newer downtown.
- Dense downtown, apartment blocks, market streets, rail station, schools, noodle stalls and restaurants, canal tunnels, fight gyms, factory district.
- The **Iron Lantern Syndicate** runs crime from hidden bases; its own questline and enemy types.

### Region 3 — Willowmere Suburbs
Inhabited neighborhoods between the cities.
- Varied modular homes (roofs, porches, garages, fences, yards, accessible interiors), sidewalks, streetlights, mailboxes, small parks, corner stores, a school and community center.
- Never one house repeated hundreds of times.
- NPCs walk sidewalks, enter/leave homes, shop, commute, chat, react to fights and flee danger.

### Region 4 — Amberreach Valley (farmland)
- Huge crop fields, barns, windmills, rural homes, dirt roads, tractors, livestock, rivers and bridges.
- Farmers, workers, harvest and delivery quests, rural merchants, wildlife.
- Some farms peaceful; others hide monster nests, bandits, or a reclusive master.

### Region 5 — Mount Tenrai (starter highlands)
The player's starting home.
- Forested peaks, waterfalls, fishing spots, cliffside trails, hidden caves and roaming **thunderhorn** beasts (original giant reptiles).
- **Tenrai Dojo**, a mountain cabin-dojo run by gruff, kind mentor **Master Hoshigane**.

### Region 6 — The Glass Sea and its islands
Vast oceans with real distances between islands.
- **Driftshell Isle:** tiny tropical island with a ramshackle beach hut, dock and sparring sand. Home of eccentric old **Grandmaster Oru** and his sarcastic pelican **Captain Pell** — the beginner's teacher.
- **Sunreef Archipelago:** jungles, an active volcano, fishing villages, sky-pirate bases, sunken ruins, rare enemies and hidden bosses.
- **Hermit Isles:** remote islands holding secret masters, forbidden techniques and special trials.
- Ocean gameplay: swimming, diving, underwater caves, boats, Fold-Cube watercraft, sea life, coastal enemies.

### Additional biomes
- **Ridgeback Mountains:** colossal rounded peaks, cliff temples, waterfalls, caves.
- **Saffron Expanse:** dunes, canyons, ghost towns, bandit hideouts, buried ruins.
- **Whisperwood:** dense forest, hidden villages, secret training groves, enemy camps.
- **Frostveil Reach:** frozen lakes, ice caves, a research outpost, dangerous beasts.
- **The Scar:** wasteland of a ruined city and military base from an old invasion; hostile factions.
- **Sacred heights:** floating sanctuaries and divine training grounds.

Every region gets unique terrain, architecture, enemies, NPCs, quests, weather and rewards.

### Landmark locations
- **Grand Crucible Arena** — the world martial-arts tournament.
- **The Skyspire** — an impossibly tall tower; climbing it is a trial. At the top lives hermit sage **Kotaro**, who grows **Vigor Seeds** (full-heal items).
- **Celestial Terrace** — a floating sanctuary above the clouds, guarded by the serene **Warden Elys**.
- **The Echo Vault** — a training chamber where time runs differently; limited-use, high-reward training.
- **Ironclad Citadel** — fortress of the Syndicate's arms supplier, a mid-game raid.
- **Fort Dread** — abandoned invasion base in The Scar.
- **Oracle's Lantern** — a floating palace where a fortune-teller sets riddle quests.

Gate distant landmarks behind flight range, quests or portals. Never cluster them near the start.

---

## 5. OTHER WORLDS
Aurelia is the hub; later content travels off-world, each as its own Place in one experience:
1. **Verdis** — emerald water world, home of the Verdani race; crystal villages.
2. **Kragmor Ruins** — shattered homeworld of the Vanyr warrior race.
3. **Throne of Nihl** — the god of ruin's twisted palace planet.
4. **Sanctum of Dawn** — the Luminar gods' garden world.
5. **The Afterlands** — a spirit realm along a winding road through the clouds.
6. **Underpyre** — a fire-and-chains underworld.
7. **The Hollow Abyss** — a demon dimension of inverted gravity.
8. **Vael** — a planet in a rival cosmos, with its own champions.
9. **Fractured Tomorrow** — a ruined future timeline.
10. **The Apex Ring** — a floating arena dimension for the inter-cosmos tournament.

Each world: unique terrain, architecture, NPCs, enemies, bosses, questlines, forms or techniques, environmental effects and exploration rewards.

---

## 6. LIVING-WORLD NPC AI (critical)
### Civilians
Walk naturally along roads and sidewalks, avoid obstacles, enter and leave buildings, shop, chat with each other, sit on benches, work jobs, travel between destinations, react to nearby danger, flee, then return to normal routines.

### Schedules
Time-based routines (home → commute → work → shop → home). Lightweight schedule simulation for distant NPCs; full fidelity only near players.

### Pathfinding
PathfindingService with obstacle avoidance, recalculation, stuck detection, destination selection, smooth turning, walk/run speed variation. No walking into walls.

### Animation
Idle, walk, run, turn, talk, reactions, and combat animations where relevant. No sliding without leg movement.

### Combat AI
Patrol, detect, chase intelligently, block, dodge, use melee combos and Ki attacks, retreat, coordinate with allies, react to transformations, recover from knockback. Bosses get dedicated AI.

---

## 7. ORIGINAL CAST
Each major character needs a custom model, distinct face, unique outfit, unique animations, dialogue, personality-driven behavior, their own quests, abilities and fighting style. Never identical rigs with different names.

### Mentors and allies
| Character | Role |
|---|---|
| **Grandmaster Oru** | Goofy island hermit; beginner fundamentals, breathing, first Ki blast. |
| **Captain Pell** | Oru's sarcastic pelican; comic relief and hint giver. |
| **Master Hoshigane** | Mount Tenrai dojo master; stamina and grappling. |
| **Sera Quill** | Helix Dynamics inventor; gear, the "Pulse Lens" power-tracking visor, vehicles. |
| **Thane of the Verdani** | Stern regenerating warrior; Ki control and discipline. |
| **Rook Valen** | Exiled Vanyr prince; proud rival who becomes a sparring partner. |
| **Mira Kestrel** | Tournament champion and street-fighting ace in Port Kessel. |
| **Sage Kotaro** | Skyspire hermit; climbing trial, Vigor Seeds. |
| **Warden Elys** | Celestial Terrace guardian; meditation and Echo Vault access. |
| **Seraph Iolanthe** | Attendant of the god of ruin; divine movement training. |

### Villains and rivals
| Character | Role |
|---|---|
| **Boss "Ratchet" Moreau** | Iron Lantern Syndicate kingpin (East-side early boss). |
| **Gorvan & Sythe** | Vanyr scouts — first off-world threat. |
| **Empress Kaelith** | Carapax tyrant who sheds armored shells as she escalates. |
| **The Hollow Knights** | Kaelith's five-member elite squad, each with a gimmick. |
| **Dr. Malvek Orrin** | Rogue scientist building bio-constructs. |
| **Vhorr** | Malvek's ultimate bio-construct; absorbs fighters to evolve. |
| **Gloam** | Ancient elastic chaos entity, childish and terrifying. |
| **Draxx the Unbound** | Berserker whose power grows uncontrollably. |
| **Nihl, God of Ruin** | Bored, capricious destroyer deity; late-game "test" boss. |
| **Champion Ashka of Vael** | Silent, overwhelming rival-cosmos champion. |

---

## 8. PLAYER CHARACTER
Customization: race, hairstyle, hair/eye color, face, skin tone, clothing, armor, aura color, combat stance.

### Races (original)
| Race | Identity | Tendencies |
|---|---|---|
| **Human** | Versatile, technique-focused | Fast mastery, best technique variety |
| **Vanyr** | Warrior race that grows stronger from battle | High strength, surge forms, weaker Ki control early |
| **Verdani** | Green-skinned regenerators from Verdis | Regeneration, stretch limbs, giant form |
| **Synth** | Built bio-mechanical fighters | Infinite-ish stamina, no Ki sensing |
| **Gelloid** | Elastic, absorbing beings | Absorb attacks, shape-shift strikes |
| **Carapax** | Armored imperial race | Huge defense, shell-shedding forms |
| **Luminar** | Celestial attendants | Speed, barriers, healing |
| **Ashborn** | Demon-realm race | Dark Ki, life drain, risky power |

Balance through real trade-offs, not raw numbers.

---

## 9. ANIMATION
Rebuild all player and NPC animation — default Roblox animations are not the final product.
- **Locomotion:** idle, walk, run, sprint, jump, fall, land, swim, dive, hover, fly, boost, ascend, descend.
- **Full-body motion:** coordinated shoulders, elbows, wrists, torso, hips, knees, ankles, head.
- **Combat:** five-hit combos, heavy punch, roundhouse, uppercut, ground slam, aerial combos, vanish strike, dodge, block, parry, counter, knockback reactions — each with anticipation, active frames, follow-through and recovery.
- **Architecture:** Animator, AnimationTracks, Motor6D procedural layers, skinned rigs. Clean blending, no stuck poses, no nonexistent animation IDs. Where assets can't be published directly, build procedural alternatives or import-ready data.

---

## 10. FLIGHT
Hover, normal flight, high-speed flight, boost, ascend/descend, directional dash, midair combat, braking, instant acceleration, aerial pursuit. Natural banking; poses change with speed and direction. FOV, wind, energy trails and sound sell speed. Always responsive.

---

## 11. TECHNIQUE LIBRARY
An extensible ability system: dozens of techniques at launch, 100+ over the roadmap. Each has its own animation, charge behavior, geometry, VFX, impact, sound, damage scaling, Ki cost, cooldown, mastery, unlock requirement and server validation.

### Archetypes (each must play differently)
Beam · Disc · Sphere · Barrage · Rush combo · Counter · Barrier · Grab · Teleport · Explosion · Sustained channel · Support/heal · Summon/trap

### Launch technique set (original)
| Technique | Archetype | Notes |
|---|---|---|
| **Ki Bolt** | Projectile | Basic rapid blast; everyone starts with it. |
| **Radiant Lance** | Beam | Two-handed charged beam; the "signature" starter beam. |
| **Twin Helix** | Beam | Two spiraling beams that braid together. |
| **Nova Cannon** | Beam | Huge slow beam, armor while charging. |
| **Piercing Needle** | Beam | Thin, instant, long-range drilling ray. |
| **Orbit Cutter** | Disc | Thrown spinning Ki disc that curves. |
| **Comet Barrage** | Barrage | Dozens of homing bolts from both hands. |
| **Starfall Volley** | Barrage | Bolts launched upward that rain on an area. |
| **Communion Orb** | Sphere | Huge orb charged by gathering Ki from allies/environment. |
| **Ember Core** | Sphere | Throwable miniature sun that detonates. |
| **Gravity Well** | Sphere | Slow orb that pulls enemies in. |
| **Flashstep** | Teleport | Short-range blink behind target. |
| **Phantom Step** | Counter | Leaves an afterimage that absorbs one hit. |
| **Blinding Halo** | Utility | Flash that stuns everyone facing you. |
| **Shatter Fist** | Rush | Charged punch that breaks guard. |
| **Tempest Combo** | Rush | Multi-hit aerial chain ending in a slam. |
| **Skyrend Uppercut** | Rush | Launcher into air pursuit. |
| **Iron Bastion** | Barrier | Dome shield that reflects weak projectiles. |
| **Pulse Nova** | Explosion | 360° shockwave burst. |
| **Rift Grip** | Grab | Ki tether that yanks a target in. |
| **Regrowth** | Support | Verdani regeneration. |
| **Elastic Lash** | Rush | Gelloid stretching multi-strike. |
| **Shell Shed** | Explosion | Carapax armor-burst knockback. |
| **Umbral Drain** | Sustained | Ashborn life-drain channel. |
| **Lumen Ward** | Support | Luminar shield for allies. |
| **Ruin Touch** | Special | Late-game divine erasure strike, heavy restrictions. |

Rules: never 100 names on five effects. Each technique needs distinct geometry, motion, timing and impact.

---

## 12. COMBAT
- Light and heavy attacks, aerial combos, launchers, slams, block, perfect block, dodge, vanish, counter, grabs, teleport strikes, cinematic finishers.
- **Feel:** hitstop, directional knockback, impact flashes, motion trails, camera shake, screen effects, ground impacts, air pursuit, environmental reactions.
- Timing and positioning matter; stats alone don't decide fights.
- **Beam clashes:** colliding beams lock into a synchronized struggle — collision sphere, deforming beams, sparks, camera work, timing-based input (not pure mashing), server-authoritative result.

---

## 13. VFX
Custom MeshParts, Beams, Trails, ParticleEmitters, animated textures, procedural geometry, dynamic lights, Highlights, camera effects. Energy attacks have bright cores, layered outer energy, turbulence, lightning, trails, shockwaves and distinct explosions. No plain neon cylinders as finished effects; no recolored duplicates.

---

## 14. DESTRUCTION
Craters, dust, debris, cracked terrain, damaged buildings, breakable rocks, shockwaves — temporary, auto-restoring, inside controlled zones. Never permanently break quest areas.

---

## 15. POWER-UP FORMS (original)
Every form changes the character visually **and** mechanically: unique hair/body change, eyes, aura, energy motion, transformation animation, idle stance, combat VFX, stat modifiers, Ki/stamina drain and mastery. Mastered forms activate faster. Some forms are race-specific or locked behind exceptional quests.

### Vanyr
| Form | Look | Play |
|---|---|---|
| **Ember Surge** | Hair turns molten amber with drifting embers; eyes glow orange | Strength boost, slow Ki drain |
| **Ember Surge II** | Glowing fissure markings spread over the arms; crackling heat haze | Faster, heavier hits, higher drain |
| **Ember Surge III** | Hair lengthens into a flowing mane of flame; obsidian horns form | Massive power, punishing drain |
| **Primal Ascent** | Feral crimson fur on shoulders, rune tattoos, golden irises | Brawler form, lifesteal on hits |
| **Crimson Ascension** | Leaner build, deep red hair and calm red aura | Divine Ki, efficient, faster regen |
| **Azure Apex** | Hair crystallizes cyan-white, aura becomes geometric shards | Top-tier Ki damage |
| **Stillmind** | Silver-white aura like rippling water; eyes go pale | Auto-dodges, counters, calm movement |
| **Ravage Ascent** | Violet aura of jagged smoke; hair spikes dark purple | Grows stronger when hit |

### Other races
- **Verdani:** Rooted Awakening (bark-like armor), Titan Growth (giant form), Bloom State (luminous orange-green).
- **Carapax:** Second Shell, Third Shell, True Form, Gilded Shell (gold), Void Shell (black).
- **Gelloid:** Pure, Cruel, Absorbed-Trait forms (gains a trait from an absorbed enemy).
- **Human:** Unlocked Potential, Overdrive (risky multiplier), Clear Mind, Limit Break.
- **Luminar / Ashborn:** Divine Awakening, Dawnbringer; Abyss Awakening, Hollow Crown.

### Transformation sequences
Full-body animation, hair/body morph, aura buildup, ground shake, floating rocks, shockwaves, energy pulses, camera moves, sound.

---

## 16. RPG PROGRESSION
Loop: Explore → Train → Quest → Fight → Level → Stats → Techniques → Forms → Bosses → New regions.
- **Stats:** Strength, Ki, Defense, Agility, Stamina, Ki Control, Technique Mastery.
- **Training:** dummies, gravity rooms, sparring, meditation, Ki control drills, flight courses, speed trials, martial-arts challenges, the Echo Vault.
- **Rewards:** XP, levels, stat points, technique and form mastery, currency (**Zen**), gear, quest rewards.
- Meaningful progress without mindless grinding.

---

## 17. QUESTS
Main story, side quests, training, boss hunts, exploration, collection, form-unlock quests, character quests, tournament quests, off-world questlines.

Examples:
- **Grandmaster Oru:** first Ki blast, balance on the dock, outrun Captain Pell.
- **Master Hoshigane:** carry boulders up Tenrai, waterfall endurance.
- **Thane:** hold Ki steady under pressure; regeneration trial.
- **Rook Valen:** escalating spars — beat him once to earn his respect.
- **Sera Quill:** gather parts for Fold-Cube vehicles and the Pulse Lens.
- **Seraph Iolanthe:** divine movement drills; dodge-only trials.
- **Nihl:** "entertain me" challenges with ridiculous stakes.

Every quest has dialogue, objectives, rewards and requirements.

---

## 18. BOSSES
Unique models, animations and moves; multiple phases; transformations; cinematic intros; ultimate attacks; environmental interactions. Never just a big health bar.

Launch boss line: Ratchet Moreau → Gorvan & Sythe → Hollow Knights → Empress Kaelith → Dr. Malvek's constructs → Vhorr → Draxx → Gloam → Nihl → Champion Ashka.

---

## 19. HUD AND MENUS
- **Bottom-left:** portrait, level, health, Ki, stamina, form status.
- **Bottom-right:** equipped techniques with custom icons, keybinds, cooldowns, Ki costs.
- **Top-right:** collapsible quest tracker.
- **Top-center:** notifications, boss announcements, form unlocks.
- One compact menu button → Character, Stats, Techniques, Forms, Inventory, Quests, Map, Settings, Party, Achievements. All buttons work.
- UI scale slider 60–140%. Desktop, mobile and controller layouts.

---

## 20. LIVING WORLD
Day/night cycle, regional weather (clear, rain, thunderstorm, fog, snow, sandstorm), civilian schedules, hover-traffic, wildlife, ambient dialogue, shops, restaurants, schools, farms, random encounters, world events (meteor falls, Syndicate raids, invasion scouts).

---

## 21. MULTIPLAYER
Parties, co-op quests, PvP arenas, Grand Crucible tournaments, world bosses, group training, trading where appropriate, guilds/factions, synchronized transformations and beam clashes. Server-authoritative combat; anti-exploit checks on damage, rewards, movement and progression.

---

## 22. THE RESONANCE KEYS
Seven **Resonance Keys** are scattered across Aurelia, found through exploration, quests and events. With all seven, the player opens the **Resonance Gate**, summoning **Aurelis**, a colossal star-whale of living light, in a cinematic sequence. Wishes: rare gear, stat reset, special training, currency, cosmetics, limited progression boosts. The Keys scatter again afterward. Later worlds can have their own key sets.

---

## 23. TECHNICAL ARCHITECTURE
Modern Luau, modular:
combat · technique registry · form registry · NPC behavior · pathfinding · quest manager · progression manager · data persistence · VFX manager · animation controller · flight controller · UI controller · world streaming · multiplayer sync.

Use StreamingEnabled, object pooling, distance-based NPC simulation, mesh reuse, LOD, particle budgets, client-side cosmetics, server-side validation and proper cleanup. Smooth on capable PCs with scalable graphics settings.

---

## 24. DEVELOPMENT EXECUTION
This is an implementation request.
1. **Inspect the existing project:** architecture, world, combat, animation, HUD, NPCs, quests, forms, techniques, performance limits.
2. **Preserve what works:** don't delete working systems; keep saved-data compatibility. Rename any existing franchise-specific names to the original equivalents in this document, migrating save data where needed.
3. **Ship large integrated releases**, prioritizing:
   1. World expansion and architecture
   2. NPC models, movement and AI
   3. Animation rebuild
   4. HUD and menus
   5. Technique library
   6. Form system
   7. Combat and VFX
   8. Landmark locations and cast
   9. Quests and progression
   10. Optimization and multiplayer stability

---

## 25. QUALITY CONTROL
Before calling a release done, verify: spawning, flight, melee, Ki attacks, forms, NPC movement and obstacle navigation, NPC animations, quest progress, enemy respawns, bosses, UI buttons, HUD updates, data saving, region travel, performance, preserved functionality. Never claim testing that didn't happen; flag what needs Roblox Studio verification.

---

## 26. RULES
1. No low-quality shortcuts — no plain boxes as finished buildings.
2. No generic NPCs.
3. No repetitive attacks.
4. No superficial forms.
5. No tiny world.
6. No empty cities.
7. No fake implementation.
8. No unnecessary restarts — preserve the project.
9. No excessive incrementalism — ship meaningful releases.
10. No unnecessary approval requests — make reasonable decisions.
11. No unsupported technology claims.
12. No false completion claims — label implemented / partial / planned / untested.
13. **No franchise material** — everything original (see the originality rule at the top).

---

## 27. DELIVERABLES
1. Updated Roblox project (prefer `.rbxl`/`.rbxlx`; otherwise a Rojo-compatible project).
2. Updated Luau modules.
3. World and environment assets.
4. NPC systems.
5. Animation systems.
6. HUD and menus.
7. Technique registry.
8. Form registry.
9. Quest and progression systems.
10. Installation and testing instructions.
11. List of implemented changes.
12. Remaining asset requirements.
13. Known limitations.

No pseudocode in place of implementation.

---

## 28. FINAL DIRECTIVE
Make Project Ascendant the definitive anime martial-arts open-world RPG on Roblox. I want to explore a gleaming capital, a harbor city, quiet suburbs, golden farmland, forests, mountains, deserts and oceans; fly across the world to distant islands; train under eccentric masters; face theatrical villains; travel to other worlds. I want NPCs with real lives, fluid flight, cinematic melee, spectacular Ki techniques and dozens of meaningful forms — with a professional HUD and satisfying progression.

Quality over quantity. Build a scalable foundation, then deliver substantial integrated releases toward the full vision.

**Begin:** inspect the existing project, preserve its functionality, implement the highest-impact improvements, and deliver real updated project files.
