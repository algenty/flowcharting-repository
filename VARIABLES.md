# Variables

## Grafana Variables
You can use variables in xml définition or url in link.  
Be carreful, at this time, only uncompressed xml supports variables.  
Syntax : ${myVariable}
Supported field with variables :
  - Source Content in flowchart section
  - URL in flowchart section when download source is active
  - Link mapping Url in Mapping section

[![animation](images/variable_link_ani.png)](images/variable_link_ani.png)

## Custom variables
Custom variables and eval are availables on fields :
  - Text/Label Mapping, field 'With'  
  - Event Mapping, field 'value'  
  - Link Mapping, field 'Url'

List of custom variables :
 - ${_level} : Current level
 - ${_color} : Current color
 - ${_rule} : Name of rule
 - ${_value} : Raw value
 - ${_formated} : Formated value