PlayerStudio
============

This is a Work In Progress Unreal Engine 4 implementation of a Player Studio draft site for PlanetSide 2.

Requires Unreal Engine 4.7 Official Release and above.

##Notes
To visualize faction color switching your level must be using the HUD_PS2 HUD asset. Once that is done, play your level in editor and hold R to enable the popup menu. Click the faction you would like to switch to.

Don't want the music playing in-game? Hit M.

##To-Do

There are more to do than this, but here are some things I can think of.
###Audio
* Add more audio from the game.

###Blueprints
* Add remaining window and door covers to building blueprints.
* Create a working Teleporter.
* Create a working JumpPad with proper targeting.
* Fix generators not properly executing Amp Station and Tech Plant shield event targets.
* Redo NewTower blueprint to make more sense and be less wonky and more efficient.

###Materials
* Esamir Terrain Material
* Hossin Terrain Material
* Searhus Terrain Material
* Master Material Vector Up Based Snow (For Esamir Assets)
* Master Material Crevice Based Sand (For Indar Assets)
* Master Material Moss (For Hossin and possibly Amerish/Koltyr Assets)
* Adjust Master Material for additional overlays currently handled by TwoTex Material.
* Add adjustable sky materials for each continent.

###Models
* Shields
* Character Classes
* Foliage
* Fix Lightning Turret
  
###Particles
* Add particles for SCU and its stages.
* Add particles for vertical part of Gravity Lifts.
* Add Teleporter particles.
* Fix Ammo Tower particles getting culled during play but not in-editor.
* Fix missing stage 2 and 3 particles on Generator.
  
###Textures
* Fix Harasser Specular texture order.
* Add sky textures for each continent.
* Add faction color capability to many other NS textures.
