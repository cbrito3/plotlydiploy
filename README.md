# Belly Button Biodiversity Using Plotly
In this project, we are helping Roza complete the dashboard. We are visualzing the bacterial data for each volunteer, we have to able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

## Deliverables: 
* Deliverable 1: Create a Horizontal Bar Chart
* Deliverable 2: Create a Bubble Chart
* Deliverable 3: Create a Gauge Chart
* Deliverable 4: Customize the Dashboard

## Horizontal Bar Chart 
* To produce a Horizontal Bar Chart the following was created:
  - Code is written to create the arrays when a sample is selected from the dropdown menu 
  - Code is written to create the trace object in the buildCharts() function, and it contains the following: 
    - The y values are the otu_ids in descending order.
    - The x values are the sample_values in descending order.
    - The hover text is the otu_labels in descending order.
  - Code is written to create the layout array in the buildCharts() function that creates a title for the chart
  - When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and the bar chart has the following: 
    - The top 10 sample_values are sorted in descending order
    - The top 10 sample_values as values
    - The otu_ids as the labels
    
![Horizontal%20Bar%20grap](https://github.com/cbrito3/plotlydiploy/blob/main/Horizontal%20Bar%20graph.png)

## Bubble Chart 
* The code for the trace object in the buildCharts(); function does the following: 
  - Sets the otu_ids as the x-axis values
  - Sets the sample_values as the y-axis values
  - Sets the otu_labels as the hover-text values
  - Sets the sample_values as the marker size
  - Sets the otu_ids as the marker colors
* The code for the layout in the buildCharts(); function does the following: 
  - Creates a title
  - Creates a label for the x-axis
* The text for a bubble is shown when hovered over
* When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard. All three charts should also be working according to their requirements when a sample is selected from the dropdown menu. 

![Bubble%20plot](https://github.com/cbrito3/plotlydiploy/blob/main/Bubble%20plot.png)

## Gauge Chart 
* The code to build the gauge chart does the following: 
  - Creates a title for the chart.
  - Creates the ranges for the gauge in increments of two, with a different color for each increment.
  - Adds the washing frequency value on the gauge chart.
  - The indicator shows the level for the washing frequency on the gauge.
  - The gauge is added to the dashboard.
  - The gauge fits in the margin of the <div> element.
* When the webpage loads, the bar and bubble chart are working according to the requirements in Deliverable 1 and 2, respectively, and the gauge chart is working according to the requirements listed for this Deliverable. 

![Gauge%20chart](https://github.com/cbrito3/plotlydiploy/blob/main/Gauge%20chart.png)

## Customize the Dashboard
* The webpage has three customizations. 
* When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu. 

Interactive Webpage can be found here: https://cbrito3.github.io/plotlydiploy/

    
