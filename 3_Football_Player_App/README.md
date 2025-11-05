# 3_Football_Player_App

## Overview
Interactive R Shiny application for managing and analyzing football player data using CRUD operations, Plotly visualizations, and reactive filtering.

## Features
- Add, update, and delete player records
- Filter by nationality and age range
- Interactive scatter plot (Overall vs Potential)
- Age distribution histogram using ggplot2

## Run locally
1. Clone this repository or download this folder.
2. Open R or RStudio.
3. Install packages:
   ```r
   install.packages(c("shiny","DT","plotly","ggplot2"))

shiny::runApp("3_Football_Player_App")
