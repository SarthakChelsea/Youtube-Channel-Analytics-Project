
# FreeCodeCamp YouTube Channel Data Analysis

![FreeCodeCamp Logo](https://upload.wikimedia.org/wikipedia/commons/3/39/FreeCodeCamp_logo.png) 

## Overview

This project aims to analyze the FreeCodeCamp YouTube channel using the YouTube API v3 service. The analysis focuses on understanding the popularity and performance of videos, viewership trends, and upload rates over the period from 2015 to 2023. Python libraries such as pandas, numpy, matplotlib, and seaborn were employed for feature engineering, data preprocessing, and data visualization.

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Data Visualization](#data-visualization)
- [Observation and Inferences](#observation-and-inferences)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)

## Project Structure

- `data/`: Contains the collected raw data from the YouTube API.
- `notebook/`: Python notebook used for data preprocessing, feature engineering, and visualization.
- `images/`: Visualizations generated during the analysis.
- `README.md`: This file, providing an overview of the project.

## Data Collection

The data was collected using the YouTube API v3 service, which provided information about the FreeCodeCamp channel, including video details such as view counts, likes, comments, and upload dates. The collected data was then saved into CSV files for further analysis.

## Data Preprocessing

The raw data was cleaned and preprocessed to handle missing values, remove duplicates, and ensure data integrity. Cleaning steps included handling null values, eliminating duplicate entries, and converting data types where necessary.

## Feature Engineering

New features were created based on the existing data to enhance the analysis. Feature engineering involved extracting the year from upload dates, calculating video popularity metrics based on views, likes, and comments, and any other relevant data transformations.

## Data Visualization

Using Python libraries such as Matplotlib and Seaborn, the data was visualized in various ways, including line plots, bar charts, and scatter plots. Visualizations were designed to highlight trends in viewership, upload rates, and other key metrics, providing valuable insights.

## Observation and Inferences

The analysis aimed to identify popular and unpopular videos, understand viewership trends over time, and uncover any significant growth patterns. Insights were drawn from the analysis, and inferences may be provided for channel improvement or content strategy based on the findings.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook/


## Usage

1. Acquire a YouTube API key and place it in the appropriate location in the notebooks to access the data.

2. Run the Jupyter notebook in the `notebook/` directory in sequential order for  data extraction,data preprocessing, feature engineering, and data visualization.

3. Explore the generated visualizations in the `images/` directory.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.


## Acknowledgments

- The FreeCodeCamp community and their educational content on YouTube.
- YouTube API v3 for providing access to valuable data.



---
