
# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning. By exploring the dataset, handling missing values, encoding categorical variables, and scaling numerical features, a Logistic Regression model was trained and evaluated. The model achieved an accuracy of approximately 80%, demonstrating its ability to make reasonable predictions based on passenger characteristics.

## Project Overview

The Titanic dataset contains information about passengers who were on board the Titanic, including their demographics, ticket details, and survival status. The goal of this project is to build a model that can accurately predict whether a passenger survived or not based on their features.

## Steps Involved

1. **Data Exploration and Cleaning:**
   - Explored the dataset to understand its structure and characteristics.
   - Handled missing values by imputing or removing them.
   - Encoded categorical variables into numerical representations.
   - Scaled numerical features to ensure they contribute equally to the model.

2. **Model Selection and Training:**
   - Chose Logistic Regression as the machine learning model for this classification task.
   - Trained the model on a portion of the dataset (training set).

3. **Model Evaluation:**
   - Evaluated the model's performance on a separate portion of the dataset (testing set).
   - Used metrics like accuracy, precision, recall, and F1-score to assess the model's effectiveness.

## Results

The Logistic Regression model achieved an accuracy of approximately 80% in predicting passenger survival. This indicates that the model is able to make reasonable predictions based on the given features.

## Insights

The analysis revealed key factors influencing survival, such as:

- **Gender:** Females had a higher survival rate.
- **Passenger Class:** Higher classes had better chances of survival.
- **Age:** Younger passengers were more likely to survive.

These insights align with historical accounts of the disaster.

## Conclusion

This project demonstrates the power of data science and machine learning in extracting meaningful insights from historical events and making predictions. The developed model can serve as a foundation for further research and analysis related to the Titanic disaster.


## Usage

To run this project, you will need the following:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

You can install these packages using pip:

Once you have installed the necessary packages, you can open the  Google colab or Jupyter Notebook file and run the code cells.
