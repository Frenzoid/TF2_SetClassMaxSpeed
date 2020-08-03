# TF2 Set Class Max Speed

- This plugin allows to change ones max movement speed.

## How to install.
- Download this repository (right top green button), and copy `setclassmaxspeed.smx` on your plugins folder.

## CVars:

cvar name, default value, description.

-    g_cvSEnabled = CreateConVar("sm_spenabled", "1", "Sets whether the plugin is enabled.");

-    g_cvSMode = CreateConVar("sm_spmode", "0", "Sets plugins mode, 0: sm_spincrement = Set % speed for everyone, 1: Custom speed % for each class from each ones cvar");
-    g_cvSTeam = CreateConVar("sm_spteam", "1", "0: apply to all teams, 1: Only RED, 2: Only Blue");

-    g_cvSIncrement = CreateConVar("sm_spincrement", "1.1", "Default % speed added to everyone if sm_spmode = 1.");

-    g_cvSSoldier = CreateConVar("sm_spsoldier", "1.1", "Change speed % on Soldiers speed");
-    g_cvSPyro = CreateConVar("sm_sppyro", "1.1", "Change speed % on Pyros speed");
-    g_cvSSpy = CreateConVar("sm_spspy", "1.1", "Change speed % on  Spys speed");
-    g_cvSDemoman = CreateConVar("sm_spdemoman", "1.1", "Change speed % on Demomans speed");
-    g_cvSSniper = CreateConVar("sm_spsniper", "1.1", "Change speed % on Sniers speed");
-    g_cvSEngineer = CreateConVar("sm_spengineer", "1.1", "Change speed % on Engineers speed");
-    g_cvSHeavy = CreateConVar("sm_spheavy", "1.1", "Change speed % on Heavys speed");
-    g_cvSScout = CreateConVar("sm_spscout", "1.1", "Change speed % on Scouts speed");
-    g_cvSMedic = CreateConVar("sm_spmedic", "1.1", "Change speed % on Medics speed");


## Config file:
- Config file located at `cfg/sourcemod/setclassmaxspeed.cfg`.

## Current known bugs:
none

## This plugin is not fully tested, if you find any issues, report it to [ISSUES](https://github.com/Frenzoid/TF2_SetClassHealthRegen/issues) or [send me a private message via Steam](https://steamcommunity.com/id/MrFren/).
