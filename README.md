# **BlueBike Traffic/Accident Analysis**

## Table of Contents
1. [Project Overview](#project-overview)
2. [What I Contributed](#what-i-contributed)
3. [Project Link](#project-link)
4. [Folder Structure](#folder-structure)
5. [About the Data](#about-the-data)
6. [References](#references)

## Project Overview
We completed this group project for DS4200: Data Visualization and Presentation. The task was to create data visualizations for a designated stakeholder, and we designed an interactive visualization for the BlueBikes team responsible for station locations. The visualizations combined bike accident data with station data to improve customer safety.

Our project features a heat map showing bike accidents, along with points representing station locations. Hovering over the points reveals the in- and out-flow of each station. By switching modes, users can explore accidents at intersections versus streets. This tool can assist BlueBikes in placing stations in safer areas.

## What I Contributed
I was responsible for developing the bar and pie charts, and for linking these charts to the heatmap to create an interactive experience. This involved:
- Creating tooltips
- Implementing brushing and linking
- Enabling hover actions to regenerate new graphs

I also contributed significantly to the design process, assessing stakeholder needs and determining the most relevant visualizations for safe station placement.

Technologies used: **HTML, CSS, JavaScript (d3 library)**

## Project Link
Check out our website here: [BlueBike Traffic/Accident Analysis](https://ds4200-s23-class.github.io/project-julian-jake-david-aneek/)

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
