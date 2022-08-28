# Swarm Special Forces


SwarmSpecialForces.SC2Map contains all scripts and data. Assets like custom models and incons are located in SwarmSpecialForcesAssets.SC2Mod.

### Simple install:
- Download the repository as a ZIP file.
- Move `SwarmSpecialForcesAssets.SC2Mod` into `Starcraft II/Mods`.
- Open the map by double clicking on `SwarmSpecialForces.SC2Mod/ComponentList.SC2Components`.
- Once the Starcraft 2 editor opened and loaded the map you can hit Test Document (Ctrl+F9).

### Advanced install:
- Close this repository into `Starcraft II/Maps`.
- Create a Junction or Symbolic Link pointing from `Starcraft II/Mods/SwarmSpecialForcesAssets.SC2Mod` to `Starcraft II/Maps/SwarmSpecialForces/SwarmSpecialForcesAssets.SC2Mod`.
- Start the map using `Startcraft II/Support64/SC2_Switcher.exe -run SwarmSpecialForces/SwarmSpecialForces.SC2Map` or `SC2_Switcher.exe -run "SwarmSpecialForces/SwarmSpecialForces.SC2Map" -displaymode 0 -trigdebug` for debugging.


## Tools


### SC2UserDataConverter


SwarmSpecialForcesAssets.SC2Mod contains all nessecary outsourced custom assets because assets dont need to be reuploaded each patch (reduced file size for upload from ~40 to 4 mb resulting in 10x faster upload time).

To test the map you need to change the SwarmSpecialForcesAssets dependency to your local copy of it, which should be located inside the Mods folder within your Starcraft 2 install directionary. If you do not change the dependency the game will not load the game/crash upon start.

Spreadsheet for everything:
https://docs.google.com/spreadsheets/d/1yyu7c10L5TqKTQIRxCbO2EhMih84HBKGQACy9V61J0E/edit#gid=1688450518
