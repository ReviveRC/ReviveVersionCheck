# Revive Client 1.2

## Illicit → Singleplayer

Adds nine modules for private singleplayer worlds. Each feature starts disabled. Leaving the world, joining a remote server, or opening the world to LAN clears these toggles. Returning to singleplayer does not turn them back on. The original Illicit modules retain their existing behavior.

| Feature | Behavior and settings |
| --- | --- |
| Arrow impact changer | Choose primed TNT, fire, lava, an iron golem, lightning, or teleporting to the impact. Applies once per owned arrow. |
| God mode | Blocks damage and death, restores health, and maintains Resistance 256 (amplifier 255). Restores a previous resistance effect when disabled, accounting for elapsed time. |
| Noclip | Enters spectator mode with selectable flight speed. Disabling it restores the original game mode and flight speed. |
| Fast bow | Hold Use with a bow to fire automatically. Choose 2, 5, 10, or 20 arrows per second at the normal server tick rate. |
| Time slow | Choose 2×, 4×, or 10× slower world simulation. |
| Time stop | Freezes world simulation while the player can move. Restores the previous time settings when disabled. |
| Ice mage | Independent checkboxes for temporary ice beneath your feet and Slowness V arrows that surround targets with temporary ice spikes. Choose a 3, 5, 10, or 20 second lifetime. Ice uses packed ice to prevent meltwater and preserves blocks subsequently replaced by the player. |
| Vein Miner | Separate ore and log checkboxes, matching-tool requirement, diagonal connectivity, maximum block count, and search radius. Mines connected matching blocks through normal game rules, including drops and tool wear. |
| No hunger | Maintains full hunger and saturation. |

All features execute on the integrated server and authorize only its owning player. They work in worlds without cheats enabled. Temporary ice, spectator mode, time changes, and owned resistance are cleaned up when disabled or when the owner leaves. Brief descriptions appear above the settings controls; press Tab to focus the popup.

Minecraft 1.20.4 and newer use the native tick-rate manager. Earlier versions selectively pause world clocks, entities, block entities, scheduled ticks, weather, and spawning while retaining player updates. Fast bow rates and temporary-ice lifetimes follow the effective server/world simulation rate.

Release JARs are named `dist/revive-<minecraft>-1.2.jar`. The published 1.1 release is unchanged.

## Validation

Built all seven supported Minecraft versions. The gameplay scenario passed on 1.8.9, 1.16.5, 1.20.1, 1.20.4, and 26.3. The 1.21 and 1.21.1 builds compiled and passed archive integrity checks; their new gameplay scenario was not run. The online-entry guard was checked by simulating loss of integrated-server access, without connecting to a remote server.
