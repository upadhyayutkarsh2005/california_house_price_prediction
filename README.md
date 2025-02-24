

## 📌 Project Overview
The **California House Price Prediction** project is a machine learning model designed to predict house prices in California based on various features such as location, population, median income, and other housing-related attributes. The dataset used for this project is derived from the California Census data.

## 📂 Dataset
The dataset contains features like:
- `longitude` - Geographical coordinate
- `latitude` - Geographical coordinate
- `housing_median_age` - Median age of the houses in the block
- `total_rooms` - Total number of rooms in a block
- `total_bedrooms` - Total number of bedrooms in a block
- `population` - Total population in a block
- `households` - Total number of households in a block
- `median_income` - Median income of residents in a block
- `ocean_proximity` - Proximity to the ocean (categorical feature)
- `median_house_value` - Target variable (house price)

## 🛠️ Tech Stack
- **Programming Language:** Python
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
- **Machine Learning Model:** Linear Regression, Random Forest, XGBoost
- **Version Control:** Git & GitHub

## 🚀 Project Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling & transformation
   
2. **Exploratory Data Analysis (EDA)**
   - Correlation analysis
   - Data visualization using Matplotlib & Seaborn
   - Distribution and outlier detection

3. **Model Training & Evaluation**
   - Splitting data into train and test sets
   - Training multiple regression models
   - Evaluating performance using RMSE, MAE, and R² score

4. **Hyperparameter Tuning**
   - GridSearchCV for model optimization
   - Cross-validation for robustness

5. **Deployment (Optional)**
   - Deploying using Flask or Streamlit (Future work)

## 📊 Results
- The **Random Forest Regressor** and **XGBoost** models performed best with low RMSE and high R² scores.
- **Feature Importance Analysis:** Median income and location were the most significant predictors of house prices.

## 🏗️ How to Run the Project
### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/upadhyayutkarsh2005/california_house_price_prediction.git
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook
```sh
jupyter notebook
```

## 🤝 Contributing
Feel free to contribute by opening an issue or submitting a pull request.

## 📜 License
This project is licensed under the MIT License.

## 📞 Contact
For any inquiries, reach out to [Utkarsh Upadhyay](https://github.com/upadhyayutkarsh2005).

