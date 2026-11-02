# Install - Serpentine's Custom Heads

**TL/DR:** Close the game, import `SerpentinesCustomHeads.pak` into BG3 Mod Manager (or copy it into the game's
`Mods` folder), activate "Serpentine's Custom Heads", then Save and Export the load order. No Script Extender, no
other mod, no particular load order. To remove it: give your characters other heads first, deactivate and export
second, delete the file last.

## What you need

1. **Baldur's Gate 3 on PC.** Tested on Baldur's Gate 3 version 4.1.1.7631656.
2. **BG3 Mod Manager (BG3MM)** - the way the author installs and tested the mod.
3. Nothing else. The file contains no scripts and lists no required mod.

## The file

| File | Contents |
|---|---|
| `SerpentinesCustomHeads.pak` | All 15 heads (Altariel 1, Altariel 2, Ayrin, Debbie, Deborah, Dolores 1, Dolores 2, Ellen, Juliette, Margot, Ripley, Samantha, Undomiel 1, Undomiel 2, Wendy) and their thumbnails |

## Install with BG3 Mod Manager

1. **Close the game and close BG3 Mod Manager.**
2. Unzip the download.
3. Either:
   - open BG3MM and use its import command on `SerpentinesCustomHeads.pak`; or
   - open File Explorer, paste `%LocalAppData%\Larian Studios\Baldur's Gate 3\Mods` into the address bar, press
     Enter, and copy `SerpentinesCustomHeads.pak` into that folder. Then open BG3MM and refresh the list.
4. "Serpentine's Custom Heads" appears in the **inactive** list. Move it to the **active** list. No position is
   needed: the mod depends on nothing.
5. **Save** and **Export** the load order to the game.
6. Start the game.

Do not edit `modsettings.lsx` by hand while you use a mod manager: the manager writes that file itself and
overwrites your change.

## Check that it worked

1. New Game, character creation. Choose a **female Human, Elf, Drow, Half-Elf or Half-Drow** with the **standard body**.
2. Open the Head list. You should find 15 new entries, each with its own thumbnail: Altariel 1, Altariel 2,
   Ayrin, Debbie, Deborah, Dolores 1, Dolores 2, Ellen, Juliette, Margot, Ripley, Samantha, Undomiel 1,
   Undomiel 2, Wendy.
3. Elf and Drow show the heads with elf ears, Half-Elf and Half-Drow with half-elf ears, Human with human ears.
   (Half-Drow is a kind of Half-Elf in the game and uses the Half-Elf heads; it has no entries of its own.)

If the heads are missing: check that the mod is in the ACTIVE list and that you exported the load order, and
check the character's race, sex and body. The heads are not offered to male characters, to the strong body, or to
other races.

## Updating (also from an earlier copy of this mod)

1. Close the game **and BG3 Mod Manager**.
2. Replace `SerpentinesCustomHeads.pak` in the `Mods` folder with the new file of the same name.
3. Open BG3MM and press **Refresh**. Check that the active list shows the mod under its current name,
   "Serpentine's Custom Heads".
4. **Save** and **Export** the load order. This also rewrites the mod's name stored in the load order, so no old
   name is left behind. Do not edit `modsettings.lsx` by hand.

Version 1.1.0 is the same mod as 1.0.0 with one head added (Wendy), so it replaces the 1.0.0 file: keep only one
`SerpentinesCustomHeads.pak` in the `Mods` folder. The 14 heads of 1.0.0 are unchanged.

## Removing the mod

1. **Give every character that uses one of these heads another head, and save.**
2. Close the game.
3. In BG3MM move "Serpentine's Custom Heads" to the **inactive** list, then **Save** and **Export** the load
   order.
4. **Close BG3 Mod Manager**, and only then delete `SerpentinesCustomHeads.pak` from the `Mods` folder.

Keep this order. If the load order still lists a mod whose file is gone, the game can drop your whole mod list.

## Checksum

| File | Bytes | SHA-256 |
|---|---:|---|
| `SerpentinesCustomHeads.pak` (1.1.0) | 31,898,405 | `C4CE4E0692477581455E8A7309B48368CC6D4F60740D49D095934147D1D54C33` |
