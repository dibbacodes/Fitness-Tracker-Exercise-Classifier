# Exercise Classifier

## Overview

This project aims to analyze and visualize fitness data collected from various sensors. The dataset consists of CSV files containing measurements related to participants, exercises performed, and intensity levels. The goal is to perform comprehensive data processing, feature engineering, and modeling to derive insights and build predictive models.

## Steps Involved

### 1. Setup and Environment

- **Download Dataset:** Obtain the dataset and place it in the `data/raw` directory.
- **Open VS Code Workspace:** Use Visual Studio Code as the development environment.
- **Create Conda Environment:** Set up a Conda environment using `environment.yml` to manage dependencies and activate it within VS Code.

### 2. Data Processing

- **File Exploration:** Navigate to `src/data/make_dataset.py` to begin exploring and processing the dataset.
- **Understanding CSV Files:** Gain insights into the structure and content of CSV files including measurements, participants, exercises, and intensity levels.
- **Data Transformation:** Prepare the data for supervised learning tasks, ensuring it's formatted correctly for modeling.

### 3. Data Visualization

- **Workflow Overview:** Implement a visualization workflow to explore data patterns.
- **Plotting:** Visualize single columns, all exercises, and compare metrics such as sets, repetitions (reps), and intensity levels.
- **Advanced Plotting:** Utilize multi-axis plots to analyze combinations of sensor data and consolidate multiple plots into one figure.

### 4. Outlier Detection and Handling

- **Identifying Outliers:** Define outliers and implement methods such as Boxplots with Interquartile Range (IQR), Chauvenet’s Criterion, and Local Outlier Factor (LOF) to identify them.
- **Time-Series Outliers:** Visualize outliers in time-series data for deeper analysis.
- **Handling Outliers:** Develop functions to replace or mitigate outlier effects, ensuring data quality for subsequent analysis.

### 5. Feature Engineering

- **Feature Extraction:** Implement feature engineering techniques to derive meaningful attributes from raw sensor data.
- **Dealing with Missing Values:** Apply methods like imputation to manage missing data effectively.
- **Temporal and Frequency Abstraction:** Abstract features in both temporal and frequency domains to capture essential patterns and insights.

### 6. Modeling and Evaluation

- **Model Training:** Split data into training and test sets for model development.
- **Feature Selection:** Employ techniques such as forward feature selection using simple decision trees to identify relevant features.
- **Hyperparameter Tuning:** Use grid search to optimize model parameters and select the best-performing model.
- **Evaluation:** Evaluate models using metrics appropriate for the task, comparing results across different participants or subsets of data.

### 7. Results and Discussion

- **Visualization of Findings:** Present visualized data patterns and insights derived from the analysis.
- **Benchmarking:** Establish benchmark results and evaluate model performance against these benchmarks.
- **Discussion:** Interpret results, discuss limitations, and suggest potential areas for further exploration or improvement.

---

