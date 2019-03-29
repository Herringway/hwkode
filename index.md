# Herringway's Kode of Battle

## Introduction

Welcome to Herringway Arena! Test your skills against famous bosses of all types in this collaborative RPG system.

Each battle consists of one or more enemies, a ref to keep things moving (mostly) and plenty of player-controlled combatants. The goal is to defeat the enemies by cooperating with your teammates, usually by reducing the HP of the enemies to zero before they do the same to you.

## Terms

* HP: Health Points. Run out of these and you're dead! Hope someone else is merciful...
* SP: Skill/Spell points. You can spend these in battle to use your abilities.
* A-Skill: Active Skill. These are skills that you purchase with XP and can use whenever your turn comes up.
* P-Skill: Passive Skill. These are skills that you purchase with XP and provide various effects, like increased magic strength or HP absorbing.
* Caster: Refers to whoever is using an ability, regardless of whether or not it is magical or physical.
* Unit: A specific combatant in the battle.
* Arena Barrier: Similar to the ref barrier, this barrier protects the audience from everything going on in the arena. The reverse is also true - those inside the arena are safe from those who are outside.
* RCP: Referee Control Panel. This wonderful device is responsible for all the arena functions, from protecting the audience and ref to simple stat displays. Occasionally crashes or glitches. Usually operated by the ref, but not always...
* Ref: Short for referee. The person refereeing is responsible for keeping the battle moving, resolving conflicts and generally making sure things stay fun, even if that means ending the battle. Ingame, the ref is responsible for operating the RCP and is an active part of battles. Normally, the ref is present but protected by a ref barrier, preventing any negative effects from affecting them. But when the barrier goes down... beware.
* Ref Barrier: This barrier is projected by the RCP on the ref and RCP itself during normal operation. Whoever is protected enjoys immunity to everything thrown about the arena.

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

Each battle is divided into several (hopefully) rounds. At the start of each round, players choose an action to take. Once everyone has decided what they will do, the actions will execute, with the fastest combatants going first and the slowest going last. Some status effects change the number of turns a player will get in a round. Enemies may be able to take multiple turns as well.

A round will be resolved once all fighters have selected their actions, or when the ref runs out of patience. Fighters that haven't picked any actions won't do anything that round. Don't miss your turn!

Note that some skills may be used freely while deciding actions - You can use as many of them as you want, but unless stated otherwise, you may use each one only once per round.

At the beginning of each round, a [Hazard](#hazards) is selected. The effects of the selected hazard will not activate until the next round, however.

Every fighter recovers 10% SP at the start of a round.

## Skills

This system has two main types of skills. A-Skills are Active Skills, skills you can use when your turn comes up in battle. P-Skills are Passive Skills, which are always active. Players can choose any combination of skills as long as they do not exceed the point limits. Players currently have 2000AXP and 1000PXP to spend on A-Skills and P-Skills respectively. Players cannot earn additional XP, but the limit will rise over time for everyone as the system progresses.

### A-Skills

Many A-Skills have multiple levels, often adding more power and/or effects. Selecting skills will increase a relevant statistic.

#### Default A-Skills

Everyone has access to these a-skills no matter what they choose.

* Fight - Deals physical damage with a 1.0x multiplier.
* Defend - Halves damage taken for this turn.
* Mix - Combines two items into one. Can be used before a round is resolved. Positive results not guaranteed...

#### Physical A-Skills

| Name            | AXP    | Description                                                                                                   | Prerequisites | Boosted Stats| SP Cost |
|-----------------|--------|---------------------------------------------------------------------------------------------------------------|---------------|--------------|---------|
| Cutting Edge    | 100AXP | Deals 3.0x water damage.                                                                                      |               | ATK, DEF     | 10      |
| Plume Edge      | 100AXP | Deals 5.0x water damage.                                                                                      | Cutting Edge  | ATK, DEF     | 20      |
| Ragnarok        | 100AXP | Deals 3.0x earth damage.                                                                                      |               | ATK, DEF     | 10      |
| Odyssey         | 100AXP | Deals 5.0x earth damage.                                                                                      | Ragnarok      | ATK, DEF     | 20      |
| Planet Diver    | 100AXP | Deals 3.0x fire damage. 5.0x if jumping.                                                                      |               | ATK, DEF     | 10      |
| Planetary       | 100AXP | Deals 5.0x fire damage. 8.0x if jumping.                                                                      | Planet Diver  | ATK, DEF     | 20      |
| Astral Blast    | 100AXP | Deals 3.0x wind damage.                                                                                       |               | ATK, DEF     | 10      |
| Thunder Mine    | 100AXP | Deals 5.0x wind damage.                                                                                       | Astral Blast  | ATK, DEF     | 20      |
| Elec Sword      | 100AXP | Deals 3.0x lightning damage.                                                                                  |               | ATK, DEF     | 10      |
| Elec Blade      | 100AXP | Deals 5.0x lightning damage.                                                                                  | Elec Sword    | ATK, DEF     | 20      |
| Saint Cross     | 200AXP | Deals 5.0x holy damage.                                                                                       |               | ATK, DEF     | 20      |
| Jump            | 100AXP | Allows caster to jump into the skies for one turn, out of range of many attacks.                              |               | ATK, DEF     | 10      |
| Dive            | 100AXP | Deals 9.0x non-elemental damage. Only usable while caster is jumping.                                         | Jump          | ATK, DEF     | 20      |
| Drain Jump      | 100AXP | Deals 5.0x non-elemental damage and heals the caster for the same amount. Only usable while caster is jumping.| Jump          | ATK, DEF     | 20      |
| Ultra Jump      | 100AXP | Deals 4.0x non-elemental damage and jump back into the sky. Only usable while caster is jumping.              | Jump          | ATK, DEF     | 20      |
| Metal Cut       | 300AXP | Deals 2.0x non-elemental damage. Cuts through defenses.                                                       |               | ATK, DEF     | 30      |
| Magnum Break    | 200AXP | Deals 3.0x fire damage to all enemies.                                                                        |               | ATK, DEF     | 20      |
| Chomp           | 250AXP | Pull out a random item and throw it.                                                                          |               | ATK, DEF     | 15      |
| Throw           | 400AXP | Throw a held item.                                                                                            |               | ATK, SPD     | 0       |
| Sledge          | 100AXP | Deals 4.0x non-elemental damage, 35% chance of inflicting mini status.                                        |               | ATK, DEF     | 20      |
| Element Sonic   | 300AXP | Deals 1.25x fire/water/lightning/earth damage to 4 units.                                                     |               | ATK, DEF     | 40      |
| Muramasa        | 150AXP | Deals damage equal to caster max hp - current hp.                                                             |               | HP, ATK      | 20      |
| Goblin Punch    | 100AXP | Deals 8.0x non-elemental damage if caster and target's hp digits add up to the same number.                   |               | HP, ATK      | 0       |
| Magic Hammer    | 150AXP | Deals 1.0x non-elemental damage to target's SP.                                                               |               | ATK, DEF     | 20      |
| Ice Shard       | 150AXP | Deals 3.0x ice damage. Hits before other moves.                                                               |               | ATK, DEF     | 20      |
| Dizzy Punch     | 200AXP | Deals 3.0x non-elemental damage. 50% chance of afflicting target with confusion.                              |               | ATK, DEF     | 20      |
| Dynamic Punch   | 200AXP | Deals 12.0x non-elemental damage, but is likely to miss. Will confuse if it connects.                         |               | ATK, DEF     | 20      |
| Sky Uppercut    | 150AXP | Deals 4.0x non-elemental damage and can hit targets that are normally unreachable.                            |               | ATK, DEF     | 15      |
| Shadow Claw     | 200AXP | Deals 4.0x dark damage. Increased chance of critical hit.                                                     |               | ATK, DEF     | 20      |
| Steal           | 150AXP | Steals an item from the target.                                                                               |               | ATK, SPD     | 10      |
| Steal Dexterity | 150AXP | Inflicts slow on target and grants user haste.                                                                | Steal         | ATK, SPD     | 25      |
| Steal Power     | 150AXP | Inflicts Attack- on target and grants user Attack+.                                                           | Steal         | ATK, SPD     | 25      |
| Steal Defense   | 150AXP | Inflicts Defense- on target and grants user Defense+.                                                         | Steal         | ATK, SPD     | 25      |
| Steal Health    | 150AXP | Inflicts Poison on target and grants user Regen.                                                              | Steal         | ATK, SPD     | 25      |

#### Magical A-Skills

| Name            | AXP    | Description                                                                                                   | Prerequisites | Boosted Stats| SP Cost |
|-----------------|--------|---------------------------------------------------------------------------------------------------------------|---------------|--------------|---------|
| Fira            | 100AXP | Deals 3.0x fire damage.                                                                                       |               | MAG, MDEF    | 10      |
| Firaja          | 100AXP | Deals 5.0x fire damage.                                                                                       | Fira          | MAG, MDEF    | 20      |
| Blizzara        | 100AXP | Deals 3.0x ice damage.                                                                                        |               | MAG, MDEF    | 10      |
| Blizzaja        | 100AXP | Deals 5.0x ice damage.                                                                                        | Blizzara      | MAG, MDEF    | 20      |
| Thundara        | 100AXP | Deals 3.0x lightning damage.                                                                                  |               | MAG, MDEF    | 10      |
| Thundaja        | 100AXP | Deals 5.0x lightning damage.                                                                                  | Thundara      | MAG, MDEF    | 20      |
| Aera            | 100AXP | Deals 3.0x wind damage.                                                                                       |               | MAG, MDEF    | 10      |
| Aeroja          | 100AXP | Deals 5.0x wind damage.                                                                                       | Aera          | MAG, MDEF    | 20      |
| Bio             | 100AXP | Deals 3.0x poison damage.                                                                                     |               | MAG, MDEF    | 10      |
| Bioga           | 100AXP | Deals 5.0x poison damage.                                                                                     | Bio           | MAG, MDEF    | 20      |
| Zammle          | 100AXP | Deals 3.0x dark damage.                                                                                       |               | MAG, MDEF    | 10      |
| Kazammle        | 100AXP | Deals 5.0x dark damage.                                                                                       | Zammle        | MAG, MDEF    | 20      |
| Holy            | 200AXP | Deals 5.0x holy damage.                                                                                       |               | MAG, MDEF    | 30      |
| Gravity         | 100AXP | Deals 25% HP worth of gravity damage.                                                                         |               | MAG, MDEF    | 30      |
| Graviga         | 100AXP | Deals 50% HP worth of gravity damage.                                                                         | Gravity       | MAG, MDEF    | 40      |
| Quake           | 300AXP | Deals 6.0x earth damage. Targets everyone.                                                                    |               | MAG, MDEF    | 15      |
| Drain           | 100AXP | Deals 3.0x damage, and heals user for the same amount.                                                        |               | MAG, MDEF    | 15      |
| Osmose          | 50AXP  | Drains SP from an enemy. 1.0x multiplier.                                                                     |               | MAG, MDEF, SP| 1       |
| Osmosega        | 100AXP | Drains SP from an enemy. 2.0x multiplier.                                                                     | Osmose        | MAG, MDEF, SP| 1       |
| Hyper Beam      | 300AXP | Deals 12.0x non-elemental damage. Caster cannot act next turn.                                                |               | MAG, MDEF    | 50      |
| Flare           | 300AXP | Deals 6.0x non-elemental damage. Pierces defense.                                                             |               | MAG, MDEF    | 30      |
| Ultima          | 300AXP | Deals 5.0x non-elemental damage to all enemies.                                                               |               | MAG, MDEF    | 30      |
| Psyshock        | 100AXP | Deals 4.0x non-elemental physical damage.                                                                     |               | MAG, MDEF    | 20      |
| Aqua Breath     | 200AXP | Deals 4.0x water/wind damage to all enemies.                                                                  |               | MAG, MDEF    | 30      |
| Breath Wing     | 200AXP | Deals 25% HP gravity/wind-elemental damage to all enemies.                                                    |               | MAG, MDEF    | 60      |

#### Support A-Skills

| Name            | AXP    | Description                                                                                                   | Prerequisites | Boosted Stats| SP Cost |
|-----------------|--------|---------------------------------------------------------------------------------------------------------------|---------------|--------------|---------|
| Cura            | 300AXP | Heals 2.0x damage.                                                                                            |               | MAG, MDEF, HP| 10      |
| Curaja          | 300AXP | Heals 4.0x damage.                                                                                            | Cura          | MAG, MDEF, HP| 20      |
| Astra           | 200AXP | Blocks a status effect-causing attack.                                                                        |               | MAG, MDEF, HP| 20      |
| Prayer          | 150AXP | Heals 1.0x damage and grants regen status to targets.                                                         |               | MAG, MDEF, HP| 30      |
| Protect         | 100AXP | Doubles physical defense.                                                                                     |               | DEF, MDEF, HP| 30      |
| Shell           | 100AXP | Doubles magic defense.                                                                                        |               | DEF, MDEF, HP| 30      |
| White Wind      | 300AXP | Restores an amount of HP equal to caster's HP to all allies.                                                  |               | DEF, MDEF, HP| 40      |
| PSI Healing α   | 100AXP | Heals negative status effects, except death.                                                                  |               | DEF, MDEF, HP| 20      |
| PSI Healing Ω   | 100AXP | Heals negative status effects, including death.                                                               | PSI Healing α | DEF, MDEF, HP| 40      |
| Slots           | 300AXP | Spin the slots for something good!                                                                            |               | HP, SP       | 15      |
| Disappear       | 150AXP | Gain the missing-in-action status for one round.                                                              |               | ATK, SPD     | 15      |
| Dragon Dance    | 400AXP | Grant Haste, Attack+ and Defense+ to user.                                                                    |               | HP, SPD      | 40      |
| Find Item       | 300AXP | Look around for an item. This doesn't use a turn and can only be used once per round.                         |               | HP, SPD      | 0       |

### P-Skills

P-skills are your passive abilities. Many of these can change your playstyle significantly.

| Name              | PXP    | Description                                                                                           |
|-------------------|--------|-------------------------------------------------------------------------------------------------------|
| Magic Power+      | 500PXP | Increases magic power by 50%.                                                                         |
| Attack Power+     | 500PXP | Increases attack power by 50%.                                                                        |
| Piercing Blow     | 500PXP | Fight now ignores defense.                                                                            |
| Reckless          | 200PXP | Increases attack power by 50%, decreases defense by 25%.                                              |
| Sluggish          | 200PXP | Increases attack power by 50%, decreases speed by 50%.                                                |
| Turbo SP          | 500PXP | Magic strength and cost increased by 30%.                                                             |
| Elemancy          | 500PXP | Elemental spells treat enemy resistance as if it were 25 lower.                                       |
| Mystic Blade      | 250PXP | Spells can be cast through weapons. Treat as physical attacks instead.                                |
| Geomancy          | 500PXP | Gain a stat bonus and/or status effect related to the current arena, usually positive.                |
| Mugging           | 250PXP | Steal x skills have increased success rate and can deal damage.                                       |
| Integration       | 500PXP | Can choose to "equip" items instead of using them, gaining a (usually) beneficial boost.              |
| Status Boost      | 500PXP | Negative status effects are more likely to land.                                                      |
| Bloodbath         | 500PXP | Increases damage by 50% at the cost of 12.5% max HP per turn.                                         |
| (Element) Resist  | 200PXP | Increases resistance to an element by 25.                                                             |
| Auto-protection   | 150PXP | Begin battle with protect and shell.                                                                  |
| Undead            | 100PXP | Begin battle undead.                                                                                  |
| Double or Nothing | 100PXP | Attack and magic power double, but your accuracy is halved.                                           |
| Regenerative      | 300PXP | Begin battle with permanent regen.                                                                    |
| Lightweight       | 100PXP | Begin battle with permanent float.                                                                    |
| Speedy            | 200PXP | Begin battle with permanent haste.                                                                    |
| Evasive           | 500PXP | Boosts physical evasion by 50%.                                                                       |
| Dual Wield        | 500PXP | You automatically use Fight in addition to your selected action.                                      |

## Base Stats

With no skills or other modifiers, everyone has *100 HP*, *100 SP*, *50 ATK*, *50 DEF*, *50 MATK*, *50 MDEF* and *10 SPD*. The main way to increase stats is to invest AXP in relevant [A-Skills]. Final stats are determined by a set of formulae:

ATK, DEF, MATK and MDEF: ```StatBonus = sqrt(3 * XPSpentInRelevantSkills)```

HP: ```StatBonus = sqrt(4 * XPSpentInHPSkills + 0.5 * XPSpentInDEFSkills + 0.1 * XPSpentInMDEFSkills)```

SP: ```StatBonus = sqrt(4 * XPSpentInSPSkills + 0.1 * XPSpentInATKSkills + 0.5 * XPSpentInMATKSkills)```

Speed: ```StatBonus = sqrt(2 * XPSPentInRelevantSkills)```

All stats are rounded up to the next nearest integer.

## Presets

While you can choose your own skills, you may also join battle with some pre-made sets.

### White Mage
Mostly healing, but not totally defenseless.

#### A-Skills

- Cura
- Curaja
- Protect
- Shell
- Astra
- Prayer
- White Wind
- PSI Healing alpha
- PSI Healing omega
- Osmose
- Osmosega
- Holy

#### P-Skills

- Regenerative
- Speedy
- Magic Power+

### Black Mage
Destroy everything with magic!

#### A-Skills

- Fira
- Firaja
- Thundara
- Thundaja
- Blizzara
- Blizzaja
- Flare
- Ultima
- Osmose
- Osmosega
- Quake
- Bio
- Bioga
- Gravity

#### P-Skills

- Elemancy
- Magic Power+

### Spellblade
These warriors channel magic through their bodies to fuel unusual, powerful techniques.

#### A-Skills

- Cutting Edge
- Plume Edge
- Ragnarok
- Odyssey
- Planet Diver
- Planetary
- Elec Sword
- Elec Blade
- Astral Blast
- Thunder Mine
- Metal Cut
- Magnum Break
- Life Sword
- Saint Cross

#### P-Skills

- Attack Power+
- Piercing Blow

### Ninja
Masters of sabotage and assassination.

#### A-Skills

- Throw
- Chomp
- Muramasa
- Find Item
- Shadow Claw
- Disappear
- Steal
- Steal Dexterity
- Steal Power
- Steal Defense
- Steal Health

#### P-Skills

- Dual Wield
- Evasive

## Elements

|Element   | Symbol |
|----------|--------|
|Water     |💧       |
|Fire      |🔥       |
|Lightning |⚡       |
|Wind      |🌪️       |
|Earth     |⛰️       |
|Poison    |☣️       |
|Holy      |✝️       |
|Dark      |😈       |
|Ice       |⛸️       |
|Gravity   |🌑       |

## Status Effects

### Positive

* Protect: Unit's defense is doubled.
* Shell: Unit's magic defense is doubled.
* Haste: Unit's speed is double.
* Bubble: Unit's HP is doubled.
* Aura: Unit will not take damage if it less than the number indicated.
* Auto-Life: Raise will automatically be cast on this unit when it dies.
* Metal: Unit's defenses are raised significantly.
* Quick: Unit has twice as many turns this round, and may use these new turns immediately after gaining the status.
* Attack+: Unit's attack stats increase by 50%.
* Defense+: Unit's defense stats increase by 50%.
* Regen: Unit recovers 1/8th of their max HP each round.
* Elemental Infusion: Unit deals 50% more damage with a particular element and gains 25 resist against that element.
* Reflect: Most spells targeted at unit will bounce off and hit the caster.
* Last Stand: Unit will survive the next fatal blow with 1HP.
* Astra: Prevents the next negative status effect from landing.

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
* Sap: Unit loses 1% of their HP each round. Usually expires after 5 rounds.
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

* Multitargetting: Some a-skills can optionally target multiple units. When this occurs, damage is divided according to the number of units. This does not apply to skills that are always multitargetted.
* Elemental Resistance: A stat that determines how much damage you take from a particular element. 100 is the standard, representing the normal 100% damage taken. A resist of 50 means 50% damage, 200 means 200% damage, etc.

## Custom Shop

Looking for even more variation? Look no further! You can earn HL for these by defeating bosses.

* 50000HL: Noise change. You'll gain several positive and negative attributes from a boss you've fought before. Which boss? The ref decides.
* 5000HL: Elemental armour. You'll absorb one element and be weak to another.
* 5000HL: Law card. You can use one of these to nullify a rule of your choosing, such as hazards or their lingering effects. Not everything may be nullified. You must choose what to nullify when you purchase. Lasts for one battle. This will affect EVERY fighter, so beware...
* 10000HL: Chet Rippo will boost one of your stats...?
* 0HL: Smiles are free! :)

## Hazards

Hazards are random effects that occur each round after the first. They will be announced at the start of each round and take effect at the start of the next. Many of these are one-time effects, like dealing damage to random fighters or inflicting status effects. Others linger for the entire round, affecting rules or empowering random fighters. Others are permanent and will last throughout the battle. See [hazards.md](hazards.md) for a list of hazards.

NOTE: Hazards are extremely incomplete.
