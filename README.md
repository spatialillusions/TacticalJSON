# TacticalJSON

Specification for different types of tactical data in JSON format

## Why TacticalJSON

Primary intended to be a specification for data in [milgraphics](https://github.com/spatialillusions/milgraphics) but also as an [alternative exchange format between systems](https://xkcd.com/927/).

TacticalJSON is based on GeoJSON and simply defines what properties names should be, and what geometry types that should be used for different symbols, and the symbol geometries are based on the definitions in MIL-STD-2525D. Being based on a existing file format, you can read the base geometries of TacticalJSON with any client that can read GeoJSON today. On the contrary NVG, Nato Vector Graphics, and MSDL, Military Scenario Definition Language, requires a custom client to read the raw information, the same goes for ADEM, Alternate Development and Exchange Method.

It is also possible to utilize any OGC WFS server capable of serving GeoJSON to provide TacticalJSON to networked clients. OGC WFS was marked as Combat ready in 2014 by [DGIWG](https://www.dgiwg.org/dgiwg/), Defence Geospatial Information Working Group, so it is a proven technique to provide information. 

## Why GeoJSON and not GML

TacticalJSON main target is web based clients, and parsing of JSON objects is much faster than parsing of XML in web browsers. It would however be possible to use the same data profile for transmitting data as GML instead of GeoJSON.

## Extended TacticalJSON

The specification for TacticalJSON only lists the properties needed to draw the tactical symbology, and any other properties can be added to the transmitted data as additional information. 

In the future TacticalJSON might include extensions listing additional property names used for other purposes.

## Non geospatial data

The first version of TacticalJSON will only include support for geospatial data, but in the future a structure for transmitting data such as Order of Battle, might be included in the format or as an extension.