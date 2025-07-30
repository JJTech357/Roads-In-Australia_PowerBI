# Roads-In-Australia_PowerBI
Statistical Analysis of different Roads in Australia.

Roads in Australia - Major Road Length Analysis
This Power BI report provides an interactive visualization of major road lengths across different states and territories in Australia. The primary goal of this report is to allow users to quickly identify which states have the longest major road networks, represented by a choropleth map with varying shades.

Features
Interactive Map: A map of Australia where each state is colored based on the total length of its major roads. Darker shades indicate a greater total road length.

State-wise Breakdown: Easily compare road lengths between different states.

Data Source: Built using the MajorRoads - Copy.csv dataset, which contains detailed information about road segments across Australia.

How to Use the Report
Download Power BI Desktop: If you don't already have it, download and install Power BI Desktop.

Download the Report: Download the Roads in Australia.pbix file from this repository.

Open the Report: Open Power BI Desktop and go to File > Open Report > Browse and select the Roads in Australia.pbix file.

Interact with the Visuals:

The main page displays the choropleth map.

Hover over any state on the map to see a tooltip with its total major road length.

(Optional) If there are other visuals or slicers, use them to filter or cross-highlight data.

Data Source
The report uses data from the MajorRoads - Copy.csv file. This CSV file contains the following key columns relevant to the visualization:

state: The Australian state or territory to which the road segment belongs.

Shape__Length: The length of the road segment.

A pre-processed CSV file, Major_Roads_by_State.csv, was generated to aggregate the Shape__Length by state for easier visualization in Power BI. This file contains:

State: The Australian state or territory abbreviation.

Total_Road_Length: The sum of Shape__Length for all major roads in that state.

Visual Used
The core visualization for the map is the Filled Map visual in Power BI. This visual is ideal for displaying geographical data with color saturation based on a numerical measure.

Setup for Development (Optional)
If you wish to modify or extend this report:

Email to jeevan.rajgopal@gmail.com

Open in Power BI Desktop: Open the .pbix file in Power BI Desktop.

Data Transformation: The data was pre-processed using Python to aggregate road lengths by state. The Python script for this transformation is not included in the .pbix file but involved steps similar to:





