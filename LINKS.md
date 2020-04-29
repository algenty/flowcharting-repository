# Link Mappings
In this section, you can add object/shapes from panel to link to an other dashboard/site with the conditions of current rule.

# Label/Text Mapping
In this section, you can change the text with the value of metric. 

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

## When
Define condition when link is available.
  - Warning/Critical : If state is OK, Shapes, arrows or text are not colored, keep orginal color.
  - Always : Objects defined in "Shape Mapping" are colored for each state.

## Url
Absolute URL or relative URL are accepted like :

A relative path to the dashboard
```
/d/VaxdbasZk/base?tab=visualization&panelId=2&edit&fullscreen&orgId=1
```

Or an absolute url to an external link
```
https://mysharepoint.com/path/document
```

URL can contain Grafana variables or local variables
[more detail ...](VARIABLES) 

NB : Only one url is accepted by object.

## Params
If checked, Flowcharting concats current url parameters of dashboard to the link.
