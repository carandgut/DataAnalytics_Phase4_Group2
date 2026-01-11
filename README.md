IoT-Enabled Packaging Activity Recognition (OpenPack)

Course: Data Analytics (203018207) - Master in IoT 

Project Overview
This project implements an analytical solution to automate the recognition of packaging activities in industrial logistics. Using the OpenPack dataset (Kitamura et al., 2022), we developed a predictive model that processes data from IoT multimodal sensors (IMU) to improve traceability in Industry 4.0 environments.


Problem Statement & Articulation
Manual packaging tasks often lack real-time monitoring, leading to productivity issues. This project addresses the problem by creating a post-processing algorithm that transforms raw sensor signals into actionable operational insights.
Technical Justification: We utilize a Random Forest classifier to manage the high-dimensional and non-linear nature of human movement data captured by IoT devices, ensuring robust activity recognition.


Authors (Group 2)
Carlos Andres Gutierrez - ML Engineer 
Lucero Chamorro Serna - Data Engineer 


Technologies Used

Language: Python 
Environment: Google Colab / Jupyter Notebook 
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Joblib 
Data Source: OpenPack Dataset (Kitamura et al., 2022) 

Methodology Implemented

Data Acquisition: Loading 102 industrial sessions from IoT-IMU sensors.
Preprocessing: Data cleaning, handling missing values, and StandardScaler normalization.


Modeling: Implementation of a Random Forest algorithm for predictive modeling.
Evaluation: Performance assessment using Confusion Matrix and Accuracy metrics.


How to use
Clone this repository.
Open the .ipynb file in Google Colab.
Ensure the OpenPack CSV files are available in your Google Drive path.
Run all cells to reproduce the preprocessing, training, and evaluation
