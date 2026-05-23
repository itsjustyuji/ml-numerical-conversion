# Data Preprocessing: Categorical to Numerical Conversion

This is my very first Machine Learning utility project! The primary focus of this notebook is to practice and master **Data Preprocessing**, specifically converting non-numerical (categorical) data into numerical formats so that Machine Learning algorithms can process them.

Instead of optimizing for model accuracy, the core objective here was to build a clean pipeline that transforms raw text features into a format ready for Scikit-Learn estimators.

## 🎯 Project Objective
In Machine Learning, models cannot naturally understand text strings like "Honda" or "Blue". They only understand numbers. This project serves as a practical implementation of converting those text attributes using Python and Pandas.

## 📊 Dataset Used
The project utilizes `car-sales-extended.csv`, which contains the following features:
* **Make** (Categorical string: Honda, BMW, Toyota, Nissan)
* **Colour** (Categorical string: White, Blue, etc.)
* **Odometer (KM)** (Numerical)
* **Doors** (Numerical/Categorical)
* **Price** (Target Variable)

## 🛠️ Concepts Handled
* **Data Inspection:** Loading and inspecting the structural shape of data using `pd.read_csv()` and `.head()`.
* **Feature & Label Separation:** Splitting data into Features ($X$) and Target Labels ($y$).
* **Numerical Conversion:** Implementing encoding techniques to transform string columns (`Make`, `Colour`) into numeric values.

## 🚀 Key Takeaway
Model evaluation metrics (like accuracy or $R^2$ score) weren't the focus of this repository. This project successfully demonstrates a foundational understanding of the **Data Preparation phase** of the data science lifecycle.
