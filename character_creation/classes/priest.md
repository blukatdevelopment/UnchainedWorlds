```
################################################################################
# ______     _           _                                                     #
# | ___ \   (_)         | |                                                    #
# | |_/ / __ _  ___  ___| |_                                                   #
# |  __/ '__| |/ _ \/ __| __|                                                  #
# | |  | |  | |  __/\__ \ |_                                                   #
# \_|  |_|  |_|\___||___/\__|                                                  #
################################################################################
```
You live as an example to all that share your faith. In service of a deity,
you live by a strict code of conduct and leverage your piety to wield your
deity's magic.

## Starting hit points
You start with 4+CON hit points.

## Proficiencies
Armor: Light, Medium, Shield
Weapons: simple weapons, 
Saving Throws: Wisdom, Charisma

## Skills
Choose two from the following:
- Religion
- Persuasion
- Medicine
- Insight
- History
- Perception

## Starting equipment
- Dagger or mace
- Holy Book
- Holy Symbol
- Priest's Pack

```
LVL = level
XP = total experience points needed for level
SD = Stamina Dice
Prof = proficiency bonus
+-----+-------+-----+-------------+----------------------------+
| LVL |XP     | SD  | Spell Level |        Features            |
+-----+-------+-----+-------------+----------------------------+
|   1 |     0 | 1d4 |   Cantrip   | Divine Spellcasting        |
|   2 |   300 | 2d4 | 1           | Domain, Hit point Increase |
|   3 |   900 | 3d4 | 2           | Hit point Increase         |
|   4 |  1200 | 4d4 | 2           | Hit point re-roll          |
|   5 |  2700 | 5d4 | 3           | Ability Score Increase     |
|   6 |  5000 | 6d4 | 3           | Channel Divinity           |
|   7 |  7500 | 7d4 | 4           |                            |
|   8 | 10000 | 8d4 | 4           |                            |
|   9 | 15000 | 9d4 | 5           |                            |
|  10 | 20000 |10d4 | 5           | Ability Score Increase     |
+-----+-------+-----+-------------+----------------------------+
```

## Feats

### Divine Spellcasting
You've learned to call upon the power of a deity. Wisdom is your spellcasting
ability. You learn two cantrips
Your spell DC (difficulty class) is 8+proficiency bonus + wisdom modifier.
Your spell attack modifier is proficiency bonus + wisdom modifier.

```
+-------------+-------------+
| Spell Level |  Piety Cost |
+-------------+-------------+
| Cantrip     |          25 |
| 1           |         200 |
| 2           |         800 |
| 3           |        2400 |
| 4           |        7200 |
| 5           |       21600 |
+-------------+-------------+
```

#### Preparing Spells
Before you sleep at night, you may perform a prayer to request a number of
spells equal to half your priest level (rounded down) plus your wisdom modifier, 
minimum of one spell. You may select these spells from the 
priest spell list, and they must be first level or higher. You may only cast
spells that you have prepared.

#### Piety
A deity provides your source of magic, and so your fuel for spellcasting
is piety. Your actions are judged, providing and revoking piety. If your
balance of piety ever falls below zero, you lose all all divine spellcasting and
magical abilities. You cannot cast a spell if you do not have enough piety to do
so.

```
+-----------------------------------+--------------+
|            Good Acts              | Piety Gained |
+-----------------------------------+--------------+
| Lead Prayer(10 min, 1 stamina die)| 1d100        |
| Celebrate Holiday                 | 1d100        |
| Bless newborn, wedding, funeral   | 2d100        |
| Provide counsel(Roleplay it)      | 2d100        |
| Honorable Act(Domain Specific)    | 1d2 * 100    |
| Alms to the poor                  | 5d100        |
| Convert non-believer              | 1d10 * 100   |
| Apprehend/dissuade Criminal       | 1d10 * 100   |
| Sacrifice heart of large monster  | 1d4 * 1000   |
| Save a life from immediate danger | 1d12 * 100   |
| Cure the sick                     | 1d4 * 1000   |
| Sacrifice heart of huge monster   | 1d6 * 1000   |
+-----------------------------------+--------------+
```

```
+-------------------------------+-------------+
|          Bad Acts             | Piety Lost  |
+-------------------------------+-------------+
| Knowingly Harming innocents   | 1d10 * 1000 |
| Blasphemy or profanity        | 1d10 * 1000 |
| Murder                        | 2d20 * 1000 |
| Forbidden Act(Domain specific)|  1d6 * 1000 |
| Deceive, Cheat, or Steal      | 1d20 * 100  |
+-------------------------------+-------------+
```

### Domain
You have earned enough trust from you deity to access their special reserve of
spells. With this trust, you will be responsible for abstaining from forbidden
acts. Domain spells do not count against the number of spells you may prepare.


```
+-----------+-----------------------+------------------------+----------------------------------------+
|  Domain   |     Honorable Act     |     Forbidden Act      |                Spells                  |
+-----------+-----------------------+------------------------+----------------------------------------+
| Light     | Lighting a new shrine | Leaving a shrine unlit | Light[1], Dazzling Light, Bend Light   |
| Life      | Blessing a child      | Killing a humanoid     | Spare the dying[1], Mana, Revivify     |
| Nature    | Planting a tree       | Cutting a tree         | Thornwhip[1], Vine Suit, lightning bolt|
| Knowledge | Teaching someone      | Keeping a secret       | Eye stone[1], Identify, Mind Probe[1]  |
|           | for an hour           |                        |                                        |
| Justice   | Provide Judgement     | Fail to fight bad acts | Chastise, Smite, confess               |
|           | for a crime           | of others              |                                        |
+-----------+-----------------------+------------------------+----------------------------------------+
[1]: Spell is found in the Spell Compendium Volume 1
```

### Hit point Increase
Your maximum hit points increase by 1d4+CON.

### Hit point Increase
Your maximum hit points increase by 1d4+CON.

### Hit point re-roll
Now, and again each time you gain a level from now on, you recalculate your hit
points. Roll 3d4 and add your CON modifier three times. If the value rolled is
higher than your current max hit points, you may keep it.

### Channel Divinity
As the discipline in your domain grows solid, your deity offers up a domain-specific ability.
Using channel divinity uses an action and expends 2 stamina dice.

#### Holy Light (Light Domain)
You outstretch your arms and a 60 foot diameter cylinder that extends from the 
sky to your feet illuminates it's space as if in bright daylight. The light
crosses through solid objects and may penetrate into subterranean spaces.
Creatures cannot hide within the light, and invisible creatures become
visible. Any friendly creatures within the light are immune to necrotic damage
and any enemy creatures within the light are vulnerable to radiant damage.
The light lasts for 1 minute.

#### Miasma of Restoration (Life Domain)
You call out the name of your deity and smoke rolls out of your nostrils, ears,
and mouth. A 15 foot radius cloud forms around you and heavily obscures visibility.
Any creature which begins it's turn within or enters the cloud is healed for 1d6
hit points. You may use an action each turn to sustain the cloud. The effect
lasts up to 1 minute.

#### Spirit Bomb (Nature Domain)
You hold your hands with wrists touching and call out to the spirits of nature
to lend you their energy. An orb of spirit energy forms in front of your
hands as you siphon the collective energy of the plants and animals on your
plane of existence. Now, and until this effect ends, you may choose to
build or release the channeled energy.

You may release the spirit bomb by firing it at a point within 120 feet, The orb
explodes on impact and all creatures within a 30ft range must make a dexterity
saving throw, taking 2d8 radiant damage on a failure and half as much on a
success. Within the point of impact any metal objects degrade into piles of rust
powder. This ends the channel divinity.

You may build the channeled energy further, growing the orb. The radius when you
release the spirit bomb increases by 5ft, and the damage dealt increases by 2d8,
up to a maximum of 50ft and 10d8 radiant damage. You must hold concentration to
build the spirit bomb's energy.

#### Omniscient Sight (Knowledge Domain)
Your eyes begin to glow brightly. You can see all creatures within 120 feet of
you, whether they are invisible, hiding, or in a parallel dimension such as the
ethereal plane. You chant a holy prayer, and any friendly creatures within
range share this sight, and additionally gain advantage on any attack rolls
they make. Each turn, you may use your action to continue chanting in order to
extend this effect for up to 1 minute.

#### Reap (Justice Domain)
You use one hand to point at an evil creature within 60 feet, and hold your
other hand in the air as you declare that the creature will be reaped in the
name of your deity. A spectral scythe appears in your hand. You are proficient
with the scythe and it uses wisdom instead of strength. The scythe deals 3d10
force damage on a hit. If you kill the targeted creature, their soul is harvested
and you receive 1d2 * 1000 piety. The weapon disappears after 1 minute, or if
you end a turn without having attacked with it, or after killing the targeted
creature.

## Spell List

### Cantrip
- Mending 
- Sacred Flame 
- Guidance 
- Touch Light 
- Lay On Hands 
- Thaumaturgy 
- Toll the Dead 
- Resistance 
- Spare the Dying 
- Word of Radiance 

### 1st
- Guiding Bolt 
- Healing Word 
- Cure Wounds 
- Shield of Faith 
- Calm Emotions 
- Command 
- Protection from good and evil 
- Vorpal Snare
- Push
- Bane 
- Bless 
- Create or Destroy Water 
- Detect Evil and Good 
- Detect Magic 
- Detect Poison and Disease 
- Inflict Wounds 
- Sanctuary 
- Purify Drink or Food 
- Diagnose Curse
- Death Ward

### 2nd
- Insight Arrow 
- Radiant Weapon 
- Holy Weapon 
- Bird Friend 
- Words of Warning 
- Walk Through Walls 
- Channel the Dead 
- Words of Strength 
- Object of Desire 
- Spirit Barrier 
- Cure Sickness 
- Hold Person 
- Aid 
- Blindness/Deafness 
- Continual Flame 
- Enhance Ability 
- Find Traps 
- Gentle Repose 
- Lesser Restoration 
- Locate Object 
- Prayer of Healing 
- Protection from Poison 
- Silence 
- Warding Bond

### 3rd
- Sacrifice 
- Kindness 
- Confession 
- Riddle 
- Exorcism 
- Dispel Magic 
- Feign Death 
- Gaseous Form 

### 4th
- Miracle 
- Life Mist 

### 5th
- Judgement 
- Curse 
- Angelic Transformation 