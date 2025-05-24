# Car Price Prediction - Data Preprocessing & Exploration

This project is focused on data preprocessing and exploratory analysis for a car price prediction dataset. It includes techniques to handle missing values, perform encoding, and prepare the data for machine learning tasks.

## 📂 Project Structure

* `carprice.ipynb`: Jupyter Notebook containing all the preprocessing steps including:

  * Data loading
  * Missing value treatment
  * Label encoding
  * One-hot encoding
  * Statistical imputation (mean, median, mode)

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 📊 Dataset Overview

The dataset includes information about various car features that influence car prices. Columns include:

* `CarName`
* `fueltype`
* And other numerical and categorical features

> 📌 Note: The actual dataset `car_price.csv` is expected to be in the same directory or updated in the notebook path.

## 🦼️ Key Data Preprocessing Steps

* **Missing Value Handling:**

  * Dropping rows/columns
  * Mean/Median imputation for numeric columns
  * Mode imputation for categorical columns

* **Encoding:**

  * Label Encoding
  * One-Hot Encoding

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Mayank-Rajputt/Car-Price-Preprocessing.git
   cd Car-Price-Preprocessing

   ```

2. Make sure you have Jupyter and necessary libraries installed:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. Run the notebook:

   ```bash
   jupyter notebook carprice.ipynb
   ```

## 📌 Future Enhancements

* Feature Engineering
* Model Training (Linear Regression, Random Forest, etc.)
* Hyperparameter Tuning
* Model Evaluation

## 📄 License

This project is licensed under the MIT License.

---

*Created with ❤️ by Mayank Rana*
