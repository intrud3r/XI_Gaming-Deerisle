# What is ScriptableAreas

`ScriptableAreas` are a special type of areas that the `TerjeCore` mod adds. Unlike standard areas - scriptable areas can have more flexible functionality, support custom parameters, have a power gradient between the inner and outer radiuses, when overlapping multiple areas of the same type - the effect is summarized.

# How to add scripted areas on the map?

You can add static scriptable areas in the `spawn_scriptable_areas.json` file located in the same folder.

Main parameters of scriptable areas:
- `Active`: Takes the value 0 or 1. Where 0 is disabled, 1 is enabled.
- `Classname`: The name of the scriptable zone class. A list of available script zone classes with descriptions of their effects can be found later in this manual under `List of available script zone classnames`.
- `Position`: The position of the script zone in the world. If parameter Y is zero - the script zone will be automatically set at ground level.
- `SpawnChance`: Chance of zone spawning (at server startup). The value is from 0 to 1, where 1 is 100% chance.
- `Filter`: A special field applied to some specific area types as an internal filter. Must be empty if not used.
- `Data`: additional parameters of the zone, may be different for each individual type of zone.



# List of available scripted areas:


