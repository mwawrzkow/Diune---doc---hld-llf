# LLF of Battle simulations

## Actor

An actor in the battle mode is someone in command of the army, can be player or AI.

- Actor has his resources
- Has army
- Can see the whole map, can't see past fog of war
- Has his initial positon for the battle
- Can set the army in desired location

### Entitiy 

- Has health points
- Has actions points
- Has movement speed
- Has vision distance
- Has damage
- Can deal damage
- Can recieve damage
- can die


### Army (battle mode)

- built from entities
- always have seperate commander
- always in formation
- has possible actions (ambush, attack, defend)

### Commander

- inherites from enitity
- is special entity form turn based mode
- has unique skills
- has mana
- has cooldown

## Map 

- has size
- coordinates
- has buff and debuff zones -> on hills dmg buff, roads for buffed movement speed
- has blockers (walls, mouintains, cliffs) -> certain entities can move through them
- has unique events -> sandstorms, sandworms, quicksands
