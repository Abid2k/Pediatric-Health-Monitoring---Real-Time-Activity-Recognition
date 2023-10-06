# Pediatric Health Monitoring - Real-Time Activity Recognition

![Pediatric Health Monitoring](insert_image_link_here)

## Overview
This project aims to revolutionize pediatric health monitoring by using real-time activity recognition. It leverages machine learning techniques, particularly a Random Forest Classifier, to predict the activities of children based on certain features. The project includes data visualization, model training, and performance evaluation.

## Features
- Data visualization using histograms, box plots, pairplots, and heatmaps to explore the dataset.
- Training a Random Forest Classifier for activity recognition.
- Displaying model accuracy and generating a confusion matrix.
- Providing a detailed classification report and a heatmap representation of the report.

## Prerequisites
Before running the code, ensure you have the following libraries installed:
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn

You should also have a dataset with labeled activities and features.

## Usage
1. Make sure you have the required libraries installed.
2. Load your dataset and update the `categories` list accordingly.
3. Run the code by executing the Python script.
4. The code will visualize the data, train a Random Forest Classifier, and provide performance metrics.

## Contribution
Contributions are welcome! If you want to enhance the code or fix issues, please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes thoroughly.
5. Create a pull request with a detailed description of your contribution.

## How the Code Works
1. The code starts by loading the dataset and visualizing the data using histograms, box plots, pairplots, and a correlation heatmap.
2. It then prepares the data for training by splitting it into training and testing sets.
3. A Random Forest Classifier is trained on the training data.
4. Model accuracy and a confusion matrix are displayed.
5. The code generates a classification report with precision, recall, F1-score, and support for each category.
6. Finally, a heatmap representation of the classification report is created for better visualization.

Feel free to reach out if you have any questions or suggestions!

