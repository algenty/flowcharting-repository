# Color/Tooltip Mappings
In this section, choose the shapes and conditions of use.

## Identify by
You can select the method of selection for the field "What" :    
    - by the uniq ID of shapes.
    - by the value of the text (experimental).

## Regular exression
If checked, the field "What" accepts a regular expression (less efficient) like this :
```
/.*My label.*/
```

## Buttons
  - ![remove](images/fa-remove.png) : Remove line/shapes from current rule
  - ![hide](images/fa-hide.png) : Hide and ignore line from current rule
  - ![link](images/fa-link.png) : Click on it to select shapes/object in panel and auto fill input with id object.

## What
Enter the id or text of shape, if the field "regular expression" is checked, regular expression is accepted but less efficient for performance.  
You can target/select the shape by clicking on link button.  
![images/fc_subway_example.png](images/fc_subway_example.png)

## When
Select when color is applied :
  - never : No color applied, only tooltip applied
  - Warning/Critical : If state is OK, Shapes, arrows or text are not colored, keep orginal color.
  - Always : Objects defined in "Shape Mapping" are colored for each state.

## How
Define the method to color :  
  - Shape Fill : Fill the object with the defined color and state.
  - Shape Stoke/Border : Color the object's perimeter with the defined color and state (Use it for the arrows).
  - Label font color : Color the object's label with the defined color and state.
  - Label border color : Color the border of text in shape.   
  - Label backgroud color : Color the background of text in shape .
  - Backgroud : only for the image like clipart, Color the image's backgroud.
  - Border : only for the image like clipart, Color the image's perimeter. 

![Metrics name example](images/colormode_ani.png)

## Example/Demo
[https://play.grafana.org/d/VbE3_jqZz/flowcharting-options-demo?orgId=1](https://play.grafana.org/d/VbE3_jqZz/flowcharting-options-demo?orgId=1)