# The Remnant Beneath — Game Structure

The whole game, every part, and where it lives on GitHub. One page, kept current as the game grows.

Live game: https://ejyoungr-hash.github.io/the-remnant-beneath/
Repo: https://github.com/ejyoungr-hash/the-remnant-beneath

## The world

A far future. The old world is gone, its machines buried under grass and dirt. Four realms grew over the ruins, a swamp hides the entrance, and a sealed fifth realm waits underground. The hero finds a buried ember relic that reveals the map to the fifth realm.

The map is one connected world, screen to screen, Zelda style. Walk off an edge and the next screen slides in. 60 screens in all, 10 per realm. One save shrine per realm. Difficulty rises the further out you go.

```
            Whitepeak (north)
                |
  Thornwood ---- Meadowlands ---- Dustfall
   (west)         (center)         (east)
                |
            Mistmire (south)
                |
          The Remnant (underground, through the Sealed Door)
```

## Realms and screens

### Meadowlands (10) — BUILT, live
The village and the meadow around it. The hub of the game.

1. Village — Elder Bram, Renn, Mira, the shops, the village girl
2. North Meadow — herbs for Mira, goblins
3. East Meadow — toward Dustfall, Lucky charm on the east edge
4. West Meadow — toward Thornwood, Ember charm on the west edge
5. South Meadow — toward Mistmire
6. Herb Field — sunleaf and moonpetal
7. Goblin Den — the Goblin Trouble quest
8. Old Mill — abandoned, coins and secrets
9. Flower Field — the village girl's secret spots
10. Meadow Shrine — save shrine

### Thornwood (10) — slice 1 BUILT and live, slices 2 and 3 next
The dark forest west of the meadow. Dense trees at the edges, open middle, fireflies.

1. Forest Edge — Joren's cabin (slice 2)
2. Deep Forest — wisps and wolves
3. Wolf Den — Hunter Sable's camp (slice 2)
4. Thornwolf's Lair — the boss room (slice 3)
5. Goblin Cave — hidden cave, Joren's axe (slice 2)
6. Hollow Log — where the bow scout found the ember
7. Old Oak — the biggest tree in the forest, a secret at its roots
8. Mushroom Grove — healing herbs
9. Thorn Maze — a minigame gate (slice 3)
10. Forest Shrine — save shrine

### Dustfall (10) — designed, not built yet
The desert east of the meadow. Dark wisps and stone golems.

1. The Dunes — Zeke's camp
2. The Oasis — water for the Water Run
3. Buried Ruins — wisps and golems
4. Dune Colossus Arena — the boss room
5. Broken Bridge — the crossing over the canyon from the East Meadow
6. Dead Palms — Old Maren's relic, where the two dead palms lean together
7. Sand Pit — dig for coins
8. Old Well — the Water Run's waterskin
9. Ruined Watchtower — a view over the whole desert
10. Desert Shrine — save shrine

### Whitepeak (10) — designed, not built yet
The snowy mountains north of the meadow. Shadow wolves and stone golems.

1. Mountain Path — Hilda's inn at the foot
2. Frozen Lake — Storm Crystals
3. Blizzard Pass — wolves and golems
4. Storm Wraith Peak — the boss room
5. Hilda's Inn — warm bed, hot stew
6. Frozen Traveler's Camp — the pack from Hilda's quest
7. Ice Caves — hidden cave
8. Snowy Ridge — Guardian charm on the north edge
9. Crystal Field — more Storm Crystals
10. Mountain Shrine — save shrine

### Mistmire (10) — designed, not built yet
The swamp south of the meadow. Dark wisps, shadow wolves, goblins. Hides the entrance to the fifth realm.

1. Swamp Edge — Mudfoot
2. Black Water — Pell's ferry crossing
3. Sunken Shrine — the Sunken Shrine quest
4. The Sealed Door — the entrance to the Remnant, needs the Master Key
5. Mudfoot's Hut — the Medicine quest
6. Sunken Cave — hidden cave
7. Firefly Marsh — the Swamp Lights quest
8. Deep Bog — wolves and wisps
9. Old Ferry Dock — where the ferry used to run
10. Swamp Shrine — save shrine

### The Remnant (10) — designed, not built yet
The sealed fifth realm, underground, through the Sealed Door in Mistmire. The last of the old world's light still burns here. Stone golems, dark wisps, lesser shadow knights. The robots are shiny and well kept, not rusty.

1. The Gate — Unit-7 and Nix
2. The Halls — Vendor-9 and the robots
3. The Throne Room — the Shadow Knight, the final boss
4. Old Terminal — Unit-7's quest
5. Vendor-9's Shop — Remnant tech gear
6. Sleeping Robot Bay — the Sleeping Robot quest
7. Broken Guardian Chamber — the Broken Guardian quest
8. Power Core — the Last Battery quest
9. Machine Gardens — the old world's gardens, still growing
10. Remnant Shrine — save shrine

## Bosses and keys

One boss per realm. Each drops a key. The four keys combine into one Master Key that opens the Sealed Door.

| Boss | Realm | Key | Status |
|---|---|---|---|
| Grak, the Goblin King | Meadowlands | Meadow Key | Built, live |
| Thornwolf, alpha of the shadow wolves | Thornwood | Thorn Key | Slice 3, next |
| Dune Colossus, ancient sandstone golem | Dustfall | Dust Key | Designed |
| Storm Wraith, ice spirit | Whitepeak | Peak Key | Designed |
| Shadow Knight | The Remnant | Final boss | Designed |

Boss deaths dissolve into embers, bigger and slower than regular enemies. No blood.

## NPCs and quests

16 NPCs, 16 side quests. Rewards are coins, ember shards, healing, or gear.

| Realm | NPCs | Quests |
|---|---|---|
| Meadowlands | Elder Bram, Farmer Dell, Guard Captain Renn, Mira, the village girl | Lost Goat, Goblin Trouble |
| Thornwood | Woodcutter Joren, Hunter Sable | Lost Axe, Wolf Pelts |
| Dustfall | Trader Zeke, Old Maren | Water Run, Buried Relic |
| Whitepeak | Innkeeper Hilda | Frozen Traveler, Storm Crystals |
| Mistmire | Ferryman Pell, Mudfoot | Swamp Lights, Ferryman's Lantern, Sunken Shrine, Mudfoot's Medicine |
| The Remnant | Scrapper Nix, Unit-7, Vendor-9, Scholar Ivo | Sleeping Robot, Broken Guardian, Old Terminal, Last Battery |

NPCs stand in place. Walk up and press E to talk. A "!" shows when they have a quest. Dialogue shows a detailed close up portrait.

## Heroes, gear, and charms

5 playable heroes, male and female (10 total): swordsman, spear wanderer, bow scout, mage, guardian. The starting look is the base form before upgrades. Armor and weapons change how the hero looks.

You start with NO weapons. The first weapon is tier 1, earned by collecting herbs for Mira, then Captain Renn awards it. A second, long range weapon comes from a second, harder Renn quest, or it can be bought at Renn's Armory. The mage's staff does both, so no second weapon is needed.

- Weapons: 3 tiers per hero. Prices 60, 150, 300 coins.
- Armor: 3 tiers (Leather, Chainmail, Emberplate). Prices 80, 200, 400 coins.
- Bag: starts at 12 slots, upgrades to 20 (100 coins) then 30 (250 coins).
- Health: embers, not hearts. Start with 3. A weak hit takes half an ember. Ember shards add more.
- Ammo: Easy unlimited, Medium refills at shrines, Hard limited, buy more.
- Coins: from enemies, secret spots, cutting bushes and trees, digging.
- Charms (wear two at a time): Lucky (more coin drops), Guardian (less damage), Ember (slow health regen), Seeker (reveals hidden secrets). Lucky sits on the east edge toward Dustfall, Guardian on the north edge toward Whitepeak, Ember on the west edge toward Thornwood, Seeker in the village girl's third chest.

The village girl follows you in the village and shows secret locations, 4 chests in sequence: an ember shard, 100 coins, the Seeker charm, then a hidden chest with a shard and coins.

## Shops

- Village general store (herbs 15, potions 40, bag upgrades)
- Captain Renn's Armory (weapons)
- Mira's Healing (herbs, potions)
- Trader Zeke (desert gear, after the Water Run quest)
- Vendor-9 (Remnant tech gear, once restarted)

## Systems

- Save: browser local storage, 5 save slots (one per hero type). Save shrines and campfires, autosave on entering a new screen and after bosses. Continue on the start screen when a save exists.
- Death: respawn at the last shrine (or the village if closer), keep all inventory. "The Ember Fades" screen with Wake at the Shrine or Return to Title.
- Victory: defeating the Shadow Knight shows "The Light Returns" epilogue with stats, Keep Exploring, and Start Quest Over.
- Map: toggleable, only visited areas revealed. Minimap always in the corner.
- Pause menu: Resume, How to Play, Music and Sound effects toggles with volume sliders, Voices toggle, Save game, Screen mode, Quit to title.
- Controls: WASD or arrows to move, Space or J to attack, E to interact, M for map, I for bag, Esc or P to pause. Touch joystick and buttons on phone. Desktop first with fullscreen, plus a vertical phone mode that switches automatically.
- Cutscenes: still image panels with story text and fades, plus scripted in engine moments. Not video. Boss meetings use a full close up portrait. Item finds animate: the item rises glowing, sparkles burst, a shine sweeps across, then words in a slim text box.
- Music: softer fantasy, made in code, no audio files. One theme per realm plus a tenser boss version of each. 20 code made sound effects.
- Minigames: rune sequence, sliding tiles, connect the flow, torch order, target practice, unscramble ancient word, find hidden rune, cup game, guide ember through maze.
- Art rule: all characters, enemies, NPCs and creatures are chunky 16 bit pixel art matching the hero sprites, few flat colors, thick dark outline, simple shapes, 2 frame walk cycle facing the direction of movement. Portraits and scenery are the exception (portraits are painterly, scenery can be real art). Scenes stay open and less cluttered.

## Build status

- Meadowlands: built and live (10 screens, herb quest, Grak, side quests, chests, charms, shops).
- Thornwood slice 1: built and live (v17, Nov 26, 2026): the 10 forest screens, the forest look, entry narration, Forest Shrine, wisps and wolves, Thornwood melody, Mushroom Grove herbs.
- Thornwood slices 2 and 3: built and live (v18, Nov 26, 2026): Joren moved to Forest Edge with his cabin and the Lost Axe quest, Sable at the Wolf Den with Wolf Pelts, the Thornwolf boss fight and Thorn Key, the Thorn Maze minigame.
- Dustfall, Whitepeak, Mistmire, The Remnant: designed, to be built realm by realm after Thornwood.
- After the game is completed: a graphic novel version of the story.

## Where it lives on GitHub

Repo: `ejyoungr-hash/the-remnant-beneath`, branch `main`, GitHub Pages serving the root. Live at https://ejyoungr-hash.github.io/the-remnant-beneath/

### Files

| File | What it holds |
|---|---|
| `index.html` | All game logic and the interface: screens, movement, combat, dialogue, quests, shops, save, music, cutscenes |
| `data/heroes.js` | Hero sprites, all 10 heroes, all tiers and walk frames |
| `data/panels.js` | Cutscene panels and realm entry art |
| `data/portraits.js` | NPC dialogue portraits |
| `data/grak.js` | Grak boss art and the Meadow Key |
| `data/items.js` | Charms, coins, and item art |
| `data/sprites.js` | Enemy and NPC sprites |
| `data/scenery.js` | Ground tiles, trees, houses, and props |
| `README.md` | This file, the game structure |

The game used to be one single file. It hit about 4.7 MB, so it was split (v16) into `index.html` plus the 7 data files, loaded by script tags. It still runs offline from a file and over HTTP. The art stays as data URIs inside the data files.

### How a new part gets added

- New screens: an entry in `SCREENS` and a spot in `GRID` in `index.html`, plus its ground and props in the screen builder.
- New enemies: sprite art into `data/sprites.js`, stats and drops in the enemy code in `index.html`.
- New NPCs: portrait into `data/portraits.js`, sprite into `data/sprites.js`, dialogue lines and a spot in `index.html`.
- New bosses: boss art and a key image, meeting pages and fight stats modeled on Grak, in `index.html`.
- New realm art: entry art into `data/panels.js`, the realm melody into the music table in `index.html`.
- New data files: add a script tag in `index.html` and add the path to the push manifest.

### Working copy, staged copy, live site

Three copies, in order:

1. Working copy: `~/workspace/trb-fixes30/` (the current build; the number goes up each version). All edits happen here, and tests run here.
2. Staged copy: `~/workspace/github/the-remnant-beneath/`. A fresh export is copied here, the view counter is re added, then it is pushed.
3. Live site: GitHub Pages. After a push, check the Actions "pages build and deployment" run before calling it live, then check the live page itself.

Versions are numbered v1, v2, and so on. The live site is always the latest pushed version. The current live version is v18 (Thornwood slices 2 and 3, pushed Nov 26, 2026).

### View counter

A real view counter sits at the bottom of the live site, "Views: N", using countapi.mileshilliard.com, one key per site (`ejyoungr-hash-the-remnant-beneath`). It lives only in the GitHub copy, never in the working copy's source. It is re added after every staging, with a 15 second timeout and a dash on failure.
