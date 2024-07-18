# Crime Data Analysis in Los Angeles

![Los Angeles skyline](la_skyline.jpg)

Welcome to the Crime Data Analysis project focused on Los Angeles, California. This project aims to analyze crime patterns in different areas of Los Angeles using publicly available data. By exploring and visualizing crime trends, we aim to provide insights that can support resource allocation and strategic decisions for law enforcement agencies like the Los Angeles Police Department (LAPD).

## Objective

The primary objective of this project is to analyze crime data to identify patterns in criminal behavior across various dimensions such as time of day, geographical areas, types of crimes, and demographics of victims. The insights derived from this analysis can help in optimizing crime prevention strategies and resource allocation.

## Dataset Overview

### Dataset: `crimes.csv`

The dataset contains detailed records of reported crimes in Los Angeles, including information such as:

- Date and time of occurrence
- Crime category and description
- Area where the crime occurred
- Age, sex, and descent of the victim
- Weapon used (if applicable)
- Crime status and location details

### Key Analysis Sections

1. **Analysis of Crime by Hour**

   - Identifying peak hours of crime occurrence throughout the day using bar charts.
2. **Night Crimes Analysis**

   - Investigating areas with the highest frequency of crimes during night hours (10 PM to 4 AM).
3. **Demographic Analysis**

   - Analyzing the proportion of crimes based on the age categories of victims using bar charts.

## Getting Started

To run the analysis yourself or explore the dataset:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the IPython Notebook crime_analysis.ipynb to view the detailed analysis.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
