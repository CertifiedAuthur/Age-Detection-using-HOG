# Age Detection using Histogram Oriented Gradient (HOG)

This project employs the Histogram Oriented Gradient (HOG) feature extraction technique combined with a Support Vector Machine (SVM) classifier to detect the age of a person depicted in an image. The HOG method captures the gradient information of an image, which is then fed into the SVM for age classification.

The accuracy achieved by the model is relatively low, which can be attributed to the limited number of images used for training. 

## Technology Stack
1. Python
2. Support Vector Machine (SVM)
3. Histogram Oriented Gradient (HOG)

## Age Prediction with SVM using HOG Features

### Overview
This project focuses on predicting the age of individuals using Support Vector Machines (SVM) trained on Histogram of Oriented Gradients (HOG) features extracted from images. The implementation includes image preprocessing, feature extraction, model training, hyperparameter tuning, and result reporting.

### Project Details

#### Data Preparation
The image dataset is automatically downloaded from the CV Studio platform.
Each image is labeled with the corresponding age group of the individual.

#### Image Preprocessing
Images are resized to a fixed dimension (64x64) for consistency.
Grayscale conversion is performed to reduce the number of channels.

#### Feature Extraction
HOG features are extracted from the preprocessed images.
HOG captures gradient orientation information from localized image regions.

#### Model Training
SVM classifier is trained on the extracted HOG features.
Hyperparameters such as kernel type (linear, RBF), C value, and gamma are tuned using grid search with cross-validation.

#### Evaluation
The trained model is evaluated on a validation set to measure accuracy and performance.
Confusion matrix is generated to analyze classification results.

#### Technology Stack
Python
OpenCV
Scikit-learn
CV Studio (for dataset management and collaboration)

### Results
Maximum validation accuracy achieved: 31.6%
Best hyperparameters: {'C': 10, 'kernel': 'rbf'}
Further optimization and experimentation are recommended for improved performance.

### Instructions for Use
##### Data Preparation:
Ensure proper labeling of the image dataset.
Utilize CV Studio for dataset management and annotation.
##### Image Preprocessing:
Resize images to a fixed dimension.
Convert images to grayscale.
##### Feature Extraction:
Extract HOG features from preprocessed images.
##### Model Training:
Train SVM classifier on the extracted features.
Tune hyperparameters using grid search with cross-validation.
##### Evaluation:
Evaluate the trained model on a validation set.
Analyze classification performance using confusion matrix.
##### Reporting Results:
Report the results back to CV Studio for tracking and collaboration.


#### Acknowledgments
This project makes use of the CV Studio platform for dataset management and collaboration.
License
This project is licensed under the MIT License.




