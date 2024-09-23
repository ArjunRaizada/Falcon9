# Falcon 9 First Stage Descent Predictor

This project uses machine learning techniques to predict the success of SpaceX Falcon 9 first stage landings based on flight parameters. The goal is to classify whether a landing attempt is successful or not using various classifiers, including Logistic Regression, Support Vector Machines (SVM), Decision Trees, and K-Nearest Neighbors (KNN).

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Overview

The dataset includes various features related to Falcon 9 flights, such as payload mass, orbit, launch site, and more. The classification task aims to predict the landing outcome (successful or unsuccessful).

## Data

Two datasets were utilized in this project:

1. **Dataset Part 2**: Contains flight details and landing outcomes.
2. **Dataset Part 3**: Contains additional features derived from the flight data.

Both datasets can be found in the following URLs:
- [Dataset Part 2](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/dataset_part_2.csv)
- [Dataset Part 3](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-DS0321EN-SkillsNetwork/datasets/dataset_part_3.csv)

## Installation

To run the project, you'll need the following Python libraries:

numpy 
pandas 
seaborn 
matplotlib 
scikit-learn



## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ArjunRaizada/Falcon9/

2. Open a Jupyter Notebook or Python script and run the provided code.
3. Ensure the data is loaded properly and proceed with the model training and evaluation steps.



## Model Training

The following models were trained and evaluated:

Logistic Regression<br>
Support Vector Machine (SVM)<br>
Decision Tree<br>
K-Nearest Neighbors (KNN)<br>
Hyperparameters were optimized using Grid Search with 10-fold cross-validation.<br>

## Results

Model	Validation Accuracy	Test Accuracy
Logistic Regression	~82.2%	~94.4%
Support Vector Machine	~82.2%	~94.4%
Decision Tree	~88.9%	~88.9%
K-Nearest Neighbors	~84.4%	~94.4%
Confusion matrices were plotted for each model to visualize their performance.

## Conclusion

The SVM and KNN models achieved the highest test accuracy of ~94.4%. Future work could involve exploring feature engineering and more advanced modeling techniques to improve predictions further.

## License

This project is open source.


## Author

Arjun Raizada

