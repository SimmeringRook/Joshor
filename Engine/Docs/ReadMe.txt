﻿Creature IDs are 1 - 100
Weapon IDs are 101 - 200
Item IDs are 201 - 300
Treasure IDs are 301 - 400
Room IDs are 401 - 500

These will change in the future but for this simple game as we are building
this will work for our needs.

The Monster List is populated from a text file. The following is the format of the text
file.

//ID
//Name
//Experiance gained from killing
//Amount of Gold gained from killing
//Armor Class
//Damage delt by monster
//Amount added or subtraction of monsters attack
//Image file of monster

The Weapon List is populated from a text file. The following is the format of the 
text file.

//ID
//Weapon name
//Weapon cost
//Damage done by weapon
//The type of damage the weapon does.

The Room List is populated from a text file. The following is the format of the 
text file.

//ID
//Room name
//Room description
//If there is an exit north then true, or else false
//If there is an exit East then true, or else false
//If there is an exit South then true, or else false
//If there is an exit West then true, or else false
//Is there a monster in this room, -1 no, or the list element of the monster.