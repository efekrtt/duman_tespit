## Fire Detection with Decision Trees

This repository contains a Python script that uses a decision tree to detect fires. The script uses a dataset of images of smoke from the Wildfire Smoke Dataset. The images are classified as either "no fire" or "fire".

The script first pre-processes the images by converting them to grayscale and resizing them to 28x28 pixels. The pre-processed images are then used to train a decision tree classifier. The classifier is trained on 80% of the data and tested on 20% of the data.

The script also plots the ROC curve for the classifier. The ROC curve shows the trade-off between true positive rate (TPR) and false positive rate (FPR).

## Instructions

To run the script, first install the required libraries:

pip install numpy
pip install PIL
pip install pandas
pip install sklearn

Then, run the following command:

python yangin_tespit.py

## Results

The script will print the following results:

The best parameters for the decision tree classifier
The accuracy of the classifier on the test data
The ROC curve for the classifier
Example Results

The following are example results from the script:

Best parameters:
criterion: entropy
max_depth: 30

Accuracy: 0.95

ROC curve:
AUC = 0.96
Conclusion

The results show that the decision tree classifier is able to accurately detect fires. The accuracy of the classifier is 95%, and the ROC curve shows that the classifier is able to achieve a high true positive rate without sacrificing too much false positive rate.
