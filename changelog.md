## v2.0

This is a **major refactoring** that includes the following changes:

- Add vehicles and turrets from Vanilla Plus. With this change, EA now includes 99% of the contents of VP (the Xenorauder and catgirls are unlikely to make it back, sorry).

- Reuse gear and weapon definitions from Haakon's Tons of Guns:
  - Items are now available for sale only in specific star systems; see below for the list
  - Some item IDs have changed (eg clan lasers, LRMs and SRMs)
  - Legacy weapons have been moved into the `weapon_legacy` directory; they are still present in-game to allow loading existing saves, but are not used on mechs and should not appear in stores

There are a few reasons for using Haakon's mods: to help integrate EA into the broader mod ecosystem; to make shopping more interesting than simply having everything available everywhere; and to make more toys available. (I recommend the variable speed pulse lasers.)

The full list of planets with the new gear is as follows. Not every item is available on every planet, if you can't find the item you're after, try a different one.

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

- Some item names have been modified for consistency, and to follow the vanilla convention of using +/++/+++ for upgrades
- Targeting Computer Mk I now ignores 2 evasion pips with ballistic and energy weapons, rather than giving +2 accuracy
  - Ignoring evasion should be much more powerful than accuracy, and appropriate for an item weighing 3 tons (more than a +++TTS)
- Targeting Computer Mk II renamed to Targeting Computer +; ignores 2 evasion pips; reduced to 2 tons
- IS Artemis IV ignores 2 evasion pips with missile weapons, rather than giving an accuracy bonus
- Clan Artemis IV ignores 2 evasion pips, and also grants +50% crit chance
- The unremovable CT items representing engine DHS have been removed; they have been replaced with a straight +30 heatsinking capacity on the chassis, which is how the vanilla game works
- Remove items representing internal endosteel and ferro-fibrous space. These were only used by 3 mechs, and it wasn't worth it to extend this approach to the entire mod.
- Add some new mechs:
  - King Crab KGC-001, a 3052 ComStar variant designed to fight the Clans
  - Shadow Hawk SHD-5M, a 3048 Marik overhaul and upgrade
- Reduce damage for heavy Gauss rifle to 140 damage + 25 structural damage, and 160 + 25 for the + variant; the existing 205 damage was just a little bit too extreme
  - The good news is that you can get back to the original with the ++heavy Gauss rifle in the Elite Arsenal mod! You'll just have to kill its existing user first....

### Bug fixes
- Fix heatsinks and jumpjets for Hauptmann
- Fix movedef for Archer 2R
- Fix movedef for Incubus


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

