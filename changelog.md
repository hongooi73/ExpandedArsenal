## v2.0.1

This version includes the remaining legacy content from Vanilla Plus, to allow for a smooth upgrade from VP to EA:

- LAMs, Jihad-era and easter egg mechs
- Portrait files for the ronin pilots

These mechs and pilots won't appear in missions or for hire, but you'll be able to load a saved game that contains them.

Elite Forces and Elite Arsenal can now be enabled and disabled freely in the middle of a game. (Previously, once these mods were enabled you couldn't disable them again without breaking your save.)

### New mechs

- King Crab KGB-000B, the SLDF version of the vanilla King Crab

### Other changes

- Fix stability values for several mechs
- Fix overweight Imp chassisdefs, remove 10 heatsinks from mechdefs
- Fix Yeoman weight and heatsink values (1 heatsink removed)
- Fix an issue with the vanilla game where you could sometimes get a lance of turrets as allies
- Fix internal structure values for several vehicles
- Fix Hellhound 2 to move at 7/11
- Fix number of jumpjets for Hellhound


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
- Niomede
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


### New mechs

- King Crab KGC-001, a 3052 ComStar clanbuster variant
- Mauler MAL-1R, the standard 3048 version that replaced the Daboku
- Cataphract CTF-3L, a 3050 Liao variant based on Davion plans
- Shadow Hawk SHD-5M, a 3048 Marik overhaul and upgrade
- Wolverine WVR-7K, a 3050 Kurita lostech upgrade
- Griffin GRF-3M, a 3049 Marik upgrade, also used by Davion


### Other changes

- Prices have been revised to be more consistent with each other, and also with vanilla items. In particular, Clan weapons should now always be more expensive than their IS counterparts.
- Make Gauss ammo and IS double heatsinks available as loot
- Some item names have been modified for consistency, and to follow the vanilla convention of using +/++/+++ for upgrades
- Targeting Computer Mk I now ignores 2 evasion pips with ballistic and energy weapons, rather than giving +2 accuracy
  - Ignoring evasion should be much more powerful than accuracy, and appropriate for an item weighing 3 tons (more than a +++TTS)
- Targeting Computer Mk II renamed to Targeting Computer +; ignores 2 evasion pips; reduced to 2 tons
- IS Artemis IV ignores 2 evasion pips with missile weapons, rather than giving an accuracy bonus
- Clan Artemis IV ignores 2 evasion pips, and also grants +50% crit chance
- Revert stats for melee mods back to vanilla
- The unremovable CT items representing engine DHS have been removed; they have been replaced with a straight +30 heatsinking capacity on the chassis, which is how the vanilla game works
- Remove items representing internal endosteel and ferro-fibrous space. These were only used by 3 mechs, and it wasn't worth it to extend this approach to the entire mod.
- Reduce damage for heavy Gauss rifle to 140 damage + 25 structural damage, and 160 + 25 for the + variant; the existing 205 damage was just a little bit too extreme
  - The good news is that you can get back to the original with the ++heavy Gauss rifle in the Elite Arsenal mod! You'll just have to kill the current user first....


### Bug fixes

- Fix heatsinks and jumpjets for Hauptmann
- Fix movedef for Archer 2R
- Fix movedef for Incubus
- Fix movedef for Kodiak
- Fix heat generation for MASC (IS and Clan)
- Fix stats for vibrosword and Valiant hatchet
- Fix jumpjets for Arctic Cheetah
- Fix maximum armour for Turkina
- Fix engine heatsinks for Lament (should be DHS)
- Fix AC/5 ammunition for Kanga
- Fix LB20-X ammunition for Oro
- Adjust mech and chassis prices for Medusa


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

