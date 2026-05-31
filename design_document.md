# Team Fortress Invasion - Design Document
This document contains all needed technical information for development of the project.

## Genre & Synopsis

### Genre
Team-based objective shooter with resource management, vehicles, buildings, technologies, and tactical commander elements.

### Synopsis
Two teams, Humans and Aliens, fight to complete map objectives such as capturing Control Zones while collecting and spending Resources throughout the match. Players gather resources from Resource Zones, destroyed buildings, and defeated enemies. Resources are used to purchase Technologies, Buildings, Vehicles, ammunition, grenades, and support structures.

The Humans and Aliens differ in gameplay philosophy. Humans require external power sources for some structures, while Aliens do not. Humans receive a 20% discount on buildings, while Aliens previously utilized reinforcement wave respawning.

## Control settings
|              Action              |  PC   | Gamepad |
|----------------------------------|-------|---------|
| Move Forward                     | W     | LS      |
| Move Back                        | S     | LS      |
| Move Left                        | A     | LS      |
| Move Right                       | D     | LS      |
| Sprint                           | Shift | LSB     |
| Jump                             | Space | Ⓐ      |
| Crouch                           | Ctrl  | RSB     |
| Primary fire                     | LMB   | RT      |
| Secondary fire                   | RMB   | LT      |
| Throw grenade                    | F     | LB      |
| Throw secondary grenade          | G     | RB      |
| Reload                           | R     | Ⓧ      |
| Scroll weapons                   | SW    | Ⓨ      |
| Cancel action                    | Esc   | Ⓑ      |
| Use Voice Chat                   | V     |         |
| Text chat                        | Y     |         |
| Team text chat                   | U     |         |
| Call for Medic                   | E     |         |
| Change Class                     | ,     |         |
| Change Team                      | .     |         |
| Taunt                            | H     |         |

## General game style
dark n' gritty, green and otherworldly skyboxes, distorted cities and overworld maps ith wide open areas for the firefight and flanking parts, thats some of the examples of atmosphere for team fortress invasion. the visuals are dirty and the gameplay is non-stop shooting and resource harvesting. a fast-paced game that each match goes around 15 minutes.
## Systems & Mechanics

### Systems
**buildings** - classes have buildings like bunkers and walls, others have buildings like buffstations and powerpacks which are meant to help out other players.

### Classes

A distinctive feature of the Team Fortress series are the classes. This game has 9 classes including: the Recon, the Commando, the Defender, the Medic, the Pyro, the Infiltrator, the Support, the Escort and the Sniper.

| Name | HP | Speed (hu/s) | Equipment | Abilities |
| ---- | -- | ------------ | --------- | ----------- |
| the Recon | 125 | 400 | Dual pistols, melee, conclussion grenade, sticky grenade | double jump |
| the Commando | 200 | 250 | Rocket launcher, J-stye, melee, frag grenade, nail grenade | (??) |
| the Defender | 125 | 300 | Shotgun, frag grenade, melee, EMP grenade | build sentry guns, gain Technology upgrades such as increased sentry gun count, can unlock Welder technology, repair buildings |
| the Medic | 150 | 320 | Plasma rifle, Repair Gun, frag grenade, heal grenade | heal, repair buildings, HP regeneration |
| the Pyro | 150 | 290 | Flamethrower, shotgun, melee, frag grenade, gas can | immune to afterburn |
| the Infiltrator | 125 | 320 | Tranquilizer, knife, frag grenade, gas grenade | assassinate enemy players using a knife, disguise as enemy players, consume corpses, eavesdrop on the enemy voicechat and teamchat when in range of them, use thermal vision |
| the Support | 250 | 270 | Plasma grenade launcher, harpoon, melee, frag grenade, dynamite | Mortar Strike (stun and AoE damage). Mortars came in multiple round types, (which could be unlocked from Technology Upgrades) from Smoke Rounds, that did minimal damage but covered enemies in smoke, to Starburst Rounds, that blinded enemies much like the Flash-bang in Counter-Strike, and finally to the Cluster (MIRV) Rounds, which split up into two mid-air for more damage and impact spread.|
| the Escort | 150 | 320 | Laser minigun, shotgun, melee, frag grenade, heal grenade | VIP, can't build |
| the Sniper | 125 | 290 | Sniper rifle, laser rifle, melee, frag grenade, indicator grenade | add Wrangler's laser sight when he's scoped, pls:3 |

### Mechanics
**shield** - some classes have the shield, which reduces the damage by half and has 5 seconds of use and 12 seconds of cooldown.

**grenades** - grenades can be thrown by pressing H and if you hold the key, they cook, exploding in you, but if done correctly, this can turn into a grenade jump. each class has a special grenade.

### weapons
**dual pistols** - used by recon only, the dual pistols fires laser toward the enemies.

**rocket launcher** - used by commando only, the rocket launcher fires laser-designated rockets.

**J-stye** - used by commando, the J-stye is a converted vickers machine gun, made to be carried around instead of being stationary, it fires 30 cal. bullets.

**shotgun** - well, its a shotgun, a winchester 1897 for humans, and for aliens its a brand new equivalent.

**flamethrower** - its just a flamethrower for humans and other kind of the same for aliens, the second fire drops gasoline which can be used to set traps to the enemies.

**tranquilizer** - used by infiltrator only, it fires 1 dart that slow down the enemies.

**laser rifle** - its a laser rifle, it fires... laser lol

**laser minigun** - used by escort, the name explains itself.

**plasma grenade launcher** - used by support only, it fire grenades just like tf2 grenade launcher

**harpoon** - used by support only, it can fire at enemies and pull them close to your grenades range.

**sniper rifle** - used by sniper, its a springfield rifle converted to fire lasers.
## Parameters
**grenades** - each class has 3 grenades (supposed to change when we get a better idea of special grenades)

**dual pistols** - it fires 5 bullets per second and has a 10 round clip and 60 bullets as reserve. it deals 15 damage.

**rocket launcher** - works just like hl2 rocket launcher. it deals 100 damage on direct hit.

**J-stye** - it has 32 round clip and 128 bullets in reserve.

**shotgun** - works just like its TF2 counterpart.

**flamethrower** - works just like its TF2 counterpart.

**tranquilizer** - it fires 1 dart then the gun need to be reloaded, the dart deals 20 damage but slows down the enemy for 5 seconds..

**laser rifle** - 

**laser minigun** - works just like its TF2 counterpart.

**plasma grenade launcher** - works just like its TF2 counterpart.

**harpoon** -

**sniper rifle** - works just like its TF2 counterpart.
## Design
The game ressembles a cartoonish version of half-life 2 beta, especially 2000-2001 era, with dirty visuals and WW1 inspired designs.
## Interface
like classic valve games, looks like valve GUI but with green boarders.
### References
[hl2-beta.ru - Team Fortress 2: Invasion mechanics](https://hl2-beta.ru/index.php?action=articles;sa=view;article=59;language=english)

[Official TF2 wiki - invasion](https://wiki.teamfortress.com/wiki/Invasion)
