# Revive Client 1.1

- Brief feature descriptions now appear at the top of the settings popup beside the mod menu. Press Tab to focus the popup. The existing footer hover behavior is unchanged.
- Added **Illicit** with ESP, X-ray, Kill aura, No-fall, Auto-totem, Criticals, Speed, Flight, and Scaffold. These modules start disabled and have no single-player-only check.
- ESP offers Glow and Hitbox modes, a color selector, and independent checkboxes for players, hostile mobs, passive mobs, and other entities. Both modes show through walls.
- X-ray shows colored block volumes through terrain. Its searchable block picker saves independent selections, with adjustable color and scan range. Scanning uses loaded client chunks and bounded work per tick.
- Kill aura includes range, CPS, and independent player, hostile-mob, and passive-mob selections. Actual reach and damage remain subject to Minecraft's combat rules.
- Auto-totem swaps a carried totem directly into the offhand without leaving an item on the cursor. It is available on Minecraft 1.16.5 and newer supported builds; Minecraft 1.8.9 has no totem item or offhand slot.
- Criticals uses a short airborne movement sequence on older versions. On 26.3 it performs a normal hop and attacks during descent, keeping movement within that version's protocol.
- Speed offers selectable multipliers. Flight supports Hover, Directional, and Glide modes with configurable speed, and restores the prior movement state when disabled.
- Scaffold uses blocks from the hotbar and restores the selected slot after placement.

Builds: Minecraft 1.8.9, 1.16.5, 1.20.1, 1.20.4, 1.21, 1.21.1, and 26.3.

The portable Windows launcher remains version 1.0 and discovers the new client JARs through the build catalog.
