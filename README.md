# Coronary-Heart-Disease-Prediction-
A machine learning model for estimating level of obesity levels using features such as eating habits and physical conditions, including variables like diet patterns, physical activity frequency, and lifestyle choices.


### Summary of the Machine Learning Model for Estimating Obesity Levels

This project developed a machine learning model to estimate obesity levels based on eating habits, physical activity, and lifestyle choices. Key methods included **data preprocessing**, **feature engineering**, **exploratory data analysis (EDA)**, and **correlation analysis**. Four models were evaluated:

#### Models and Results:
1. **Logistic Regression**  
   - Accuracy: 0.82 | F1-Score: 0.82  
   - **Strength:** High precision and recall for specific obesity levels (class 0, 3).  

2. **K-Nearest Neighbors (KNN)**  
   - Accuracy: 0.98 | F1-Score: 0.98  
   - **Strength:** Consistent high performance across all obesity classes.  

3. **Support Vector Machine (SVM)**  
   - Accuracy: 0.74 | F1-Score: 0.74  
   - **Challenge:** Struggled with classifying certain instances accurately.  

4. **Random Forest Classifier**  
   - **Accuracy: 1.00** | **F1-Score: 1.00**  
   - **Strength:** Perfect classification with excellent precision, recall, and F1-scores across all classes. This model was selected as the **best performer**.

#### Key Findings:
- **Feature Importance:**  
  - **Body Mass Index (BMI)** and **Weight** were the most important predictors.  
  - Other important features included **Vegetable Consumption Frequency** and **Age**.  
  - Features like **Gender**, **Smoking**, and **Transportation Mode** had minimal impact.

#### Suggestions for Improvement:
- Address **class imbalance** using techniques like oversampling or undersampling.
- Apply **regularization** to reduce overfitting risks.
- Experiment with other ensemble models or deep learning approaches.
- **Deploy the model** using a Flask app for real-time input and predictions.

The Random Forest model's perfect performance and robust feature insights make it the ideal candidate for future applications.
