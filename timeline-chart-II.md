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





