# Fishing Realms — Phase Tracker

This document tracks what has been built, what's in progress, and what's next.
Update this file as each phase is completed.

---

## Phase 1 — Core Fishing
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/server/Core/FishingManager.lua` — handles cast, catch, rarity roll
- [ ] `src/client/Tools/RodTool.lua` — rod tool LocalScript (click to cast)
- [ ] `src/client/UI/MinigameUI.lua` — timing bar minigame UI
- [ ] `src/shared/Data/FishData.lua` — fish rarity table

---

## Phase 2 — Fish & Inventory
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/shared/Data/FishData.lua` — 25 fish with rarity, value, name
- [ ] `src/server/Core/DataManager.lua` — DataStore save/load
- [ ] `src/client/UI/InventoryUI.lua` — inventory screen

---

## Phase 3 — Economy
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/server/Economy/SellManager.lua` — sell logic, coin awards
- [ ] `src/client/UI/SellUI.lua` — Sell All button UI

---

## Phase 4 — Shop
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/server/Shop/ShopManager.lua` — purchase handler
- [ ] `src/client/UI/ShopUI.lua` — shop GUI
- [ ] `src/shared/Data/ShopData.lua` — rod & bait item tables

---

## Phase 5 — World System
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/server/Worlds/RealmManager.lua` — unlock & teleport logic
- [ ] `src/client/UI/RealmUI.lua` — realm selection UI
- [ ] `src/shared/Data/RealmData.lua` — realm config table

---

## Phase 6 — Progression
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/server/Progression/LevelManager.lua` — XP, level-up logic
- [ ] `src/client/UI/LevelUI.lua` — XP bar, level display

---

## Phase 7 — Aquarium
**Status:** 🔲 Not started  
**Scripts:**
- [ ] `src/server/Aquarium/AquariumManager.lua` — store fish, passive income loop
- [ ] `src/client/UI/AquariumUI.lua` — aquarium display

---

## Phase 8 — Polish
**Status:** 🔲 Not started  
**Tasks:**
- [ ] Sound system (cast, catch, sell, level-up SFX)
- [ ] UI animations and transitions
- [ ] Full bug fix pass
- [ ] Performance review

---

## Bugs / Issues Log
| # | Description | Phase | Fixed? |
|---|-------------|-------|--------|
| — | No bugs yet | — | — |
