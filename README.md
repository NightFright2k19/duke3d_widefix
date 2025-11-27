![duke3d_wide](https://github.com/user-attachments/assets/831095c6-1e74-409f-889f-ad4d0c85f342)

# WIDESCREEN FIXES FOR DUKE NUKEM 3D

This file provides widescreen graphics to make Duke Nukem 3D look a bit more polished and 
visually "complete" for EDuke32 users.

What you get:
- Widescreen graphics (statusbar, weapons, menu)
  Fox made a really nice widescreen statusbar for the game. I improved a few pixels here and there and increased its width a bit to cover higher screen resolutions.
  Widescreen-compatible weapons for Duke Nukem 3D and Life's A Beach made by Jimmy are also included, only loaded when the same tiles are not replaced by custom mods.
  Finally, the most important menu tiles have been provided as widescreen versions, covering original Duke3D and all addons.

- 8-bit redfont from Duke3D v1.3D
  With the Atomic Edition, 3D Realms switched to a new menu font that was much thicker than the one that came with the initial release of the game. Many liked the previous
  font better, so here it is. I took the 8-bit version of the redfont from the HRP (made by SwissCM) and integrated it into .art files with some palette fixes (so the
  characters would also look OK in custom content).


## R E Q U I R E M E N T S

1) Duke Nukem 3D groupfile (duke3d.grp, preferrably v1.5 Atomic Edition)
2) One of the supported ports:
   - EDuke32 (http://dukeworld.duke4.net/eduke32/synthesis)
   - Rednukem (https://lerppu.net/wannabethesis)
   - Raze (https://github.com/ZDoom/Raze/releases)

Note about DukeGDX: 
This port comes with its own widescreen graphics (even though without widescreen menu
tiles which are not supported) and therefore won't require this mod. 


## I N S T A L L A T I O N

1) Extract "duke3d_widefix.zip" into your EDuke32 autoload dir.
2) Make sure "Enable 'autoload' folder" option is checked in EDuke32 launcher. 
3) Launch EDuke32.
