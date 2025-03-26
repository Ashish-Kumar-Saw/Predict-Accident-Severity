# US Accidents Machine Learning Analysis with Random Forest

This script performs a machine learning analysis on a dataset of US accidents in Montgomery County, PA. The script aims to predict accident severity using various supervised machine learning algorithms, with a focus on Random Forest.

# Predicting Accident Severity

This project analyzes a dataset of traffic accidents to:

* **Predict Accident Severity:** Develop machine learning models to accurately predict the severity of accidents.
* **Identify Contributing Factors:** Analyze the data to identify key factors that contribute to the occurrence and severity of accidents.
* **Develop Mitigation Strategies:** Propose data-driven strategies for mitigating accidents based on the insights gained from the analysis.

## Key Activities

**Data Cleaning and Processing:**

* Handle missing values and outliers.
* Transform and engineer relevant features (e.g., time of day, day of the week, weather conditions).
* Explore and visualize the data to gain initial insights through data visualizations (e.g., histograms, scatter plots, box plots).

**Model Development:**

* Split the dataset into:
    * Training set (75%)
    * Validation set (15%)
    * Testing set (10%)
* Train and evaluate various machine learning models, including:
    * Logistic Regression
    * Random Forest
    * Support Vector Machines (SVM)
    * K-Nearest Neighbors
    * Decision Trees   
    * Naive Bayes
    * Gradient Boosting
* Perform hyperparameter tuning using techniques like grid search or random search to optimize model performance.

**Model Evaluation:**

* Assess model performance using relevant metrics:
    * Accuracy
    * Precision
    * Recall
    * F1-score
    * Area Under the ROC Curve (AUC)
* Conduct rigorous testing and validation to ensure model reliability and robustness.

## Key Skills

* **Data Handling:**
    * Data cleaning and preprocessing
    * Feature engineering
* **Data Analysis:**
    * Exploratory data analysis
    * Data visualization
* **Machine Learning:**
    * Model selection and training
    * Hyperparameter tuning
    * Model evaluation and interpretation

## Deliverables

* **Jupyter Notebook:** Contains well-documented code for all stages of the project, including data loading, cleaning, feature engineering, model training, evaluation, and visualization. Includes clear and concise comments explaining the purpose of each code block.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ashish-Kumar-Saw/Predict-Accident-Severity-.git
2. **Create a virtual environment (recommended):**

    ```bash
    python -m venv venv 
3. **Activate the virtual environment:**

    Windows:
    ```bash
    venv\Scripts\activate

        macOS/Linux:
    
        source venv/bin/activate

4. **Install Required Packages:**  
    ```bash
    pip install -r requirements.txt 