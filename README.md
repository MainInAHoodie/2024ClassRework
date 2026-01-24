# 2024ClassRework
Overhaul all the classes based on their 2024 PHB implementations...plus some of my own additions

**So what is this?**
This mod makes a number of changes to Classes, based on the 2024 rules as well as my own homebrew.

**You know there's already a mod for this, right?**
I specifically didn't want to do a 1:1 translation of the 2024 PHB.  I wanted to improve a few things that I thought were underpowered (I'm looking at you, Warden Druids) and adapt some things based on what I thought would adapt better to Baldur's Gate 3.  In particular, I didn't want to make any changes to the Backgrounds because of how special dialogue choices work in this game.

---

# __List of Changes__

# Script Changes

In the base game, the game will take away some of your starting equipment and put it on a Dead Thrall you can find shortly after your first battle with the Imps on the Nautiloid.  The Bard's Rapier is an example of this.  Why Larian did this is unclear.

This no longer happens -- you keep all your starting gear right at the start of the game.  That dead guy now gets an extra gold piece for his troubles.

# Class Changes

## Barbarian
### Starting Ability Scores
17 STR, 14 DEX, 14 CON, 8 INT, 12 WIS, 10 CHA

### Starting Equipment
You can now pick your starting equipment from the following options:
 - Any Martial Melee Weapon, a Spear, or a Quarterstaff
 - Any Ranged Weapon
 - Barbarian Leathers or Scale Armor
 - A Shield or a Javelin ("No Shield" isn't directly an option because of how the engine works).

There's no good way to give you, say, a five-pack of Javelins, unfortunately.

Barbarians also start with a Simple Robe so they don't appear starkers in the character creation screen.  They also start with a Dagger, because reasons.  Hey, one more thing to throw, right?

### All Barbarians

**3rd Level**
At 3rd Level, all Barbarians gain Primal Knowledge.  This lets them pick another skill proficiency from the list of Barbarian skills and lets them add half their Strength to Intimidation, Stealth, Survival, and Perception.

**9th Level**
*Brutal Critical* has been replaced by *Brutal Strike*.  This new Ability removes the Advantage from your Reckless Attack (for that attack onky) in exchange for an extra D10 of damage and one of the following rider effects:
 - **Forceful Strike**: If the target is Large or smaller, they make a Strength Saving Throw to avoid being knocked 15ft backwards.  If they fail, you can also move an additional half your movement speed without provoking Opportunity Attacks.
 - **Hamstring Blow**: Reduce the target's speed by 15ft.

### Berserker

**10th Level**
*Intimidating Presence* has been replaced with *Retaliation*.  Similar to Riposte, if you take damage from a target within 5ft of you, you can spend a Reaction to make one melee attack against that target.

### Wildheart
*Bear Heart* no longer grants resistance to Radiant, Necrotic, or Force damages.

## Bard
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 12 INT, 10 WIS, 17 CHA

### New Abilities
**Font of Inspiration**
Once per rest, you can convert a Spell Slot to a number of uses of Bardic Inspiration equal to half the spell slot's level, rounded up.

## Cleric
### Starting Ability Scores
Trickery Domain Clerics: 12 STR, 14 DEX, 14 CON, 10 INT, 17 WIS, 8 CHA
Everyone else: 10 CHA, 14 DEX, 14 CON, 12 INT, 17 WIS, 8 CHA

### Starting Equipment
Your starting equipment now includes a Dagger, as does Shadowheart's.  Sadly, letting you pick your equipment doesn't work, for reasons I'll get into in the "Known Issues" section.

## Druid
### Starting Ability Scores
Unchanged from before.

### Starting Equipment
Your starting equipment now includes both a Dagger and a Shield.  You can't pick your starting equipment for the same reasons as the Cleric, unfortunately.

## Fighter
### Starting Ability Scores
17 STR, 14 DEX, 14 CON, 10 INT, 12 WIS, 8 CHA
(though really, put your 15 in either Dexterity or Strength and your 10 in the other)

### Starting Equipment

You can now pick your starting equipment from among the following options:
 - Any Martial Melee Weapon, a Spear, or a Quarterstaff
 - Any Ranged Weapon
 - Studded Leather Armor, Scale Armor, or Chain Mail

Your starting equipment now also includes both a Shield and a Dagger.

### All Fighters

**1st Level**
Fighting Style has been moved to 2nd Level for reasons discussed under Known Issues.

## Monk
### Starting Ability Scores
Unchanged from before

### Starting Equipment
Yep, Monks get a Dagger now.

## Paladin
### Starting Abilities
Unchanged from before

### Starting Equipment
You can now pick your starting equipment from among the following options:
 - Any Martial Melee Weapon, a Spear, or a Quarterstaff
 - Any Ranged Weapon

Your starting equipment now also includes a Dagger.

Your starting armor is limited to the Paladin-specific Scale Armor.  You'll take what your order gives you and like it!

## Ranger
### Starting Ability Scores
Unchanged from before.

### Starting Equipment
Rangers now start with Studded Leather and a Longbow instead of Regular Leather and a Shortbow.  Oh, and a Dagger.  Don't forget the Dagger.

## Rogue
### Starting Ability Scores
8 STR, 17 DEX, 14 CON, 14 INT, 12 WIS, 10 CHA

### Starting Equipment
Rogues get their choice of a Hand Crossbow, a Light Crossbow, or a Shortbow.  Melee-wise, you're limited to starting with Daggers, but you now start with two of them.

## Sorcerer
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 12 INT, 10 WIS, 17 CHA

### Starting Equipment
Your starting equipment now includes a Dagger.

## Warlock
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 12 INT, 10 WIS, 17 CHA

### Starting Equipment
Hexblade Warlocks now start with a Chain Shirt, a Shield, and their choice of Martial Melee Weapon (same options as Fighters, Barbarians, and Paladins).

## 2nd Level

*Repelling Blast* now only works on targets that are Large or smaller, and the forced movement can be blocked with a Strength Saving Throw.

## Wizard
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 17 INT, 10 WIS, 12 CHA

### Starting Equipment
You're not gonna believe this, but Wizards start with a Dagger now.

---

# Spell Changes

## Bard
### Cantrips

**Vicious Mockery**
Vicious Mockery now uses a D6 instead of a D4.

## Druid
### Cantrips

**Shillelagh**
Shillelagh can now apply to Greatclubs, too.  Hey, a giant club is still a club.

---

# New Spells

## Cantrips

### Cleric

### Druid
**Druidcraft**
Give yourself Advantage on Nature and Survival checks for one minute.  Thaumaturgy for Druids, basically.

**Starry Wisp**
Hurl a mote of light at a target.  On a hit, they take a scaling amount of D8s of Radiant damage and can't benefit from being Invisible until the end of their next turn.

## 1st Level

## 2nd Level

---

# Known Issues

## Selecting Equipment and Selecting Passives

For whatever reason, selecting a Passive at the same level you select Equipment doesn't work.  It will *look* like you're selecting a Passive, but when you actually leave Character Creation, you'll find you don't have whatever Passive you selected.

For this reason, the Fighter's Fighting Style has been moved to 2nd Level.  This is also why Clerics and Druids can't select their starting equipment -- they wouldn't actually keep their Protector/Thaumaturge Passives, which would defeat the whole point of having them.
