# C.O.M.P.A.S.S

Crimento's Omnidirectional Modulated Portable Anomalous Slipstreaming Stations.

GAMMA addon for placeable Hideout Furniture teleportation stations.

## Install

Download the `.zip` from GitHub and install it as a normal MO2 addon anywhere after xlibs and Hideout Furniture.

Expected tree:

```text
C.O.M.P.A.S.S/
  gamedata/
    scripts/
      compass.script
```

## Requirements

This mod was created for the G.A.M.M.A modpack.

It has not been tested with vanilla Anomaly, but should work with the required dependencies installed:

- [xlibs](https://www.moddb.com/mods/stalker-anomaly/addons/xlibs-1001) by @damiansirbu-stalker for logging, messaging, and location name detection
- [Hideout Furniture](https://www.moddb.com/mods/stalker-anomaly/addons/hideout-furniture-hf) by @Aoldri for the placeable objects framework
- [Expanded/Fixed Maps All In One](https://www.moddb.com/mods/stalker-anomaly/addons/expandedfixed-maps-all-in-one) by HailTheMonolith for several teleport failure locations

## Usage

The crafting recipe is unlocked by `The Art of Artefacts Fusion Vol. 3` and requires an RF receiver, a Compass artifact, and some metal scrap.

After placement, the station allows the player to teleport to another selected station, essentially acting as a free fast travel system.

For balance and lore reasons, the station also requires calibration time after placement and has a configurable failure chance. Both can be adjusted in MCM.

## Credits

- GSC Game World for creating the wonderful world of S.T.A.L.K.E.R.
- @Grokitach for the G.A.M.M.A modpack
- @damiansirbu-stalker for an extremely useful modding library providing easy access to many essential things
- @Aoldri for Hideout Furniture that allowed the base building part in Anomaly in the first place
- OpenAI Codex for most of the technical parts and code review

## TODO

- Create an actual model for the station instead of reusing the `transiver` Anomaly prop
- Add device icon (currently reuses the Compass artifact icon)
- Add more failure destinations
