# FrozenCore AddOns 3.3.5a

A beginner-friendly addon bundle for World of Warcraft 3.3.5a.

## Included addons

- **DragonUI** and **DragonUI_Options**: action bars, unit frames, minimap, cooldown numbers, and other interface improvements. Use `/dui` to open its settings.
- **DBM** and its encounter modules: boss and dungeon warnings.
- **Skada**: damage, healing, and other combat statistics. Use `/skada` to open its settings.
- **NotPlater**: customizable, threat-aware nameplates. Use `/np` to open its settings.
- **UnBot** and **YssBossLoot**: bot controls and UnBot's required dependency.
- **DungeonClear**: controls for an autonomous bot tank. This requires the server-side `mod-dungeon-clear` module and a playerbot tank in your party.

YssBossLoot: [official WowAce release](https://www.wowace.com/projects/yssbossloot/files/455663).
NotPlater: [source](https://github.com/RichSteini/NotPlater); Skada: [source](https://github.com/bkader/Skada-WoTLK).
DragonUI: [official v2.5 release](https://github.com/NeticSoul/DragonUI/tree/v2.5); its license and third-party notices are included in the `DragonUI` folder.

## Install

Download the repository ZIP from GitHub, extract it, and copy the addon folders into:

```text
World of Warcraft 3.3.5a\Interface\AddOns
```

Each addon's `.toc` file should be directly inside its own folder. Restart the game and enable the addons on the character selection screen.

If upgrading from an older FrozenCore bundle, disable or remove your existing Dominos and OmniCC addons: the new bundle does not remove old folders, and DragonUI supplies action bars and action-button cooldown numbers. Other UI addons that manage the same elements may also need to be disabled.

When upgrading, disable or remove Details and its companion modules before using Skada. Disable or remove other nameplate addons such as Tidy Plates before using NotPlater. Copying this bundle does not remove older addon folders or their saved settings.
