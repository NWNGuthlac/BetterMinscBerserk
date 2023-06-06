# BetterMinscBerserk
Eliminates the (cursed) true-berserk property from Minsc's special ability and optionally adds other goodies.

I built this mod because I play no-reload and could never justify popping Minsc's berserk in case he killed my run. The idea is not to overhaul the character (it's been done: see the Rashemen Berserker mod) but simply to give vanilla Minsc a usable berserk. Once per day for a two-turn duration is actually pretty nice.

Minsc's berserk behaviour is coded in the SpIn117.spl file. To use this mod, drag the replacement file of your choice into your Override folder.

This mod contains different versions of the file, depending on how aggressively you want to modify the berserk. 

Version 0: default
- the unmodified file with the default behaviour.

Version 1. Player Control
- this is the lightest edit, leaving Minsc's berserk unchanged except to remove the true/cursed-berserk property so he remains under player control. (Note: after personally experimenting with the more aggressive options I ended up settling for this one as my favourite.)
- All higher versions include this feature. 

Version 2. Fall Unconscious if HP Too Low
- includes Version 1 changes
- in the default version Minsc will die if the berserk expires when his HP are too low. This version changes the expiry damage type to nonlethal, so he will just fall unconscious (like with the Berserker kit ability). 
- All higher versions include this feature.

Version 3a. Imprisonment Immunity
- includes all Version 2 changes
- this brings Minsc's berserk fully in line with the Berserker kit effects, and adds Imprisonment to the immunity list.

Version 3b. Barbarian Flavour
- includes all Version 2 changes
- this causes Minsc's berserk to have more of a Barbarian flavour. Instead of imprisonment immunity, this berserk will give a +10 physical DR boost and increase Minsc's move to that of a Barbarian.
