########################################
40k Imperial Guard Mini Addon by Buscher
########################################

Version 0.291 for 40k version 029

#######
Purpose
#######

Fixing some of my nitpicks and adding some other things.
The rebalance only handles little things to not change too much from the original
If you don't like a change just delete the rul file (details listed later in the README)

#######
License
#######

MIT for all my stuff.
That means do as you like.
But if the work is going to be credited, that would be appreciated.

Other people's stuff are of course not part of my licensing.


############################################
THIRD PARTY Intellectual Property Disclaimer
############################################

Any parts marked as third party inside IGMA_extra_sprites and IGMA_extra_sounds rul files are neither my property nor licensed by me.
Of course anything, that derivative work is based on, is not my property.
I don't challenge their Copyright and/or Trademark. They belong to their respective owners.
This mod is a non-profit hobby only. I do not have any kind of commercial interest (selling, advertisement, donations, etc.).


#######
Changes
#######

- Added Vindicare Assassin (IGMA_armors_imperial_assassin.rul, IGMA_manufacture_imperial_assassin, IGMA_units_imperial_assassin.rul, IGMA_weapons_exitus.rul)
  - Uses an Exitus Rifle
  - Can use different ammo (Standard, Turbo Penetrator with ignore armor values, Shell Breaker piercing shields, Hellfire with low ranged HE)
  - Ammo uses 50-150% damage range as an experiement, may change in the future
- Added Priest (IGMA_armors_priest.rul, IGMA_manufacture_priest.rul, IGMA_units_priest.rul, IGMA_weapons_eviscerator.rul)
  - Can buff the melee of IG units. The buff will dissipate over the turns. (IGMA_items_priest.rul, IGMA_scripts_buff.rul)
- Added Elysian Jump Armor with flight capability (IGMA_armors_elysian.rul, IGMA_manufacture_elysian.rul)
- Added a laser designator for air strikes (IGMA_manufacture_airstrike.rul, IGMA_research_airstrike.rul, IGMA_weapons_airstrike.rul)
 - added ivandogovich's improved hand object for laser designator
- Added Multilaser Sentinel (IGMA_armors_multilaser_sentinel.rul)
  - Basic sentinel (open cockpit) with multilaser taken from the Chimera
  - Fires 5 rounds instead of 10 (only one barrel)
  - Can fire 2 salvos per turn
  - Currently uses the graphics of the Lascannon version. 
  - New kitbashed graphic (bigobs) for the multilaser weapon
  - Delayed Lascannon Sentinel in favor of Multilaser Sentinel (IGMA_research.rul)
- Added Veteran officers as well as Scion officers (IGMA_units_veteran_officers.rul and IGMA_armors_veteran_carapace.rul)
  - Can be transformed from officers who qualify for veteran status or from any veteran
  - Starts with Adv. Carapace by default
  - Added graphics from Advanced Carapace for Others and kitbashed them. The mix with golden and white shoulder insignias was my choice.
  - Uses graphics from Advanced Carapace for Others
- Added the ability for officers to buff firing accuracy (IGMA_items_officers.rul, IGMA_scripts_buff.rul)
- Added chainsword variant of the officer sword (in cooperation with Leflair and Tal'Raziid) (IGMA_weapons_officer_sword.rul)
- Added medics for Veterans and Scions (IGMA_armors_veteran_carapace.rul)
  - Uses graphics Advanced Carapace for Others
- Added Hellpistol variant for Adv. Carapace and Scion Backpacks (IGMA_weapons_hellpistol.rul and IGMA_armors_veteran_carapace.rul)
  - requires no ammo
  - requires an item to be manufactured similar to the Volleygun
  - can't be dropped
  - made a kitbashed graphic (bigobs) and used green laspistol for handobs
  - Added a purple version for Scions
  - Turned the original Hellpistol into Master Crafted Laspistol
- Fixed inconsistent (training) statcaps for Veterans, Scions plus their Officers.  (IGMA_units_veteran.rul and IGMA_units_veteran_officers.rul)
  - There is no difference between Veterans and Scions anymore. 
- Added light/handheld version for the heavy stubber and rebalanced the heavy stubber (IGMA_weapons_heavy_stubber.rul)
  - Heavy stubber (normal) has the same autofire range than the IG Heavy Bolter
  - Heavy stubber (handheld) is the same one as the Arbites with slightly increased autofire range
  - There is a manufacture project to turn normal version into handheld and vice versa
  - New kitbashed graphics (bigobs, handobs and floorobs) 
- Added Hotshot to Mastercrafted Lasgun (IGMA_weapons_mc_lasgun_hotshot.rul)
- Added Mastercrafted shells to Mastercrafted shotgun (IGMA_weapons_mc_shotgun.rul)
  - MC shells were only available for the Lawbringer
  - MC shells can be manufactured by any faction now
- Made IG armors consistent (IGMA_armors_rebalance.rul)
  - Armors have the same stats modifiers, no matter if normal, medic or advanced
  - Advanced is the only exception, getting only positive modifiers
  - Carapace now have weight instead of lower strength. The bonus strength is compensated by weight
  - Lowered difference between Flak and Carapace by giving Flak only a bonus of 5 TU but Carapace a malus of 5 TU
  - Increased stamina for Flak and lowered stamina for Carapace to compensate (Alternative Movement Methods) 
  - Commissar carapace got visibilityAtDark increased to the same value as the other carapace, assuming some headgear
- Sentinel Lascannon got a buff but still isn't as good as the other ones (IGMA_weapons_others.rul)
- Sentinel Missile got an additional inventory slot to store missiles (IGMA_armors_missile_sentinel.rul)
- Fixed some pet peeves of mine (IGMA_weapons_others.rul and IGMA_manufacture_other.rul)
  - Manufacturing process related to officer requisition gives a guard laspistol and not the blue one anymore
  - Autoguns have trainingmode 4 (100% firing) now. I get the idea why they have 50% but I don't like the implementation.
  - Changed some melee sounds to be more meaty and gave flamethrower arcing shot
- Added Vulture as fighter-bomber craft before Marauder (IGMA_crafts_vulture.rul, IGMA_research_vulture.rul)
- Added HWP slot to Grav Drop Valkyrie (IGMA_crafts_valk_grav_drop.rul)
- Added 4 soldiers slots to the Tauros (IGMA_crafts_tauros.rul) [4 additional slots might be too much but IG is all about numbers]
- Modified Tauros weapons (IGMA_weapons_tauros.rul)
  - Grenade launcher can fire 5 different types of grenades (Frag, Krak, incendiary, Smoke, Photon)
  - Lascannon got aimed firing mode
- Added Kraken Penetrator and Metal Storm ammo for Light Bolters (IGMA_weapons_light_bolters.rul)
- Added an Ultra Pattern version for the Light Bolter and Light Boltpistol (IGMA_weapons_light_bolters.rul)
- Added a trade for exotic items (special ammo and weapons). They can only be bought at a trade outpost. (IGMA_weapons_light_bolters.rul and IGMA_items_trade.rul)
- Added new exotic items to maps (IGMA_terrains_weapons.rul)
- Added smoke and photon grenade drums to grenade launcher (IGMA_weapons_grenade_launcher.rul)
- Added shields to Psykers (IGMA_armors_psykers.rul)
- Added outpost with transmission decoder
  - Can be build on a normal outpost (IG)
  - Depending on your game setting you may need the temporary storage
  - The temporary storage is meant to be temporary. If you try to pay upkeep for it, it will ruin your balance. So do the upgrade in the beginning of the month.
- Improved the firing accuracy of NPC guardsmen (IGMA_units_civ.rul)
- Added ufopaedia articles (IGMA_armors_ufopaedia.rul and IGMA_units_ufopaedia.rul)
- Allowed the Drop Transport and Taurus to be used in the Tanith missions (IGMA_missions.rul)
- "Rebalanced" lasguns. Essentially I made sure that they can autofire 3 times independent of rounding basede on the TUs of the soldier (IGMA_weapons_rebalance.rul)
- Depending on ammo type weapons will change the color for the magazine (IGMA_scripts_change_color_ammo.rul, IGMA_weapons_mc_lasgun_hotshot.rul, IGMA_weapons_light_bolters.rul, IGMA_weapons_hellpistol.rul, IGMA_weapons_heavy_stubber.rul, IGMA_weapons_exitus.rul)
- A few fixes here and there (IGMA_other.rul + other files)

#############
Want to help?
#############

- I can't draw sprites well yet, so that would be a great help. I have started kitbashing so let's see how that goes.
- Also translating the extra strings into different languages would be great
  - currently 40k only got russian next to en-US
  - I am lacking translations into Russian
- Of course the ufopaedia articles could be written a bit nicer
- Feedback and ideas are welcome of course

###############
Troubleshooting
###############

Please let me know if you run into any issues. Currently I am available in the OpenXcom 40k discord 
(https://discord.gg/w8kPJ27R)
There is also a post on the forums https://openxcom.org/forum/index.php/topic,8936.msg134976.html

Of course I am also interested in any feedback. Thanks!

#######
CREDITS
#######

- xanroth and Tal'Raziid for letting me use the sprites of the mod "Advanced Carapace for Others"
- Meridian, Yankes, ohartenstein23 et al. who answered my modding questions with great detail
- Leflair and and Xom126 who give me advice on spriting
- Ticker175 for proofreading and making ufopaedia entries more lore-consistent
- Dioxine and the contributors to XPiratez whose assets may also be used.
- ivandogovich for the improved hand objects (motion scanner -> laser designator)


And the great people who made
- OpenXcom
- OpenXcom Extended
- 40k mod for OpenXcom

Thanks to all of them!
