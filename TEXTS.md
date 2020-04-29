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
![images/fc_subway_example.png](images/fc_subway_example.png)

## When
Define condition when text/values is displayed.
  - Never : Hide text
  - When metric displayed : Show data if serie not empty.
  - Warning/Critical : Display value instead original selected text if non OK.
  - Critical only : Same, but only if state is critical.

## How
Define which part of text is replaced vy values.
  - All content : Replace all text by the formatted value.
  - Substring : only a part of string with a regular expression in field "with"  
  - Append (new line) : Append formated value with a carriage return.
  - Append (new line) : Append formated value with a space at right.

## With
Enter a regular expression when substring is selected.  

### Example :  
Original text = "Number of sessions : VALUE".  
Change "VALUE" with this pattern "/VALUE/" and keep string before.  

![See full example animation](images/example_text_pattern.png)

### Demo
[https://play.grafana.org/d/VbE3_jqZz/flowcharting-options-demo?orgId=1](https://play.grafana.org/d/VbE3_jqZz/flowcharting-options-demo?orgId=1)