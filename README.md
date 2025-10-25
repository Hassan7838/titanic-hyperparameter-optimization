# titanic-hyperparameter-optimization 
"Hyperparameter Optimization of ML Model for Survival Prediction"

This project demonstrates **systematic hyperparameter optimization** of a machine learning classifier (Logistic Regression or Decision Tree) for predicting passenger survival on the Titanic dataset.  

Developed as part of my **Machine Learning internship**, this project explores the impact of hyperparameter tuning on model performance using both **Grid Search** and **Randomized Search** strategies.

# Project Goal

To identify the **optimal hyperparameters** that maximize model performance for the Titanic survival classification task and to analyze the performance improvements achieved through tuning.

# Project Workflow

### 1. Model Selection and Initialization
- Selected **Logistic Regression** or **Decision Tree Classifier** as the base model.  
- Trained the model using **default parameters** to establish baseline performance.

### 2. Hyperparameter Search Strategies
Implemented two tuning methods using **cross-validation**:
- **Grid Search:** Exhaustively explores a defined grid of parameter combinations.  
- **Randomized Search:** Randomly samples parameter combinations from specified distributions.

### 3. Model Training and Evaluation
- Trained models using both search strategies.  
- Evaluated performance using key metrics:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**

### 4. Performance Comparison and Analysis
- Compared:
  - Default model  
  - Best model from **Grid Search**  
  - Best model from **Randomized Search**
- Documented the **optimal hyperparameters** for each method.  
- Visualized performance improvements.

# Tools and Libraries
- **Python 3.x**
- **Pandas** – for data handling  
- **NumPy** – for numerical operations  
- **Scikit-learn** – for:
  - Models: `LogisticRegression`, `DecisionTreeClassifier`
  - Optimization: `GridSearchCV`, `RandomizedSearchCV`
  - Evaluation: `accuracy_score`, `precision_score`, `recall_score`, `f1_score`
 
# Dataset Information

- Source: [Kaggle - Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)  
- The dataset is **not uploaded** due to size constraints.  
- You can download it directly from Kaggle and place it in your working directory.

# How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-hyperparameter-optimization.git
