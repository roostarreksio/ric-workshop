# ric-workshop [![GitHub release (latest by date)](https://img.shields.io/github/v/release/roostarreksio/ric-workshop?color=orange&style=flat-square)](https://github.com/roostarreksio/ric-workshop/releases/latest)

A place created to make working on Rex and Wizards game modding/fixing easier.

---

### How to install:
* Download the latest release ZIP [here](https://github.com/roostarreksio/ric-workshop/releases/latest) (*-dev* version has decoded files) 
* Copy contents of the archive to your game's installation folder (e.g. *C:/Program Files/AidemMedia/Reksio i Czarodzieje*)

---

### Bugfixes:

#### Kubki
* Fixed a bug that caused the game to crash during Genie's riddle mini-game  
#### Labirynt
* Fixed the effect of the Changing Into A Frog spell and added new graphics
* Fixed the effect of the Circles And Whirls spell on playable characters (affecting Reksio regardless of which character has been hit)
* Fixed the effect of the Darkness spell on hostile (non-playable) characters
* Fixed the effect of the Sleep spell which could render a character asleep forever if "covered" by another spell
* Fixed some graphics bugs (ie. unaligned spell effect animation or Darkness visual effect glitching near the left side of the screen)
* Nullified spell effects for characters that happen to hit themselves with a spell
* Disabled the keyboard during the restart sequences
* Fixed the disappearance of the Sleep and Changing Into A Frog effects occuring when switching the active player character
* Fixed a bug that caused an asleep character to become awake when hit with the Changing Into A Frog spell
* Fixed player position becoming unaligned after elapsing of the Globe Of Pudding spell
* Fixed spells being cast by enemies even after hitting them with a spell
#### Magic
* Restored effects of the Fly Plague, Changing Into A Frog and Circles And Whirls spells on Reksio.
* Prevented possible infinite loop from happening if an opponent fails in drawing a spell
#### Shooter
* Fixed a bug that caused the game to crash when losing the fight after loading a save-state made during the fight  
#### Smokret
* Fixed a bug that prohibited Smokret's talking animation from playing
---
### Mods (optional):
* DrobLoader

---
CNV encoder/decoder [AMkd](https://github.com/Dove6/AMkd) by Dove6 is used to create releases.


![](https://i.imgur.com/d2DkcNd.png)
