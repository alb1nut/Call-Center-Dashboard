# Call Center Data Analysis Project

![image](https://github.com/alb1nut/Call-Center-Dashboard/assets/86856866/01ab7d0b-f0f9-4421-ab90-2f59f6d9aef1)


## Project Overview
This project involves analyzing a Call Center dataset to generate meaningful insights and visualizations. The dataset contains information about calls, agents, topics, and satisfaction ratings. The goal is to clean the data, perform analysis, and create a dashboard to display key performance indicators (KPIs).

## Steps

### Data Cleaning and Preparation

1. **Format the Data as a Table**
   - Select the entire dataset.
   - Go to `Insert` > `Table` to format the data as a table.

2. **Check for Duplicates in CALLER ID Column**
   - Select the CALLER ID column.
   - Go to `Home` > `Conditional Formatting` > `Highlight Cells Rules` > `Duplicate Values`.

3. **Check for Empty Cells in AGENT Column**
   - Apply a filter to the AGENT column.
   - Check if there are any blank cells and fill them if necessary.

4. **Check and Format DATE Column**
   - Ensure there are no empty cells.
   - Verify that the dates are in the correct format.

5. **Extract Month from DATE Column Using Power Query**
   - Select the DATE column.
   - Go to `Data` > `Get Data` > `From Table/Range`.
   - In the Power Query Editor, click `Add Column` > `Date` > `Month`.
   - Apply and close the editor.

6. **Check for Empty Cells in TIME Column**
   - Confirm there are no empty cells in the TIME column.

7. **Validate ANSWERED (Y/N) Column**
   - Apply a filter and ensure the column only contains 'Y' or 'N' values.

8. **Validate RESOLVED (Y/N) Column**
   - Apply a filter and ensure the column only contains 'Y' or 'N' values.

9. **Fill Empty Cells in SPEED OF ANSWER IN SECOND Column**
   - Select the column.
   - Press `Ctrl + G` or `F5` > `Special` > `Blanks`.
   - Enter the average value in the active cell and press `Ctrl + Enter` to fill all empty cells.

10. **Fill Empty Cells in AVG. TALK DURATION and SATISFACTION RATE Columns**
    - Select the columns.
    - Press `Ctrl + G` or `F5` > `Special` > `Blanks`.
    - Enter the average value in the active cell and press `Ctrl + Enter` to fill all empty cells.

### Data Analysis and Visualization

1. **Calculate Total Number of Calls**
   - Use a pivot table to count the total number of calls.

2. **Create Columns for Answered and Rejected Calls**
   - Add calculated columns to determine the total number of calls answered and rejected.

3. **Calculate Percentage of Answered and Rejected Calls**
   - Add calculated fields to determine the percentage of calls answered and rejected.

4. **Create Columns for Resolved and Unresolved Calls**
   - Add calculated columns to determine the number of calls resolved and unresolved.

5. **Find Top Agent by Number of Calls Answered**
   - Use a pivot table to find the agent with the maximum number of answered calls.

6. **Find Top Agent by Satisfaction Rate**
   - Use a pivot table to find the agent with the highest satisfaction rate.

7. **Visualize Total Number of Calls by Topic**
   - Create a bar chart to display the total number of calls by topic.

8. **Analyze Duration on Calls by Agent**
   - Create a bar chart to show the average talk duration for each agent.

9. **Visualize Total Calls by Day and Month for 2021**
   - Create a line chart to display the total number of calls by day and month.

10. **Use Slicers for Interactive Filtering**
    - Add slicers to filter data by month and day for interactive analysis.

### Dashboard Design

1. **Create the Dashboard Layout**
   - Design the layout in Excel using pivot tables and pivot charts.

2. **Add Key Metrics**
   - Add the total number of calls, total calls accepted, percentage accepted, total calls rejected, and percentage rejected as key metrics.

3. **Add Charts and Visualizations**
   - Include bar charts, line charts, and other visualizations as created in the analysis steps.

4. **Incorporate Slicers for Interactivity**
   - Add slicers for month and day to allow for interactive filtering of the data.

### Final Steps

1. **Review and Refine the Dashboard**
   - Ensure all data is accurate and visualizations are clear.

2. **Save and Share the Dashboard**
   - Save the Excel file and share the dashboard as required.

## Conclusion

This project involves a thorough process of data cleaning, analysis, and visualization to create an informative call center dashboard. By following the steps outlined above, you can effectively transform raw data into meaningful insights.
