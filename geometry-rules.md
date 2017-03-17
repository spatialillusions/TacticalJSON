# Geometry Rules

This document will show how geometries should be stored in TacticalJSON. It is based on the geometry rules in MIL-STD-2525D and then mapped to different geometry types in GeoJSON.

| Type | Anchor Points | TacticalJSON |
|--|--|--|
| Area1 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. Add as many points as necessary to accurately reflect the area’s size and shape. | `Polygon` |
| Area2 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. Add as many points as necessary to accurately reflect the area’s size and shape. The LAA point symbol requires one anchor point and is connected to the area symbol with a straight line. | `Polygon` |
| Area3 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. Add as many points as necessary to accurately reflect the area’s size and shape. | `Polygon` |
| Area4 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. Add as many points as necessary to accurately reflect the area’s size and shape. | `Polygon` |
| Area5 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the semicircle's opening. Point 3 defines the end of the arrow. | `Polygon` |
| Area6 | Anchor Points: This symbol requires two anchor points. Point 1 defines the center point of the symbol and point 2 defines the symbol’s start point and radius. | `Polygon` |
| Area7 | Anchor Points: This symbol requires three anchor points. Point 1 is the tip of the arrowhead. Points 2 and 3 define the endpoints of the straight line on the back side of the symbol. | `Polygon` |
| Area8 | Anchor Points: This symbol requires four anchor points. Points 1 and 2 define the endpoints of the straight line on the back side of the symbol. Points 3 and 4 define the tips of the arrowheads. | `Polygon` |
| Area9 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. Add as many points as necessary to accurately reflect the area’s size and shape. | `Polygon` |
| Area10 | Anchor Points: This symbol requires a minimum of three (3) and a maximum of six (6) anchor points to define the boundary of the area. The anchor points shall be sequentially numbered, in increments of one (1), beginning with point one (1). | `Polygon` |
| Area11 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the symbol’s vertical line. Point 3 defines the endpoint of the symbol’s horizontal line. | `Polygon` |
| Area12 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the end points of the symbol’s vertical line. Point 3 defines the tip of the longest arrow. | `Polygon` |
| Area13 | Anchor Points: This symbol requires at least two anchor points. Points 1 and 2 define the corners of the symbol. | `Polygon` |
| Area14 | Anchor Points: This symbol requires three anchor points. The center point defines the center of the symbol. Points 1 and 2 define the radii of circles 1 and 2. | `Polygon` |
| Area15 | Anchor Points: This symbol requires two anchor points. Point 1 defines the center point of the symbol and point 2 defines the symbol’s start point and radius. | `Polygon` |
| Area16 | Anchor Points: This symbol requires two anchor points. Point 1 defines the center point of the symbol and point 2 defines the symbol’s start point and radius. | `Polygon` |
| Area17 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the symbol’s vertical line. Point 3 defines the rear of the symbol. | `Polygon` |
| Area18 | Anchor Points: This symbol requires four anchor points. Point 1 defines the tip of the first arrowhead. Point 2 defines the end of the straight line portion of the first arrow. Point 3 defines the tip of the second arrowhead. Point 4 defines the end of the second arrow. |  |
| Area19 | Anchor Points: This symbol requires two anchor points. Point 1 defines the center point of the symbol and point 2 defines the symbol’s start point and radius. | `Polygon` |
| Area20 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. Add as many points as necessary to accurately reflect the area’s size and shape. | `Polygon` |
| Area21 | Anchor Points: This symbol requires three anchor points. Point 1 defines the vertex of the symbol. Points 2 and 3 define the tips of the arrowheads. | `Polygon` |
| Area22 | Anchor Points: This symbol requires one anchor point. The center point defines the center of the symbol. | `Polygon` |
| Area23 | Anchor Points: This symbol requires at least three anchor points to define the boundary of the area. | `Polygon` |
| Area24 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the symbol’s vertical line. Point 3 defines the endpoint of the symbol’s horizontal line. | `Polygon` |
| Area25 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the end points of the symbol’s vertical line. Point 3 defines the tip of the longest arrow. | `Polygon` |
| Area26 | Anchor Points: This symbol requires a minimum of 6 anchor points.  Add as many pairs of points as needed to accurately define the areas.  The number of points shall always be an even number, with an equal number of points for both polygons.  Points 1 through N/2 define the inner safe zone (zone 1).  Points N/2 +1 though point N defines the outer zone (zone 2). | `Polygon` |
| Point1 | Anchor Points: This symbol requires one anchor point. The anchor point defines/is the tip of the inverted cone. | `Point` |
| Point2 | Anchor Points: This symbol requires one anchor point. The center point defines/is the center of the symbol. | `Point` |
| Point3 | Anchor Points: This symbol requires one anchor point. | `Point` |
| Point4 | Anchor Points: This symbol requires one anchor point. The point defines the bottom of the central vertical line in the symbol where the curved and vertical lines meet. | `Point` |
| Point5 | Anchor Points: This symbol requires one anchor point. The point defines the point where all the lines meet. | `Point` |
| Point6 | Anchor Points: This symbol requires one anchor point. The anchor point defines/is the center of the bottom of the control measure symbol as shown in the template and example. | `Point` |
| Point7 | Anchor Points: This symbol requires one anchor point. The anchor point defines the midpoint of the symbol’s base. | `Point` |
| Point8 | Anchor Points: This symbol requires one anchor point. The center point defines the center of the symbol. | `Point` |
| Point9 | Anchor Points: This symbol requires one anchor (center) point. The point defines the center of the symbol. | `Point` |
| Point10 | Anchor Points: This symbol requires one anchor point. The point defines the center of the circle. | `Point` |
| Point11 | Anchor Points: This symbol requires one center point. The point defines the center of the symbol.  | `Point` |
| Point12 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the tips of the arrowheads and point 3 defines the rear of the symbol. | `Point` |
| Point13 | Anchor Points: This symbol requires one anchor point. The center point defines the center of the circle. | `Point` |
| Point14 | Anchor Points: This symbol requires one anchor point. The center point defines the center of the symbol. | `Point` |
| Point15 | Anchor Points: This symbol requires one anchor point. The anchor point defines “nose” of the symbol. | `Point` |
| Point16 | Anchor Points: This symbol requires one anchor point; the point defines the circle at the base of the tower. | `Point` |
| Line1 | Anchor Points: This symbol requires at least two anchor points, points 1 and 2, to define the line. Additional points can be defined to extend the line.  | `LineString` |
| Line2 | Anchor Points: This symbol requires at least two anchor points, points 1 and 2, to define the line. Additional points can be defined to extend the line.  | `LineString` |
| Line3 | Anchor Points: This symbol requires three anchor points. Point 1 defines the vertex of the symbol. Points 2 and 3 define the tips of the arrowheads. | `LineString` |
| Line4 | Anchor Points: This symbol requires two anchor points. Points 1 and 2 define the corner points of the symbol. | `LineString` |
| Line5 | Anchor Points: This symbol requires two anchor points. Points 1 and 2 define the endpoints of the symbol. | `LineString` |
| Line6 | Anchor Points: This symbol requires 3 anchor points. Point 1 defines the vertex of the symbol and points 2 and 3 define its endpoints. | `LineString` |
| Line7 | Anchor Points: This symbol requires at least two anchor points, points 1 and 2, to define the line. Additional points can be defined to extend the line.  | `LineString` |
| Line8 | Anchor Points: This symbol requires a minimum of two (2) anchor points. Up to 298 additional points can be added to extend the line. The first point (point 1) defines the start point. The last point defines the endpoint. The points are numbered sequentially beginning with point one (1), in increments of one. | `LineString` |
| Line9 | Anchor Points: This symbol requires 2 anchor points. Point 1 defines the tip of the arrowhead and point 2 defines the rear of the symbol.2 | `LineString` |
| Line10 | Anchor Points: This symbol requires two anchor points. Point 1 defines the rear of the symbol. Point 2 defines the tip of the arrowhead. Point 3 defines the 90 degree arc. | `LineString` |
| Line11 | Anchor Points: This symbol requires four points. Points 1 and 2 define one side of the gap and points 3 and 4 define the opposite side of the gap. | `LineString` |
| Line12 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the symbol and point 3 defines the location of one side of the symbol. | `LineString` |
| Line13 | Anchor Points: This symbol requires at least two anchor points, points 1 and 2, to define the line. Additional points can be defined to extend the line. | `LineString` |
| Line14 | Anchor Points: This symbol requires two anchor points. Points 1 and 2 define the tips of the arrowheads. | `LineString` |
| Line15 | Anchor Points: This symbol requires two anchor points. Points 1 and 2 define the length and orientation of the straight line (trip wire) portion of the symbol.  | `LineString` |
| Line16 | Anchor Points: This symbol requires four points. Points 1 and 2 define one side of the assault crossing site and points 3 and 4 define the opposite side of the assault crossing site. | `LineString` |
| Line17 | Anchor Points. This symbol requires three anchor points. Points 1 and 2 define the endpoints of the first line. Point 3 defines the location of the parallel line. | `LineString` |
| Line18 | Anchor Points: This symbol requires two anchor points. Points 1 and two define the tips of the arrowheads. | `LineString` |
| Line19 | Anchor Points: This symbol requires two anchor points. Points 1 and two define the corners on the front of the symbol. | `LineString` |
| Line20 | Anchor Points: This graphic requires two anchor points. Point 1 defines the tip of the arrowhead, and point 2 defines the rear of the graphic. | `LineString` |
| Line21 | Anchor Points: This symbol requires at least two anchor points to define the line. Additional points can be defined to extend and shape the line. | `LineString` |
| Line22 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the symbol’s opening and point 3 defines the rear of the symbol. | `LineString` |
| Line23 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the symbol’s vertical line and point 3 defines the rear of the symbol. | `LineString` |
| Line24 | Anchor Points: This symbol requires three anchor points. Point 1 defines the tip of the arrowhead. Point 2 defines the end of the straight line portion of the symbol. Point 3 defines the diameter and orientation of the 180 degree circular arc. | `LineString` |
| Line25 | Anchor Points: This symbol requires exactly two anchor points. Point 1 defines the tip of the arrowhead and point 2 defines the rear of the symbol. | `LineString` |
| Line26 | Anchor Points: Where four points are available Point 1 and Point 2 define the ends of one arrow and Point 3 and Point 4 define the ends of the other arrow. Point 1 and Point 4 define the ends of their respective arrowheads. Where three points are available Point 1 defines the vertex of the symbol. Points 2 and 3 define the tips of the arrowheads. | `LineString` |
| Line27 | Anchor Points: Where four points are available Point 1 defines the center of the circle. Point 2 defines the radius of the circle. Point 3 defines the curvature of the arc. Point 4 defines the end of the arrow. Where three points are available Point 1 defines the center point of the circle. Point 2 defines the tip of the arrowhead. Point 3 defines the 90 degree arc. | `LineString` |
| Line28 | Anchor Points: This symbol requires 2 anchor points. Point 1 defines the tip of the arrowhead, and point 2 defines the rear of the symbol. | `LineString` |
| Line29 | Anchor Points: This symbol requires three anchor points. Point 1 is the tip of the arrowhead. Points 2 and 3 define the endpoints of the curved line on the back side of the symbol.  | `LineString` |
| Corridor1 | Anchor Points: This symbol may contain multiple segments. Each segment requires 2 anchor points. Point numbers that define the trace of the segment are sequential beginning with point 1, in increments of 1, up to a max of 99 points. Each anchor point defines the endpoint of a segment’s centerline. The anchor points are Air Control Points (ACP), Communications Checkpoints (CCP) or both. | `LineString` |
| Axis1 | Anchor Points: The symbol requires N anchor points, where N is between 3 and 50. Point 1 defines the tip of the arrowhead. Point N-1 defines the rear of the symbol. Point N defines the back of the arrowhead. Anchor points are numbered sequentially beginning with point number one (1), in increments of one (1). | `LineString` |
| Axis2 | Anchor Points: The symbol requires N anchor points, where N is between 3 and 50. Point 1 defines the tip of the arrowhead. Point N-1 defines the rear of the symbol. Point N defines the back of the arrowhead. Anchor points are numbered sequentially beginning with point number one (1), in increments of one (1). | `LineString` |
| Polyline1 | Anchor Points: This symbol requires three anchor points. Points 1 and 2 define the endpoints of the infiltration lane and point 3 defines the width on one side of the lane. | `LineString` |
| Ellipse1 | Anchor Points: This symbol requires one anchor point. This anchor point represents the center of an ellipse and, therefore, the geographic location of that ellipse. | `Point` |
| Rectangular1 | Anchor Points: This symbol requires two anchor points and a width, defined in meters, to define the boundary of the area. Points 1 and 2 will be located in the center of two opposing sides of the rectangle. | `LineString` |
| Rectangular2 | Anchor Points: This symbol requires one (1) anchor point to define the center of the area. | `Point` |
| Rectangular3 | Anchor Points: This symbol requires one anchor (center) point to define the center of the symbol. The target tactical symbol shall be centered upon the center of the area. The size and the orientation of the target symbol are fixed within the area. | `Point` |
| Circular1 | Anchor Points: This symbol requires one (1) anchor point and a radius. Point 1 defines the center point of the symbol. | `Point` |
| Circular2 | Anchor Points: This symbol requires one anchor point that defines an object at a dynamic grid location. This coordinate, which pinpoints the current physical location of a specific unit, weapon or acquisition system, may change with the movement of the object. The symbol for that object is located at the anchor point. | `Point` |
| Arc1 | Anchor Points: This symbol requires one anchor point that defines an object at a dynamic grid location. This coordinate, which pinpoints the current physical location of a specific unit, weapon or acquisition system, may change with the movement of the object. The symbol for that object is located at the anchor point. | `Point` |
