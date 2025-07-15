
# Diamond Analysis

A data analysis and machine learning project that explores how various characteristics of diamonds affect their price. This project uses data visualization, exploratory data analysis (EDA), and a simple linear regression model to predict diamond prices based on features like carat, cut, color, clarity, and size.


##  Project Overview

This project analyzes a dataset of diamonds, performs feature engineering by calculating a new 'size' feature, visualizes the relationships between different features and price, and builds a linear regression model to predict prices.

It’s a beginner-friendly demonstration of data preprocessing, visualization, correlation analysis, and regression modeling using Python libraries.


##  Technologies & Libraries Used

* **Python**
* **Pandas** — data handling and preprocessing
* **NumPy** — numerical operations
* **Matplotlib** — data visualization
* **Seaborn** — statistical data visualization
* **Scikit-learn** — machine learning model building and evaluation

---

##  Key Features

* **Data Cleaning**: Removed missing values from the dataset.
* **Feature Engineering**: Created a new feature 'size' by multiplying diamond dimensions (`x * y * z`).
* **Label Encoding**: Converted categorical features (`cut`, `color`, `clarity`) to numerical format using `LabelEncoder`.
* **Exploratory Data Analysis (EDA)**:

  * Summary statistics
  * Correlation analysis
  * Scatter plots (Carat vs Price, Size vs Price)
  * Bar plots for average price by Cut and Color
  * Heatmap of feature correlations
* **Model Building**:

  * Train-test split (80:20)
  * Trained a **Linear Regression** model on the data
* **Model Evaluation**:

  * Calculated **MSE**, **MAE**, and **R² score**
  * Visualized actual vs predicted prices with a scatter plot
* **Feature Importance**:

  * Analyzed model coefficients to understand the impact of each feature on diamond price


## Results

The model provides a basic but interpretable prediction of diamond prices, with insights into which factors most strongly affect price (like **carat**, **size**, and **clarity**).

Model evaluation metrics:

* **Mean Squared Error (MSE)**
* **Mean Absolute Error (MAE)**
* **R² Score**

---

## How to Run

1. Install required libraries if not already installed:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Place the `diamonds.csv` dataset in the same directory as the Python script.

3. Run the Python script:

   ```bash
   python diamond_analysis.py
   ```

4. Visualizations and model outputs will be displayed in the console and as plots.


