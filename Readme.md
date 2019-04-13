Spawns a trail of invisible objects behind every player. Other players can see them using the Detect Key spell effect.

Requires [DataManager](https://github.com/tes3mp-scripts/DataManager)!

You can find the configuration file in `server/data/custom/__config_FootPrints.json`.
* `interval` how often foot prints should be placed
* `refId` refId of the permanent record created to use as a footprint
* `baseId` baseId used for `refId`
* `name` displayed name (only matters if you make the object visible)
* `model` model to use for `refId` (default is `""`, which makes it invisible)
* `limit` how many footprints should be shown for any player. Also defines how long they last (up to `limit * interval` secodns)
* `Z` vertical offset between player feet and the footprint