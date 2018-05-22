# RadGH's Dwarf Therapist Professions

**Updated for Dwarf Fortress 0.44.10** on May 21st, 2018.

Adds 44 custom professions to Dwarf Therapist, which fall under three different categories of professions.

### Installation:

1. [Click here to download](https://raw.githubusercontent.com/RadGH/Rad-s-Dwarf-Therapist-Professions/master/custom_professions.dtp) (Right-click, save as)
2. Open [Dwarf Therapist](http://www.bay12forums.com/smf/index.php?topic=168411.0)
3. File > Import Custom Professions
4. Load the file `custom_professions.dtp` that you just downloaded.

>Preview using [Meph's Tileset](http://www.bay12forums.com/smf/index.php?topic=161047.0) _(which changes `$` to a crown, and `@` to crossed-swords)_.
>
> ![Preview of custom professions assigned to dwarves on the Nobles interface of Dwarf Fortress](https://s3-us-west-2.amazonaws.com/elasticbeanstalk-us-west-2-868470985522/ShareX/2018/05/Dwarf%20Fortress_2018-05-22_00-44-31.png)

## Profession Categories

**1. Workforce:**

Prefixed with a number for quick identification of skill level. For example `1: Cleaner` has many cleaning/hauling labors, while the more specialized roles such as `2: Weaponsmith` have only the specific skill, intended for skill-based labors.

**2. Soldiers:**

Prefixed such as `@ Elite`. Four versions include Militia, Soldier, Elite, and Archer. Used primarily for categorizing your military. All labors are the same and exclude stone and wood hauling to prevent Dwarves from being caught carrying heavy objects when drafted.

**3. Nobles:**

Prefixed such as `$ Noble`. Only two professions exist, which you should rename as needed for your Queen, Hammer, etc. One profession is `$ Leader` with labors similar to a worker. The other is `$ Noble` which has no labors, for your lazy king and his entourage.

## More Details

**Generic Professions**

If your dwarves aren't good at anything, put them here. If you have a lot of workers, you should make some workshops restricted to higher skill levels.

```
1: Cleaner
1: Hauler
1: Housekeeper  (Cleaning, hauling)
1: Laborer      (Cleaning, hauling, building)
1: Worker       (Cleaning, hauling, building, crafting)
1: Woodsman     (Great for your starting 7)
1: Stoneworker  (Great for your starting 7)
```

**Specialized Professions**

These professions are pretty specific and should go to your skilled dwarves.

```
2: Animal Trainer
2: Armorer
2: Blacksmith
2: Bonecarver
2: Brewer
2: Builder
2: Carpenter
2: Clothier
2: Cook
2: Doctor
2: Farmer
2: Furnacedwarf
2: Gemsetter
2: Hunter
2: Leatherworker
2: Mason
2: Metalcrafter
2: Miner
2: Nurse            (Only feeds patients)
2: Plant Gatherer
2: Siegebuilder     (Builds siege weapons)
2: Siegedriver      (Fires siege weapons)
2: Stone Detailer
2: Stonecrafter
2: Strand Extractor
2: Weaponsmith
2: Woodcrafter
2: Woodcutter
```

**Noblility**

You should generally use the Noble labor if you want to keep your nobles free. Rename it on an individual basis, optional.

```
$ Noble    (Basic hauling labors)
$ Leader   (Same labors as 1: Worker, used for Expedition leader)
```

**Military**

These professions are mainly for identifying units on the military screen (especially by searching with dfhack!). They do not carry wood or stone so that they don't get drafted while slowed by hauling a heavy object.

```
@ Elite     (For your most skilled soldiers)
@ Soldier
@ Militia
@ Archer    (For crossbow-punchers)
```