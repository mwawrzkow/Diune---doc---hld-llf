# [ HLD ] High Level definition

## Table of contents
 1. Prerequisites
 2. Feature Set





### Prerequisites
This section will provide basic information about The Engine and used frameworks. 

The project will use Unity Engine. 

List of packages: 
 - Cinemachine
 - Text Mesh PRO

Platforms: 
 - OSX 
 - Windows 
 - Linux (ac Ubuntu 22.04)


 ### Feature set 
 This Section will describe the basic feature set, which will provide information about core mechanics of game.


Core Mechanics: 
 - Battle simulations
 - Resources management 
 - Concept of entities(high and low) - Entitis design 
 - Generals - have their own divisions
 - Different entities (eg. Diplomats, Spies)
 - Random weather events in Provinces
 - Random sand worm events + custom behavior based
 - Dialogs + relationships between fractions etc.(?)
 - Uniqe types of entities for each faction

#### Provinces 
 - High level map is divided into provinces
 - Moving between provinces takes turns 
 - Player can move generals between provinces
 - Player can Build buildings 
 - Player can see only his province, otherwise fog of war
 

 #### Low level map
 - The RTS fight 
 - Each army is divided into divisions
 - Each general has speciall attributes and spells 
 - The fight outcome between divisions is determined by the terrain and divisions
 - divisions can be destroyed or harmly harrased
 - fog of war
 
 #### AI
 - Framework for designing "AI" opponents behavior

 #### More campains
 - Framework for designing initial map state


 ### additional feature tools
 - Map editor 
 - company editor 
