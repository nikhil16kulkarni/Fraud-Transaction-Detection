# Fraud Detection in Financial Transactions


## Overview
This project aims to detect fraudulent financial transactions using various machine learning techniques. Given the critical nature of financial transactions, it is essential to have an effective fraud detection system in place to minimize financial losses, protect customer trust, and comply with regulatory requirements. </br>

## Project Structure
1. **Data Collection:** The dataset includes financial transaction records with labels indicating whether each transaction is fraudulent or not. (can be found here: https://github.com/CapitalOneRecruiting/DS) </br>
2. **Exploratory Data Analysis (EDA):** Conducted to understand data distribution, identify patterns, and gain insights through visualizations and statistical measures.</br>
3. **Feature Engineering:** Created new features to enhance model performance, such as transaction time, account age, and days since the last address change.</br>
4. **Model Selection and Training:** Tested various machine learning models to determine the most effective one for fraud detection.</br>
5. **Handling Imbalanced Data:** Applied resampling techniques to address class imbalance in the dataset.</br>
6. **Model Evaluation:** Evaluated models using metrics such as accuracy, precision, recall, F1 score, and confusion matrix.</br>
7. **Final Model Selection:** Chose the best-performing model based on evaluation metrics.</br>

## Technologies Used
**Python:** Programming language used for implementing the entire project.</br>
**Pandas:** Data manipulation and analysis.</br>
**NumPy:** Numerical computations.</br>
**Matplotlib & Seaborn:** Data visualization.</br>
**Scikit-Learn:** Machine learning library for model training, evaluation, and resampling techniques.</br>
**Jupyter Notebook:** Interactive computing environment for development and analysis.</br>

## Exploratory Data Analysis (EDA)
**Purpose:** To gain insights into the data, identify patterns, and detect anomalies.</br>
**Methods:** Visualizations (histograms, box plots, scatter plots), statistical measures (mean, median, standard deviation), and correlation analysis.</br>
**Outcome:** Identified key patterns and relationships in the data, which guided feature engineering and model selection.</br>

## Feature Engineering
**Purpose:** To create new features that improve the model's ability to detect fraud.</br>
**Methods:** Derived features such as transaction time, account age, days since the last address change, and others.</br>
**Outcome:** Enhanced model performance by providing additional relevant information.</br>

## Handling Imbalanced Data
**Purpose:** To address the issue of class imbalance, where fraudulent transactions are significantly fewer than non-fraudulent ones.</br>
**Methods:**</br>
  1) **Downsampling:** Reducing the majority class size (non-fraudulent transactions) through random downsampling and cluster centroid downsampling.</br>
  2) **Upsampling:** Increasing the minority class size (fraudulent transactions) through random upsampling and Synthetic Minority Over-sampling Technique (SMOTE).</br>

**Outcome:** Balanced the dataset, which improved the model's ability to detect fraud.</br>

## Model Selection and Evaluation
**Purpose:** To identify the best-performing model for fraud detection.</br>
**Models Tested:** Logistic Regression, Random Forest.</br>
**Evaluation Metrics:**</br>
  1) **Accuracy:** Ratio of correctly predicted instances to the total instances. Can be misleading for imbalanced datasets.</br>
  2) **Precision:** Ratio of true positive predictions to the total positive predictions. Indicates the ability to correctly identify fraud.</br>
  3) **Recall:** Ratio of true positive predictions to the total actual positives. Measures the ability to capture all relevant fraud instances.</br>
  4) **F1 Score:** Harmonic mean of precision and recall, balancing both metrics.</br>
  5) **Confusion Matrix:** Describes the performance by showing true positives, true negatives, false positives, and false negatives.</br>

**Outcome:** The Random Forest model with SMOTE achieved near-perfect precision and recall.</br>

## Final Model
**Selected Model:** Random Forest combined with SMOTE.</br>
**Performance:** High precision and recall, ensuring comprehensive fraud detection with minimal false positives and false negatives.</br>
**Metrics:**</br>
  1) **Precision:** Near-perfect</br>
  2) **Recall:** Near-perfect</br>
  3) **F1 Score:** High, indicating balanced performance between precision and recall.</br>

## Future Work
**Regular Updates:** Continuously update the model with new data to maintain accuracy.</br>
**Explore Ensemble Models:** Investigate the use of ensemble models such as Support Vector Machines (SVM) and neural networks for potential improvements.</br>

## How to Run the Project
1) **Clone the Repository:** git clone https://github.com/nikhil16kulkarni/Fraud-Transaction-Detection.git</br>
2) **Run the Jupyter Notebook**</br>

## Conclusion
This project demonstrates the effectiveness of using machine learning techniques for fraud detection in financial transactions. By addressing challenges such as imbalanced data and evolving fraud techniques, the implemented solution provides a robust framework for detecting fraudulent activities and protecting financial institutions and customers.
