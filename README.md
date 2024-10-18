# Formula-1-Data-Analysis

This repository contains code and analysis for exploring and visualizing Formula 1 race data, focusing on the 2021 season. The project provides insights into driver performance, cumulative points, and mechanical DNF (Did Not Finish) patterns across various races. The analysis was conducted using data sourced from historical Formula 1 records, including drivers, teams, tracks, and lap times.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Key Features](#key-features)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Visualizations](#visualizations)

## Project Overview
This project aims to provide a detailed analysis of Formula 1 races, focusing primarily on the 2021 season. It includes data analysis techniques to calculate cumulative points per driver, investigate DNF trends, and visualize performance metrics across races.

## Data Sources
The analysis relies on the following datasets:
- `drivers.csv`: Information on drivers participating in Formula 1.
- `races.csv`: Details of each race, including date and location.
- `results.csv`: Results of each race for individual drivers.
- `lap_times.csv`: Lap times for each driver during the races.
- `constructor_results.csv`: Data on team performance.
- `circuits.csv`: Information on racing circuits.
- `status.csv`: Details on drivers' finishing statuses, including DNFs.

## Key Features
- **Cumulative Driver Points**: Calculates total points earned by each driver throughout the 2021 season, incorporating both race results and sprint points.
- **DNF Analysis**: Analyzes mechanical DNF patterns across races, providing insights into reliability issues.
- **Lap Time Analysis**: Compares lap times between drivers to evaluate consistency and performance during individual races.
- **Visualizations**: Interactive graphs and charts to visualize key insights like cumulative points, DNF trends, and race performance.

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Formula-1-Data-Analysis.git
    ```
2. Install the required Python libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Place the dataset files in the `data/` directory.
4. Run the Jupyter notebooks or Python scripts to reproduce the analysis.

## Usage
- **Analyzing Driver Performance**:
   - Use the `driver_performance.py` script or Jupyter notebook to analyze driver points, lap times, and finishing statuses.
   - Modify the race year or driver code to analyze different seasons or specific drivers.
   
- **Visualizing Results**:
   - Run the visualization scripts to generate charts that display driver points progression and DNF statistics.
   - View interactive visualizations in the notebooks for more detailed insights.

## Visualizations
The project includes a variety of visualizations to make the analysis more interpretable:
- **Cumulative Driver Points**: Line graphs showing how driver points accumulate across races.
- **DNF Trends**: Bar charts illustrating the number of mechanical DNFs per year and per driver.
- **Lap Time Differences**: Comparative analysis of lap times between drivers during key races.


