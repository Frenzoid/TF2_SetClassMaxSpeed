# TF2 Set Class Max Speed

- This plugin allows to change ones max movement speed.

## How to install.
- Download this repository (right top green button), and copy `setclassmaxspeed.smx` on your plugins folder.

## CVars:
% examples: 

1.0 = 100% of the merc's total speed.

1.1 = 110% of the merc's total speed.

2.0 = 200% of the merc's total speed, etc.

All speed values are Float.
------

cvar name, default value, description.

-    "sm_spenabled", "1", "Sets whether the plugin is enabled."

-    "sm_spmode", "0", "Sets plugins mode, 0: sm_spincrement = Set % speed for everyone, 1: Custom speed % for each class from each ones cvar"
-    "sm_spteam", "1", "0: apply to all teams, 1: Only RED, 2: Only Blue"

-    "sm_spincrement", "1.1", "Default % speed added to everyone if sm_spmode = 1."

-    "sm_spsoldier", "1.1", "Change speed % on Soldiers speed"
-    "sm_sppyro", "1.1", "Change speed % on Pyros speed"
-    "sm_spspy", "1.1", "Change speed % on  Spys speed"
-    "sm_spdemoman", "1.1", "Change speed % on Demomans speed"
-    "sm_spsniper", "1.1", "Change speed % on Sniers speed"
-    "sm_spengineer", "1.1", "Change speed % on Engineers speed"
-    "sm_spheavy", "1.1", "Change speed % on Heavys speed"
-    "sm_spscout", "1.1", "Change speed % on Scouts speed"
-    "sm_spmedic", "1.1", "Change speed % on Medics speed"


## Config file:
- Config file located at `cfg/sourcemod/setclassmaxspeed.cfg`.

## Current known bugs:
none

## This plugin is not fully tested, if you find any issues, report it to [ISSUES](https://github.com/Frenzoid/TF2_SetClassHealthRegen/issues) or [send me a private message via Steam](https://steamcommunity.com/id/MrFren/).
