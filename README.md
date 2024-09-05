# Black Friday Dataset: EDA and Feature Engineering

This project focuses on conducting **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the Black Friday dataset. As a beginner, I aimed to apply foundational data science techniques, from cleaning and understanding the dataset to preparing it for model training.

## Project Overview

The Black Friday dataset contains customer purchase details. The main objective of this project is to:
- Explore the dataset to identify patterns and insights.
- Engineer features that could help in building predictive models.
- Prepare the data for training machine learning models.

### Key Steps in the Project
1. **Data Loading and Preprocessing:**
   - The dataset was loaded using pandas.
   - Missing values were handled by separating rows with missing purchase values into test and train sets.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics were performed to understand the dataset.
   - Visualizations such as bar plots were used to explore purchase trends and customer demographics.

3. **Feature Engineering:**
   - Unnecessary columns, like `Product_ID`, were dropped from the feature set.
   - Numerical features were scaled using **StandardScaler** to prepare for machine learning models.

4. **Train-Test Split:**
   - The data was split into training and test sets using `train_test_split` from `sklearn`.
   - The target variable was the `Purchase` column, and all other columns were used as features.

5. **Feature Scaling:**
   - Implemented scaling of the features to standardize the data, which is essential for certain machine learning models.

### Next Steps
- The dataset is ready to be used for training machine learning models.

## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/YashsTiwari/BlackFriday-EDA-and-Feature-Engineering.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to view the analysis.
