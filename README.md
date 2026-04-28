# 2024ClassRework
Overhaul all the classes based on their 2024 PHB implementations...plus some of my own additions

**So what is this?**

This mod makes a number of changes to Classes, based on the 2024 rules as well as my own homebrew.

**You know there's already a mod for this, right?**

I specifically didn't want to do a 1:1 translation of the 2024 PHB.  I wanted to improve a few things that I thought were underpowered (I'm looking at you, Warden Druids) and adapt some things based on what I thought would adapt better to Baldur's Gate 3.  In particular, I didn't want to make any changes to the Backgrounds because of how special dialogue choices work in this game.

---

# **List of Changes**

# Script Changes

In the base game, the game will take away some of your starting equipment and put it on a Dead Thrall you can find shortly after your first battle with the Imps on the Nautiloid.  The Bard's Rapier is an example of this.  Why Larian did this is unclear.

This no longer happens -- you keep all your starting gear right at the start of the game.  That dead guy has been moved next to the player's starting point on the Nautiloid and will have different equipment based on what Passives you have: Ring Armor for Protector Clerics (see Known Issues), Hide Armor for Warden Druids, and Leather Armor and a Shield otherwise.

# Class Changes

## Barbarian
### Starting Ability Scores
17 STR, 14 DEX, 14 CON, 8 INT, 12 WIS, 10 CHA

### Starting Equipment
You can now pick your starting equipment from the following options:
 - Any Martial Melee Weapon, a Spear, a Quarterstaff, or a Handaxe
 - Any Ranged Weapon
 - Barbarian Leathers or Scale Armor
 - One of four shields (Metal, Wooden, Studded, or Iron-Banded), a Handaxe, a Shortsword, a Scimitar, a Light Hammer, a Javelin, or a Dagger.

There's no good way to give you, say, a five-pack of Javelins, unfortunately.

Barbarians also start with a Simple Robe so they don't appear starkers in the character creation screen.  They also start with a Dagger, because reasons.  Hey, one more thing to throw, right?

### All Barbarians
#### **3rd Level**
At 3rd Level, all Barbarians gain Primal Knowledge.  This lets them pick another skill proficiency from the list of Barbarian skills and lets them add half their Strength to Intimidation, Stealth, Survival, and Perception.

#### **9th Level**
**Brutal Critical** has been replaced by **Brutal Strike**.  This new Ability removes the Advantage from your Reckless Attack (for that attack onky) in exchange for an extra D10 of damage and one of the following rider effects:
 - **Forceful Strike**: If the target is Large or smaller, they make a Strength Saving Throw to avoid being knocked 15ft backwards.  If they fail, you can also move an additional half your movement speed without provoking Opportunity Attacks.
 - **Hamstring Blow**: Reduce the target's speed by 15ft.

### Berserker
#### **10th Level**
**Intimidating Presence** has been replaced with **Retaliation**.  Similar to Riposte, if you take damage from a target within 5ft of you, you can spend a Reaction to make one melee attack against that target.

### Wildheart
- **Bear Heart** no longer grants resistance to Radiant, Necrotic, or Force damages.
- **Eagle Heart** now lets you Dash and Disengage both on activation and as a Bonus Action while Raging.

## Bard
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 12 INT, 10 WIS, 17 CHA

### New Abilities
**Font of Inspiration**
Once per rest, you can convert a Spell Slot to a number of uses of Bardic Inspiration equal to half the spell slot's level, rounded up.

## Cleric
### Starting Ability Scores
Trickery Domain Clerics, including Shadowheart: 12 STR, 14 DEX, 14 CON, 10 INT, 17 WIS, 8 CHA
Everyone else: 10 CHA, 14 DEX, 14 CON, 12 INT, 17 WIS, 8 CHA

### Starting Equipment
Your starting equipment now includes a Dagger, as does Shadowheart's.  Sadly, letting you pick your equipment doesn't work, for reasons I'll get into in the "Known Issues" section.

### All Clerics
#### **1st Level**
At 1st Level, you're given the choice between two Divine Orders (well, technically 5 because of how the game's engine works):
- **Protector**
  - Grants Heavy Armor Proficiency and, in a departure from the PHB, no longer grants any Martial Weapon Proficiencies.  Instead, you can now Bind a Mace, Spear, or Dagger, imbuing it with Divine Energy.  You can use your Wisdom in place of your Strength or Dexterity for attack and damage rolls, and the damage die becomes a d6, unless it was already higher than that. 
  - At 5th Cleric level, you can make a second attack with this weapon, and the weapon's damage becomes magical if it wasn't already
- **Thaumaturge**
  - You can add your Wisdom Modifier to Arcana and Religion checks.  You can also choose an additional cantrip from Produce Flame, Thaumaturgy, Toll the Dead, and Word of Radiance.

*Explanation*: I found Protector to be very underpowered as written.  Martial Weapon proficiency doesn't suddenly make Clerics good at using weapons, so all you're functionally getting is Proficiency in Heavy Armor.  If you want that, starting with a level of Fighter gets you that and more, and it's not like you have bad AC without Heavy Armor.  This was intended to make Protector more viable.

#### **2nd Level**
You always have the following Channel Divinity option:
- **Divine Spark**
    Starting at 2nd Level, you can heal an ally for 1d8 + Wisdom HP or deal that much Radiant or Necrotic damage (your choice) to an enemy.  This amount increases to 2d8 at 7th level and 3d8 at 12th.

#### **5th Level**
**Destroy Undead** has been renamed to **Sear Undead** and damage scales, starting at 4d8 when you unlock it.

#### **7th Level**
At 7th Level, you can pick between the following two Blessed Strikes:
- Potent Cantrips: Add your Spellcasting Ability Modifier to your Cantrip's damage.
- Blessed Strike: Make an attack with your melee weapon to deal an extra 1d8 Radiant or Necrotic damage.  Now actually usable, IMO, with the changes to Protector.

### Life Domain
Now grants permanently-prepared Aura of Life instead of Guardian of Faith at 7th level.

### Light Domain
Warding Flare can now be used on either yourself or an ally right from the get-go.  At 6th level, using it also grants Temporary HP to the target.  This Temp HP will override any other source of Temp HP, including things like Armor of Agathys, so keep that in mind.

### Trickery Domain
#### **1st Level**
Now grants Medium Armor Master for free, so you're not at cross-purposes with what the class is theoretically supposed to be doing.

#### 6th Level
**Trickster's Transposition**: 3 free uses of Misty Step per Long Rest.  I wasn't able to figure out how to implement moving the Invoke Duplicity clone or any of the stuff around that, although granted, I didn't try very hard.  Maybe I'll look into that at some point down the road.

### War Domain
#### **1st Level**
In another break with the PHB, War Priest charges no longer restore on a Short Rest at any point.  If you're a Protector, you already get two attacks per turn, so it felt like overkill.

#### **2nd Level**
You can now give Guided Strike to either yourself or an Ally right at 2nd level.

#### **6th Level**
You can now cast either Shield of Faith or Spiritual Weapon at 1st Level once per Long Rest without using a Spell Slot.  These spells will last for 1 minute and do not require Concentration.

### Knowledge Domain
#### **1st Level**
The Knowledge Skills list now includes Medicine.  It's Wisdom-based rather than Intelligence, but I think it makes thematic sense.

#### **6th Level**
To compensate for the fact that Knowledge Domain no longer has semi-exclusive access to Potent Spellcasting, you can pick a third Expertise now instead.

## Druid
### Starting Ability Scores
Unchanged from before.

### Starting Equipment
Your starting equipment now includes both a Dagger and a Shield.  You can't pick your starting equipment for the same reasons as the Cleric, unfortunately.

### All Druids
#### **1st Level**
- **Warden**
    - Grants Proficiency in Medium Armor and Scimitars, and, in a departure from the Player's Handbook, no longer grants Proficiency in any other Martial Weapons.  Instead, in a mix of a Warlock's Pact Weapon and Shillelagh, a Warden Druid can Bind a Club, Quarterstaff, Greatclub, or Scimitar, imbuing it with natural energy.  You can use your Wisdom in place of Strength or Dexterity for attack and damage rolls, and the damage die becomes a D6, unless it was already higher than that.
    - At 5th Druid Level, you can make two attacks per turn with this weapon, and the weapon's damage becomes magical if it wasn't already.
    - This does have the side effect of making the Sylvan Scimitar obsolete, but that's a small price to pay for making Warden actually usable, IMO.
- **Magician**
    -  You can add your Wisdom Modifier to Nature and Religion checks.  You can also pick an additional cantrip from among Druidcraft, Poison Spray, Produce Flame, Resistance, Starry Wisp, Shillelagh, and Thorn Whip

*Explanation*: everything I wrote about Protector Clerics above applies to Warden Druids.  It's even worse for Warden Druids, though, since Shillelagh essentially forces them into Clubs or Quarterstaffs anyway.

**Druidic**
In a nutshell, you always have Speak With Animals prepared for free.  Speak With Animals is still on the Druid's Spell List, though, just in case you pick Magic Initiate.

#### **2nd Level**
**Wild Companion**: You can cast Find Familiar and always have it prepared for free.

#### **3rd Level**
**Wild Resurgence**
- Once on each of your turns, you can convert a Spell Slot into a number of uses of Wild Shape equal to half the spell slot's level, rounded up.  
- Once per Long Rest, you can convert one use of Wild Shape into a 1st Level Spell Slot.

#### **7th Level**
**Elemental Fury**: Choose one of the following options:
- **Potent Spellcasting**: Add your Wisdom modifier to the damage rolls of your Druid cantrips
- **Elemental Strike**: Once per turn, you can deal an extra 1d8 Fire, Cold, Thunder, or Lightning when you make a weapon attack or attack while Wildshaped.  Now actually usable, IMO, with the changes to Warden.

### Circle of the Land
#### **2nd Level**
Now limited to four options: Arid, Temperate, Polar, or Tropical.

- **Arid**
    - Cantrip (unlocked immediately): Fire Bolt
    - 1st Level Spell (unlocked immediately): Burning Hands
    - 2nd Level Spell (unlocked at 3rd Level): Blur
    - 3rd Level Spell (unlocked at 5th Level): Fireball
    - 4th Level Spell (unlocked at 7th Level): Blight
    - 5th Level Spell (unlocked at 9th Level): Wall of Stone
- **Temperate**
    - Cantrip (unlocked immediately): Shocking Grasp
    - 1st Level Spell (unlocked immediately): Sleep
    - 2nd Level Spell (unlocked at 3rd Level): Misty Step
    - 3rd Level Spell (unlocked at 5th Level): Lightning Bolt
    - 4th Level Spell (unlocked at 7th Level): Freedom of Movement
    - 5th Level Spell (unlocked at 9th Level): Conjure Elemental
- **Polar**
    - Cantrip (unlocked immediately): Ray of Frost
    - 1st Level Spell (unlocked immediately): Fog Cloud
    - 2nd Level Spell (unlocked at 3rd Level): Hold Person
    - 3rd Level Spell (unlocked at 5th Level): Sleet Storm
    - 4th Level Spell (unlocked at 7th Level): Ice Storm
    - 5th Level Spell (unlocked at 9th Level): Cone of Cold
- **Tropical**
    - Cantrip (unlocked immediately): Acid Splash
    - 1st Level Spell (unlocked immediately): Ray of Sickness
    - 2nd Level Spell (unlocked at 3rd Level): Web
    - 3rd Level Spell (unlocked at 5th Level): Stinking Cloud
    - 4th Level Spell (unlocked at 7th Level): Polymorph
    - 5th Level Spell (unlocked at 9th Level): Insect Plague

### Circle of the Moon
#### **2nd Level**
- At 3rd Level, you unlock Cure Wounds, Moonbeam, and Starry Wisp
- At 5th Level, you unlock Conjure Animal
- At 7th Level, you unlock Fount of Moonlight
- At 9th Level, you unlock Mass Cure Wounds

#### **3rd Level**
**Lunar Magic**: While Wildshaped, your AC is equal to 13 plus your Wisdom, unless it was already higher (which it usually isn't).

#### **6th Level**
**Improved Toughness**: You can add your Wisdom Modifier to your Constitution Saving Throws.

#### **10th Level**
**Moonlight Step**: This is effectively a free Misty Step that gives you Advantage on your next attack roll before the end of your next turn.  You can convert Spell Slots to Moonlight Step uses at a rate of half the Spell Slot's level, rounded up.

## Fighter
### Starting Ability Scores
17 STR, 14 DEX, 14 CON, 10 INT, 12 WIS, 8 CHA
(though really, put your 15 in either Dexterity or Strength and your 10 in the other)

### Starting Equipment

You can now pick your starting equipment from among the following options:
 - Any Martial Melee Weapon, a Spear, a Quarterstaff, or a Handaxe
 - Any Ranged Weapon
 - Studded Leather Armor, Scale Armor, or Chain Mail
 - One of four shields (Metal, Wooden, Studded, or Iron-Banded), a Handaxe, a Shortsword, a Scimitar, a Light Hammer, a Javelin, or a Dagger.

Your starting equipment now also includes a Dagger.

### Skills
Persuasion has been added to the Fighter's Skill list.

### All Fighters
#### **1st Level**
Fighting Style has been moved to 2nd Level for reasons discussed under Known Issues.

#### **2nd Level**
- **Tactical Mind**: Once per Short Rest, you can add 1d10 to a Skill Check.

#### **5th Level**
- **Tactical Shift**: When you use your Second Wind, you can move an additional 10 ft without provoking Opportunity Attacks.

#### **9th Level**
 - **Tactical Mastery**: Once per turn, you can attempt to apply one of the following effects to the target of one of your melee attacks:
    - **Push**: On a failed Strength save, the target is pushed back 10 feet/3 meters.
    - **Sap**: On a failed Constitution save, the target has Disadvantage on their next attack.
    - **Slow**: On a failed Constitution save, the target loses 10 feet/3 meters of movement speed on their next turn.
 - **Indomitable** now grants a +10 to the Saving Throw reroll.

## Monk
### Starting Ability Scores
Unchanged from before.

### Starting Equipment
Yep, Monks get a Dagger now.

### All Monks
#### **2nd Level**
- **Flurry of Blows** can now target multiple enemies.  They all have to be within melee range, thouugh.
- You can now use **Step of the Wind** to Dash or **Patient Defense** to Disengage as a Bonus Action without spending a Ki Point.
- You can also spend a Ki Point to use **Step of the Wind** to both Dash and Disengage or **Patient Defense** to Dodge and Disengage.
- **Uncanny Metabolism:** New.  Once per Long Rest, while not in combat, you regain all of your Ki Points and heal for one Martial Arts die plus your Monk Level.

#### **10th Level**
- **Flurry of Blows** increases to three attacks instead of two.
- When you spend a Ki Point to both Dodge and Disengage with **Patient Defense**, you also gain Temp HP equal to two Monk Unarmed Attack dice.
- Once per Short Rest, when you spend a Ki Point on **Step of the Wind**, you can teleport yourself and one ally (Medium or smaller) up to 50 feet/15 meters in addition to Dodging and Dashing.

#### **12th Level**
- **Disciplined Survivor**: You gain Proficiency in all Saving Throws, two levels before the PHB would give it to you.

### Way of the Elements
You no longer select "spells" (Elemental Disciplines, but let's face it, they're spells) at any point.  The most useful among your options are just given to you automatically as you level up.

#### **3rd Level**
- **Harmony of Fire and Water** has been removed entirely.
- **Elemental Attunement**: For the cost of 1 Ki Point, you can change your Weapon's damage type to Acid, Cold, Fire, Lightning, or Thunder damage for the next minute.  Because of how the engine works, it doesn't appear possible to directly override the damage type of your unarmed attacks, and making new techniques that deal different damage types is just incredibly clunky from a user perspective.  Plus, there are just too many good quarterstaffs and other Monk equipment to rely entirely on your fists.

#### **6th Level**
- You gain Water Whip, Fangs of the Fire Snake, and Shaping of the Ice for free.

#### **9th Level**
- Water Whip increases to 4d10 Bludgeoning.
- Fangs of the Fire Snake now correctly scales to deal an extra 2d10 on the initial hit.

#### **11th Level**
You gain Mist Stance for free.  It is otherwise unchanged.

#### **12th Level**
You gain Ride the Wind for free.  It is otherwise unchanged.

### Way of the Open Hand
#### **3rd Level**
**Flurry of Blows: Push** now lets the target make a Strength save to prevent the forced movement.

## Paladin
### Starting Abilities
Unchanged from before

### Starting Equipment
You can now pick your starting equipment from among the following options:
 - Any Martial Melee Weapon, a Spear, a Quarterstaff, or a Handaxe
 - Any Ranged Weapon
 - One of four shields (Metal, Wooden, Studded, or Iron-Banded), a Handaxe, a Shortsword, a Scimitar, a Light Hammer, a Javelin, or a Dagger.

You can also pick your starting armor from among the following:
 - Studded Leather
 - Scale Mail
 - Chain Mail

The Studded Leather and Chain Mail include new versions that match the color scheme of each order's Scale Mail.

Your starting equipment now also includes a Dagger.

## Ranger
### Starting Ability Scores
Unchanged from before.

### Starting Equipment
Rangers now start with Studded Leather and a Longbow instead of Regular Leather and a Shortbow.  Their new Studded Leather has a unique color scheme, too.

Oh, and they get a Dagger.  Don't forget the Dagger.

### All Rangers
#### **2nd Level**
- **Deft Explorer**: Gain Expertise in one Skill.

#### **9th Level**
- **Expertise**: Gain Expertise in another Skill.

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

### All Sorcerers
#### **2nd Level**
**Innate Sorcery**: Gain Advantage on your Spell Attacks and a +1 increase to your Spell Save DC for 1 minute.  Costs 1 Sorcery Point and can be used once per Short Rest, unlike the book.

#### **3rd Level**
The **Empowered Spell** Metamagic returns.  For 1 Sorcery Point, reroll damage of a direct damage spell and use the higher of the two.

#### **7th Level**
**Sorcerous Restoration**: Restore up to half your Sorcery Points once per Long Rest.

### Draconic Bloodline Sorcerer
#### **1st Level**
Your Draconic Resilience now sets you AC to 10 + DEX + CHA when you're not wearing Armor.  You can use a Shield and still gain this benefit, assuming you get Shield proficiency from somewhere else.

## Warlock
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 12 INT, 10 WIS, 17 CHA

### Starting Equipment
Hexblade Warlocks now start with a Chain Shirt, a Shield, and their choice of Martial Melee Weapon (same options as Fighters, Barbarians, and Paladins).  Their Chain Shirt has been recolored to match their starting Padded Armor.

#### **2nd Level**
*Repelling Blast* now only works on targets that are Large or smaller, and the forced movement can be blocked with a Strength Saving Throw.

## Wizard
### Starting Ability Scores
8 STR, 14 DEX, 14 CON, 17 INT, 10 WIS, 12 CHA

### Starting Equipment
You're not gonna believe this, but Wizards start with a Dagger now.

### Skills
Nature has been added to the Wizard's Spell List

### All Wizards
#### **2nd Level**
**Scholar**: Gain Expertise in one Skill on the Wizard's Spell List other than Insight.

---

# Spell Changes
## Cantrips
### Bard
- **Vicious Mockery**: Vicious Mockery now uses a D6 instead of a D4.

### Druid
- **Shillelagh**: Shillelagh can now apply to Greatclubs, too.  Hey, a giant club is still a club.

### Wizard
- **True Strike**: True Strike now lets you make one attack with your melee weapon using your Spellcasting Ability Modifier.

## 1st Level
### Cleric
- **Cure Wounds** now starts at 2d8 + Spellcasting and scales up 2d8 per level from there.
- **Healing Word** now starts at 2d4 + Spellcasting and scales up 2d4 per level from there.

### Ranger
- **Hunter's Mark** now applies to all attacks, not just weapons, and now does 1d6 of Force damage.

## 2nd Level
### Druid
- **Barkskin** now increases AC to 17 instead of 16.

### Wizard
**Color Spray**
Now a Constitution Save instead of a Hit Point total.  Cone size starts at 4 meters and scales up 1 meter per Spell Level, topping out at 9 meters (30 feet) at 6th level.

**Sleep**
Now a Constitution Save instead of a Hit Point total.  Targets sleep for one extra turn for each Spell Slot level above 1.

**Witch Bolt**
Activating the ongoing damage now costs a Bonus Action instead of a full Action.  The ongoing damage has been reduced, but now actually scales as follows:
- 1st Level: 1d6
- 2nd Level: 1d12
- 3rd Level: 2d6
- 4th Level: 3d6
- 5th Level: 2d12
- 6th Level: 4d6

The initial damage is the same as the recurring damage now.

## 3rd Level
### Cleric
- **Mass Healing Word** now starts at 2d4 + Spellcasting and scales up 1d4 per level from there

### Druid

## 4th Level
### Druid
- **Fount of Moonlight**: A cool light wreathes your body.  Until the spell ends, you are Resistant to Radiant damage, and your weapon attacks deal an extra 2d6 damage.

## 5th Level
### Cleric
- **Mass Cure Wounds**  now starts at 5d8 + Spellcasting and scales up 1d8 per level from there.
---

# New Spells
## Cantrips
### Cleric
- **Word of Radiance**: Each enemy within 7.5 ft of you (an increase from the book, because the Effect Radius in the engine doesn't let me enter 1.5 meters for some reason) must pass a Constitution Saving Throw or take 1d6 Radiant damage (scaling as you level)

### Druid
- **Druidcraft**: Give yourself Advantage on Nature and Survival checks for one minute.  Thaumaturgy for Druids, basically.
- **Starry Wisp**: Hurl a mote of light at a target.  On a hit, they take a scaling amount of D8s of Radiant damage and can't benefit from being Invisible until the end of their next turn.

### Sorcerer
- **Sorcerous Burst**: Make a ranged spell attack that deals your choice of Acid, Cold, Fire, Lightning, Poison, or Thunder.  This spell, unlike the PHB, will deal 2d4 at 1st Level, 3d4 at 5th Level, and 4d4 at 10th Level, a change made in a misguided attempt at game balance (the "exploding dice" mechanic isn't especially easy to implement in the BG3 engine, and leaving it at 1d8 meant there was very little reason to select anything else).

## 2nd Level

## 3rd Level
### Druid
- **Conjure Animal**:
   - You call to the nature spirits to take the form of an animal to aid you.  This effectively lets you summon a Ranger's animal companion (though unlike them, you have to spend a spell slot to do it).
   - To start with, they have the Companion's Bond Passive
   - If you summon them with a 4th level spell slot, they get the Exceptional Training passive as well
   - If you summon them with a 5th level spell slot, they get an Ability Score boost
   - If you summon them with a 6th level spell slot, they get an extra attack.
   - This should have been Conjure Animals, perhaps letting you conjure a Large pack of spectral, intangible animals in an unoccupied space, but the nature spirits are a bit short-staffed right now what with the whole Shadow Curse thing.

## 4th Level
### Cleric
**Aura of Life**
You and any Allies within 30 feet of you gain Resistance to Necrotic damage and can't have your maximum HP reduced, at least not by anything in the base game.  The way the game engine works means it can only block specific Statuses that reduce Maximum HP, so if a mod adds a new Status that does that, this aura ain't gonna help one bit.  

In addition, if an Ally starts their turn in the Aura with 0HP remaining, they gain 1HP.

---

# Character Defaults

- Jaheira starts with Warden for her Primal Order
- Halsin starts with Magician: Starry Wisp for his Primal Order
- Shadowheart has Thaumaturge: Produce Flame for her Divine Order
- Shadowheart starts with a fancy Sharran Dagger (the same one the Justiciar Nightweavers carry in the Gauntlet of Shar) instead of the standard one.

# Known Issues

## Selecting Equipment and Selecting Passives

For whatever reason, selecting a Passive at the same level you select Equipment doesn't work.  It will *look* like you're selecting a Passive, but when you actually leave Character Creation, you'll find you don't have whatever Passive you selected.  Apparently, SelectPassive() and SelectEquipment() don't play nicely together.

For this reason, the Fighter's Fighting Style has been moved to 2nd Level.  This is also why Clerics and Druids can't select their starting equipment -- they wouldn't actually keep their Protector/Thaumaturge Passives, which would defeat the whole point of having them.
