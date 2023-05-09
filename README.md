# Galaxy Classification using Machine Learning

This project aims to classify galaxies into three classes - elliptical, spiral, and irregular - using machine learning algorithms. The dataset consists of galaxy features derived from Sloan Digital Sky Survey (SDSS) data, including color indices, eccentricity, and concentrations.

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)

## Introduction
Galaxy classification is an essential task in the field of astronomy, as it helps scientists better understand the properties and evolution of galaxies. Traditionally, galaxy classification is done manually by astronomers, which is a time-consuming and labor-intensive process. This project aims to automate the galaxy classification process using machine learning algorithms, such as Decision Tree and Random Forest.

## Data Description
The dataset used in this project is derived from the SDSS and contains the following features:
- Color indices (u-g, g-r, r-i, i-z)
- Eccentricity
- Concentrations (PetroR50/PetroR90) in u, r, and z bands
- M4 (the fourth moment of the flux profile) in u, g, r, i, and z bands

The dataset has been divided into training and testing sets for model evaluation.

## Methodology
The project utilizes the following machine learning algorithms for galaxy classification:
1. Decision Tree Classifier
2. Random Forest Classifier

The performance of the models is evaluated using metrics such as accuracy, precision, and recall. Additionally, confusion matrices are generated to visualize the model's performance on both training and testing sets.

## Results
The models demonstrate promising results, with the Random Forest Classifier outperforming the Decision Tree Classifier in terms of accuracy, precision, and recall. Further details on the performance metrics can be found in the Jupyter Notebook.

## Conclusion
The project successfully demonstrates the application of machine learning algorithms in classifying galaxies based on their features. The models can be further improved with better preprocessing techniques, feature selection, and hyperparameter tuning. Additionally, computational time and other performance metrics can be further explored to enhance the model's efficiency.

## How to Run
1. Clone the repository to your local machine.
2. Ensure you have Python 3.x and the required libraries (numpy, pandas, scikit-learn, and matplotlib) installed.
3. Download the dataset and place it in the same directory as the project files.
4. Run the Jupyter Notebook to execute the code and view the results.
