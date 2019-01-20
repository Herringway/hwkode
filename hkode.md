# Herringway's Kode of Battle

## Introduction

Welcome to Herringway Arena! Test your skills against famous bosses of all types in this collaborative RPG system.

Each battle consists of one or more enemies, a ref to keep things moving (mostly) and plenty of player-controlled combatants. The goal is to defeat the enemies by cooperating with your teammates, usually by reducing the HP of the enemies to zero before they do the same to you.

## Terms

* A-Skill: Active Skill. These are skills that you purchase with XP and can use whenever your turn comes up.
* Arena Barrier: Similar to the ref barrier, this barrier protects the audience from everything going on in the arena. The reverse is also true - those inside the arena are safe from those who are outside.
* Caster: Refers to whoever is using an ability, regardless of whether or not it is magical or physical.
* HP: Health Points. Run out of these and you're dead! Hope someone else is merciful...
* P-Skill: Passive Skill. These are skills that you purchase with XP and provide various effects, like increased magic strength or HP absorbing.
* RCP: Referee Control Panel. This wonderful device is responsible for all the arena functions, from protecting the audience and ref to simple stat displays. Occasionally crashes or glitches. Usually operated by the ref, but not always...
* Ref: Short for referee. The person refereeing is responsible for keeping the battle moving, resolving conflicts and generally making sure things stay fun, even if that means ending the battle. Ingame, the ref is responsible for operating the RCP and is an active part of battles. Normally, the ref is present but protected by a ref barrier, preventing any negative effects from affecting them. But when the barrier goes down... beware.
* Ref Barrier: This barrier is projected by the RCP on the ref and RCP itself during normal operation. Whoever is protected enjoys immunity to everything thrown about the arena.
* SP: Skill/Spell points. You can spend these in battle to use your abilities.
* Unit: A specific combatant in the battle.

## Battle Objectives

The ultimate goal of a battle is to defeat your opponents.

* Standard Rules: Reduce your opponents to 0HP before they do it to you.
* Survival Battle: In these battles, you fight for your survival in harsh arena conditions. Hazard set is permanently set to evil and the RCP is likely in need of a reboot.
* Coin Battle: Gain money when dealing damage. Participants cannot die in this battle type.
* Horde Battle: No boss, just lots of enemies. Defeat as many as you can!
* Player Vs Player: Your opponents are other players!
* Party: Anything can happen, but it's probably good!
* JOKAR: ha ha ha

## Turn System

Each battle is divided into (hopefully several) rounds. At the start of each round, players choose an action to take. Once everyone has decided what they will do, the actions will execute, with the fastest combatants going first and the slowest going last. Some status effects change the number of turns a player will get in a round. Enemies may be able to take multiple turns as well.

## Elements

|Element   | Symbol | Special                                              |
|----------|--------|------------------------------------------------------|
|Water     |💧       |Douses flames                                         |
|Fire      |🔥       |Thaws ice                                             |
|Lightning |⚡       |Double damage on wet targets, backfire on wet casters |
|Wind      |🌪️       |                                                     |
|Earth     |⛰️       |                                                     |
|Poison    |☣️       |                                                     |
|Holy      |✝️       |                                                     |
|Dark      |😈       |                                                      |
|Ice       |⛸️       |Wet targets may be frozen                            |
|Heart     |💖       |                                                      |
|Imaginary |💭       |Always hits weakness, but 25% chance to fail          |
|Gravity   |🌑       |Damage dealt is usually a percentage of current HP    |

## Status Effects

### Positive

* Protect: Unit's defense increased by 50.
* Shell: Unit's magic defense increased by 50.
* Haste: Doubles unit's speed.
* Bubble: Unit's HP is doubled.
* Aura: Unit will not take damage if it less than the number indicated.
* Auto-Life: Raise will automatically be cast on this unit when it dies.
* Metal: All damage done to this unit is reduced to 1.
* Quick: Unit has twice as many turns this round, and may use these new turns immediately after gaining the status.
* Attack+: Unit's attack stats increase by 50%.
* Defense+: Unit's defense stats increase by 50%.
* Regen: Unit recovers 1/8th of their max HP each round.
* Elemental Infusion: Unit deals 50% more damage with a particular element and gains 25 resist against that element.
* Reflect: Most spells targeted at unit will bounce off and hit the caster.
* Last Stand: Unit will survive the next fatal blow with 1HP.

### Negative

* Blindness: Halves accuracy of unit.
* Silence: Unit cannot use magic or sound-based a-skills.
* Paralysis: Unit cannot use physical a-skills.
* Slow: Halves speed of unit.
* Poison: Unit loses 1/8th of their max HP each round.
* Sleep: Unit cannot take turns. Healed by physical attacks.
* Confusion: Unit's a-skills have a 25% of their target changing. 25% chance of failure. Healed by physical attacks.
* Stop: Unit cannot take turns.
* Frozen: Unit cannot take turns. Thawed by fire.
* Old: Unit's stats drop until healed.
* Doom: Unit is KOed once timer expires.
* Lock: Unit may only use default a-skills.
* Embargo: Unit may not use items.
* Sap: Unit loses 1/32nd HP each round. Expires after 10 rounds.
* Curse: Any damage dealt by unit is also dealt to it.
* Petrified: Unit is unable to act and is considered dead.
* Attack-: Unit's attack stats decrease by 25%.
* Defense-: Unit's defense stats decrease by 25%.

### Neutral

* Berserk: Unit loses control, but gains +50% attack. Cannot be confused.
* Mini: Unit's attack drops to 1, but evasion doubles.
* Float: Unit avoids earth attacks, but cannot jump or pick up items.
* Reverse: Unit is healed by damage and damaged by healing.
* Mushroom: Unit cannot act, but regenerates HP every round.
* Missing in action: Unit cannot act, but also cannot be harmed.
* Undead: Unit is healed by most instant death effects, but harmed by healing.

### ???

* Imp: Unit can't use items or most a-skills, but...?
* Glitched: Things will happen.

## Miscellaneous Rules

* Multitargetting: Some a-skills can optionally target multiple units. When this occurs, damage is divided by half of the number of units. This does not apply to skills that are always multitargetted.

## Base Stats

With no skills or other modifiers, everyone has *100 HP*, *100 SP*, *50 ATK*, *50 DEF*, *50 MATK*, *50 MDEF* and *10 SPD*. The main way to increase stats is to invest AXP in relevant [A-Skills]. Final stats are determined by a set of formulae:

ATK, DEF, MATK and MDEF: ```StatBonus = sqrt(3 * XPSpentInRelevantSkills)```

HP: ```StatBonus = sqrt(3 * (XPSpentInHPSkills + 0.5 * XPSpentInDEFSkills + 0.1 * XPSpentInMDEFSkills))```

SP: ```StatBonus = sqrt(3 * (XPSpentInSPSkills + 0.1 * XPSpentInATKSkills + 0.5 * XPSpentInMATKSkills))```

Speed: ```StatBonus = sqrt(XPSPentInRelevantSkills)```

All stats are rounded up to the next nearest integer.

## Skills

This system has two main types of skills. A-Skills are Active Skills, skills you can use when your turn comes up in battle. P-Skills are Passive Skills, which are always active. Players can choose any combination of skills as long as they do not exceed the point limits. Players currently have 2000AXP and 1000PXP to spend on A-Skills and P-Skills respectively. Players cannot earn additional XP, but the limit will rise over time for everyone as the system progresses.

### A-Skills

Many A-Skills have multiple levels, often adding more power and/or effects. Selecting skills will increase a relevant statistic.

#### Default A-Skills

Everyone has access to these a-skills no matter what they choose.

* Fight - Deals physical damage with a 1.0x multiplier.
* Defend - Halves damage taken for this turn.
* Mix - Combines two items into one. Result can be used immediately and can also be negative.

#### Physical A-Skills

| Name            | AXP    | Description                                                                                                   | Prerequisites | Boosted Stats|
|-----------------|--------|---------------------------------------------------------------------------------------------------------------|---------------|--------------|
| Cutting Edge    | 100AXP | Deals 3.0x water damage.                                                                                      |               | ATK, DEF     |
| Plume Edge      | 100AXP | Deals 5.0x water damage.                                                                                      | Cutting Edge  | ATK, DEF     |
| Ragnarok        | 100AXP | Deals 3.0x earth damage.                                                                                      |               | ATK, DEF     |
| Odyssey         | 100AXP | Deals 5.0x earth damage.                                                                                      | Ragnarok      | ATK, DEF     |
| Planet Diver    | 100AXP | Deals 3.0x fire damage. 5.0x if jumping.                                                                      |               | ATK, DEF     |
| Planetary       | 100AXP | Deals 5.0x fire damage. 8.0x if jumping.                                                                      | Planet Diver  | ATK, DEF     |
| Astral Blast    | 100AXP | Deals 3.0x wind damage.                                                                                       |               | ATK, DEF     |
| Thunder Mine    | 100AXP | Deals 5.0x wind damage.                                                                                       | Astral Blast  | ATK, DEF     |
| Elec Sword      | 100AXP | Deals 3.0x lightning damage.                                                                                  |               | ATK, DEF     |
| Elec Blade      | 100AXP | Deals 5.0x lightning damage.                                                                                  | Elec Sword    | ATK, DEF     |
| Jump            | 100AXP | Allows caster to jump into the skies for one turn, out of range of many attacks.                              |               | ATK, DEF     |
| Dive            | 100AXP | Deals 9.0x non-elemental damage. Only usable while caster is jumping.                                         | Jump          | ATK, DEF     |
| Drain Jump      | 100AXP | Deals 4.0x non-elemental damage and heals the caster for the same amount. Only usable while caster is jumping.| Jump          | ATK, DEF     |
| Ultra Jump      | 100AXP | Deals 4.0x non-elemental damage and jump back into the sky. Only usable while caster is jumping.              | Jump          | ATK, DEF     |
| Metal Cut       | 300AXP | Deals 2.0x non-elemental damage. Cuts through metallic defenses.                                              |               | ATK, DEF     |
| Magnum Break    | 200AXP | Deals 3.0x fire damage to all enemies.                                                                        |               | ATK, DEF     |
| Chomp           | 250AXP | Pull out a random item and throw it.                                                                          |               | ATK, DEF     |
| Throw           | 400AXP | Throw a held item.                                                                                            |               | ATK, SPD     |
| Sledge          | 100AXP | Deals 4.0x non-elemental damage, 35% chance of inflicting mini status.                                        |               | ATK, DEF     |
| Life Sword      | 300AXP | Deals 4.0x fire/water/lightning/earth damage to up to 2 units.                                                |               | ATK, DEF     |
| Muramasa        | 150AXP | Deals damage equal to caster max hp - current hp.                                                             |               | HP, ATK      |
| Goblin Punch    | 100AXP | Deals 8.0x non-elemental damage if caster and target's hp digits add up to the same number.                   |               | HP, ATK      |
| Magic Hammer    | 150AXP | Deals 1.0x non-elemental damage to target's MP.                                                               |               | ATK, DEF     |
| Ice Shard       | 150AXP | Deals 3.0x ice damage. Hits before other moves.                                                               |               | ATK, DEF     |
| Dizzy Punch     | 200AXP | Deals 3.0x non-elemental damage. 50% chance of afflicting target with confusion.                              |               | ATK, DEF     |
| Focus Punch     | 200AXP | Deals 12.0x non-elemental damage, but requires a turn to charge up and fails if the caster is hit.            |               | ATK, DEF     |
| Sky Uppercut    | 150AXP | Deals 4.0x non-elemental damage and can hit targets that are normally unreachable.                            |               | ATK, DEF     |
| Shadow Claw     | 200AXP | Deals 4.0x dark damage. Increased chance of critical hit.                                                     |               | ATK, DEF     |
| Steal           | 150AXP | Steals an item from the target.                                                                               |               | ATK, SPD     |
| Steal Dexterity | 150AXP | Inflicts slow on target and grants user haste.                                                                | Steal         | ATK, SPD     |
| Steal Power     | 150AXP | Inflicts Attack- on target and grants user Attack+.                                                           | Steal         | ATK, SPD     |
| Steal Defense   | 150AXP | Inflicts Defense- on target and grants user Defense+.                                                         | Steal         | ATK, SPD     |
| Steal Health    | 150AXP | Inflicts Poison on target and grants user Regen.                                                              | Steal         | ATK, SPD     |
| Steal Soul      | 300AXP | Inflicts Doom on target and grants user Auto-Life.                                                            | Steal         | ATK, SPD     |

#### Magical A-Skills

| Name            | AXP    | Description                                                                                                   | Prerequisites | Boosted Stats|
|-----------------|--------|---------------------------------------------------------------------------------------------------------------|---------------|--------------|
| Fira            | 100AXP | Deals 3.0x fire damage. Can be multitargetted.                                                                |               | MAG, MDEF    |
| Firaja          | 100AXP | Deals 5.0x fire damage.                                                                                       | Fira          | MAG, MDEF    |
| Blizzara        | 100AXP | Deals 3.0x ice damage. Can be multitargetted.                                                                 |               | MAG, MDEF    |
| Blizzaja        | 100AXP | Deals 5.0x ice damage.                                                                                        | Blizzara      | MAG, MDEF    |
| Thundara        | 100AXP | Deals 3.0x lightning damage. Can be multitargetted.                                                           |               | MAG, MDEF    |
| Thundaja        | 100AXP | Deals 5.0x lightning damage.                                                                                  | Thundara      | MAG, MDEF    |
| Aera            | 100AXP | Deals 3.0x wind damage. Can be multitargetted.                                                                |               | MAG, MDEF    |
| Aeroja          | 100AXP | Deals 5.0x wind damage.                                                                                       | Aera          | MAG, MDEF    |
| Bio             | 100AXP | Deals 3.0x poison damage. Can be multitargetted.                                                              |               | MAG, MDEF    |
| Bioga           | 100AXP | Deals 5.0x poison damage.                                                                                     | Bio           | MAG, MDEF    |
| Zammle          | 100AXP | Deals 3.0x dark damage. Can be multitargetted.                                                                |               | MAG, MDEF    |
| Kazammle        | 100AXP | Deals 5.0x dark damage.                                                                                       | Zammle        | MAG, MDEF    |
| Gravity         | 100AXP | Deals 25% HP worth of gravity damage.                                                                         |               | MAG, MDEF    |
| Graviga         | 100AXP | Deals 50% HP worth of gravity damage.                                                                         | Gravity       | MAG, MDEF    |
| Quake           | 300AXP | Deals 6.0x earth damage. Targets everyone.                                                                    |               | MAG, MDEF    |
| Osmose          | 50AXP  | Drains SP from an enemy. 1.0x multiplier.                                                                     |               | MAG, MDEF, SP|
| Osmosega        | 100AXP | 2.0x multiplier.                                                                                              | Osmose        | MAG, MDEF, SP|
| Hyper Beam      | 300AXP | Deals 12.0x non-elemental damage. Caster cannot act next turn.                                                |               | MAG, MDEF    |
| Flare           | 300AXP | Deals 6.0x non-elemental damage. Pierces defense.                                                             |               | MAG, MDEF    |
| Ultima          | 300AXP | Deals 5.0x non-elemental damage to all enemies.                                                               |               | MAG, MDEF    |
| Psyshock        | 100AXP | Deals 4.0x non-elemental physical damage.                                                                     |               | MAG, MDEF    |
| Aqua Breath     | 200AXP | Deals 4.0x water/wind damage to all enemies.                                                                  |               | MAG, MDEF    |
| Breath Wing     | 200AXP | Deals 25% HP wind-elemental damage to all enemies.                                                            |               | MAG, MDEF    |

#### Support A-Skills

| Name            | AXP    | Description                                                                                                   | Prerequisites | Boosted Stats|
|-----------------|--------|---------------------------------------------------------------------------------------------------------------|---------------|--------------|
| Cura            | 300AXP | Heals 2.0x damage. Can be multitargetted.                                                                     |               | MAG, MDEF, HP|
| Curaja          | 300AXP | Heals 4.0x damage.                                                                                            | Cura          | MAG, MDEF, HP|
| Protect         | 100AXP | Increases physical defense by 50.                                                                             |               | DEF, MDEF, HP|
| Shell           | 100AXP | Increases magic defense by 50.                                                                                |               | DEF, MDEF, HP|
| White Wind      | 300AXP | Restores an amount of HP equal to caster's MP to all allies.                                                  |               | DEF, MDEF, HP|
| PSI Healing α   | 100AXP | Heals some negative status effects.                                                                           |               | DEF, MDEF, HP|
| PSI Healing Ω   | 100AXP | Heals all negative status effects, including death.                                                           | PSI Healing α | DEF, MDEF, HP|
| Slots           | 300AXP | Spin the slots for something good!                                                                            |               | HP, SP       |
| Dragon Dance    | 400AXP | Grant Haste, Attack+ and Defense+ to user.                                                                    |               | HP, SPD      |
| Find Item       | 300AXP | Look around for an item. This doesn't use a turn and can only be used once per round.                         |               | HP, SPD      |

### P-Skills

P-skills are your passive abilities. Many of these can change your playstyle significantly.

* Magic Power+ (500PXP): Increases magic power by 15%.
* Turbo MP (500PXP): Magic strength and cost increased by 30%.
* Elemancy (500PXP): Elemental spells treat enemy resistance as if it were 25 lower.
* Mystic Blade (250PXP): Spells can be cast through weapons. Treat as physical attacks instead.
* Geomancy (500PXP): Gain a stat bonus and/or status effect related to the current arena.
* Mugging (250PXP): Steal x skills have increased success rate and can deal damage.
* Integration (500PXP): Can choose to "equip" items instead of using them, gaining a (usually) beneficial boost.
* Suffering (500PXP): Magic power is increased by 10% per negative status effect on target.
* Status Boost (500PXP): Positive status effects are empowered.
* Antimagic (500PXP): Can choose to deal damage to mp instead.
* Bloodbath (500PXP): Increases damage by 50% at the cost of 12.5% max HP per turn.
* Absorption (500PXP): When dealing damage, can absorb 10% total damage as healing. Can temporarily learn certain abilities when hit by them.
* Multicasting (500PXP): Can attack multiple times per turn at the cost of upcoming turns. Gains a bonus based on how many extra turns are spent.
* Phazon Infused (1000PXP): Skill strength increases by 75% and HP regenerates by 20HP per round, but you become immune to healing (Except revival) and have permanent doom status.

## Custom Shop

Looking for even more variation? Look no further! You can earn HL for these by defeating bosses.

* 50000HL: Noise change. You'll gain several positive and negative attributes from a boss you've fought before. Which boss? The ref decides.
* 5000HL: Elemental armour. You'll absorb one element and be weak to another.
* 5000HL: Law card. You can use one of these to nullify a rule of your choosing, such as hazards or their lingering effects. Not everything may be nullified. You must choose what to nullify when you purchase. Lasts for one battle. This will affect EVERY fighter, so beware...
* 10000HL: Rip Cheato. Rip Cheato will boost one of your stats...?
* 0HL: Smiles are free! :)

## Hazards

Hazards are random effects that occur each round after the first. They will be announced at the start of each round and take effect immediately. Many of these are one-time effects, like dealing damage to random fighters or inflicting status effects. Others linger for the entire round, affecting rules or empowering random fighters. Others are permanent and will last throughout the battle. See [hazards.md](hazards.md) for a list of hazards.
