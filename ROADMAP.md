## OVERALL ROADMAP

My ultimate vision for Remnant Horizon is to evolve into a full-fledged space exploration game, offering an immersive experience with a strong sense of scale, lively star systems, and refined gameplay mechanics.

### What's Complete ✅
- ✅ **Custom Physics Engine** with thrust, drag, inertia, and collision handling
- ✅ **Single Source of Truth State Management** with persistence, missions, reputation, and cargo
- ✅ **Main Menu** - Full menu with starting new game, loading save and game settings.
- ✅ **Pause Menu** - Full pause menu with saving, loading, settings, exit to main menu, etc.
- ✅ **Space ↔ Planet Surface Transitions** with dedicated surface lighting and gravity
- ✅ **Procedural Terrain Generation** with bilinear height sampling and biome-specific POIs
- ✅ **NPC AI System** with planetary avoidance and physics parity
- ✅ **Ship Wreckage Salvage** salvage/tractor beam logic to gather cargo from destroyed enemy ships
- ✅ **Dynamic HUD** with ship info, coordinates, 2D radar and proximity prompts
- ✅ **Tutorial System** - The Pilot's Handbook
- ✅ **Player Ship Entity** with integrated thruster physics, weapon systems, and damage logic
- ✅ **Logarithmic Depth Buffer** for proper space scale rendering
- ✅ **Modular Architecture** with clear separation of concerns
- ✅ **Cross-module Communication** via custom DOM events
- ✅ **Frame-rate Independent Physics** using delta time integration
- ✅ **Deterministic Procedural Generation** using seeded RNG
- ✅ **Code Best Practices** including proper material usage and depth sorting
- ✅ **Atmospheric entrance & flight** - enter a planet instance and can fly around in the atmposphere.
- ✅ **Walkable Planet Surfaces** - ability to get out of ship and walk around on planets freely.
- ✅ **Warp & Hyperdrive Systems** - Differentiated intra-system and interstellar travel
- ✅ **Death & Respawn System** - Proper destruction mechanics with station-based respawning
- ✅ **Free Look Camera System** - Independent camera control in first and third-person views
- ✅ **Camera Systems** - Dual first-person cockpit and third-person "jet fighter" cameras
- ✅ **Space Station System** with trade markets, ship upgrades, dynamic mission generation
- ✅ **Interstellar Travel** - Warp drive mechanics with visual effects and cooldowns
- ✅ **Solar System Navigation & Boundaries** - Clear navigation and system transitions
- ✅ **Station UI Scalability** - Large inventory support with scrolling and filtering
- ✅ **Cargo Quantity Indicators** - Accurate display for buying/selling items
- ✅ **Active Salvaging / Resource Harvesting** - Tactile mechanics for resource gathering
- ✅ **Currency & Trading** - Full in-game currency and operational markets
- ✅ **Advanced HUD** - Dynamic HUD with minimap, radar, coordinates, and status indicators
- ✅ **Minimap Improvements** - Repositioned UI elements and enhanced functionality
- ✅ **Galaxy & System Maps** - Comprehensive mapping systems
- ✅ **UI & Inventory Systems** - Refined inventory UI with Commander Status

### What's In Progress (WIP) 🔄
- (WIP) **Event-Driven Communication System** using prefixed DOM events
- (WIP) **Player Guide (Pilot's Handbook)** - Implemented base guide, but will keep expanding as complexities grow
- (WIP) **Save System** . Currently only 1 save and load slot. Working on making more with 3 localStorage slots and auto-save functionality
- (WIP) **Procedural Universe Generation** with textured stars and noise-based planet continents
- (WIP) **Core Systems Loop** with mission tracking, economy drift
- (WIP) **Refined Ship-to-Ship Combat** - Implement inertia-based physics for visceral, skill-based combat
- (WIP) **Walkable Ship Interiors** - Partially detailed interiors with interactable elements. Resolving some bugs around this.
- (WIP) **Full Atmospheric Entry & Seamless Planet Landing** - Currently able to land on planets and get out of ship, collect resources. However, needs Realistic gravity and atmospheric drag effects
- (WIP) **Ground Combat & Interaction** - planetary resource interaction implemented and working, no ground combat yet.
- (WIP) **Ship Flight Model & Thrust Balancing** - Refined handling with realistic inertia. Feeling like a space jet, but still refining over time.
- (WIP) **Ship Progression System** - tiered upgrades. Works on most upgrades, haven't tested all.
- (WIP) **Difficulty Settings** - Adjustable game difficulty scaling enemy behavior
- (WIP) **True Space Feel/Scale** - Massive stars, proper spatial distances. Decent, but looking to scale further.
- (WIP) **Factions & Territories** - Multiple dynamic factions with controlled systems
- (WIP) **Points of Interest (POIs)** - Procedurally generated surface POIs. I have POIs and they work, but want to expand and make more meaningful.
- (WIP) **Simple Economy System** - Dynamic supply/demand influenced pricing
- (WIP) **Diverse Reward-Based Mission System** - Trade runs, combat bounties, mining contracts. Basic ones almost done.
- (WIP) **Mission Guidance & Navigation** - Clear objectives with navigation assistance
- (WIP) **Comprehensive Ship Upgrades** - Extensive upgrade trees for all ship systems
- (WIP) **Mining Gameplay** - Asteroid mining mechanics and dedicated ships. Planet resource deposit "mining" implemented. Very early stages.
- (WIP) **Procedural Audio System** using Web Audio API - all sounds synthesized in real-time
- (WIP) **Graphics & Rendering Enhancements** - Advanced techniques, shaders, post-processing

### What's Not Started Yet ❌
- ❌ **Vast Procedural Universe** - Fully generated star systems with unique planets. Currently have 4 star systems for generation, economy and mission testing.
- ❌ **Environmental Hazards & Fuel Management** - Radiation zones, temperature extremes, nebulae, gravitational anomalies
- ❌ **Multiple Slot Save System** - Expanded save functionality with comprehensive persistence
- ❌ **Dynamic & Living Star Systems** - Active NPC ships, trade convoys, pirate fleets
- ❌ **Interactive Walkable Space Stations** - Vibrant hubs with active NPCs and services. Interior exploration and vendor interaction.
- ❌ **Enemy Spawning Logic** - Logical spawning based on faction control
- ❌ **Dynamic Environmental Events & Anomalies** - Unpredictable procedural events
- ❌ **Scanning & Reconnaissance Mechanics** - Active scanning for information gathering
- ❌ **Dialogue Options & Reputation Feedback** - Impactful NPC interactions
- ❌ **Player Upgrades** - Armor and personal weapon upgrade systems
- ❌ **Ship Class System** - Multiple ship types with unique strengths and roles
- ❌ **Basic Ship Customization** - Cosmetic options (paint jobs, decals)
- ❌ **Suit Upgrades** - EVA capability and suit integrity upgrades
- ❌ **Weapon Variety** - Expanded weapon types beyond basic projectiles
- ❌ **Simple Co-op Multiplayer** - State synchronization for shared gameplay
- ❌ **Core Story Arcs** - Full rescue arc, signal investigation, fortress infiltration, motivation reveal
- ❌ **Narrative Delivery Systems** - Expanded AI and radio systems
