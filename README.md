Model for prediction of class: https://drive.google.com/file/d/1XFVK0qyhoMFrVZb2hWtRcOui77biLCOc/view?usp=drive_link

Model for prediction of sub_class: https://drive.google.com/file/d/1DuvNudwLJ7IyuRusmTaPRcUXoUZuQThd/view?usp=drive_link

Model Fine-Tuning and Prediction
This repository contains resources for fine-tuning and testing a model on your custom dataset. Each directory contains essential files and notebooks structured for ease of use. Here’s how to use each component.

Directory Structure:
Each directory includes the following:

1.Results Folder:
  Contains visualizations of model performance, specifically pie charts of class distributions.

2.Train Notebook:
  A Kaggle notebook for model fine-tuning on a dataset.
    -Define paths for training and testing datasets.
    -Uses the test dataset as the validation set.
    -Outputs accuracy, precision, recall, and F1 score at the end of training.

3.Test Notebook: 
  A Kaggle notebook for model testing and further predictions.
    -Load the trained model and specify its path.
    -Specify the path to a dataset if you’re predicting on a large batch of texts.
    -For single text predictions, paste the text into the specified section at the end of the notebook.
