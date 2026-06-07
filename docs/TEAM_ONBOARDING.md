# Team Onboarding — Fishing Realms

Welcome to the Fishing Realms dev team! Read this before touching any code.

---

## How This Project Works

All code is written with **Claude AI** as the dev assistant.
Every script in this repo was generated, reviewed, and structured by Claude based on the game plan.

---

## Your First Steps

1. **Clone the repo**
   ```
   git clone https://github.com/YOUR_ORG/FishingRealms.git
   ```

2. **Open Roblox Studio**
   - Open the shared `.rbxl` place file (ask the lead dev for access)

3. **Check the Phase Tracker**
   - See `docs/PHASE_TRACKER.md` to know what's done and what's next

4. **Place scripts correctly**
   - Follow the service map in `README.md` — wrong placement = nothing works

---

## How to Use Claude for This Project

Any team member can continue development with Claude. Just:

1. Go to [claude.ai](https://claude.ai)
2. Upload the relevant script file(s) from this repo
3. Say: *"I'm working on Fishing Realms. Here's the current [script name]. I need to [add feature / fix bug / extend system]."*
4. Claude will generate or fix the code knowing the full context

---

## Git Workflow

- `main` branch = stable, tested code only
- Create a branch for each phase: `phase-1-fishing`, `phase-2-inventory`, etc.
- Never push directly to main — open a pull request
- Commit message format: `[Phase X] Description of change`

---

## Coding Rules

- **Never** put game logic in a LocalScript — that goes in ServerScripts
- **Never** use `wait()` — always use `task.wait()`
- All RemoteEvents must be created in `ReplicatedStorage/Events`
- All player data goes through `DataManager.lua` only
- Keep scripts under ~150 lines — split if longer

---

## Questions?

Ask in the team Discord, or just open a Claude chat and paste the script you're confused about.
