# Tips and tricks

## Examples dashboards with Flowcharting
More examples dashboard at
https://flowcharting.grafana.net

## Zoom into a zone

Double click on empty zone without shape don't work, to zoom on a portion of the graph, we need to create a zone.  
  
Example :  

1. Replace source by value of this [model](https://raw.githubusercontent.com/algenty/flowcharting-repository/master/graphs/ch2_zone.drawio)
2. Open graph in with button "Edit Draw".
3. Create a zone with a rectangle.
4. Resize the zone with the aim that all "A" are in rectangle.
5. Put it to back.
6. In style panel, uncheck "fill" and "line" or keep it visible.
7. Duplicate rectangle : Select rectangle, hold Ctrl and move rectangle on "C".
8. Resize and repeat for the "B".
9.  Click on Save.
10. Double click on zone to test it.

[![animation](images/zoom_zone_ani.png)](images/zoom_zone_ani.png)

## Beautify your graph

In editor or draw.io, use "Shadow" and "Glass" to beautify the graph.
NB : Gradient is not supported at this time in plugin.

[![animation](images/tips_beautify.png)](images/tips_beautify.png)

## Floorplan colorization

In draw.io, use a rectangle to front on the room and reduce opacity to see under the rectangle when color changes.
Uncheck the line if you don't want to see the borderlines.

[![animation](images/floorplan_ani.png)](images/floorplan_ani.png)

## Variables
You can use variables in xml définition or url in link.  
Be carreful, at this time, only uncompressed xml supports variables.  
Syntax : ${myVariable}
Supported field with variables :
  - Source Content in flowchart section
  - URL in flowchart section when download source is active
  - Link mapping Url in Mapping section

[![animation](images/variable_link_ani.png)](images/variable_link_ani.png)


Again ? Send me your tips and tricks by email at <grafana.flowcharting@gmail.com>
