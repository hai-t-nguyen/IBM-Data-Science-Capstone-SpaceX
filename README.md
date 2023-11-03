# IBM Data Science Capstone Project
![spacex-OHOU-5UVIYQ-unsplash](https://github.com/hai-t-nguyen/IBM-Data-Science-Capstone-SpaceX/assets/124855223/2568718e-7773-4ef9-a1d3-2dc313e537a2)
# Falcon 9 First-Stage Landing Success Prediction

## Objective

The primary objective of this project is to predict the success of Falcon 9 first-stage landings during SpaceX rocket launches. The successful landing of the first stage is pivotal for reducing launch costs and making SpaceX competitive in the aerospace industry.

## Methodology

Data for this analysis was collected from SpaceX launches, including historical data on first-stage landings. Various data science and machine learning techniques were employed to process and analyze the data, ultimately generating predictions regarding landing success.

## Key Findings

### Success Rate

Our analysis indicates that Falcon 9 first-stage landings have a success rate of 66.67%. This provides valuable insights into the reliability of SpaceX's reusability model.

### Factors Affecting Success

Key factors influencing landing success were identified, including launch site, payload mass, orbit type, and flight number. Understanding these variables is crucial for decision-making.

### Predictive Model

We developed predictive models that can estimate the probability of successful landings based on historical data and relevant parameters.

## Repository Contents
- `pdf`: Project presentation including reports, and explanations of the analysis and results.
   - [Applied Data Science Capstone Presentation](hainguyen-spacex-datascience-capstone-presentation.pdf)

- `notebooks`: Jupyter notebooks containing the data analysis, visualization, and machine learning models.
   - [Data Collection API](hainguyen-spacex-1-data-collection-api.ipynb)
   - [Data Collection Webscraping](hainguyen-spacex-2-data-collection-webscraping.ipynb)
   - [Data Wrangling](hainguyen-spacex-3-data_wrangling.ipynb)
   - [EDA SQL](hainguyen-spacex-4-eda-sql-coursera_sqllite.ipynb)
   - [EDA Data Visualization](hainguyen-spacex-5-eda-dataviz.ipynb)
   - [Interactive Visual Analytics with Folium](hainguyen-spacex-6-interactive_visual_analytics_with_folium_launch_site_location.ipynb)
   - [Machine Learning Prediction](hainguyen-spacex-8-machine_learning_prediction.ipynb)

- `py`: Code file used in making interactive dashboards with Plotly Dash.
   - [Interactive Dashboard Plotly Dash](hainguyen-spacex-7-dash_app.py)

- `csv`: Data sources and datasets used in the project.
   - [Dataset Part 2](dataset_part_2.csv)
   - [SpaceX](Spacex.csv)
   - [SpaceX Launch Dash](spacex_launch_dash.csv)

## Getting Started

To get started with this project, you can follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/hai-t-nguyen/IBM-Data-Science-Capstone-SpaceX.git
2. Navigate to the project directory:
   ```bash
   cd IBM-Data-Science-Capstone-SpaceX
3. Explore the presentation document, Jupyter notebooks, data, and code to understand the analysis and findings.
