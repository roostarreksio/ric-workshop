# ric-workshop

A place created to make working on Rex and Wizards game modding/fixing easier.

### Bugfixes:

#### Shooter
* Fixed a bug that caused the game to crash when losing the fight after loading a save-state made during the fight

#### Magic
* Restored effects of the Fly Plague, Changing Into A Frog and Circles And Whirls spells on Reksio.
* Prevented possible infinite loop from happening if an opponent fails in drawing a spell

#### Labirynt
* Fixed the effect of the Changing Into A Frog spell
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

![](https://i.imgur.com/d2DkcNd.png)
