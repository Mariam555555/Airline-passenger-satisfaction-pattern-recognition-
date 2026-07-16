# ✈️ Airline Passenger Satisfaction - Pattern Recognition

## 📌 Project Overview
This project applies pattern recognition and data analysis techniques to the Airline Passenger Satisfaction dataset. The main objective is to identify hidden patterns and key factors that significantly impact customer satisfaction, helping airlines improve their services.

## 🎯 Objectives
* Analyze passenger data to find correlations between different flight features (e.g., seat comfort, in-flight entertainment, delays) and overall satisfaction.
* Apply pattern recognition algorithms to classify and predict passenger satisfaction levels.
* Provide data-driven insights for service improvement.

## 📊 Project Analysis & Visual Results

Here are some key visualizations from the analysis, highlighting the data distribution, feature extraction process, and model performance:

### 1. Distribution of Passenger Satisfaction
This bar chart illustrates the overall distribution of passenger satisfaction in the dataset, showing a higher count of neutral or dissatisfied passengers compared to satisfied ones.
<img width="1140" height="690" alt="Screenshot 2026-07-16 235931" src="https://github.com/user-attachments/assets/75970341-95f9-4bc9-8273-0bd4d3529b85" />

### 2. PCA Feature Extraction (Scree Plot)
This plot demonstrates the cumulative explained variance. The red line indicates the 95% information threshold, helping us determine the optimal number of principal components needed to retain most of the dataset's variance without losing critical data.
<img width="1143" height="770" alt="Screenshot 2026-07-16 235940" src="https://github.com/user-attachments/assets/a3e06abb-5e35-4162-8bea-99d308ca81db" />

### 3. Data Overlap & Random Forest Performance
The left graph visualizes the data points in a 2D space using the first two principal components, revealing the complex overlap between the two classes. The right graph displays the Confusion Matrix for the Random Forest model, providing a detailed breakdown of correct predictions versus misclassifications
<img width="1717" height="720" alt="Screenshot 2026-07-16 235907" src="https://github.com/user-attachments/assets/4f65a8be-1dd0-4054-8752-d13e1a13dbeb" />

## 4. Model Comparison (ROC Curve)
The Receiver Operating Characteristic (ROC) curve compares the performance of our models. The Random Forest classifier significantly outperforms Logistic Regression, achieving an excellent Area Under the Curve (AUC) of 0.98.
<img width="752" height="810" alt="Screenshot 2026-07-16 235918" src="https://github.com/user-attachments/assets/135692c7-2a94-4af2-84e2-bea6f3c0275b" />

## 🛠️ Technologies Used
* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Tools:** Jupyter Notebook

## 🚀 How to Run the Project
1. Clone the repository:
   `git clone https://github.com/Mariam555555/Airline-passenger-satisfaction-pattern-recognition-.git`
2. Navigate to the project directory:
   `cd Pattern-Project`
3. Install the required dependencies:
   `pip install -r requirements.txt`
4. Run the Jupyter Notebook or Python script to see the analysis and results.
