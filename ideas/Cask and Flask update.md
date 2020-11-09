# Charm - Cask and Flask update
a.k.a. **101 Different Uses For Copper**


## Casks
Crafted from wood and copper like a barrel, but the slabs are copper.
```
PCP
P P
PCP
```


* A **cask** holds potions (and water).
* Right-click on a cask with a filled bottle to add the contents to the cask (and return the bottle)
* A cask holds **64** bottles of liquid.
* Right-click on a cask with an empty bottle to get one filled bottle of the cask contents.
* Right-click on a cask with a **flask** to add the equivalent of one bottle to the flask.

### Casks: Mixing

* The cask takes an **average** of the lengths and strengths of all potions added.
* Adding water to a cask of potion dilutes the potion (reduces its amplifier and duration).
* Combining more than one kind of potion risks the contents becoming **dubious**.
* Right-clicking on a dubious cask gets you a potion bottle that  gives you the combined potion effect but with a chance of negative effects.
* The more you mix, the more chance the resulting potion will be crappy.

### Casks: Aging

* As a cask ages, the duration bonus of the contained potion will increase.

### Casks: Misc

* Breaking a cask does **not** lose its contents.
* Will probably be the POIT for the Innkeeper (Strange).



## Cooking pot
Crafted like a cauldron but with copper instead of iron.
```
C C
C C
CCC
```

* A **Cooking pot** holds food (in the form of a stew).
* To start, you have to fill the cooking pot with water and put it on the block above a fire (campfire, soul campfire or normal fire block)
* Right-click on a cooking pot with any food to add it to the pot.
* A cooking pot holds **64** food items.
* Right-click on a cooking pot with a bowl to get a filled bowl of stew.
* Right-click on a cooking pot with a **flask** to add the equivalent of one bowl of stew to the flask.

### Cooking pot: Mixing

* The cooking pot takes an **average** of the hunger and saturation of all food items added.
* Adding food that gives an effect (e.g. rotten flesh, suspicious stew etc) has a chance to **taint** the entire stew, giving you that effect for every bowl taken.

### Cooking pot: Misc

* As you take food from the cooking pot, the level of the stew in the pot visually decreases
* Adding food to the bot visually increases the level of the stew.
* Extinguishing the fire means you can no longer add food to the pot, but you can still take contents.  Restoring the fire allows you to add food again.
* Once a pot is completely empty (the last bowl of stew is taken), you have to add water to add more food.
* Breaking a pot does **not** lose its contents.



## Flasks
Crafted with leather and copper (TBC).
Inspired by bundles.

* A **flask** holds liquids **or** food (in the form of stew).
* It stores the equivalent of 64 potion/water bottles **or** 64 bowls of stew.
* Right-click and hold a flask to consume the equivalent of one bottle or bowl of the flask contents.
* When the flask is depleted, it does not expire.



## Barometer
Crafted with copper and quartz like a clock.
```
 C
CQC
 C
```

* Allows the player to determine the weather change.  Shows animation like the clock but depends on weather ticks instead.
* Maximum point of clear weather moves the barometer to the right.
* Maximum point of stormy weather moves the barometer to the left.



### Quadrant
Crafted like:
```
  C
 CC
C C
```
where `C` is copper ingot.

* Hold in off-hand.
* Remembers the cardinal direction (NESW) that the player was looking when they first moved it to their off-hand.
* All placed blocks with rotation will face the direction of the quadrant, instead of the player's facing direction, while held.



## Wind chimes
Crafted with copper somehow, I'm not sure what the recipe is.

* Wind chimes hang similar to lanterns.
* When a mob or player passes under them, they activate.
* Checks the weather ticks, and every X ticks will ring with increasing volume and sound complexity until the weather changes.
* Projectile impact causes them to activate.
* When they ring they emit a redstone signal.

Recipe could be wood planks and copper.

PPP
C C
C C


