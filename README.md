# **BlueBike Traffic/Accident Analysis**

## Table of Contents
1. [Project Overview](#project-overview)
2. [What I Contributed](#what-i-contributed)
3. [Project Link](#project-link)
4. [About the Data](#about-the-data)
5. [Contributors](#contributors)
6. [Folder Structure](#folder-structure)
7. [References](#references)

## Project Overview
This webpage is intended to help BlueBikes employees ensure the safety of BlueBikes users. Our product visualizes where bikes accidents are occuring in Boston. The webpage contains three visualizations. The first visualization displays a heatmap of bike accidents in Boston, and bike station points. Hovering over the points reveals the in- and out-flow of each station. Bluebikes employees can use this information to identify how frequent these bike stops are visited, and identify which bikestops need the most attention.

By switching modes, users can explore accidents at intersections versus streets. This tool can assist BlueBikes in placing stations in safer areas. For further exploration, users can highlight an area over the heatmap, which then shows the total number of accidents that occured in intersections and/or streets.

## What I Contributed
I was responsible for developing the bar and pie charts, and for linking these charts to the heatmap to create an interactive experience. This involved:
- Creating tooltips
- Creating the pie chart and bar chart
- Implementing brushing and linking
- Enabling hover actions to regenerate new graphs

I also contributed significantly to the design process, assessing stakeholder needs and determining the most relevant visualizations for safe station placement.

Technologies used: **HTML, CSS, JavaScript (d3 library)**

## Project Link
Check out our website here: [BlueBike Traffic/Accident Analysis](https://ds4200-s23-class.github.io/project-julian-jake-david-aneek/)

## About the Data
We used the following data sources for this project:

Bike Accident Data: Boston_Accidents.csv contains information about bike accidents in Boston, including the location, date, and severity of the accidents.
BlueBikes Station Data: This includes station information in multiple files, such as Jan2023_station_data.csv, end_station_data.csv, start_station_data.csv, and merged_station_data.csv, which provide details on station locations and bike inflow/outflow.
Map Data: The file boston_map.json contains geographic information for rendering the base map of Boston.
Our goal was to merge accident data with BlueBikes station locations to help identify hazardous areas and guide safer station placements.

## Contributors

All contributors were undergraduate students at Northeastern University.

Julian Savini
Email: savini.j@northeastern.edu

Aneek Mahajan
Email: mahajan.a@northeastern.edu

Jake Ashkenase
Email: ashkenase.j@northeastern.edu

This was the final project for the course DS 4200 - Data Visualization and Presentation (Spring 2023), at Northeastern University

## Folder Structure
```plaintext
project-julian-jake-david-aneek/
│
├── data/                   # Contains the datasets
│   ├── Boston_Accidents.csv
│   ├── Jan2023_station_data.csv
│   ├── boston_map.json
│   ├── end_station_data.csv
│   ├── merged_station_data.csv
│   └── start_station_data.csv
├── images/                 # Contains images used in the project
│   ├── Legend.svg
│   ├── bluebike.png
│   ├── dangerous_gradient.svg
│   ├── favicon.png
│   └── red_circle.png
├── js/                     # JavaScript scripts and libraries
│   ├── d3.v6.1.1/
│   ├── API.md
│   ├── CHANGES.md
│   ├── LICENSE
│   ├── README.md
│   ├── d3.js
│   ├── d3.min.js
│   └── script.js
├── video/                  # Project demo video and captions
│   ├── Demo_Video.mp4
│   └── captions.vtt
├── .DS_Store                # Metadata file
├── README.md                # This file
├── index.html               # Main webpage
└── style.css                # Custom styles for visualizations
```

## References
1. [HTML Structure Example](https://github.com/DS4200-S23-Class/hw-06-aneek-and-jake/blob/master/index.html)
2. [D3.js Zoom and Pan Tutorial](https://www.d3indepth.com/zoom-and-pan/)
3. [D3.js Brush Interactivity Example](https://d3-graph-gallery.com/graph/interactivity_brush.html)
4. [Creating Tooltips in D3.js](https://www.pluralsight.com/guides/create-tooltips-in-d3js)
5. [D3.js Line and Points on Map from CSV Data](https://stackoverflow.com/questions/47917730/d3-line-and-points-on-map-from-csv-data)
6. [D3.js Mapping Tutorial](https://maptimeboston.github.io/d3-maptime/#/)
7. [Vision Zero Crash Records Dataset](https://data.boston.gov/dataset/vision-zero-crash-records)
8. [CSS Switch Tutorial](https://www.w3schools.com/howto/howto_css_switch.asp)
9. [GeoJSON Example with D3.js](http://132.72.155.230:3838/js/geojson-1.html)
10. [D3.js Geo Projections Tutorial](https://www.sohamkamani.com/javascript/d3-geo-projections/)
11. [D3-Geo GitHub Repository](https://github.com/d3/d3-geo)
12. [CSS Buttons Tutorial](https://www.w3schools.com/css/css3_buttons.asp)
13. [CSS Three-Column Layout Tutorial](https://www.w3schools.com/howto/howto_css_three_columns.asp)
