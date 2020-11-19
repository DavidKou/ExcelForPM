# Create timeline/milestone chart using Excel (Part II)

## The 2nd part walks through how to add fancier features such as current progress indicator etc. to a timeline or milestone chart using Excel. The chart is data driven, and the location, label, current progress of each milestone can be customized by updating the data directly in the excel table. The output of this part is shown below.

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/part(II).png)

## For Part I of this tutorial, click [here](https://github.com/DavidKou/ExcelForPM/blob/main/timeline-chart-I.md).

In part I, a basic timeline chart is created, and it looks like now:
![](https://github.com/DavidKou/ExcelForPM/blob/main/images/part(I).png)


We are going to add each node indicator to each milestone, indicating the "Completed" or "In Progress" state. To do so we need to create [combo chart](https://trumpexcel.com/combination-charts-in-excel/) in Excel.
<hr/>

**1. Add two columns of data: "Completed" and "In Progress"**

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/d4.png)

The data will be used as markers to indicate the current progress of the milestones.


**2. Convert the previous single series to a Combo chart**

- Select the chart desined in Part I.
- Drag the bottom right corner of the excel table to enlarge the data included in the chart
- Excel is smart enough to change this from a single chart to a combo chart.

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/ConvertToComboChart.gif)


**3. Change the chart type of the newly added data series**

- Select the orange chart (labelled with "Complete"), right click > Change Series Chart Type > Change the type from "Clustered Columns" --> "Line with Markers"
- Select the grey chart (labelled with "In Progress"), right click > Change Series Chart Type > Change the type from "Clustered Columns" --> "Line with Markers"

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c21.png)

The chart now looks like:<br/>
![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c22.png)

**4. Hide the line, show markers only for the two line charts**

- Select the two line charts
- Set the line style to "No line"
- Set the mark color and size

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c23.png)

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c24.png)

**5. Select the the chart value labels and delete them**

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c24.png)


**6. Update the table for all values 5 or -5, change them to 0**

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c24a.png)

This moves all marks to the horizontal line (y=0):

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c25.png)

And the chart now looks like:

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c26.png)


**7. Add legend to the chart**

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c27.png)

Remove the "Position" label, and leave the rest two legend labels.

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c28.png)


**8. Fine tune the Position column value and make it look neat**

![](https://github.com/DavidKou/ExcelForPM/blob/main/images/c29.png)
