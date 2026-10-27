HalfCraft Revamped 0.2.1
===========================

Half-Life 2, played with Minecraft. Real Minecraft runs hidden and does your physics, inventory,
blocks and combat; Half-Life 2 runs its world, NPCs and story around you. Build on its maps, fight
the Combine with a diamond sword, light City 17 with torches.

This is a modified version of HalfCraft by whisky (https://github.com/whiskydumb/halfcraft), which
grew out of SkyCraft by chasmlol (https://github.com/chasmlol/SkyCraft). All the hard part is
theirs; what this version changes is listed under WHAT'S DIFFERENT FROM THE ORIGINAL below.


YOU NEED

- Windows 10 or 11, 64-bit
- Steam, with Half-Life 2 and Half-Life 2: Deathmatch installed (Deathmatch's engine runs HalfCraft)
- a Microsoft account that owns Minecraft: Java Edition
- about 1 GB of free space for Minecraft and Java, which download on the first start


PLAY

1. Unpack the zip anywhere, e.g. C:\Games\HalfCraft. A path with only English letters is safest.
2. Start HalfCraft.exe.
3. The first time, Prism Launcher opens: sign in with your Microsoft account. Half-Life 2 starts
   once you're signed in. Minecraft downloads (a few minutes the first time) and joins by itself;
   a line at the top of the screen says how far along it is.
4. Start a new game, or load a save.

Arguments for Half-Life 2 go after HalfCraft.exe, e.g. a shortcut to
   HalfCraft.exe -windowed -w 1920 -h 1080


CONTROLS

Minecraft's layout by default (WASD, Shift sneaks, Ctrl sprints, mouse, E for the inventory,
Q drops, F swaps hands, 1-9, F5 for the camera, T for chat, ...), plus Half-Life's own:

  G          use: doors, buttons, chargers, ladders, picking up props
  mouse      while carrying a prop: left throws it, right drops it
  R          gravity gun out / away: right click pulls a block out of a wall, left throws it
  V          flashlight
  C          squad orders
  F4         creative mode on / off
  Esc        Half-Life's menu: save, load, options, quit
  F6 / F9    quick save / quick load

Every key can be changed in Half-Life's Options > Keyboard (Minecraft's actions are listed there
too); the mouse speed is Half-Life's Options > Mouse. Leave Minecraft's own controls at their
defaults.


SAVES

Half-Life's saves are in game\save. Minecraft's world is in
minecraft\Prism\instances\HalfCraft\.minecraft\saves\HalfCraft.
Loading a Half-Life save rolls Minecraft's blocks and your inventory back to that save too.


UPDATING

Unpack the new zip over this folder and overwrite. Your saves, your Minecraft account and the
downloaded Minecraft stay.


IF SOMETHING'S WRONG

- The line at the top of the screen says what Minecraft is doing. If it says Minecraft isn't
  running, quit and start HalfCraft.exe again.
- Logs: game\console.log (Half-Life), minecraft\Prism\instances\HalfCraft\.minecraft\logs\latest.log
  (Minecraft), minecraft\Prism\logs (Prism Launcher).


WHAT'S DIFFERENT FROM THE ORIGINAL

- Ultrawide and 4K screens don't crash (the original crashed on screens wider than 2048 pixels).
- Several times the frame rate: Minecraft's HUD reaches Half-Life much faster.
- Every chapter is open in New Game from the first start.
- Half-Life 2's controls drive Minecraft: every key is set in Half-Life's keyboard options, and its
  mouse sensitivity and reverse mouse apply.
- A creative mode switch: F4, or "Creative mode on / off" in the pause menu.
- Blocks sit flush on the floor instead of floating above it or sinking into it.
- Minecraft's mobs and Half-Life's NPCs fight each other: zombies and the rest go for the Combine,
  and the Combine shoot back. Mobs walk Half-Life's own AI routes to their targets and can't see
  or walk through Half-Life's walls.
- The warden goes for the Combine too: Half-Life's hostile NPCs close by anger it like a vibration.
- Undead burn in the sun only under Half-Life's open daytime sky, never at night or indoors.
- Burning mobs show Minecraft's fire.
- Half-Life's explosions and bullets break Minecraft's blocks.
- The gravity gun (R) tears blocks out of Minecraft builds and throws them.
- No Half-Life weapon shows up in Minecraft's hands.
- A new game clears the map's builds; loading a save rolls them back to that save.
- Ground-material triggers work (e.g. Sandtraps' antlions come when you touch the sand).
- Brighter torches and other Minecraft lights.
- hc_mc <command> in the console runs a Minecraft command (summon, give, time, ...).
- Crash fixes: Half-Life's zombies swatting gravity-gun blocks, and the strider battle in City 17
  (d3_c17_13).


HalfCraft is MIT-licensed (LICENSE.txt): HalfCraft by whisky, based on SkyCraft by chasmlol. What
it bundles is listed in THIRD-PARTY-NOTICES.md. It isn't affiliated with or endorsed by Valve, Mojang or Microsoft.
