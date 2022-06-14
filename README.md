# RadGH's Dwarf Therapist Professions

**Updated for Dwarf Fortress 0.47.05 (Dwarf Therapist 41.2.3)** 
Updated on June 14th, 2022. No changes were made to the professions, but the file has been re-exported for the latest version of Dwarf Therapist.

Adds 45 custom professions to Dwarf Therapist, which fall under three different categories of professions.

### Installation:

1. [Click here to download](https://raw.githubusercontent.com/RadGH/RadGH-s-Dwarf-Therapist-Professions/master/custom_professions.dtp) (Right-click, save as)
2. Open [Dwarf Therapist](http://www.bay12forums.com/smf/index.php?topic=168411.0)
3. File > Import Custom Professions
4. Load the file `custom_professions.dtp` that you just downloaded.

## Preview of all professions
![All professions displayed in Dwarf Therapist](https://s3.us-west-2.amazonaws.com/elasticbeanstalk-us-west-2-868470985522/ShareX/2022/06/dwarf-therapist-professions-by-radley.png)

>Preview using [Meph's Tileset](http://www.bay12forums.com/smf/index.php?topic=161047.0) _(which changes `$` to a crown, and `@` to crossed-swords)_ (from 2018).
>
> ![Preview of custom professions assigned to dwarves on the Nobles interface of Dwarf Fortress](https://s3-us-west-2.amazonaws.com/elasticbeanstalk-us-west-2-868470985522/ShareX/2018/05/Dwarf%20Fortress_2018-05-22_00-44-31.png)

## How to use this effectively

Here is an example scenario describing how I personally use these professions. Once you get the hang of it, this takes up very little time and helps ensure you didn't miss a dwarf.

1. A new migrant wave arrives.
2. Go to [Dwarf Therapist](http://www.bay12forums.com/smf/index.php?topic=168411.0) and sort by `Migration wave`.
3. Assigning **Soldiers**: Go to the military tab and examine dwarves from the most recent wave. Assign notable dwarves to a military profession (Based on fighter and weapon skills, or marksdwarf skill).
4. Assigning **Skilled Crafters**: Go back to the labors tab and find best skilled dwarves and assign them to their appropriate `2: (Skillname)` role. Ignore useless skills, of course.
5. Assigning **Workers**: Now that your soldiers and skilled dwarves are assigned, switch sorting from Migration Wave to Profession. Because of the prefixes for the custom professions, any unassigned dwarves will appear at the bottom of the list. Assign these to Worker, Laborer, Hauler, or Cleaner depending on demand.
6. Once all are assigned and you wait for them all to get on the map, assign your soldiers to squads as needed. You can search for their professions on the military screen with dfhack. You can also assign dwarves to squads in Dwarf Therapist itself (thanks u/gjallerhorn).
7. Periodically check your generic workers (any with the prefix of "1:") and assign any who have gained skills in one area to be a specialized worker, like a "2: Mason".
8. Optionally assign your **nobles** as needed / if desired.

## Profession Categories

**1. Workforce:**

Prefixed with a number for quick identification of skill level. For example `1: Cleaner` has many cleaning/hauling labors, while the more specialized roles such as `2: Weaponsmith` have only the specific skill, intended for skill-based labors.

**2. Soldiers:**

Prefixed such as `@ Elite`. Four versions include Militia, Soldier, Elite, and Archer. A fifth option is Scout, intended for your scouting missions. Used primarily for categorizing your military. All labors are the same and exclude stone and wood hauling to prevent Dwarves from being caught carrying heavy objects when drafted.

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
2: Gemcutter
2: Gemsetter
2: Hunter
2: Leatherworker
2: Mason
2: Mechanic         (Makes mechanisms, builds bridges, place buildings that use mechanisms)
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
@ Scout     (For scouting missions)
```
