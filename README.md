# FETAL-AI-PREDICTION


This project is aimed at predicting the health status of a fetus based on various maternal and fetal health parameters using machine learning techniques.

Overview


The prediction of fetal health is crucial for timely intervention and care during pregnancy. This project leverages machine learning algorithms to analyze a dataset containing features related to maternal and fetal health and predict the fetal health status.

Dataset


The dataset used in this project contains the following features:

Baseline Fetal Heart Rate: Baseline heart rate of the fetus.
Accelerations: Number of accelerations per second.
Fetal Movement: Number of fetal movements per second.
Uterine Contractions: Number of uterine contractions per second.
Light Decelerations: Number of light decelerations per second.
Severe Decelerations: Number of severe decelerations per second.
Percentage of Time with Abnormal Short-Term Variability: Percentage of time with abnormal short-term variability in fetal heart rate.
Percentage of Time with Abnormal Long-Term Variability: Percentage of time with abnormal long-term variability in fetal heart rate.
Mean Value of Short-Term Variability: Mean value of short-term variability in fetal heart rate.
Mean Value of Long-Term Variability: Mean value of long-term variability in fetal heart rate.
Class: Health status of the fetus (1: Normal, 2: Suspect, 3: Pathological).
Machine Learning Model
In this project, we experimented with various machine learning algorithms including:

Logistic Regression
Random Forest
Support Vector Machine (SVM)
Gradient Boosting
The performance of each model was evaluated using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score.

Usage


To run the project locally, follow these steps:

Clone this repository to your local machine.
Navigate to the project directory.
Ensure you have Python installed on your system.
Install the required dependencies listed in requirements.txt using pip install -r requirements.txt.
Run the Jupyter notebook fetal_health_prediction.ipynb to train and evaluate the machine learning models.
Alternatively, you can use the trained models directly by running the provided Python scripts.
Results
The results of our experiments showed promising performance in predicting fetal health status. Detailed performance metrics and visualizations are provided in the Jupyter notebook.

Contributing


Contributions to this project are welcome! If you have suggestions for improvements, bug fixes, or new features, please submit an issue or pull request.

License


This project is licensed under the MIT License.

Acknowledgements


We would like to thank the contributors to the dataset used in this project for their valuable efforts.
