# Personal Fitness Tracker Analysis

## Project Overview

This project analyzes personal fitness data collected from 35 Fitbit users, including daily activity, steps, and distance. The goal is to identify trends and patterns in users' habits related to physical activity and fitness, using data analysis and visualization techniques.

## Tools and Technologies

- **Google Sheets**: Managed raw data and served as a platform for initial data exploration and organization.
- **SQL**: Used for querying and processing data stored in Google BigQuery.
- **R**: Utilized for statistical analysis and data visualization.
- **Data Visualization**: Created interactive charts and graphs to visualize trends and insights.

## Dataset

The dataset consists of personal fitness tracker data for 35 Fitbit users, including the following key features:
- **Date**: Date of the recorded activity.
- **Steps**: Total steps taken during the day.
- **Activity Level**: Intensity of activity (e.g., low, moderate, high).
- **Calories Burned**: Total calories burned during the day.

## Key Insights and Analysis

- **Activity Patterns**: Identified patterns in user activity levels, such as peak hours for walking and exercise.
- **Steps and calories burnt**: Analyzed the relationship between calories and the number of steps taken, providing insights into fitness levels.
- **Visualization**: Created dynamic charts to display trends over Calories Burned by Activity Level

## Getting Started

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/gayi3rajesh/Fitbit-User-Activity-Analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Fitbit-User-Activity-Analysis
    ```

3. Open the dataset in Google Sheets for data exploration (or load it into your preferred tool for further analysis).

4. To run the analysis in R, install the necessary packages:
    ```R
    install.packages(c("ggplot2", "dplyr", "tidyr"))
    ```

5. Load the dataset and run the analysis script:
    ```R
    source("scripts/data_analysis.R")
    ```

## Project Structure

- `/data`: Contains the raw dataset and any cleaned data.
- `/scripts`: Contains R scripts for data analysis and visualization.
- `/visualizations`: Stores output charts and graphs generated from the analysis.
- `/reports`: Includes summary reports and findings from the analysis.
- `README.md`: This file, providing an overview of the project.

## Conclusion

This project demonstrates the ability to work with real-world fitness data, apply statistical techniques, and present insights through visualizations. It showcases the skills necessary for data analysis, including data manipulation, statistical analysis, and storytelling through visualizations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**GitHub Repository**: [github.com/yourusername/fitbit-analysis](https://github.com/yourusername/fitbit-analysis)

