## 7. Ready-to-Use Addon Config Packs (`ExternalConfigPacks/`)
The plugin ships lean by default (4 core classes + 16 core perks). To expand your server in seconds—or customize packs for **UnturnedForge.com**—just copy any `.classes.json` and `.perks.json` files from `ExternalConfigPacks/` into `Rocket/Plugins/RPGSkills/ConfigPacks/` and run `/rpgadmin reload`:
- **`MMORPG_Expansion`**: Full RPG setup (`6` new classes: *Ranger*, *Assassin*, *Tank*, *Alchemist*, *Paladin*, *Bounty Hunter* + `21` perks including class-exclusives).
- **`PvP_Competitive`**: Raid & PvP focused (`4` new classes: *Ranger*, *Assassin*, *Juggernaut*, *Combat Medic* + `10` PvP perks).
- **`Hardcore_Survival`**: Wilderness & deadzone survival (`4` new classes: *Alchemist*, *Woodsman*, *Nomad*, *Trapper* + `10` survival perks).
- **`RP_Economy_Utility`**: Professions, crafting, & Uconomy (`4` new classes: *Industrial Miner*, *Master Mechanic*, *Merchant Guard*, *Master Farmer* + `10` profession perks).
> **Tip**: Anything placed in `ConfigPacks/` automatically merges onto `Classes.json` and `Perks.json`! If a pack uses the same `Id` as an existing class/perk, it updates it; otherwise it adds it cleanly.
