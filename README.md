# Natural Disasters Data Visualization Dashboard

This interactive web dashboard visualizes global natural disasters from 1900 to 2021 using D3.js. It allows users to explore geographic and temporal trends in disaster frequency, type, and impact through an interactive world map, bar chart, and line graph.

## Overview

This project provides a data-driven view of natural disasters worldwide. It includes:
- A choropleth map that displays the number of disasters by country
- Filter buttons to explore specific disaster types (e.g., Flood, Earthquake, Drought)
- Country-specific tooltips showing average deaths, economic loss, and the most common disaster type
- A bar chart showing the distribution of disaster types for a selected country
- A line graph illustrating annual disaster frequency for the selected country

## Features

- Interactive world map with hover tooltips and clickable countries
- Linked bar chart and line graph that dynamically update based on user selection
- Filtering functionality by disaster type
- Tooltips for detailed disaster statistics
- Color legend and visual cues for enhanced interpretation

## Technologies Used

- D3.js (v7)
- HTML5, CSS3, JavaScript
- GeoJSON (for world map data)
- CSV data from EM-DAT (sourced via Kaggle)
