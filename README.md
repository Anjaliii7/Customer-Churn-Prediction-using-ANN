# Customer-Churn-Prediction-using-ANN
Project Overview -

Customer churn is when customers stop doing business with a company.This project aims to predict customer churn using an Artificial Neural Network (ANN).The model was trained after applying feature selection techniques, and performance was tracked using Keras and TensorBoard for better visualization and monitoring of training progress.

🎯 Objectives -
* Perform feature selection to identify the most important predictors of churn.
* Build and train an ANN model for binary classification (Churn / No Churn).
* Monitor model performance using TensorBoard.

🛠️ Technologies Used
* Python 3.x
* TensorFlow / Keras – building and training ANN
* Pandas & NumPy – data handling
* Scikit-learn – preprocessing & feature selection
* TensorBoard – monitoring training performance

📊 Dataset-
Source: Customer Churn Dataset : Kaggle
Features: 
1. Customer Demographics
  * CustomerId → Unique ID (not used for modeling).
  * Surname / Name → Identifier (not useful for prediction).
  * Age → Older/younger customers may have different churn behavior.
  * Gender → Male / Female differences in churn rate.
  * Geography (Country/Region) → Region-specific churn patterns.
 2. Account Information
  * Tenure → How long the customer has stayed (loyalty factor).
  * Balance → Account balance; very low/high balance might affect churn.
  * EstimatedSalary → Income level can influence churn.
  * HasCrCard → Whether customer has a credit card (0/1).
  * IsActiveMember → Customer activity status, a strong churn indicator.
3. Banking / Service Usage
  * NumOfProducts → Number of products/services used (more products = less churn chance).
  * CreditScore → Higher credit score → more trusted customer.
4. Target Variable
  * Exited → Churn status (0 = stayed, 1 = churned).

⚙️ Methodology
1. Feature Selection
  * Removed irrelevant/redundant columns.
  * Applied statistical methods to identify most impactful features.
2. Data Preprocessing
  * Handled missing values.
  * Encoded categorical variables.
  * Scaled numerical features.
  * Split dataset into training and testing sets.
3. Model Training (ANN)
  * Input layer matching selected features.
  * Hidden layers with ReLU activation.
  * Output layer with Sigmoid activation for binary classification.
  * Optimizer: Adam | Loss: Binary Crossentropy | Metric: Accuracy.
4. Monitoring with TensorBoard

📈 Results -
* ANN successfully trained to classify churn with good accuracy.
* Feature selection improved training efficiency by reducing irrelevant inputs.
* TensorBoard provided clear insights into training/validation performance.

👩‍💻 Author

Anjali Jhanjhariya
📍 B.Tech CSE (3nd Year) | Aspiring AI & ML Engineer.
 Exploring deep learning, model building, and practical ML applications
