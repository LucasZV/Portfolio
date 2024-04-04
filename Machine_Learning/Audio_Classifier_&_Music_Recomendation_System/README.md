**Audio Classification and Recommendation System**

This project focuses on building a machine learning system for audio classification and recommendation. The goal is to classify audio samples into different categories and then use these classifications to recommend similar audio samples.

### Libraries Used

The project utilizes the following Python libraries:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `seaborn` and `matplotlib.pyplot` for data visualization
- `sklearn` for machine learning algorithms and evaluation metrics
- `librosa` for audio processing
- `IPython.display` for audio playback
- `tensorflow.keras` for building neural network models
- `os` for operating system-related functions

### Dataset

download link: 
https://drive.google.com/drive/folders/1GWjOkNWASPolepDBlwmm8cOIb56THQM8?usp=sharing

genres_original data folder must be placed under the following path: "./data"

### Preprocessing and Feature Extraction

The audio data is preprocessed and features are extracted using `librosa`. All the featrures are avaiable at GTZAN Dataset.
Various features such as chroma features, spectral centroid, and zero-crossing rate are extracted from the audio files to represent them in a numerical format suitable for machine learning models.

### Classification Models

Several classification algorithms are employed to classify audio samples into different categories:

- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)
- Neural Network (Keras)
- XGBoost

### Model Evaluation

The performance of each classification model is evaluated using accuracy metric and confusion matrix. Cross-validation and grid search techniques are employed for hyperparameter tuning to optimize model performance.

### Recommendation System

A recommendation system is built based on the cosine similarity between audio samples. Cosine similarity is used to calculate the similarity between audio samples, and similar samples are recommended to users based on their preferences.

### Usage

To use this project, ensure you have the necessary libraries installed. The audio dataset should be structured appropriately, and the code can be executed to preprocess the data, train classification models, and build the recommendation system.

### Note

This readme provides an overview of the project and its components. Refer to the code documentation and comments for detailed explanations of each step and implementation details.

### Libraries Installation

Ensure you have installed the required libraries using pip:

```
pip install pandas numpy seaborn matplotlib scikit-learn librosa ipython tensorflow xgboost
```

### Authors

This project was developed by Lucas Zamora Vera.