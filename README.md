# 🎣 Fishing Realms — Roblox Game

A Roblox fishing game with progression, economy, multiple realms, and an aquarium system.

> **Dev Assistant:** All code in this repo is generated and maintained with Claude AI.  
> **Team:** Upload any script file to Claude and ask questions — it knows the full project context.

---

## 📁 Project Structure

```
FishingRealms/
├── src/
│   ├── server/                  # ServerScriptService scripts
│   │   ├── Core/                # Phase 1 — Fishing system
│   │   ├── Economy/             # Phase 3 — Coins & selling
│   │   ├── Shop/                # Phase 4 — Rod & bait shop
│   │   ├── Worlds/              # Phase 5 — Realm system
│   │   ├── Progression/         # Phase 6 — XP & levels
│   │   └── Aquarium/            # Phase 7 — Passive coins
│   ├── client/                  # StarterPlayerScripts / StarterGui
│   │   ├── UI/                  # All GUI LocalScripts
│   │   └── Tools/               # Rod tool LocalScripts
│   └── shared/                  # ReplicatedStorage modules
│       ├── Data/                # Fish data, config tables
│       └── Modules/             # Shared utility modules
├── docs/                        # Phase notes & setup guides
└── assets/                      # Images, icons (reference only)
```

---

## 🗺️ Development Phases

| Phase | System | Status |
|-------|--------|--------|
| 1 | Core Fishing (rod, cast, minigame, catch) | 🔲 Not started |
| 2 | Fish & Inventory (25 fish, DataStore) | 🔲 Not started |
| 3 | Economy (coins, sell system) | 🔲 Not started |
| 4 | Shop (rod shop, bait shop) | 🔲 Not started |
| 5 | World System (Ocean, Lava, teleport) | 🔲 Not started |
| 6 | Progression (XP, levels, unlocks) | 🔲 Not started |
| 7 | Aquarium (store fish, passive coins) | 🔲 Not started |
| 8 | Polish (UI, sounds, bug fixes) | 🔲 Not started |

---

## 🚀 Getting Started (Team Setup)

### Prerequisites
- Roblox Studio installed
- Team access to this GitHub repo

### How to use the scripts
1. Clone or download this repo
2. Open Roblox Studio with the Fishing Realms place file
3. Place scripts into the correct Roblox services (see each phase doc in `/docs/`)
4. Test in Studio using Play Solo or Team Test

### Roblox Service Map
| Folder in repo | Goes into Roblox |
|---|---|
| `src/server/` | `ServerScriptService` |
| `src/client/UI/` | `StarterGui` |
| `src/client/Tools/` | `StarterPack` |
| `src/shared/` | `ReplicatedStorage` |

---

## 📋 Dev Rules (AI Guidelines)
- Keep all systems **modular** — no spaghetti scripts
- One script = one responsibility
- Avoid overcomplication — core loop first
- All RemoteEvents go through `ReplicatedStorage/Events`
- All data goes through the DataStore module — never directly

---

## 🐟 Post-Launch Roadmap
- Boss system
- Fish abilities
- Player trading
- New realms
- Seasonal events

---

## 👥 Team
Update this section with your team members and roles.

| Name | Role |
|------|------|
| | Lead Developer |
| | Builder / Map Design |
| | UI Designer |
| | Tester |

---

*Built with Claude AI — Anthropic*
