# Property Names

This table will show what names that should be used for different properties when they are saved as objects in TacticalJSON.

| FIELD | FIELD TITLE | DESCRIPTION | TacticalJSON |
| ----- | ----------- | ----------- | ------------ |
| A | Symbol Icon | The innermost part of a symbol, comprised of an icon and optional modifiers, that represents a joint military object (see 5.3.4).|  |
| B | Echelon | A graphic amplifier in a unit symbol that identifies command level |  |
| C | Quantity | A text amplifier in an equipment symbol that identifies the number of items present. | `quantity: String` |
| D | Task Force Indicator | A graphic amplifier that identifies a unit or activities symbol as a task force |  |
| F | Reinforced or Reduced | A text amplifier in a unit symbol that displays (+) for reinforced, (-) for reduced, (+) reinforced and reduced. | `reinforcedReduced: String` |
| G | Staff Comments | A text amplifier for units, equipment and installations; content is implementation specific. | `staffComments: String` |
| H | Additional Information | A text amplifier for units, equipment and installations; content is implementation specific. | `additionalInformation: String` |
| H1 | Additional Information | A text amplifier for units, equipment and installations; content is implementation specific. | `additionalInformation1: String` |
| J | Evaluation Rating | A text amplifier for units, equipment and installations that consists of a one-letter reliability rating and a one-number credibility rating:| `evaluationRating: String` |
| K | Combat Effectiveness | A text amplifier for units and installations that indicates unit effectiveness or installation capability. | `combatEffectiveness: String` |
| L | Signature Equipment | A text amplifier for hostile equipment; “!” indicates detectable electronic signatures. | `signatureEquipment: String` |
| M | Higher Formation | A text amplifier for units that indicates number or title of higher echelon command (corps are designated by Roman numerals). | `higherFormation: String` |
| N | Hostile (Enemy) | A text amplifier for equipment; letters "ENY" denote hostile symbols. | `hostile: String` |
| P | IFF/SIF/AIS | A text amplifier displaying IFF/SIF/AIS Identification modes and codes. | `iffSif: String` |
| Q | Direction of Movement Indicator | A graphic amplifier that identifies the direction of movement or intended movement of an object (see 5.3.7.8 and figure 13).| `direction: Number` |
| R | Mobility Indicator | A graphic amplifier for equipment that depicts the mobility of an object |  |
| R2 | SIGINT Mobility Indicator | M = Mobile, S = Static, or U = Uncertain. | `sigint: String` |
| S | Headquarters Staff Indicator | A graphic amplifier for units, installations and activities that identifies them as a headquarters|  |
| S2 | Offset Location Indicator | A graphic amplifier used to indicate the offset or precise location of a single point symbol (see 5.3.7.4, 5.3.12, and figure 13).|  |
| T | Unique Designation | A text amplifier for units, equipment and installations that uniquely identifies a particular symbol or track number. Identifies acquisitions number when used with SIGINT symbology. | `uniqueDesignation: String` |
| T1 | Unique Designation | A text amplifier for units, equipment and installations that uniquely identifies a particular symbol or track number. Identifies acquisitions number when used with SIGINT symbology. | `uniqueDesignation1: String` |
| V | Type | A text amplifier for equipment that indicates types of equipment. | `type: String` |
| W | Date/Time Group (DTG) | An alphanumeric designator for displaying a date-time group (DDHHMMSSZMONYYYY) or “O/O” for on order. The date-time group is composed of a group of six numeric digits with a time zone suffix and the standardized three-letter abbreviation for the month followed by four digits representing the year. The first pair of digits represents the day; the second pair, the hour; the third pair, the minutes. For automated systems, two digits may be added before the time zone suffix and after the minutes to designate seconds. | `dtg: String` |
| W1| Date/Time Group (DTG) | An alphanumeric designator for displaying a date-time group (DDHHMMSSZMONYYYY) or “O/O” for on order. The date-time group is composed of a group of six numeric digits with a time zone suffix and the standardized three-letter abbreviation for the month followed by four digits representing the year. The first pair of digits represents the day; the second pair, the hour; the third pair, the minutes. For automated systems, two digits may be added before the time zone suffix and after the minutes to designate seconds. | `dtg1: String` |
| X | Altitude/Depth | A text amplifier for units, equipment and installations, that displays either altitude, flight level, depth for submerged objects; or height of equipment or structures on the ground. See 5.3.7.5 for content.| `altitudeDepth: String` |
| Y | Location | A text amplifier for units, equipment and installations that displays a symbol’s location in degrees, minutes and decimal minutes (or in MGRS, GARS, or other applicable display formats). | `location: String` |
| Z | Speed | A text amplifier for units and equipment that displays velocity (see 5.3.7.6).| `speed: String` |
| AA | Special C2 Headquarters | A text modifier for units; indicator is contained inside the frame; contains the name of the special C2 Headquarters. | `specialHeadquarters: String` |
| AD | Platform Type | Electronic intelligence notation (ELNOT) or communications intelligence notation (CENOT) | `platformType: String` |
| AE | Equipment Teardown Time | Equipment teardown time in minutes. | `equipmentTeardownTime: String` |
| AF | Common Identifier | Example: “Hawk” for Hawk SAM system. | `commonIdentifier: String` |
| AG | Auxiliary Equipment Indicator | Towed sonar array indicator: A graphic modifier for equipment that indicates the presence of a towed sonar array (see 5.3.7.10, figure 13 and table IX).|  |
| AH | Area of Uncertainty | A graphic modifier for units, equipment and installations that indicates the area where an object is most likely to be, based on the object’s last report and the reporting accuracy of the sensor that detected the object (see 5.3.7.12.1 and table D-III).|  |
| AI | Dead Reckoning Trailer | A graphic amplifier for units and equipment that identifies where an object should be located at present, given its last reported course and speed (see 5.3.7.12.2).|  |
| AJ | Speed Leader | A graphic amplifier for units, equipment and installations that depicts the speed and direction of movement of an object (see 5.3.7.12.3 and figure 17).|  |
| AK | Pairing Line | A graphic amplifier for units, equipment and installations that connects two objects and is updated dynamically as the positions of the two objects change |  |
| AL | Operational Condition | A graphic amplifier for equipment or installations that indicates operational condition or capacity. |  |
| AM | Distance | A numeric amplifier that displays a minimum, maximum, or a specific distance (range, radius, width, length, etc.), in meters. | `distance: Number` |
| AN | Azimuth | A numeric amplifier that displays an angle measured from true north to any other line in degrees. |  |
| AO | Engagement Bar | A graphic amplifier placed immediately atop the symbol. May denote, 1) local/remote status; 2) engagement status; and 3) weapon type. |  |
| AP | Target Number | A six character text modifier used in Fire Support operations to uniquely designate targets in accordance with STANAG 2147, where characters 1 and 2 are alphabetic, and characters 3-6 are numeric: AANNNN. | `targetNumber: String` |
| AP1 | Target Number Extension | A 2-3 character text amplifier. A target number extension is a sequentially assigned number identifying the individual elements in a target (STANAG 5519), where character 1 is a dash (-) and characters 2-3 are number, from 1 through 15. It is applicable only to the “Point or Single Target” symbol, is conditional upon the presence of the Target Number amplifier, and is visually displayed appended to the Target Number amplifier. |  |
| AQ | Guarded Unit | During ballistic missile defense, some tracks are designated as guarded by a particular unit |  |
| AR | Special Designator | Special track designators such as Non-Real Time (NRT) and Tactically Significant (SIG) tracks are denoted here. |  |
| AS | Country | A three-letter code that indicates the country of origin of the organization (US systems shall use GENC). In stability activities, this field can be used for factions or groups. |  |