# TacticalJSON

Specification for tactical data in GeoJSON format

## Why TacticalJSON

Primary intended to be a specification for data in [milgraphics](https://github.com/spatialillusions/milgraphics) but also as an [alternative exchange format between systems](https://xkcd.com/927/).

TacticalJSON is based on [GeoJSON](https://tools.ietf.org/html/rfc7946) and simply defines what properties names should be, and what geometry types that should be used for different symbols, and the symbol geometries are based on the definitions in MIL-STD-2525D. The goal is to stay as close as possible to how geometries and properties are defined in 2525/APP6. 

Being based on an existing file format, you can read the base geometries of TacticalJSON with any client that can read GeoJSON today. This makes it possible to share tactical information between C2/C4ISR clients and traditional GIS, Geographical Information Systems. On the contrary NVG, Nato Vector Graphics, ADEM, Alternate Development and Exchange Method, and MSDL, Military Scenario Definition Language, requires a custom client to read the raw information.

It is also possible to utilize any OGC WFS server capable of serving GeoJSON to provide TacticalJSON to networked clients. OGC WFS was marked as Combat ready in 2014 by [DGIWG](https://www.dgiwg.org/dgiwg/), Defence Geospatial Information Working Group, so it is a proven technique to provide information. 

## Why GeoJSON and not GML

TacticalJSON main target is web based clients, and parsing of JSON objects is much faster than parsing of XML in web browsers. It would however be possible to use the same data profile for transmitting data as GML instead of GeoJSON.

## Extended TacticalJSON

The specification for TacticalJSON only lists the properties needed to draw the tactical symbology, and any other properties can be added to the transmitted data as additional information. 

## What is not in TacticalJSON

TacticalJSON is not a message format and nor a information protocol. It is simply to be used as simple way to transmit and store tactical overlays. The focus is completely on simplicity and what is drawn on the map. There is a lot of needs that TacticalJSON won't be enough for, and there are several standards that cover those usages. The philosophy behind TacticalJSON is that there should be a [KISS](https://en.wikipedia.org/wiki/KISS_principle) way of transmitting and storing tactical overlays.