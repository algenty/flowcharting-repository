# Mapping and rules
Add a rule by clicking on button "Add Rule", organize your rules order with arrows at left rule header.
The rules are defined in 2 zones :
  - The conditions
  - The targets if the following conditions are met  

![Metrics name example](images/rules_conditions.png)

## Rule name  
  Enter rule name, for infomation. It display on the header of rule.

## Apply to metrics 
  Enter alias of metric or regular pattern of metric for this rule, metric are aggregated and values are used to evaluate state.  
  ![Metrics name example](images/mp_metrics_name.png)

## Aggregation
  Select aggregation value of series for apply current rule.

  - **min** : The smallest value in the series
  - **max** : The largest value in the series
  - **avg** : The average of all the non-null values in the series
  - **last/current** : The last value in the series. If the series ends on null the previous value will be used.
  - **total** : The sum of all the non-null values in the series
  - **first** : The first value in the series
  - **delta** : The total incremental increase (of a counter) in the series.
  - **diff** : The difference between ‘current’ (last value) and ‘first’.
  - **range** : The difference between ‘min’ and ‘max’. Useful the show the range of change for a gauge.


## Type
### Number
  Unit and Decimals: Specify unit and decimal precision for numbers.

### String
#### Value/Range to text mapping
  Value/Range to text mapping allows you to translate the value of the summary stat into explicit text. The text will respect all styling, thresholds and customization defined for the value. This can be useful to translate the number of the main shape/text value into a context-specific human-readable word or message.

### Date
  Specify date format. Only available when Type is set to Date.

### Decimals
  Number of decimal to display, only for number type


## Thresholds
  Change the shape and value colors dynamically within the panel.  
  [more detail...](THRESHOLDS)



## Tooltips
Enable popup when curos is on shape with values and tooltips
[more detail...](TOOLTIPS)

## Color Mappings
In this section, you can add object/shapes from panel to colorize it with the conditions of current rule.  

[more detail...](SHAPES)

## Text Mappings
In this section, you can change the text with the value of metric.

[more detail...](TEXTS)


## Link Mappings
In this section, you can add object/shapes from panel to link to an other dashboard/site with the conditions of current rule.

[more detail...](LINKS)

## Event Mapping
In this section, you can customize custom animation or event like blink, opacity and more.

[more detail...](EVENTS)