# Lightcaster Studios Site

Website for project documentation etc.

## Contributing

To contribute...
1. Ensure you have Ruby installed
2. Ensure you have Jekyll installed, [follow the instructions in Jekyll docs](https://jekyllrb.com/docs/)
3. Clone this repo, ensure you're on another branch
4. Run `bundle install` to install gems
5. Run `bundle exec jekyll s` and site will be hosted on `localhost:4000`

### Creating Pages

All names of `.md` files in the root directory correspond to the name of their links, e.g. For the page `/beamerman`, the file to edit the contents of the page are at `/beamerman.md` in this directory. For the page `beamerman/how-to-play`, the contents of the page are at `beamerman/how-to-play.md`.

If you want to create a new link, e.g. `/beamerman/about`, create a new `.md` file at `/beamerman/`.


# How to Play

The objective of the game is to defeat your opponents, collect powerups & avoid lasers (including your own)! 
To win the game, be the last one standing!

## Basic Controls

`W` `S` `A` `D`, to move Up, down, left & right.
[Movement Gif]

Press `Spacebar` to place down a drone. After a few seconds, the drone will fire a laser!
[Drone Firing Gif]

Be sure to move out of the way before the drone fires, else, you will get hit!
When you get hit, your character will flash rapidly and becomes invulnerable for a short while.

[Self harm gif]


## HUD
At the corners of the screen you can see each players' information.

[Picture of HUD explaining each stuff]

When your health reaches zero, you're out of the game, so be careful!


## Obstacles
These are common obstacles you'll encounter throughout the game. 

***Mirrors***
Diagonal mirrors comes on multiple forms. They strafe your shots 90 degrees.

[Pictures of diag mirrors]
[reflect gif]

Horizontal mirrors bounce your shots back to where you fired. Be careful!

[picture of hor mirror][reflect]

***Prisms***
Splits your laser into a 3 way splatter of doom!
[Picture of Prism][refract]

***Crates***
These obstacles can be destroy and you may potentially find a useful powerup!
[picture of crates][destroy crates]


## Power Ups
Power-ups are strong items that can turn the tide of the battle if played right!
There are 2 types of power-ups in this game: Temporary & Permanent powerups. 

### Temporary
Grants the player a short term advantage.

**_Temp Armor_**
[animation][in action]
The most basic armor. Protects players from a single hit. Last for a short while.

**_Glass Armor_**
[animation][in action]
This armour enables laser shots to pass through the player!

**_Mirror Armor_**
[animation][in action]
This armour bounce laser shots back where it came from!



### Permanent
Permanent increases the player's stats in one aspect.

**_Drone Count_**
Increase the number of drones you can place simultaneously at a time.
With fast reaction time and proper placement you can drown your opponents with an insane barrage of lasers!! 

**_Reflect Level_**
Increase the number of times your laser can reflect/refract off mirrors and prism.
[ref level]
[reflect spam gif]

**_Range_**
Increase the range of your laser. Pick off your rivals from far!
[range]

**_Speed_**
Increase your walking speed. Dodge or rush down your opponent with your ferocious speed!
[speed]



### Editing Layout

This site is styled using [bulma](https://bulma.io/documentation/), to change page styles, please read the docs.

### Credits

Theme is WhatATheme by [thedevslot](https://github.com/thedevslot/WhatATheme) 
