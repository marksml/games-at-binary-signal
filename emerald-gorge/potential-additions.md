# Potential Additions for Emerald Gorge

Ideas to make **Emerald Gorge** (`emerald-gorge/index.html`) more engaging, varied, and replayable while building on its existing Three.js + Tone.js single-file architecture.

---

## 1. Movement & Gliding Depth

- **Thermal Updrafts**: Add rising, shimmering wind columns over gorges, volcanic vents, and waterfall bases that lift the canopy glider upward, turning gliding from a slow descent into soaring across mountain peaks.
- **Aerial Sky Rings / Boost Hoops**: String floating emerald or gold rings between cliffs and over the river. Flying through them grants a speed + altitude boost and plays an ascending harmonic chime streak.
- **Relic-Powered Progression Upgrades**: Reward exploration with tangible upgrades as relics are collected (e.g., 2 relics = stronger glider lift, 4 relics = faster sprint & swim, 6 relics = mid-air boost / double-jump).
- **River Current**: Gently push swimming players downstream so crossing the river becomes a more tactical choice between the suspension bridge, gliding across, or timing a swim past crocodiles.

---

## 2. Varied Relic Challenges & Secrets

Give individual relics distinct discovery mechanics instead of placing all 8 on identical open pedestals:

- **Secret Waterfall Grotto**: Tuck a relic inside a small glowing alcove behind one of the cascading waterfalls.
- **Stepping-Stone River Crossing**: Place a relic on mossy stone pillars or a sandbar island guarded by patrolling crocodiles.
- **Ancient Pressure Totems**: Lock a sanctuary relic until the player activates 3 nearby glowing stone switches.
- **Volcanic Geyser Launch**: Position a steam vent near the tallest spire to launch the player high enough to glide onto the summit.

---

## 3. Wildlife, Risk & Atmosphere

- **Crocodile Warning & Escape Counterplay**: Add a splash/growl Tone.js sound cue and visual ripple warning when a crocodile begins chasing, plus a well-timed jump/dash escape window.
- **Bioluminescent Night Mode**: Add a 4th **Starry Night** lighting preset (alongside Noon, Sunset, and Dawn Mist) featuring a starfield sky, brighter fireflies, glowing jungle mushrooms, and stronger campfire illumination.
- **Richer Procedural Audio (Tone.js)**:
  - Proximity-based waterfall roar
  - Surface-specific footsteps (grass, sand, wooden bridge planks)
  - Water splash and crocodile snap sound effects
  - Soft tropical marimba/kalimba melody notes while gliding or discovering landmarks
- **Distinct Landmarks & Ruins**: Add memorable visual anchors across the valley—an ancient stone temple arch, mossy tiki totems, a second high-altitude gorge bridge, or a wooden lookout tower near Base Camp.

---

## 4. Replayability & Quality-of-Life

- **Expedition Timer & Personal Best (`localStorage`)**: Track run completion time, distance glided, and crocodile escapes; display Bronze / Silver / Gold Explorer medals and save personal records locally.
- **Optional Bonus Collectibles**: Scatter extra **Golden Coconuts** or **Sun Shards** along scenic ridges and aerial glide lines for completionists.
- **Toggleable Mini-Map**: Add a compact corner map (`M` key or HUD toggle) showing the river, bridges, player heading, and discovered vs. undiscovered relic areas.

---

## Suggested Implementation Bundles

If implementing in stages, these combinations pair well together:

1. **Soaring & Progression Pack**: Thermal Updrafts + Aerial Sky Rings + Relic-Powered Upgrades
2. **Atmosphere & Immersion Pack**: Bioluminescent Night Mode + Expanded Tone.js Soundscape + Ancient Ruin Landmarks
3. **Challenge & Replayability Pack**: Varied Relic Puzzles + River Current + Expedition Timer & Medals
