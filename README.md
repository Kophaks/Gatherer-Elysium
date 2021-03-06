# Gatherer-Elysium
A complete* and 100% accurate Gatherer file for Elysium vanilla WoW realms. For a version of Gatherer that fixes Night Dragons and Whipper Roots not appearing, check https://github.com/Grymskvll/Gatherer-FelwoodFix. Some nodes only spawn if the current online player count exceeds a value. At the time of this writing, that value is 2500. The low_population branch is available if your realm typically has less players online.

**WARNING**
**This file does NOT go in the Interface\Addons folder.**

### *This Gatherer database should include the following:
- All herbs
- All ore nodes
- All fishing nodes
- All Felwood corrupted plants
- All solid chests
- All Blood of Heroes


### Installation:
1. Delete (or backup) the following files if they are present:
```
WoW\WTF\Account\YOUR_ACCOUNT_NAME\SavedVariables\Gatherer.lua
WoW\WTF\Account\YOUR_ACCOUNT_NAME\SavedVariables\Gatherer.lua.bak
```

2. Place Gatherer.lua in the following directory:
```
WoW\WTF\Account\YOUR_ACCOUNT_NAME\SavedVariables\
```

3. Enter the game and configure Gatherer's filters. Because of the enormous amount of nodes, Gatherer might cause an interface error if you don't filter some node types.\

### To do:
- Fix nodes being visible in adjacent zones on the world map
- Include AV nodes