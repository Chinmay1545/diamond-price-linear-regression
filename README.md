# Diamond Price Prediction using Linear Regression

This project explores how physical and quality attributes of diamonds influence market price using multiple linear regression. The goal of the project is not only to build a predictive model, but to understand feature importance and interpretability in a real world dataset.

I chose this problem to practice end to end data analysis, including data cleaning, exploratory analysis, categorical encoding, and regression modeling, while focusing on statistical reasoning rather than black box models.

## Dataset

The dataset is a cubic zirconia diamonds dataset containing both numerical and categorical attributes related to diamond quality and dimensions.

Key features include:

* carat
* cut
* color
* clarity
* depth
* table
* length
* width
* height
* price

## Project Structure

* `Linear_Regression_Diamond_Dataset_FINAL.ipynb`
  Contains the complete workflow including preprocessing, visualization, regression modeling, and coefficient interpretation.

* `cubic_zirconia.csv`
  Raw dataset used for analysis.

## Methodology

* Cleaned and validated numerical and categorical features
* Performed exploratory data analysis using histograms, KDE plots, and summary statistics
* Applied ordinal encoding to categorical variables such as cut, color, and clarity
* Analyzed feature relationships using correlation matrices and heatmaps
* Built a multiple linear regression model to estimate price
* Interpreted coefficients to understand feature impact and directionality

## Final Regression Model

The final model expresses diamond price as a linear combination of physical dimensions and quality attributes, enabling clear interpretation of how each feature contributes to price variation.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit learn

## How to Run

1. Clone the repository
2. Open `Linear_Regression_Diamond_Dataset_FINAL.ipynb`
3. Run all cells sequentially

## Key Takeaways

* Carat and physical dimensions have the strongest influence on price
* Ordinal encoding choices significantly impact interpretability
* Linear regression provides transparent insight into feature relationships compared to more complex models
