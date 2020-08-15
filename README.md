# Kiwi's CTT Overhaul

## Version 0.1.7; 15 August 2020; Made for KSP 1.9.1

![Kiwi CTT Overhaul](https://i.imgur.com/StiyWnp.png)

A CTT "Probes/Planes Before Crew" type Overhaul based on the Zee's [PBC Mod](https://forum.kerbalspaceprogram.com/index.php?/topic/181013-ksp-181-probes-before-crew-pbc-version-28/) and inspired by Spink Akron's [UnKerballed Start](https://forum.kerbalspaceprogram.com/index.php?/topic/181932-18x-unkerballed-start-v110-updated-oct-27-2019/). Requires the Community Tech Tree: [CTT](https://forum.kerbalspaceprogram.com/index.php?/topic/90530-110x-community-tech-tree-august-1-2020/).

This overhaul, like its predecessors, revolves around the  premise that probes should come before crewed space missions.  While I really enjoyed both aforementioned mods, I found two issues: It took a bit too long to see my kerbals in game and I could get a good way through the tech tree before leaving Kerbin/Mun/Minmus.  

This is an attempt to make my tech choices a bit more meaningful and allow me to have my kerbins spend some time testing jets in Kerbin's atmosphere before launching in space.  I have added another 62 tech nodes across the tree, but have tried to leave the general layout of the tree largely intact.  The major changes are adding a separate branch for solid rocket boosters and if you have mods which have cryogenic engines, this will move them to a different branch from the Liquid Fuel Branch. While I have shifted some of the nodes around, I have not removed any, thus leaving some compatibility with any mod that I have not explictly linked here (which as of now is functionally none).

Like UnKerballed Start, I have started with 0.625 meter engines and tanks and work progressively larger.  To try and prevent early crewed missions using spaceplane parts, I have nerfed the skin temperature of the spaceplanes, but have provided higher skin temperatures to the spaceplanes once they reach the High Altitude tech node (same as the introduction of the Mk3 spaceplane).

I calibrated the basic idea around stock and the expansion packs alongside Restock/Restock+ and Missing History.  Ultimately, given the number of nodes, you will benefit by having several parts mods.

In limited cases, I have added a couple of rescaled parts and a couple more if Restock is installed.  In other cases such as Missing History, I will use the Restock texture when available for consistency in the visual style. I've currently given myself a "Mk0" inline cockpit in the start node because I am terrible at plane design and it is a bit cheaty.  This will probably change as this develops.

## Current Supported Mods (see details below for general changes):
* BetterSRBs 1.2.3
* Completely Non-Aggressive Rocketry 1.0.2
* LTech 0.5.1 Beta
* Mark IV Spaceplane System 3.1.2
* Missing History 1.8.2
* M.O.L.E. (Very Limited Support) 1.22.1
* Near Future Solar 1.2.3
* Restock/Restock+ 1.1.2
* SCANsat 20.2

The mods that I am looking at incorporating if changes necessary in the sort-of order of preference: 
1. Nertea's Full Suite of Parts mods excluding the current Far Future due to his current revamp
2. DMagic Orbital Science
3. Universal Storage 2
4. Luciole
5. B9 Procedural Wings
6. AirplanePlus
7. Stockalike Mk1 Open cockpit
8. Mk2/Mk3 Expansion
9. Rational Resources
10. MKS
11. Knes
12. KIS/KAS
13. Stockish Project Orion
14. Mining Expansion

## Great Mods, but not likely to be added by me (Happy to accept help):
* BDB and Tantares (Scale and Scope are huge and hard to break down like Near Future)
* Kerbalism (Doesn't fit my personal playstyle)

## BetterSRBs 1.2.3
Moved the new parts to the SRB tech nodes. Deprecate a couple of parts unless other Jade of Maar mods detected; Undeprecate the Missing History SRB in this stage to offer a third tier of SRBs in the 1.875m category.  Replace new SRB parts with Restock if available to maintain similar aesthetic.

## Completely Non-Aggressive Rocketry 1.0.2
Created a new node in the tech tree between the start and other tech nodes for these.  Shrunk the size to 0.625m to match the small size of the early rockets and balanced fuel and thrust size for similar performance to original.  Ensures that these will not be OP relative to other early career rockets.  Also added an antenna, added a temp and pressure to probe body and soft deprecated the experiments.  Added an upgrade to basicRocketry to allow the rocket to reach space

## Mark IV Spaceplane System 3.1.2
Shuffled the tech nodes.

## Missing History 1.8.2
Soft-deprecate liquid engines of Restock+ installed; hide a few more parts if Restock+ is installed; Used Restock models if available.

## M.O.L.E. 1.22.1
I've taken a few selective pieces out for my personal playthrough and provided some configurations for them that also strip out the WBI Experiment and Omniconverter functionality as I am not intending to use these systems in my playthrough.  I'm providing this only because I can't be bothered putting another folder for this, so consider this incomplete.  But if you want some great looking Restock quality extensions to the Mk1 Cockpit, check out the updated Appaloosa textures in this mod, beautiful.

## Near Future Solar 1.2.3
If installed, this will place solar a touch earlier in the tech tree and place most stock parts available a bit earlier.  I've also added B9PS support to the panels, having advanced and concentrated panels similar to NF Solar (no visual difference as seen in Nertea's version). I also spread Nertea's solar parts further through the tech tree and added concentrated part variants to those parts which excluded (Just used the Advanced textures in cases where there were no concentrated versions of the textures). The basic layout is that fixed panels came first, then deployable, but non-tracking, then deployable and tracking.  Along the nodes we have upgrades to each of these variants.

Lastly, the advanced and concentrated versions of both Nertea and stock require a tech upgrade to access.  Advanced will occur one level above the part, Concentrated two levels.

## Restock/Restock+ 1.1.2
Shuffled the tech nodes. Slight cost rebalancing on a couple of science parts.

## SCANsat 20.2
Shuffled the tech nodes. Slight cost rebalancing.

## Alternate Tech Tree Mods


## Changelog
* 0.1.7 Slight rebalance of solar parts; Added Near Future Solar support; Added Omega Solar Tech node in tree.
* 0.1.6 Added LTech Beta and SCANsat support; rebalanced stock resource scanners compared to SCANsat
* 0.1.5 Added a couple of nodes to support the command module strand.
* 0.1.4 Added Nuclear Power & Propulsion
* 0.1.3 Added CNAR support.
* 0.1.2 Added BetterSRBs support, Added couple of parts.  Began adding support for optional mod, KiwiDeprecated which soft deprecates parts on the basis of overlap of Nertea's mods if they don't fit in a stockalike style.
* 0.1.1 Added MkIV Spaceplane Support, Added part upgrades to Mk1-3 crewed parts to discourage those being used for the first crewed space missions, cost balancing for engines and SRBs.

## Disclaimer

This mod has not been endorsed by _Zee, Spink Akron, Nertea or any other mod/part creator referenced in the config files.  All errors are my own.  Please do not hassle mod authors if these configurations cause conflicts with other mods.

## License

MIT License
Copyright (c) 2019, _Zee; 2020, Hemeac

Permission is hereby granted, free of charge, to any person obtaining a copy of this software 
and associated documentation files (the "Software"), to deal in the Software without restriction, 
including without limitation the rights to use, copy, modify, merge, publish, distribute, 
sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is 
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or 
substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING 
BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND 
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, 
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Additional Licenses and attributions:

Icons from Community Tech Tree by Nertea were modified and included in this mod and are licensed under Creative Commons Attribution-NonCommercial 4.0.

Additional icons sourced from flaticon.com and thenounproject.com.
