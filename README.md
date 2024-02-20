## Predictive Modeling for Agriculture

This project aims to build a multi-class Logistic Regression model to predict categories of "crop" with a F1 score of more than 0.5.

### Introduction

Crop prediction plays a crucial role in agriculture by helping farmers make informed decisions about crop selection and management practices. Machine learning techniques, such as logistic regression, can assist in predicting the types of crops based on various soil measures.


### Dataset

The dataset used in this project, soil_measures.csv, contains information about soil measures and corresponding crop types. It includes features such as soil pH, nitrogen levels, phosphorus levels, and potassium levels along with the target variable "crop".


### Project Structure

Data Preparation: The dataset is loaded into a pandas DataFrame, and initial data checks are performed to ensure data quality.
Data Splitting: The data is split into training and test sets to train and evaluate the model.
Feature Selection: We predict the "crop" type using each feature individually to identify the most influential features.
Multicollinearity Check: Correlation analysis is performed to detect and handle multicollinearity among features.
Final Model Training and Evaluation: The final model is trained using the selected features, and its performance is evaluated using the F1 score metric.


### Requirements

- Python 3
- pandas
- scikit-learn
  

### Conclusion

The final model achieves an F1 score of about 0.60, indicating its effectiveness in predicting crop types based on soil measures.

For detailed implementation and analysis, refer to the Jupyter Notebook or Python script in the repository.





