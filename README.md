# 2023_MLB_Playoff_Predictions_And_Realignment-Project-4
# PART A
# MLB Playoff Team Prediction

This repository contains code for predicting MLB postseason contenders using machine learning and hyperparameter tuning. Additionally, it includes a presentation that explains the code's functionality and presents the results of the prediction.

## Project Objectives

- To determine which Major League Baseball teams would make it to the playoffs. 
- Develop an optimized neural network model for predictive analysis 
- Visualization and Interpretation of Major League Baseball Data
- Analysis of Machine Learning model 

## Code Overview

The code is structured as follows:

- `mlb_nn_8years - Final.py`: The Python script that performs the prediction.
- `2023_Batting.csv`, `2023_Pitching.csv`, `2023_Fielding.csv`: Datasets containing performance data for the 2023 MLB season.
- `mlb_network.h5`: The saved machine learning model.
- `Resources/`: A directory containing additional resources and datasets.

### Running the Code

1. Ensure you have Python 3.x, TensorFlow, and the required libraries installed (pandas, matplotlib, sklearn, keras_tuner).

2. Run the `mlb_nn_8years - Final.py` script to perform the prediction based on the 2023 season data.

3. Review the predictions and the output, including the sorted list of top MLB postseason contenders for 2023.

## Presentation

The PowerPoint presentation (`presentation.pptx`) provides an overview of the code's functionality and the results of the prediction. It includes the following sections:

1. Introduction
2. Code Overview
3. Data Preparation
4. Model Building
5. Neural Network Architecture
6. Hyperparameter Tuning
7. Best Model and Evaluation
8. Model Deployment
9. 2023 Season Data
10. Predictions
11. Results and Insights
12. Conclusion
13. Q&A

The presentation is designed to be informative and visually appealing, making it suitable for sharing with stakeholders and colleagues.

## Data Sources

- The code uses datasets (`2023_Batting.csv`, `2023_Pitching.csv`, `2023_Fielding.csv`) for the 2023 MLB season.
- The machine learning model is trained on historical MLB data (`mlb_complete_8years.csv`).

Team statistics were collected from https://www.baseball-reference.com/

# PART B
# MLB Team Realignment

This repository contains code for realigning sports teams into new divisions to optimize travel efficiency. Additionally, it includes a presentation that explains the code's functionality and presents the results of the realignment process.

## Project Objectives

- Presenting a code-driven solution for optimizing the divisional alignment of sports teams to minimize travel distances.

## Code Overview

The code is structured as follows:

- `mlb_realigning - Final.py`: The Python script that performs the team realignment.
- `stadiums.csv`: A dataset containing information about team locations.
- `MLBpredictions-realignment.pptx`: A PowerPoint presentation explaining the code and results.
- `Resources/`: A directory containing the realigned division output CSV file and other resources.

### Running the Code

1. Ensure you have Python 3.x and the required libraries installed (NumPy, pandas, plotly, k_means_constrained).

2. Run the `mlb_realigning - Final.py` script to perform the realignment and generate results.

3. Review the output and the CSV file `Resources/realigned_divisions.csv` containing the realigned division assignments.

## Presentation

The PowerPoint presentation (`presentation.pptx`) provides an overview of the code's functionality and the results of the team realignment process. It includes the following sections:

1. Introduction
2. The Problem
3. Data Preparation
4. Division Realignment Algorithm
5. Division Realignment Results
6. Visualizing Realignment
7. Evaluating Travel Distance Improvement
8. Travel Efficiency Improvement
9. Exporting Realigned Divisions
10. Conclusion
11. Q&A

The presentation is designed to be informative and visually appealing, making it suitable for sharing with stakeholders and colleagues.

## Data Sources

- The code uses the `stadiums.csv` dataset, which should contain information about team names, leagues, divisions, latitude, and longitude.

Team statistics were collected from https://www.baseball-reference.com/

# Constributors
- Anna Garcia
- Adolfo Linarez
- Graham Jaeger
- Lamin Burrow
- Nelson Linarez

# Technologies Used
- Python Pandas
- Python Matplotlib
- Tableau
