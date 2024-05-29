# PRODIGY_ML_03
# Cat vs Dog Image Classification
#### Description
- This project, developed during an internship with Prodigy, focuses on classifying images of cats and dogs using machine learning techniques. The model employs Histogram of Oriented Gradients (HOG) for feature extraction and a Support Vector Classifier (SVC) for training and classification.

#### Project Overview
The steps involved in this project include:

- Data Preparation: Organizing the dataset of cat and dog images.
- Feature Extraction: Utilizing HOG to extract significant features from each image.
- Model Training: Using an SVC model to learn from the HOG features and classify images.
- Model Evaluation: Assessing the model's performance on a test dataset.
- Model Saving: Saving the trained model for future use.
#### How It Helps
##### Efficient Feature Extraction: HOG captures essential features such as edges and gradients, which are critical for distinguishing between cats and dogs.
##### Effective Classification: SVC is well-suited for image classification tasks, providing high accuracy and robustness.
##### Reusability: The saved model can be used for making predictions on new images without the need for retraining.
#### Technologies Used
- Python 3.x
- NumPy
- scikit-image
- scikit-learn
- OpenCV (optional, for image preprocessing)
