```metadata
title: Weapons & Combat
description: ''
tags: ''
systems: []
renderer: legacy

```

<img src='https://i.imgur.com/QrkLez3.jpg' style='position:absolute; top:0px; left:0px; width: 850px' />
<img src='https://i.imgur.com/BjjBtUZ.png' style='position:absolute; top:435px; left: -100px; width: 1000px' />


<style>
  
  .footer {
  	--lines:1;
  	text-align:center;
  	position:absolute;
  	bottom:0px;
  	left:0px;
  	width:100%;
  	height:25px;
  	line-height:.9em;
  	padding-top:calc(6px / var(--lines));
  	color:#c9ad6a;
  	font-family:'nodesto';
  	font-variant:all-small-caps;
  	font-size:calc(1em - calc(.1em * var(--lines)));
  	z-index:205;
  }
  
  .footer a {
  	color:#c9ad6a;
  }
  
  .icons img {
  	position:relative;
  	width:10px;
  	margin-right:3px;
  	margin-left:3px;
  	top:1px;
    opacity:25%
  }
  

  
</style>


<style>
    #p1.phb h1{
        color: ;
	  		font-family: 'cormorant scc';
  			font-size: 70px;
				color: White;
    }
</style>
<style>
    #p1.phb h5{
        color: white;
    }
</style>

<style>
  .phb#p1{ text-align:center; }
  .phb#p1:after{ display:none; }
</style>

<div style='margin-top:800px;'></div>

# Weapons & Combat


<div class='wide'>
##### A Redux of the Weapons and Combat Rules of DnD 5e
</div>
\page

<style>
  .toc a {
    color: inherit !important;	
  }

  .toc li span:nth-child(2){	
    width: auto;
    overflow: hidden;
    white-space: nowrap;
    display: block;
  }

  .toc li span:nth-child(2):after{
    font-family		: BookSanity;	
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    content:
      " ........................................"
      "........................................."
      "........................................."; 
  }
  
  .toc li span:first-child{
    float: right;
    font-family		: BookSanity;	
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    margin-left		: 1px;	
  }
  
/*Special cases for headings*/    
  .toc li h3 span:nth-child(2):after{
  	content: " ";						
  }
  
  .toc li h3 {
    margin-bottom: 4px !important;		
    margin-top: 10px !important;
    line-height: initial !important;	
  }
  
  .toc li h3 span:first-child{
  	line-height: 1.8em !important;  	
  }
  
  .toc ul ul {
  	margin-left: 10px !important;		
  }
  
  .toc>ul>li {
    margin-bottom: initial !important;
  }
</style>

<div class='wide' style="text-align: center">
# Contents
</div>

<div class='toc'>
- ### [<span>1</span><span>Changes to Combat</span>](#p3)
 - #### [<span>1</span><span>**Strength Vs Dexterity**</span>](#p3)
	 - [<span>1</span><span>Weapon Attacks Table</span>](#p3)
 - #### [<span>1</span><span>**Fighting with Two Weapons**</span>](#p3)
 - #### [<span>1</span><span>**Ammunition**</span>](#p3)
	- [<span>1</span><span>Ammunition Table</span>](#p3)
 - #### [<span>1</span><span>**Grapple & Shove**</span>](#p3)
 - #### [<span>2</span><span>**Other Actions in Combat**</span>](#p4)
 - #### [<span>2</span><span>**Free Item Interaction**</span>](#p4)
	
	
- ### [<span>3</span><span>**Updated Weapons**</span>](#p5)
 - #### [<span>3</span><span>**Weapon Changes**</span>](#p5)
 - #### [<span>3</span><span>**Advanced Weapons**</span>](#p5)
 - #### [<span>3</span><span>**Firearms**</span>](#p5)
 - #### [<span>4</span><span>**Weapon Tables**</span>](#p6)
  	- [<span>4</span><span>Simple Melee Weapons</span>](#p6)
 	 - [<span>4</span><span>Simple Ranged Weapons</span>](#p6)
 	 - [<span>4</span><span>Martial Melee Weapons</span>](#p6)
 	 - [<span>5</span><span>Martial Ranged Weapons</span>](#p7)
  	- [<span>5</span><span>Advanced Weapons</span>](#p7)
  	- [<span>5</span><span>Firearms and Explosives</span>](#p7)
 - #### [<span>6</span><span>**Special Weapons**</span>](#p8)
	
	
- ### [<span>7</span><span>**Updated Feats**</span>](#p9)
 - #### [<span>7</span><span>**Athlete - CQC**</span>](#p9)
 - #### [<span>8</span><span>**Defensive Duelist - Loading Expert**</span>](#p10)
 - #### [<span>9</span><span>**Mage Slayer - Sharpshooter**</span>](#p11)
 - #### [<span>10</span><span>**Shield Master - Tavern Brawler**</span>](#p12)
	

- ### [<span>11</span><span>**Updated Fighting Styles**</span>](#p13)
 - #### [<span>11</span><span>**Dueling - Versatile**</span>](#p13)
</div>

```
```



### Formatting
This Homebrew was made using Homebrewery. Help with formating and finer details were done thanks in part to the guide by  [/u/AeronDrake](https://www.reddit.com/user/AeronDrake/). Footnote formating addition was originally made by [/u/Gazook89](https://www.reddit.com/user/Gazook89/). The watercolor stain pages were created by [/u/flamableconcrete](https://www.reddit.com/user/flamableconcrete/).

### Inspiration
In the process of making this compendium, inspiriation was taken by youtuber [Bob World Builder](https://www.youtube.com/c/BobWorldBuilder), in his pursuit to revamp the weapon system of DnD5e. 

### Art
The art in this compendium is taken from the cards of Wizards of the Coast's Magic: The Gathering trading card game. Each art piece has the card name and artist tagged. The banner used in the title page is taken from PNGwing.com.

### Foreword
The combat of 5e at times feels like it was made for rules that were never released in the finish product or expanded upon with expansions. The weapons sometimes have no mechanical difference except the name, and the damage types of the weapons are usally lumped together when it comes to resistances and immunites by the majority of monsters. Outside of hitting an enemy with a weapon, there are very few avenues for actions in combat baked into the game. The contested actions like Grapple and Shove were written to be the starting point but were never expanded upon.

This compendium was intended to expand on the overlooked rules like contested actions, as well as update the martial feats and fighting styles. Additonally, the weapon system was made more concise, as well as reworking some of the mechanuics surrounding weapons like ammunition.



<div class='pageNumber'>i</div>
<div class='footnote'>Table of Contents| Foreword</div>
<div class='footer icons'>
  This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
# Changes to Combat

### Strength Vs Dexterity
Between the martial ability scores Dexterity and Strength, Dexterity is heavily favored in 5e. Aside from both functioning the same to weapon attacks and damage, Dexterity factors into AC, Initative, and the Dexterity Saving Throw is the more common save of the two. To balance this, there should be a trade off to these benefits, here is my proposed solution:

When using your Dexterity Modifier for a weapon attack, you only add half your Dexterity Modifier rounded up, unless it's negative, if you have proficiency with that weapon. If you do not have proficiency, you do not add your Dexterity Modifier to the damage roll unless it's negative. This is summed up in the tables below. This change does not apply to the monk's Martial Arts.

<div class='classTable'>
##### Weapon Attacks
| Modifier | Attack |Damage|
|:---|:---:|:---:|
| *No Proficiency*| |  | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Strength| Str Mod | Dice + Mod | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dexterity| Dex Mod | Dice + (-Mod) | 
| *With Proficiency*|  |  |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Strength| Str Mod + PB | Dice + Mod | 
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dexterity| Dex Mod + PB |Dice + 1/2 Mod| 
</div>


### Fighting with Two Weapons
There is a difference between two weapon fighting, not to be confused with the fighting style Two-Weapon Fighting, and fighting with two weapons. When taking the Attack action, you can choose what weapons the attack is coming from if you are wielding more than one weapon. If you can take multiple attacks with the Attack action, you can choose what weapon each attack is coming from. Weapons with the thrown property can be thrown instead of making a melee attack with them.

Two weapon fighting is when you use the lighter weight of some weapons to make more attacks than you normally could. When you take the Attack action using two weapons with the light property, you can use your bonus action to make off hand attacks with the weapons you are wielding that have the light property. The number of attacks made with this bonus action is equal to half the number of attacks you can make with your Attack action, rounded up. You do not add your ability modifier to the damage with these bonus action attacks unless they are negative. Weapons with the thrown property can be thrown instead of making of a melee attack with them.

```
```

### Ammunition
Keeping track of ammunition is something that most groups do not do. It is too time consuming or is forgotten to the point of playing without it. A more abstract option that still requires some resource management is provided below:

A container of ammunition for your ranged weapon has a number of uses. When an encounter lasts a number of rounds greater than your Proficiency Bonus, one use of your container is expeneded at the end of the encounter. If you begin an encounter with only one use left in your container, rolling a natural 1 on an attack roll or being hit by a natural 20 attack roll means you have run out of ammunition. Weapons like the Alacránillo, Blunderbuss, and Hand Mortar expend one use each time they are fired.

<div class='classTable'>
##### Ammunition
| Contianer | Weapons | Cost | Weight| Uses|
|:---|---:|---:|---:|---:|
| Bandolier| Alacránillo | 1 gp | 5 lb | 10 | 
| Canister| Blowgun | 1 sp | 1 lb | 20 |
| Cartridge Box| All Firearms | 10 gp | 3 lb | 5 |
| Case | All Crossbows | 3 gp | 3 lb | 10 |
| Quiver | All Bows| 2 gp | 2 lb | 10 |
| Pouch| Sling | 1 sp | 2 lb | 15 |
</div>

At the DM's discretion, ammunition may be able to be scaveneged after an encounter from slain enemies. Making an Investigation check, after 5 minutes, ammunition is found to replenish a number of uses. The DC for the check, what kind of ammunition is found, and how many uses are replenished is determined by the DM.

### Grapple & Shove
Both the Shove and Grapple action must be done to a creature withing 5 feet of you unless your reach is augmented by a racial or class trait like the Bugbear's Long Limbs.

In addition to the other grappling rules, a creature grappled by two seperate creatures is instead restrained. The two grappling creatures are still considered grappling the target creature. A creature that can grapple more than two creatures, can restrain a creature by itself, making two seperate successful grapple checks.


<div class='pageNumber'>1</div>
<div class='footnote'>PART 1 | Combat Changes</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>

\page

### Other Actions in Combat
###### **Destroy Cover**
Using the Attack action, you can make a special melee weapon attack to reduce the benefit a creature gains from cover. If you’re able to make multiple attacks with the Attack action, this attack replaces one of them. 

Your weapon must do either slashing or bludgeoning damage, and the cover must be made of a material able to be damaged by your weapon (ex: brick for bludgeoning, tree roots for slashing). Instead of making an attack roll, you make a Strength (Athletics) check, the DC determined by the DM. On a success, you reduce the benefit of the cover by one size category (Full Cover > Three-Quarters Cover > Half Cover > No Cover). The DM can determine if this attack can target other structures like breaking open locked doors, creating entrances in walls, or structural pillars for collapsing tunnels for example.

###### **Disarm**
Using the Attack action, you can make a special melee attack to disarm a creature of an item they are wielding such as a weapon, shield, or spellcasting focus. If you’re able to make multiple attacks with the Attack action, this attack replaces one of them. Additionally, if your reach is extended by a weapon or other ability, it applies to this action too.

The target must be no more than one size larger than you and must be within your reach. Instead of making an attack roll, you make a Strength (Athletics) or Dexterity (Sleight of Hand) check (your choice) contested by the target’s Strength (Athletics) or Dexterity (Sleight of Hand) check (the target chooses the ability to use). If you succeed, they lose control of the item and it lands on the ground a number of feet equal to 5 times your Proficiency Bonus.

###### **Restrict**
Using your reaction, you can make a special melee attack in response to creature trying to make an attack or cast a spell.

The target must be within 5 feet of you and no more than one size larger than you. Instead of making an attack roll, you make a Strength (Athletics) or Dexterity (Sleight of Hand) check (your choice) contested by the target’s Strength (Athletics) or Dexterity (Sleight of Hand) check (the target chooses the ability to use). If you succeed, the next attack roll the target makes is at disadvantage, or any creature forced to make a saving throw does so at advantage.

###### **Shield Bash**
Using a shield, you can take the Shove attack as a bonus action to a creature within 5 feet of you.

###### **Stumble**
Using the Attack of Oppurtunity reaction, you can make a special melee attack to slow a creature's movement speed.

The target must be no more than one size larger than you and must be within your Reach. Instead of making an attack roll, you make a Strength (Athletics) check contested by the target’s Strength (Athletics) or Dexterity (Acrobatics) check (the target chooses the ability to use). If you succeed, the creature's movement is reduced by 10 feet.


```
```
###### **Take Item**
Using the Attack action, you can make a special melee attack to take an item a creature is wielding such as a weapon, shield, or spellcasting focus. If you’re able to make multiple attacks with the Attack action, this attack replaces one of them. 

The target must be no more than one size larger than you and must be within your Reach. Instead of making an attack roll, you make a Strength (Athletics) check contested by the target’s Strength (Athletics) or Dexterity (Sleight of Hand) check (the target chooses the ability to use). You succeed automatically if the target is incapacitated. If you succeed, they lose control of the item and you now wield the item. You must have an open hand to wield the item, otherwise you decide what item you are currently wielding to drop in order to wield the taken item.

### Free Item Interaction
There are many actions that can be taken during combat that have no mechanical translation and are purely flavor text. Such actions include scarfing down food or chugging some ale, opening unlocked doors when moving or removing a cloak. Any number of these interactions (within reason) can be done at no expense. For interactions that do have mechanical weight to them, you have one Free Item Interaction which can do the following:

* Pick up an item not being worn or carried or from a willing creature.

* Trigger an automatic mechanism like the pressure plate of a trap or saying the command word for a magical trap.

* Locking or unlocking a door, chest, or other item with a lock.

* Hand an item to another willing creature.

* Toss an item a number of feet equal to 5 times your Strength Modifier (minimum of 5).

* Draw or swap one item such as a sword, shield, or spellcasting focus.

Trying to do another Free Item Interaction requires a bonus action or action, a third Free Item Interaction requires and action.

<div class='pageNumber'>2</div>
<div class='footnote'>PART 1 | Combat Changes</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
<div style='margin-top:310px'></div>

<img src='https://scentofagamer.files.wordpress.com/2019/09/scottmurphy_ancestralblade.jpg' style='position:absolute; top:-10px; left:0px; width: 850px' />
<img src='https://watercolors.giantsoup.com/phb/phb_top/0009.png' style='position:absolute; top: 0px; left:0px; width: px' />

<div class='artist' style='top:210px;right:20px;color:white;'>
##### Ancestral Blade
Scott Murphy
</div>

# Updated Weapons
### Weapon Changes
Each weapon in the tables following have been made so to be mechanically distinct. Therefore some weapons have been removed and other have become archetypes that are catch-alls, these being the Ancillary and the Weapon-of-War. Each can do either bludgeoning, piercing, or slashing damage, but the choice is made when the weapon is first chosen and cannot be changed thereafter. The following properties have also been changed or added:
___
**Heavy.** A Small creature's speed is reduced by 5 feet while wielding a heavy weapon, and a Tiny creature additionally has disadvantage on attack rolls with heavy weapons.
___
**Loading.** Because of the time it takes to load this single-shot weapon, it can only fire once when an action, bonus action, or reaction is used to fire it. It takes an action to reload this weapon.
___
**Reload.** This weapon can be fired a number of times equal to its reload score before requiring an action to reload.
___
**Seige.** This weapon gives advantage to checks made to Destroy Cover.
___
**Silent.** Due to its stealthy nature, attacks made with this weapon do not reveal your location if you are hidden from the target, only your presence.

### Advanced Weapons
Just like how there are non magical armors that cannot be starting equipment, there should be weapons that are not starting equiptment but instead have to be earned by some other means. Advanced weapons are improved versions of other martial weapons.

These weapons come with the prequisite of having atleast a 15 in one of your ability scores or your attacks with that weapon are made at disdvantage. For Dexterity based weapons (Alacránillo and Warbow), you need atleast a 15 in Strength. For Strength based weapons (Atlatl and Greatsword), you need atleast a 15 in Dexterity. Weapons with the Finesse property (Swordstaff) need a 15 in both Strength and Dexterity.

### Firearms
The issue with executing firearms in DnD is giving them the mechanics to feel as powerful as they should be but not overpowered enough to make other options obsolete. Here are the changes to weapon properties for adding firearms:

___
**Damage.** Firearms that require an attack roll do not use your modifier for the damage roll. Instead, they have their own modifier, shown in the Firearms and Explosives chart.

Certain Firearms, as well as all explosives, have two damages shown. These firearms do not require an attack roll but instead subject creatures in range to make a Dexterity Saving Throw. the first damage is automatic damage that cannot be avoided. The second damage a creature takes on a failed save, half as much on a successful one. The DC is equal to 8 + your PB + your Dexterity modifier.
___
**Range.** Certian firearms and all explosives have an area for thier second range value. Like a spell, the weapon's first range value indicates how far the origin of the damage can be and the second shows the area that is effected by the damage.
___
**Heavy.** Instead of imposing disadvantage, when a creature sized Small or Tiny attacks with this heavy weapon, they must make a DC 15 Strength Saving Throw or be knocked Prone.

<div class='pageNumber'>3</div>
<div class='footnote'>PART 2 | Updated Weapons</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
# Weapon Tables

<div style='margin-top:0px'></div>
<div class='classTable wide'>
#### Simple Melee Weapons
| Name | cost | Damage | Weight | Properties |
|:---:|:---:|:---:|:---:|:---:|:---|
|Ancillary|1 gp| 1d4 b/p/s| 1 lb|finesse, light, thrown (range 20/60)|
|Javelin|5 sp| 1d6 piercing| 2 lb|light, thrown (range 40/120)|
|Mace|5 gp| 1d6 bludgeonig| 6 lb|heavy, siege, versatile (1d8)|
|Quarter Staff|2 sp| 1d6 bludgeonig| 2 lb|special, versatile (1d8)|
|Spear|1 gp| 1d6 piercing| 3 lb|thrown (range 20/60), versatile (1d8)|
</div>
<div class='classTable wide'>
#### Simple Ranged Weapons
| Name | cost | Damage | Weight | Properties |
|:---:|:---:|:---:|:---:|:---:|:---|
|Blowgun|2 gp| 1 piercing| 1 lb|ammunition (range 25/100), finesse, silent, special|
|Crossbow, Light|25 gp| 1d10 piercing| 6 lb|ammunition (range 80/320), loading, two-handed|
|Dart|5 cp| 1d4 piercing| 1/4 lb|finesse, light, thrown (range 30/60)|
|Shortbow|25 gp| 1d6 piercing| 2 lb|ammunition (range 80/320), two-handed|
</div>
<div class='classTable wide'>
#### Martial Melee Weapons
| Name | cost | Damage | Weight | Properties |
|:---:|:---:|:---:|:---:|:---:|:---|
|Bastard Sword|50 gp| 3d4 slashing| 7 lb|heavy, two-handed|
|Dane Axe|20 gp| 2d6 slashing| 6 lb|heavy, two-handed|
|Flail|10 gp| 1d8 bludgeoning| 2 lb|special|
|Halberd|20 gp| 1d10 slashing| 8 lb|heavy, reach, two-handed, special|
|Lance|10 gp| 1d12 piercing| 6 lb|reach, special, two-handed|
|Maul|10 gp| 1d12 bludgeoning| 10 lb|heavy, two-handed, siege|
|Rapier|25 gp| 1d8 piercing| 2 lb|finesse, special|
|Shortsword|15 gp| 1d6 slashing| 2 lb|finesse, light|
|Trident|5 gp| 1d6 piercing| 4 lb|thrown (range 20/60), versatile (1d8), special|
|Twin Scimitar|25 gp| 2d4 slashing| 6 lb|finesse, heavy, two-handed, special|
|Weapon of War|20 gp| 1d8 b/p/s| 3 lb|versatile (1d10)|
|Whip|3 gp| 1d4 slashing| 3 lb|finesse, reach, special|
</div>

<div class='pageNumber'>4</div>
<div class='footnote'>PART 2 | Updated Weapons</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
# Weapon Tables Cont.
<div style='margin-top:0px'></div>
<div class='classTable wide'>
#### Martial Ranged Weapons
| Name | cost | Damage | Weight | Properties |
|:---:|:---:|:---:|:---:|:---:|:---|
|Crossbow, Hand|75 gp| 1d8 piercing| 4 lb|ammunition (range 30/120), light, loading|
|Crossbow, Heavy|50 gp| 1d12 piercing| 18 lb|ammunition (range 100/400), heavy, loading, two-handed|
|Longbow|40 gp| 1d8 piercing| 3 lb|ammunition (range 150/600), heavy, two-handed|
|Net|2 gp| -| 3 lb| special, thrown (range 10/15)|
|Sling|1 sp| 1d6 bludgeonig| - |ammunition (range 30/120), finesse, silent|
</div>
<div class='classTable wide'>
#### Advanced Weapons
| Name | cost | Damage | Weight | Properties |
|:---:|:---:|:---:|:---:|:---:|:---|
|Alacránillo|100 gp| - | 40 lb|ammunition (range 300/900), special|
|Atlatl|3 gp| - | 1 lb|special, thrown (range 90/150)|
|Greatsword|120 gp| 3d6 slashing| 9 lb|heavy, siege, two-handed|
|Swordstaff|70 gp| 3d4 s/p| 5 lb|finesse, heavy, two-handed, reach, special|
|Warbow|90 gp| 2d8 piercing| 7 lb|ammunition (range 300/750), heavy, two-handed|
</div>
<div class='classTable wide'>
#### Firearms and Explosives
| Name | cost | Damage | Weight | Properties |
|:---:|:---:|:---:|:---:|:---:|:---|
|Blunderbuss|600 gp| - /2d8 piercing| 9 lb|ammunition (range self/15 ft cone), heavy, reload (1), two-handed|
|Grenade|150 gp| 1d8 thunder/3d6 piercing| 1 lb|range (20/15 ft cube), special|
|Hand Mortar|1200 gp| 1d6 thunder/2d8 piercing| 25 lb|ammunition (range 60/10 ft cube), heavy, reload (1),  two-handed|
|Harmonica Rifle|900 gp| 1d10+5 piercing| 10 lb|ammunition (range 250/500), heavy, reload (5), two-handed|
|Musket|700 gp| 2d6+6 piercing| 12 lb|ammunition (range 300/500), heavy, loading, two-handed|
|Pepperbox|400 gp| 1d8+3 piercing| 4 lb|ammunition (range 150/300), reload (6)|
|Pistol|300 gp| 2d4+4 piercing| 3 lb| ammunition (range 200/300), loading, light|
</div>


<div class='pageNumber'>5</div>
<div class='footnote'>PART 2 | Updated Weapons</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
<img src='https://i.pinimg.com/originals/d5/28/6b/d5286ba960f5e6a5e2c3af75ebd27c73.png' style='position:absolute; top: 500px; left:0px; width: 850px' />
<img src='https://watercolors.giantsoup.com/phb/phb_bottom/0025.png' style='position:absolute; top: 0px; left:0px; width: 0 px' />

<div class='artist' style='top:950px;right:120px;color:white;'>
##### Jousting Lance
Alayna Danner
</div>

### Special Weapons
Weapons with special rules are described here:
___
* **Alacránillo.** This large crossbow has the same properties as the heavy crossbow in addition to the ones listed for this weapon. It uses darts as ammunition. A dart fired this ways does an additional 2d10 damage. If a creature gives you the Help action to attack with this weapon, it loses the Loading property.

* **Atlatl.** This weapon itself is not thrown but instead is used to throw javelins, having the same properties in addition to the ones listed for this weapon. A javelin thrown this way does an additional 1d10 damage. 

* **Blowgun.** When coating ammunition for this weapon with poison or other substances, you can coat twice as many pieces of ammuniton than normal.

* **Flail.** This weapon ignores the AC bonus of shields. Additionally, this weapon can be used for making a Grapple attack. This weapon's damage die becomes a d6 if grappling with it.

* **Greanade.** A creature that is in the same 5 foot space that the grenade is in when it explodes has disadvantage on the Dextertity Saving Throw.

* **Halberd.** This weapon can be used for making a Shove attack. The Reach property applies to this attack.

* **Lance.** Attacks with this weapon are made at disadvantage when attacking a target withing 5 feet of you. When mounted, the damage dice of this weapon becomes 2d6, it loses the Two-handed property, and it gains the Finesse property.


```
```
___
* **Net.** A Large or smaller creature hit by a net is restrained until it is freed. A net has no effect on creatures that are formless. A creature can use its action to make a DC 10 Strength check, freeing itself or another creature within its reach on a success. Dealing 5 slashing damage to the net (AC 10) also frees the creature without harming it, ending the effect and destroying the net. Attack a creature withing 5 feet with a net can be done as a melee weapon attack.

* **Quarter Staff.** While you are not using the versatile property of this weapon, it has the reach property.

* **Rapier.** You can engage in two weapon fighting provided that the other weapon you are wielding is the Ancillary. When you are wielding this weapon in one hand and no other weapons or shields, the damage of this weapon becomes 2d4.

* **Swordstaff.** This weapon can do either slashing or piercing damage, the choice is made when the attack is made. Once per turn, if you miss an attack against a creature, you can make another attack against another creature in reach of you, the damage type of this weapon switches with this attack.

* **Trident.** You deal an extra 1d4 damage with this weapon if the target is grappled, incapacitated, or restrained.

* **Twin Scimitar.** When you take the Attack action, you can make one atttack as a bonus action. This attack's damage dice is 1d6 instead of 2d4.

* **Whip.** This weapon can be used for making a Grapple or Shove attack. The finesse and reach properties apply to this attack. If using Dexterity for this attack, a Slight of Hand check is used instead of Athletics. This weapon cannot do damage if grappling with it.

<div class='pageNumber'>6</div>
<div class='footnote'>PART 2 | Updated Weapons</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
<img src='https://i.imgur.com/3TvYTpR.jpg' style='position:absolute; top: 0px; left:9-px; width: px' />
<img src='https://watercolors.giantsoup.com/phb/phb_right/0001.png' style='position:absolute; top:0px; left:-15px; width: px' />

<div class='artist' style='top:100px;right:50px;color:white;'>
##### Knight Token
Dan Scott
</div>

# Updated Feats

### Athlete
* You gain proficiency in the Athletics skill, if you have proficiency in this skill, you get expertise instead.

* Difficult terrain doesn't cost you to move at half speed.

* You gain a climbing and swimming speed equal to your walking speed.

* When you take the Dash action, you can move an additional 10 feet.

### Cavalier
Replaces Mounted Combatant
* You have advantage on saving throws made to avoid falling off your mount. Mounting or dismounting a creature costs you only 5 feet of movement.

* You can force an attack targeted at your mount to target you instead. Additionally, if your mount is subjected to an effect that allows it to make a Dexterity Saving Throw to take only half damage, it instead takes no damage if it succeeds on the saving throw, and only half damage if it fails.

* You learn the Find Steed spell, you can cast this spell without expending a spell slot once per long rest. You can also cast this spell using spell slots you have of the appropriate level.


### Charger
* Your movement speed increases by 5 ft.

* If you move at least 10 feet in a straight line immediately before making a melee weapon attack against a creature and the attack hits, the creature must make a Strength Saving Throw with a DC equal to the amount of feet you moved. If they fail, they are either knocked prone or moved 10 feet away from you in a straight line, your choice.

### Close-Quarter-Combatant (CQC)
* Your ranged weapons can now be used to make melee weapon attacks, gaining the finesse property when making a melee weapon attack, and damage die is 1d6. The damage type can be bludgeoning, piercing, or slashing damage; you choose when gaining this feat.

* Being within 5 feet of a hostile creature doesn’t impose disadvantage on your ranged attack rolls if you have succesfully hit a creature with a melee attack this turn.

* When you use the Attack action with only a melee weapon, you can use a bonus action to make one ranged weapon attack with a loaded ranged weapon you can wield in one hand. If you are wielding a shield, your other hand must be empty prior to taking this bonus action.


<div class='pageNumber'>7</div>
<div class='footnote'>PART 3 | Updated Feats</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
<img src='https://i.imgur.com/VH5aMiQ.jpg' style='position:absolute; top:560px; left:0px; width: 850px' />
<img src='https://i.imgur.com/VH5aMiQ.jpg' style='position:absolute; top:640px; left:0px; width: 850px' />
<img src='https://watercolors.giantsoup.com/phb/phb_bottom/0020.png' style='position:absolute; top:-90px; left: 0px; width: 850px' />

<div class='artist' style='top:720px;left:50px;color:white;'>
##### DayBreak Ranger
Steve Prescott
</div>

### Defensive Duelist
* Increase your Strength or Dexterity by 1, to a maximum of 20.

* When you are wielding a weapon in one hand with which you are proficient and another creature hits you with a weapon attack, you can use your reaction to roll one of the damage die of that weapon and add it to your AC for that attack.

### Dual Wielder
* Increase your Strength or Dexterity by 1, to a maximum of 20.

* You gain a +1 bonus to AC while you are wielding a separate melee weapon in each hand.

* You can use two-weapon fighting even when the one-handed melee weapons you are wielding aren't light.

* You can use your free item interaction to swap/draw two weapons instead of one.

### Durable
* Increase your Constitution score by 1, to a maximum of 20.

* Once per turn, when you are hit with an attack you can expend one of your Hit Die and reduce the damage by a roll of your Hit Die + your Constitution modifier (minimum of 2) to a minimum of 0.

* On your turn, if you are Unconcious and rolling Death Saving Throws, you can move up to half your movement speed and are aware of your surroundings.

```
```

### Fighting Initiate
**Prerequisite:** Proficiency with a martial weapon.

* Your martial training has helped you develop a particular style of fighting. As a result, you learn one Fighting Style option of your choice. If you already have a style, the one you choose must be different.

* You can select this feat multiple times. Each time you do so, you must choose a different Fighting Style.

Whenever you reach a level that grants the Ability Score Improvement feature, you can replace this feat’s fighting style with another one from the fighter class that you don’t have.


### Grappler
**Prerequisite:** Strength 13 or higher.
* You have advantage on attack rolls against a creature you are grappling.

* While grappling a creature, you are considered behind half cover from all directions.

* You can use your action to try to pin a creature grappled by you. To do so, make another grapple check. If you succeed, the creature is considered Restrained until the grapple ends.

### Loading Expert
Replaces Gunner and Crossbow Expert.
* Increase your Dexterity score by 1, up to a maximum of 20.

* The Loading property for ranged weapons you are proficient is changed to:
Because of the time it takes to load this single-shot weapon, it can only fire once when an action, bonus action, or reaction is used to fire it. If you have multiple attacks, this only uses one of those attacks.

*  At 8th level, you ignore the Loading property on ranged weapons you are proficicent with.



<div class='pageNumber'>8</div>
<div class='footnote'>PART 3 | Updated Feats</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
### Mage Slayer
* When you damage a creature that is concentrating on a spell, that creature has disadvantage on the saving throw it makes to maintain its concentration.

* When a creature in your Reach or Range casts a spell, you can use your reaction to make one weapon attack before the spell is cast.

* When you use your reaction to hit a creature attempting to cast a spell and hit, you can roll a d20. If the roll is equal to or higher than 10 + the spell's level (cantrips count as 1), the spell fizzles out before it is cast. You can use this ability 3 times per long rest.

### Martial Adept
* You learn two maneuvers of your choice from among those available to the Battle Master archetype. If a maneuver you use requires your target to make a saving throw to resist the maneuver’s effects, the saving throw DC equals 8 + your proficiency bonus + your Strength or Dexterity modifier (your choice).

* You gain one superiority die, which is a d8 (this die is added to any superiority dice you have from another source). This die is used to fuel your maneuvers. A superiority die is expended when you use it. You regain your expended superiority dice when you finish a short or long rest. At 10th level this die becomes a d10, and at 18th level it becomes a d12.

### Master-at-Arms
Replaces Weapon Master and Lightly, Moderately, and Heavily Armored.
* Increase your Strength, Dexterity, or Constitution score by 1, to a maximum of 20.

* You gain proficiency with shields and your choice of light, medium, or heavy armor.

* You gain proficiency with four weapons of your choice. Each one must be a simple or a martial weapon.

Whenever you reach a level that grants the Ability Score Improvement feature, you can replace your armor and weapon proficiencies with the other weapon and armor options you do not have proficiency with.

### Piercer
* Increase your Strength or Dexterity by 1, to a maximum of 20.

* Once per turn, when you hit a creature with an attack that deals piercing damage, you can add double your proficiency bonus to the damage roll.

* When you score a critical hit that deals piercing damage to a creature, you can roll one additional damage die when determining the extra piercing damage the target takes.
```
```


### Polearm Master
* When you take the Attack action and attack with the halberd, quarterstaff, spear, swordstaff, or trident, you can use a bonus action to make a melee attack with the opposite end of the weapon. This attack uses the same ability modifier as the primary attack. The weapon’s damage die for this attack is a d4, and it deals bludgeoning damage.

* When you take the Shove action while wielding the halberd, quarterstaff, spear, swordstaff, or trident, the attack deals 1d6 bludgeoing damage, regardless if the attack succeeds or not.


### Reload Expert
**Prerequisite:** Must be level 4 or higher.
* Increase your Dexterity score by 1, up to a maximum of 20.

* Reloading a weapon with the Reload property takes an attack or a bonus action.

* At 8th level, reloading a weapon with the reload property takes only a Free Item Interaction or one attack.


### Savage Attacker
* When you roll damage for a weapon attack, you can reroll the weapon's damage dice and use either roll.

* When you miss a weapon attack against a creature, you can use your reaction to make one weapon attack against that creature.

### Sentinel
* Creatures provoke opportunity attacks from you even if they take the disengage action before leaving your reach.

* Creatures provoke opportunity attacks when they enter your Reach.

* You can make a Grapple attack instead of a normal weapon attack when making an Attack of Oppurtunity.

### Sharpshooter
* Attacking at long range doesn't impose disadvantage on your ranged weapon attack rolls.

* Your ranged weapon attacks ignore half cover and three-quarters cover.

* Before making a ranged weapon attack with a weapon that you are proficient with, you can choose to take a -5 penalty to the attack roll. If the attack hits, you add +10 to the attack's damage.

<div class='pageNumber'>9</div>
<div class='footnote'>PART 3 | Updated Feats</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
<img src='https://i.imgur.com/1JafNYw.jpg' style='position:absolute; top: 0px; left:-5px; width: 1450px' />
<img src='https://i.imgur.com/0SktrK7.jpg' style='position:absolute; top: 0px; left: 160px; width: 850px' />
<img src='https://watercolors.giantsoup.com/phb/phb_right/0001.png' style='position:absolute; top:0px; left:-40px; width: px' />

<div class='artist' style='top:130px;right:20px;color:white;'>
##### Theros Soldier Token
Kimonas Theodossiou
</div>

### Shield Master
* While wilding a shield, the Shove attack dealsl 1d6 bludgeoning damage regardless of it succeeds or not.

* If you aren't incapacitated, you can add your shield's AC bonus to any Dexterity saving throw you make against a spell or other harmful effect.

* If you are subjected to an effect that allows you to make a Dexterity saving throw to take only half damage, you can use your reaction to take no damage if you succeed on the saving throw, interposing your shield between yourself and the source of the effect.

### Skulker
* You can try to hide when you are lightly obscured from the creature from which you are hiding.

* All ranged weapons have the silent property, this property applies to ranged weapon attacks with thrown weapons.

* Dim light doesn't impose disadvantage on your Wisdom (Perception) checks relying on sight.

### Slasher
* Increase your Strength or Dexterity by 1, to a maximum of 20.

* Once per turn when you hit a creature with an attack that deals slashing damage, the creature's next attack roll takes a penalty equal to your proficency bonus.

* When you score a critical hit that deals slashing damage to a creature, you grievously wound it. Until the start of your next turn, the target has disadvantage on all attack rolls.


### Tavern Brawler
* You are proficient with improvised weapons. Improvised weapons that don't resemble any weapon now deal 1d6 damage and have a thrown range of 40/80 as well as the Light property. The ranged attack also deals 1d6.

* Your unarmed strike deal bludgeoning damage equal to 1d8 + your Strength Modifier.

* When you hit a creature with an unarmed strike or an improvised weapon on your turn, you can make a shove or grapple attack as a free object interaction.

* you can make a Shove attack instead of a normal weapon attack when making an Attack of Oppurtunity.

<div class='pageNumber'>10</div>
<div class='footnote'>PART 3 | Updated Feats</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>
\page
<img src='https://i.imgur.com/YfuTeWq.jpg' style='position:absolute; top: 540px; left: -35px; width: 850px' />
<img src='https://i.imgur.com/YfuTeWq.jpg' style='position:absolute; top: 640px; left: -35px; width: 850px' />
<img src='https://i.imgur.com/TVCOMx6.png' style='position:absolute; top: 0px; left:0px; width: 850px' />

<div class='artist' style='top:700px;left:20px;color:white;'>
##### Mentor of the Meek
Jana Schirmer & Johannes Voss
</div>


# Updated Fighting Styles

### Dueling
While you are wielding a melee weapon that does not have the two-handed property and no other weapons, you gain a +2 bonus to damage rolls with that weapon.

### Great Weapon Fighting
When you roll a 1 on a damage die for an attack you make with a melee weapon that you are wielding with two hands, you can reroll the die and must use the new roll. The weapon must have the two-handed or versatile property for you to gain this benefit.

At the beginning of your turn, you can choose to get a +2 to attack rolls with melee weapons that have the versatile or two-handed property. If you do, you can only move up to have your normal speed until the end of your turn.

### Interception
When a creature you can see within Reach of you is the target of an attack or attacks another creature other than you, you can use your reaction to reduce the damage of the attack by 1d10 + your proficiency bonus (to a minimum of 0 damage). You must be wielding a shield or a simple or martial weapon to use this reaction.

### Protection
When a creature within Reach of you is the target of an attack or attacks another creature other than you, you can use your reaction to make one weapon attack against the attacking creature. The attacking creature must be within your Reach or the Range of your weapon. 

```
```
### Pugilist
Replaces Unarmed Fighting.

Your unarmed strikes can deal bludgeoning damage equal to 1d6 + your Strength modifier on a hit. If you aren’t wielding any weapons or a shield when you make the attack roll, the d6 becomes 2d4.

At the start of each of your turns, you can deal 1d4 bludgeoning damage to one creature grappled by you.

### Superior Technique
You learn one maneuver of your choice from among those available to the Battle Master archetype. If a maneuver you use requires your target to make a saving throw to resist the maneuver’s effects, the saving throw DC equals 8 + your proficiency bonus + your Strength or Dexterity modifier (your choice).

You gain one superiority die, which is a d8 (this die is added to any superiority dice you have from another source). This die is used to fuel your maneuvers. A superiority die is expended when you use it. You regain your expended superiority dice when you finish a short or long rest. At 10th level this die becomes a d10, and at 18th level it becomes a d12.

### Two-Weapon Fighting
When you engage in two-weapon fighting, you can add your ability modifier to the damage of the bonus action attack.

Addditionally, you can use your reaction to add +1 to your AC if you are wielding a seperate weapon in each hand.

### Versatile
Replaces Defense

You can use your reaction to gain +2 to your AC until the beginning of your next turn, you must be wielding a weapon with the two-handed property or versatile porperty, and cannot be wielding a shield.


<div class='pageNumber'>11</div>
<div class='footnote'>PART 4 | Updated Fighting Styles</div>
<div class='footer icons'>
 This Compendium is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards of the Coast. Made by DupontBreweries.
</div>