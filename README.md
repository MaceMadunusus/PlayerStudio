PlayerStudio
============

This is a Work In Progress Unreal Engine 4 implementation of a Player Studio draft site for PlanetSide 2.

Requires Unreal Engine 4.9 Official Release and above.

**If you are updating from the 4.8 or below version of this repository then it is highly likely content will not be fully compatible due to a reorganization of assets. Backup prior to updating!**

##Notes
To visualize faction color switching your level must be using the HUD_PS2 HUD asset and Pawn_PS2. Once that is done, play your level in editor and hold TAB to enable the pop-up menu. Click the faction you would like global assets to switch to.

Don't want the music playing in-game? Hit M.
Switch your pawns faction by hitting X.
Capture a base by hitting Z.

**Files in the restricted folder are not to be taken out or modified for other projects. You can however use them within this project.**

##To-Do

There are more to do than this, but here are some things I can think of.
###Blueprints
* Add remaining window and door covers to building blueprints.
* Create a working Teleporter.
* Create a working JumpPad with proper targeting.
* Redo NewTower blueprint to make more sense and be less wonky and more efficient.

###Materials
* Searhus Terrain Material
* Master Material Vector Up Based Snow (For Esamir Assets)
* Master Material Crevice Based Sand (For Indar Assets)
* Master Material Moss (For Hossin and possibly Amerish/Koltyr Assets)
* Adjust Master Material for additional overlays currently handled by TwoTex Material.
* Add adjustable sky materials for each continent.

###Models
* Shields
* Foliage
* Fix Lightning Turret
  
###Particles
* Add particles for SCU and its stages.
* Add particles for vertical part of Gravity Lifts.
* Add Teleporter particles.
* Fix missing stage 2 and 3 particles on Generator.
  
###Textures
* Fix Harasser Specular texture order.
* Add sky textures for each continent.
* Add faction color capability to many other NS textures.
