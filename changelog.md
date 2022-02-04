## v2.0

This is a **major refactoring** that includes the following changes:
- Reuse gear and weapon definitions from Haakon's mods:
  - Items are now available for sale only in specific star systems; see below for the list
  - Some item IDs have changed (eg clan lasers, LRMs and SRMs)
  - Legacy weapons have been moved into the `weapon_legacy` directory; they are still present ingame to allow loading existing saves, but are not used on mechs and should not appear in stores

The reason for using Haakon's mods is mostly that buying the enhanced gear in this mod was a little bit too easy, since they were available on every planet. The Haakon mods provide almost exactly the same items, but are only available for sale on specific planets. Reusing these mods was the easiest and fastest way of restricting availability; no need to write a completely new set of item collections. On the upside, they give you even more toys to play with! (I recommend the VSM Pulse Laser.)

In addition, some item names have been modified to follow the vanilla convention of using +/++/+++ for upgrades.

The full list of planets with the new gear is as follows (not every item is available on every planet, if you can't find the item you're after, try a different one):

- Addasar
- Ahlat
- Alloway
- Andarmax
- Antias
- Appian
- Aquagea
- Argos
- Artru
- Balawat
- Borden
- Brixtana
- Cassilda
- Cates Hold
- Cavalor
- Claybrooke
- Decatur
- Diefenbaker
- Dunianshire
- Egress
- Electra
- Fronc
- Gardnaus
- Gaucin
- Glentworth
- Guldra
- Hastur
- Herotitus
- Ishtar
- Itrom
- Jamestown
- Joppa
- Kimi
- Leyda
- Lyreton
- Mechdur
- Menke
- Merope
- Midale
- New Vandenburg
- Niamede
- Paf
- Payia
- Piriapolis
- Renown
- Repulse
- Robsart
- Segerica
- Shiba
- Spencer
- Tarragona
- Thurrock
- Tincalunas
- Ur Cruinne
- Victoria
- Villanueva


### Other changes

- Targeting Computer Mk I now ignores 2 evasion pips with ballistic and energy weapons, rather than giving +2 accuracy
  - Ignoring evasion should be much more powerful than accuracy, and appropriate for an item weighing 3 tons (more than a +++TTS)
- Targeting Computer Mk II renamed to Targeting Computer +, to match the vanilla convention of +/++/+++ variants representing upgrades; ignores 2 evasion pips; reduced to 2 tons
- IS Artemis IV ignores 2 evasion pips with missile weapons, rather than giving an accuracy bonus
- Clan Artemis IV ignores 2 evasion pips, and also grants +50% crit chance
- Fix heatsinks and jumpjets for Hauptmann

## Initial changes (v1.3)

- Fix overweight MAD-5A chassisdef, remove 10 heatsinks from mechdef
- Fix PPC capaci(ta)tor so that it works with snub PPCs
- Fix number of jumpjets for Uziel and Hellspawn chassisdefs (6, not 7)
- Fix alternate Sun Spider chassisdefs to have the same number of jumpjets as the prime config
- Fix movedef for Blood Asp to move at 4/6
- Fix max number of jumpjets for both Yeoman chassisdefs
- Fix internal structure for Titan II
- Fix movedef and jumpjets for Cougar
- Fix clan targeting computer Mk II mismatch between ID and filename
- Fix assetbundle name for Thugs
- Fix clan targeting computer and Artemis IDs
- Fix Mad Cat Mk II movedef
- Fix Highlander IIC loadout (carrying excess ammo)
- Reduce stability damage for HAG/20, HAG/30, HAG/40 and ASC to slightly less extreme values
- Increase damage per shot for RAC/2 and RAC/5 to 25 and 45 respectively
- Remove restrictions on loading in `mod.json`

