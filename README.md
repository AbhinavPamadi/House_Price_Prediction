# House_Price_Prediction

This project focuses on analyzing and predicting house prices in Bengaluru using a dataset of real estate listings. The goal is to apply data cleaning, feature engineering, visualization, and machine learning techniques to build an accurate price prediction model.

---

## Dataset

The dataset used is `Bengaluru_House_Data.csv`, which contains the following features:
- Location
- Size (number of bedrooms)
- Total square footage
- Number of bathrooms
- Price (target variable)
- And other relevant attributes

---

## Technologies Used

- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. **Data Cleaning**
   - Handling missing values
   - Removing outliers and inconsistencies
   - Standardizing categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Visualizing price trends by location, size, and other features
   - Correlation analysis

3. **Feature Engineering**
   - Converting textual data into numeric
   - Creating new meaningful features (e.g., price per square foot)

4. **Model Building**
   - Train-test split
   - Linear Regression and other models
   - Hyperparameter tuning

5. **Evaluation**
   - Root Mean Square Error (RMSE)
   - R² Score
   - Cross-validation

---

## Results

- Achieved a reasonable level of prediction accuracy using Linear Regression and other models.
- Identified key features impacting house prices in Bengaluru.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/bengaluru-house-price-prediction.git
cd bengaluru-house-price-prediction
```

2.Install Dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3.Run the Jupyter Notebook:

```bash
jupyter notebook main.ipynb
```

