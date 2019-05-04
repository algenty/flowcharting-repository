# Getting started

In this page, by an exercice, you will understand the power of flowcharting.  
/!\ Page on beta

## installation

1. Install lastest version of plugin on you server
See last version in https://github.com/algenty/flowcharting-repository/tree/master/archives

    Here last version is agenty-flowcharting-panel-0.3.0-SNAPSHOT.zip
    ```shell
    cd <grafana_home>/data/plugin
    wget https://algenty.github.io/flowcharting-repository/archives/agenty-flowcharting-panel-0.3.0-SNAPSHOT.zip
    unzip agenty-flowcharting-panel-0.3.0-SNAPSHOT.zip
    ```

2. restart Grafana

## Dashboard
   1. Verify in grafana if plugin is ready  
       In menu : Configuration > Plugins > flowcharting

   ![flowcharting](images/plugin_conf.png)

   1. Define new dashboard and add flowcharting panel.  

## Configuration

   1. Edit the panel and enter in flowchart tab.  
   2. Replace content of XML by this code below. (source [here](https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=flowcharting_getting_started#R7VpZd6M4Gv019Thz2LEfJfbFbAbb%2BA2z7zZgA%2F71IxKnklRS1d1zunqbsc%2BJ0dUnId37LYKTLyRXT1IXnLNNG8XVFwKLpi8k%2F4UgCIyk0M%2BCzM8IjrH0M5J2efTAXoFtfo9fDB%2FoNY%2Fi%2Fp3h0LbVkJ%2Ffg2HbNHE4vMOCrmvH92ZJW72%2F6zlI4w%2FANgyqj%2Bg%2Bj4bsGV0R7Csux3mavdwZZ9bPPXXwYvzYSZ8FUTu%2BgUjhC8l1bTs8X9UTF1cLey%2B8PI8Tv9P7dWFd3Ay%2FZsDmhF3XJUyLa7ZzPDw13LPzr9VjbcP8suE4Qvt%2FNNtuyNq0bYJKeEVh116bKF5mxVDr1UZv2zMCcQQW8TDMDzGD69AiKBvq6tEbT%2FlwWIb%2Fm360%2FDc9%2FPSY%2BakxvzSaoZvfDFqa%2Ftu%2B12FPrZdxSdsMXFu13dPuSPbpi%2FB%2B6Nryq6TUV%2BSN7RpfvqjnI9MP8vv22oXxD%2Bh98digS%2BPhB3bEs93C%2FZsbPHSU4raO0Z6QQRdXwZDf3vtm8HDx9Kvdqxegi4cj%2FAanWP9dnOLvIS71lxL3Me8tqK4vm1tunsVBFHcfhH%2BVdeFqzPIh3p6DJ1pGlPHfS%2Fg9OZK8qt7g4tPnvxPlFndDPP2QxkcvST%2Fy7vxSi56b42sWx1%2Bw7E0GZ7CfRDzxgXguy1E1IjD8H0Q7Qb6nHWf%2BbN6p7%2FJO%2FIN4p9i%2FGu%2F0B97deBo%2BpX1YOt5x%2B56rpm3ib4h9QEGVpw1qhog5lL5IuDCWo%2BMbeHTUeRQ9FajPxHxftL6n5%2B%2BhzjfJCH%2BZ4o061CfiED9LHOZ74nzMRf94cchvU9afLQ7%2BsUa%2FKRWIDYD%2Bbl3getu%2FmVoL%2FjgB4tRL%2B7H4Tx5ofrOUOEO%2Bk5L6JAmSf6iUH6vPD4oO9stF5%2FtF5Htl5zPOP9PmRf8qTobfJ7Bw6hfV%2BKwi%2FTwxPpakN0eB%2F8fVr48rZvVnx9XHAva%2FG1efqPHHxtXql8Xos%2BC8XOb10wu3r0GgB6e4sto%2BH%2FJ2YenUDkNbI4Nq6YBBWKZPOr5hNnn6fBJIw%2FKqAQb9%2BflFYJJPi%2Frw6ZbgBcVeEHQdBUOAov65SYjnJv1CcPkOms6IaVLaAvQxtl4meCm6EpYmBBzw0S93CQ5y%2FITIBrfd2QoHUiUBWZkvIKjGrVjd0YU5oT98b8Nq25vSuAyoMGeXYR6xriM5ysLaAxEZkXpdXQPSKPwDrPR6PR%2Fp29WCyxpO1tZz4E7Ow%2Ftx6E6iI0pKkITkUc%2FHXaAPiiYC4TzYiqMUgZSPHQytEmoiX%2FoZhPZpEpRUXk2xgvYo5Lt4A0Fla7xTA5UrxDbdQePCc3V%2BEB0gbNO9dAHitiLYiidleTUQ1Rq70%2FdLQ3t9fb5j9xVJJl8ISNPk8Zps7nnr1zLjnRQds%2BeDflGpfY3uhOi2Du4Za%2B%2FSNd555%2FO2ngt18TQC5o3kn6SgBttSrdtSdEoENvpVp3TzkHPl3QwOBtAxj53R%2FBHIMogKKRw1m45XhFmv2tW68LctiiZYXhqgl2CXnkNVUQFvxmZKrcypNEUXE4Gq2%2Fjg%2BLk5NU5lVaszGlLVc26BBtuETsxHpaCgxA8vDExV22ZCOhJHnL8rx1G1E2e%2Fn%2FOyailPu7WJK0RZNifjkGZOK6XsWp31y46kxZbewJggZH1%2FpPH8Ai5G0OwHdQqGux4csFryDPmKnBfOO27EjUvCAwWbLmlLiyVXQqFPGAEFPdQLPAk9eozZeU5XHFjcch4qgeE7x7ItP5USDcU9k15r3eKTftihQZgr6GVur9k9auzrNE7psqJ53XzqC2VJvqFpDKcsz14zB4dIXeEyJrub%2FW2kTsbIVOQt70z3cHfMdFEIUgV9Giuwli%2F0Pt%2FIB5naXs4z3LI4PkVpa0Mzjg4g3hwU%2BbI9Ala6abWN6qgottIJXG3cXt93Ibq9Q2Okczvyt40eNwxzSrPzRdEZrc8TPqvpUJ6PsqJF9CWCgoDnnoYmgb0hyy6mKjsPnnrkSvAAEHXivce3gKRsSvUgkRR5BC0sdbSjJbJs6FLKLLTI9qQOUjNO98r11WviF8yEOITdHjGOdrcSQFqy1RAN2yI0gdXcWqPtSaEvs4PNX2eyvqAcALVpVcv6yJOXw7IgcEPAkhsj%2F0Sru4A7nYQwKjtAqYd4BFbJK7Zzoe53lGEhbqbNKbiKkrycLEQzZWdY4MO1dDnpilW2mAsgT5XjwSc7PLSlYR%2B6Qg4LoXFP8gwKSPjYDDaXTSmu6HnNb9IaEmBaG6rbluQ4HACgnYMOFkceeRXatus1%2FummzbOSEiNV41Ozo91Vm9mqzUeZm6qzWM9xBWi19VjeSYSVPzYj6u3iqTQ8yzM01033bgLwJNVbvjWwWR0N2KBgIFPfuttHcTodzlJ2T4JSA5oipsacn7MNY13TNVrH6m6HErhlObr2BW7jNyjKxRM0JiObzatNuoNTjcdtqCGDs9jQMU8kZD2OENtqqL6I4%2FlGcTJhulQJlVBAVovg6ux3F32JGllKBdBh5hjZqX%2Fzp1Ike15m49BZjxbwb%2BXxCLJdz0fOmIQ1rcAxYKUQO61mIlPdtWEIHpqG6y%2BTzLnTrR84OoowMo76YtRmlwe3w3iuZ0fW1SUMlaoPbpvEK5tMymsb47bGkZDH8Xjz7%2B3owyM2WzuDPJ%2BQ7Qb2nB4llSCBenXKj%2BqF5u6TbNOhiCniEe3jgA4rEBJ1ZxtbIZtQXblwNW815lr3FODWa9zFYL0jcwLcVJ3cxLfOPw7CDPsbbD2NgVcZd4ys18jWsIAERbQiw0JzBsl0uue0ELJXob85eQucC%2FK2JSsWa1OZaDif96gujVs0h47fA%2BaZWMqwrF1yAuRKljszdP3bkkeRsldhh7YklrwjoiOwCDxm5gQUEGJGF4KBftmIMuIZ8G0JDJ2oIe%2FoaVJqLVBHbiWkil2EnMNP%2BlBe1uJmFskUuBiVzb24B9LI9RnQUekQU8rkIk%2Bz2oOibDZNQ97oi27orexOIGQ2Y9YZvNepVrFyDBqlMZFcvMCzV2Z%2FGG%2FFEN9ZcOkXXyJP3F0UujgTmHWxkc9TFyK6BOdSMJLPXsU%2BZterUUJTVKGpohMAyqfCPICoAEVD%2BkqpEZQBDn4UK0t6ZlkqEiZgsnoSNGwP18XkkNeEX3HlYeod5Rq3ncJS1H2ZEUqnPvO1aZ02CpN2BY7p8QaxBK2Z8ZPq6EW6doYdLYz9qGk0vhBZ7xmxRxlC0jGUUOCSse7qkBXFpcsEGqqzduB7GSuzJd3wFa%2F4sqN0rQQ83Rqd65KcuLnY2UPIOii1ujvewZZNadNhSyUZg1uTRhe73ird0F6YFltVsqjtTUxVKUkgvVoWnh7h%2BrkSs3cM7f8WhE2xwYnitB%2FZfdmSNsmLmC6zGa8UJoZZySYu5JYd2uhgpN5VPnrFkt77UJ9vzHEegdFFsBczZ0PI2jFLmYy99Q1m2EaKBYW9ui%2FyacqYK7vMxZEbdwigKIe6OqjwJ1aa3T11xSWaH5lUZMHlRKqXDbVFC%2B0dZGvqNTyGgJlQihXdC6ZKuh%2Bah5gHwQCxZHIaHNLAP9VznUQFNNP2JNlrqbxW8GxGNzFOuOTq6dvJscUQimAXxcfDAZNTdHeDgyRzXTLWSDV0at7SYKEmbPfIfayYcdYwmGVv01SbAPjILGQtmjFUPlb1I2Ow7nAhqoUO3wiMsUwVU2MkNlgCTdbT3ZmMg4um2U%2Fnwq23Mx2N5nxFWU6zv8vzAP3Nu1%2BC%2BVXvr6if9jyw%2FvA8kMbDkC%2FHa2w7BGhf0V%2F4Afvloe4nv3b8VrVPnuJ%2Bp7eOqPn6bwZPfW%2F%2BW4MU%2FgM%3D))   

    ```
    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
    ```

   3. Click on button 'Extract/decode' and 'Pretify' to display xml code
   4. By Hold the right button of mouse in graph, you can move schema in panel

### Flowchart definition

  Firts, Flowcharting uses uniq id of objets. We need know witch is candidate of mapping values/conditions.
  In next release the matching with object accept values and attributes.

  The ids in draw.io are generated with a number or a string, you cannot rename or only in xml but its boring and dangerous.
  In Inspect panel, its possible to rename it. if you want to keep this id, its possible to use "mapping helper" to find the good id.

  ![Rename Id](images/inspect_rename_id_small.png)

  1. Go to inspect Tab, and double click on id with the names in the table below.
      when cursor move over id name, object in panel is selected.

      | Old ID | New Id |
      |:--:|:--:|
      |Mb0u9kBgjuhVRU1gNTpR-8|CHILD1-ARROW|
      |Mb0u9kBgjuhVRU1gNTpR-9|CHILD2-ARROW|
      |Mb0u9kBgjuhVRU1gNTpR-1|HEADER-SHAPE|
      |Mb0u9kBgjuhVRU1gNTpR-2|CHILD1-SHAPE|
      |Mb0u9kBgjuhVRU1gNTpR-4|CHILD2-SHAPE|
      |Mb0u9kBgjuhVRU1gNTpR-5|FLOW1-TEXT|
      |Mb0u9kBgjuhVRU1gNTpR-5|FLOW2-TEXT|
      |Mb0u9kBgjuhVRU1gNTpR-14|CHILD1-STATUS|
      |Mb0u9kBgjuhVRU1gNTpR-16|CHILD2-STATUS|
      |Mb0u9kBgjuhVRU1gNTpR-11|CHILD1-LEGEND|
      |Mb0u9kBgjuhVRU1gNTpR-15|CHILD2-LEGEND|

  2. Then click on button 'Apply change' or 'Reinit' to cancel change.
      You can also replace XML content in flowchart tab with value below :)  

      ```
      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
      ```

  3. Verify in flowchart tab, the result in xml content.

      ```xml
        <mxCell id="CHILD1-ARROW" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontColor=#737373;strokeWidth=4;strokeColor=#919191;" parent="1" source="HEADER-SHAPE" target="CHILD1-SHAPE" edge="1">
          <mxGeometry relative="1" as="geometry"/>
        </mxCell>
      ```

  That seems good.

### Metrics

  We'll define 4 metrics :  
  2 metrics for flows, one by child.  
  2 metrics for status, one by child.  

  1. Go to metric tab and add metric like below

      ![metrics](images/getting_started_metrics.png)

### Mapping

  We need to map objects/text with metrics, in this tab you can add rules to define conditions to display colors and values.
  In example, we need 4 rules for 4 metrics, click on mapping tab

  **Definition of flow 1 and 2**

  We don't need state and color, just value displayed.
  Enter the value below, if you don't have no first rule, click on button "Add Rule"

  **Rule Name :** Flow 1  
  **Apply to metrics named :** FLOW-1  

  ![inputs](images/getting_started_rule1_inputs.png)

  Now go to text mapping, click on '+' icon and 'Chain' icon and click on text 1
  Click on copy rule and repeat action for the _flow 2_ like this :  

  **Rule Name :** Flow 2  
  **Apply to metrics named :** FLOW-2  

  [![mapping text flow 1 and 2](images/getting_started_mapping_text_small.png)](images/getting_started_mapping_text_large.png)

  Now values are displayed

  ![Display values](images/getting_started_mapping_values_displayed.png)

  You can also enter the object's name in the field of text maps. when cursor is over field, object is selected in panel.

  Now, it's time to color child 1 and child 2 according to state.  
  The header shoulds take level of highter children's states.

  **Definition of states**

  Add a new rule by clicking on button "+ Add rule" and enter the paramter below

  **Rule Name :** Child 1
  **Apply to metrics named :** STATUS-1  
  **Thresholds :** 30,60

  On color Mapping, click 3 times on + and enter  
  * CHILD1-SHAPE  
  * CHILD1-STATUS  
  * HEADER-SHAPE  

  ![child 1](images/mapping_coloron_rule_child1.png)  
    
  Observe colors change in graph  
  ![state](images/coloron_mapping_child1_result.png)  

  Display the status in legend
  In the same rule, change type to string

  In Value Mappings, change type to "Range to text" and enter values below :  
  ![range](images/getting_started_rangetext.png)


  Change in field "Update text value", "All Content" by "Substring" and enter "/STATUS/" in "Text pattern".  

  [![animation](images/getting_started_mapping_text_legend_small.png)](images/getting_started_mapping_text_legend_large.png)


  Repeat steps for Child 1 for Child 2 with copy rule or a new rule

  ![child2](images/getting_started_mapping_text_middle_child2.png)


  At result, note that header takes highest level when it included in 2 rules of children.  
  
  ![result](images/getting_started_result.png)


# Annexe

## Complete dashboad
```JSON
{
  "flowchartsData": [
    {
      "name": "Main",
      "xml": "<mxGraphModel>\n    <root>\n        <mxCell id=\"0\"/>\n        <mxCell id=\"1\" parent=\"0\"/>\n        <mxCell id=\"CHILD1-ARROW\" style=\"edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;fontColor=#737373;strokeWidth=4;strokeColor=#919191;\" parent=\"1\" source=\"HEADER-SHAPE\" target=\"CHILD1-SHAPE\" edge=\"1\">\n            <mxGeometry relative=\"1\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD2-ARROW\" style=\"edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;fontColor=#737373;strokeWidth=4;strokeColor=#919191;\" parent=\"1\" source=\"HEADER-SHAPE\" target=\"CHILD2-SHAPE\" edge=\"1\">\n            <mxGeometry relative=\"1\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"HEADER-SHAPE\" value=\"My header\" style=\"rounded=1;whiteSpace=wrap;html=1;fontColor=#737373;fillColor=#FFFFFF;strokeColor=#919191;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"350\" y=\"20\" width=\"120\" height=\"60\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD1-SHAPE\" value=\"Child 1\" style=\"rounded=1;whiteSpace=wrap;html=1;fontColor=#737373;fillColor=#FFFFFF;strokeColor=#919191;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"230\" y=\"160\" width=\"120\" height=\"60\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD2-SHAPE\" value=\"Child 2\" style=\"rounded=1;whiteSpace=wrap;html=1;fontColor=#737373;fillColor=#FFFFFF;strokeColor=#919191;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"470\" y=\"160\" width=\"120\" height=\"60\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"FLOW2-TEXT\" value=\"Text 2\" style=\"text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontColor=#737373;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"450\" y=\"121\" width=\"40\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"FLOW1-TEXT\" value=\"Text 1\" style=\"text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontColor=#737373;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"330\" y=\"121\" width=\"40\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD1-LEGEND\" value=\"Child 1 : STATUS\" style=\"text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontColor=#737373;fontSize=14;fontStyle=1\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"163\" y=\"40\" width=\"130\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD1-STATUS\" value=\"\" style=\"rounded=0;whiteSpace=wrap;html=1;strokeColor=#919191;fillColor=#FFFFFF;fontSize=14;fontColor=#737373;align=left;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"143\" y=\"40\" width=\"20\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD2-LEGEND\" value=\"Child 2 : STATUS\" style=\"text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontColor=#737373;fontSize=14;fontStyle=1\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"163\" y=\"68\" width=\"130\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"CHILD2-STATUS\" value=\"\" style=\"rounded=0;whiteSpace=wrap;html=1;strokeColor=#919191;fillColor=#FFFFFF;fontSize=14;fontColor=#737373;align=left;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"143\" y=\"68\" width=\"20\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"Mb0u9kBgjuhVRU1gNTpR-18\" value=\"\" style=\"shape=image;verticalLabelPosition=bottom;labelBackgroundColor=#ffffff;verticalAlign=top;aspect=fixed;imageAspect=0;image=data:image/png,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;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"570\" y=\"26\" width=\"40\" height=\"40\" as=\"geometry\"/>\n        </mxCell>\n        <mxCell id=\"Mb0u9kBgjuhVRU1gNTpR-19\" value=\"getting Started\" style=\"text;html=1;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;whiteSpace=wrap;rounded=0;fontSize=10;fontColor=#737373;\" parent=\"1\" vertex=\"1\">\n            <mxGeometry x=\"570\" y=\"68\" width=\"40\" height=\"20\" as=\"geometry\"/>\n        </mxCell>\n    </root>\n</mxGraphModel>",
      "type": "xml",
      "url": "http://<source>:<port>/<pathToXml>",
      "zoom": "100%",
      "center": false,
      "scale": false,
      "lock": true,
      "tooltip": true,
      "grid": false
    }
  ],
  "format": "short",
  "graphId": "flowchart_2",
  "gridPos": {
    "h": 11,
    "w": 17,
    "x": 0,
    "y": 0
  },
  "id": 2,
  "newFlag": false,
  "rulesData": [
    {
      "pattern": "FLOW-2",
      "unit": "short",
      "type": "number",
      "alias": "Flow 2",
      "aggregation": "current",
      "decimals": 2,
      "colors": [
        "rgba(245, 54, 54, 0.9)",
        "rgba(237, 129, 40, 0.89)",
        "rgba(50, 172, 45, 0.97)"
      ],
      "style": "fillColor",
      "colorOn": "a",
      "link": false,
      "linkOn": "a",
      "linkUrl": "",
      "textOn": "wmd",
      "textReplace": "content",
      "textPattern": "/.*/",
      "dateFormat": "YYYY-MM-DD HH:mm:ss",
      "thresholds": [],
      "invert": false,
      "overlayIcon": false,
      "shapeProp": "id",
      "shapeData": [],
      "textProp": "id",
      "textData": [
        {
          "pattern": "FLOW2-TEXT",
          "hidden": false
        }
      ],
      "linkProp": "id",
      "linkData": [],
      "mappingType": 1,
      "valueData": [],
      "rangeData": [],
      "sanitize": false,
      "reduce": true
    },
    {
      "pattern": "FLOW-1",
      "unit": "short",
      "type": "number",
      "alias": "Flow 1",
      "aggregation": "current",
      "decimals": 2,
      "colors": [
        "rgba(245, 54, 54, 0.9)",
        "rgba(237, 129, 40, 0.89)",
        "rgba(50, 172, 45, 0.97)"
      ],
      "style": "fillColor",
      "colorOn": "a",
      "link": false,
      "linkOn": "a",
      "linkUrl": "",
      "textOn": "wmd",
      "textReplace": "content",
      "textPattern": "/.*/",
      "dateFormat": "YYYY-MM-DD HH:mm:ss",
      "thresholds": [],
      "invert": false,
      "overlayIcon": false,
      "shapeProp": "id",
      "shapeData": [],
      "textProp": "id",
      "textData": [
        {
          "pattern": "FLOW1-TEXT",
          "hidden": false
        }
      ],
      "linkProp": "id",
      "linkData": [],
      "mappingType": 1,
      "valueData": [],
      "rangeData": [],
      "sanitize": false,
      "reduce": true
    },
    {
      "pattern": "STATUS-2",
      "unit": "short",
      "type": "string",
      "alias": "Child 2",
      "aggregation": "current",
      "decimals": 2,
      "colors": [
        "rgba(245, 54, 54, 0.9)",
        "rgba(237, 129, 40, 0.89)",
        "rgba(50, 172, 45, 0.97)"
      ],
      "style": "fillColor",
      "colorOn": "a",
      "link": false,
      "linkOn": "a",
      "linkUrl": "",
      "textOn": "wmd",
      "textReplace": "pattern",
      "textPattern": "/STATUS/",
      "dateFormat": "YYYY-MM-DD HH:mm:ss",
      "thresholds": [
        "30",
        "60"
      ],
      "invert": false,
      "overlayIcon": false,
      "shapeProp": "id",
      "shapeData": [
        {
          "pattern": "CHILD2-SHAPE",
          "hidden": false
        },
        {
          "pattern": "HEADER-SHAPE",
          "hidden": false
        },
        {
          "pattern": "CHILD2-STATUS",
          "hidden": false
        }
      ],
      "textProp": "id",
      "textData": [
        {
          "pattern": "CHILD2-LEGEND",
          "hidden": false
        }
      ],
      "linkProp": "id",
      "linkData": [],
      "mappingType": 2,
      "valueData": [],
      "rangeData": [
        {
          "from": "-50",
          "to": "30",
          "text": "KO",
          "hidden": false
        },
        {
          "from": "30",
          "to": "60",
          "text": "WARN",
          "hidden": false
        },
        {
          "from": "60",
          "to": "500",
          "text": "OK",
          "hidden": false
        }
      ],
      "sanitize": false,
      "reduce": true
    },
    {
      "pattern": "STATUS-1",
      "unit": "short",
      "type": "string",
      "alias": "Child 1",
      "aggregation": "current",
      "decimals": 2,
      "colors": [
        "rgba(245, 54, 54, 0.9)",
        "rgba(237, 129, 40, 0.89)",
        "rgba(50, 172, 45, 0.97)"
      ],
      "style": "fillColor",
      "colorOn": "a",
      "link": false,
      "linkOn": "a",
      "linkUrl": "",
      "textOn": "wmd",
      "textReplace": "pattern",
      "textPattern": "/STATUS/",
      "dateFormat": "YYYY-MM-DD HH:mm:ss",
      "thresholds": [
        "30",
        "60"
      ],
      "invert": false,
      "overlayIcon": false,
      "shapeProp": "id",
      "shapeData": [
        {
          "pattern": "CHILD1-SHAPE",
          "hidden": false
        },
        {
          "pattern": "HEADER-SHAPE",
          "hidden": false
        },
        {
          "pattern": "CHILD1-STATUS",
          "hidden": false
        }
      ],
      "textProp": "id",
      "textData": [
        {
          "pattern": "CHILD1-LEGEND",
          "hidden": false
        }
      ],
      "linkProp": "id",
      "linkData": [],
      "mappingType": 2,
      "valueData": [],
      "rangeData": [
        {
          "from": "-50",
          "to": "30",
          "text": "KO",
          "hidden": false
        },
        {
          "from": "30",
          "to": "60",
          "text": "WARN",
          "hidden": false
        },
        {
          "from": "60",
          "to": "500",
          "text": "OK",
          "hidden": false
        }
      ],
      "sanitize": false,
      "reduce": true
    }
  ],
  "targets": [
    {
      "alias": "FLOW-1",
      "refId": "A",
      "scenarioId": "random_walk"
    },
    {
      "alias": "FLOW-2",
      "refId": "B",
      "scenarioId": "random_walk"
    },
    {
      "alias": "STATUS-1",
      "refId": "C",
      "scenarioId": "random_walk"
    },
    {
      "alias": "STATUS-2",
      "refId": "D",
      "scenarioId": "random_walk"
    }
  ],
  "title": "Panel Title",
  "type": "agenty-flowcharting-panel",
  "valueName": "current",
  "version": "0.3.0"
}
```
