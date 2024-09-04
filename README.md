# Interactive iris data set scatter plot matrix

## Introduction

This project is an interactive web application for visualizing and analyzing the famous Iris dataset. It combines data visualization techniques and machine learning algorithms to provide a powerful tool to explore the structure of data sets and the performance of different classification methods.

Check out the demo [here](https://quantumwings.github.io/Interactive-Iris-Dataset-Scatterplot-Matrix/).

## Main functions

1. Scatter plot matrix: Displays all possible combinations between the four characteristics of iris (calyx length, sepal width, petal length, petal width).
2. Interactivity: Supports interactive operations such as zooming, panning, clicking and highlighting.
3. Machine learning integration: Implements simple versions of decision tree, random forest, support vector machine (SVM) and K nearest neighbor (KNN) algorithms.
4. Data filtering: You can filter by iris variety.
5. Performance indicators: Display model performance, including accuracy, precision, recall and F1 score.
6. Confusion matrix: Visualize classification results.
7. Decision Boundary: Visualize the decision boundary of the selected algorithm.

## Installation and Setup Guide

### Environmental requirements

- Modern web browser (supports HTML5, CSS3 and ES6+)
- Network connection (for loading external libraries and data)

### How to use

1. Download the entire HTML file to your computer.
2. Open the HTML file using a modern web browser.
3. No additional installation steps are required, the page will automatically load all necessary scripts and styles.

## Instructions for use

### Operation steps

1. After opening the application, you will see a 4x4 scatter plot matrix.
2. Use the left control panel to adjust display options:
 - Select the iris varieties to display
 - Choose a machine learning algorithm
 - Adjust dot size and transparency
3. Interact with the chart:
 - Zoom and pan individual charts
 - Click on a data point to highlight it in all charts
 - Click on the chart to view it full screen
4. Use the function buttons:
 - Reset chart
 - View model performance
 - Display confusion matrix
 - Toggle display of decision boundaries

### Example

- Select the "Setosa" variety and observe the distribution of its characteristics.
- Apply the SVM algorithm and open the decision boundary view to observe the classification effect.
- Switch between different algorithms and compare their performance metrics.

## Project structure

- `index.html`: Contains all necessary HTML, CSS and JavaScript code for building and displaying interactive interfaces.

Main components:
- `IrisDataModel`: Responsible for data loading and processing.
- `IrisMatrixView`: Handles the creation and update of scatter plot matrices.
- `MLAlgorithms`: Contains a simplified version of machine learning algorithm implementation.
- Vue.js application: manages user interface state and interactions.

## Contribution Guidelines

If you would like to contribute to this project, please follow these steps:

1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request.

## Authorization information

This project is licensed under the terms of [MIT](https://opensource.org/licenses/MIT).

## Contact Information

If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com

## Other information

- This project uses external libraries such as D3.js, Plotly.js and Vue.js.
- Iris data set source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
