# 🏘️ Multivariable Regression and House Valuation Model

This project uses **multivariable linear regression** to predict **house prices** in the Boston housing dataset. The notebook explores data visualization, correlation analysis, regression modeling, and model evaluation.

---

## 📁 Project Structure
 ```
├── Multivariable_Regression_and_Valuation_Model_.ipynb # Main Jupyter notebook
├── boston.csv # Dataset used in the notebook
├── README.md # Project documentation
```


---

## 📊 Features Analyzed

- `PRICE`: Home price in $1000s
- `RM`: Average number of rooms
- `DIS`: Distance to employment centers
- `RAD`: Accessibility to highways
- `NOX`: Nitric oxide pollution levels
- `LSTAT`: Percentage of lower income population
- `CHAS`: Proximity to the Charles River

---

## 🛠️ Techniques Used

- 📈 **Data visualization** using Seaborn & Matplotlib
- 🔍 **Feature engineering**
- 🧠 **Multivariable Linear Regression** with Scikit-Learn
- 🧪 **Model evaluation** using R² score
- 🔄 **Target transformation** to improve model performance

---

## 🔬 Model Evaluation

- Compared performance before and after log-transforming the target variable.
- Evaluated model fit using R² scores.

---

## 📦 Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn
- plotly

You can install the requirements using:

To install the required dependencies on **Windows** or **macOS**, use the following command in your terminal or command prompt:

```bash
pip install -r requirements.txt



