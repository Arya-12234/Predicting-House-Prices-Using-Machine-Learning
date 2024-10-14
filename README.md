# House Price Prediction

This project uses machine learning techniques to predict house prices based on various features.

## Steps Used

1. **Data Exploration**: Analyzed a dataset containing features such as square footage, number of bedrooms, bathrooms, neighborhood, and year built.
  
2. **Data Preprocessing**:
   - Handled missing values.
   - One-hot encoded categorical variables (Neighborhood).
  
3. **Feature Selection**:
   - Defined features (`X`) and target variable (`y`).

4. **Model Training**:
   - Split the dataset into training and testing sets.
   - Used a linear regression model to train the data.

5. **Model Evaluation**:
   - Evaluated the model's performance using metrics like Mean Absolute Error (MAE) and R-squared score.
   - Visualized results through scatter plots and residual plots.

6. **Model Usage**:
   - Provided predictions for house prices based on input features.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/username/predicting-house-prices.git
cd predicting-house-prices
pip install -r requirements.txt
