## Path of Exile 2 Early Access Filter

Most of this filter is directly copied from [Neversinks PoE 2 loot filter](https://github.com/NeverSinkDev/NeverSink-PoE2litefilter)<br />
Support him by going to his [Patreon](https://www.patreon.com/Neversink)

Additions that I have made to it:
- Hiding specific Armour and Shield bases not needed for the build. (Currently set to show all strength pieces and generic pieces, but it has all the bases listed, where each line are bases for a specific attribute and you just change Hide to Show or vice versa)
- Hides all weapons besides Rattling Sceptres, just change BaseType "Rattling Sceptre" to whatever basetype weapon you want or uncomment the class right above it and insert the class of weapon you want.
- Still shows all rares so that you can disenchant them into Regal Shards, but hides magic and common versions of items described above.
- Highlights specific bases of rings, amulets and belts that I found to have the best implicits. But still shows all rings, amulets and belts.
- Hides Scroll of Wisdom if the area level is above 9 (that's when you gain access to unlimited identification)
- Highlighting items with +minion explicits, which is not very useful since it doesn't work on unidentified items, but is left there as an example.
- Minimap icon for gold piles of 500 and above.
- Red border on items that can be salvaged, so they have sockets or quality.
- Any armour that was missed in the attribute based listing of basetypes has a bright yellow background.

Both the armour and weapon selection is at the bottom of the file, so scroll all the way down to edit the filter to fit your build.<br />
If you still need magic items to disenchant then just add this to the start of the basetype section:<br />
Show<br />
Rarity Magic

## HOW TO INSTALL

1) Download the filter
2) Paste the `WitchStr.filter` file into the following folder:
   - Windows: `%userprofile%\Documents\My Games\Path of Exile 2`
   - Linux: `steamapps/compatdata/2694490/pfx/drive_c/users/steamuser/My Documents/My Games/Path of Exile 2`<br />
  You can also find the folder from In-game by going Escape -> Options -> Game -> Filters and clicking the folder icon.
3) Select the filter In-game: Escape -> Options -> Game -> Filters -> Select the filter from the dropdown box.
