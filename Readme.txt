# GDP Prediction Project

## Overview
This project aims to analyze and predict the Gross Domestic Product (GDP) of various countries using historical data. The dataset used contains GDP data over several years for different countries. The analysis focuses on the United States' GDP, with a machine learning model built to predict future GDP.

## Dataset
The dataset used in this project is from the **GDP Dataset** provided by the **World Bank**. It includes GDP values for various countries from the year 1960 to the present.

- **Data Source**: [World Bank GDP Data](https://raw.githubusercontent.com/datasets/gdp/master/data/gdp.csv)

## Libraries Used
- **pandas**: For data manipulation and cleaning.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **seaborn**: For statistical data visualization.
- **sklearn**: For machine learning (Linear Regression, metrics).

## Steps in the Project

1. **Data Loading**: Load the dataset from a CSV file.
2. **Exploratory Data Analysis (EDA)**: Perform initial analysis and visualize GDP trends.
3. **Data Cleaning**: Handle missing values in the dataset.
4. **Model Training**: Train a Linear Regression model to predict GDP based on historical data.
5. **Model Evaluation**: Evaluate the model performance using Mean Squared Error (MSE) and R2 Score.
6. **Prediction**: Predict GDP for the year 2025.

## Result
The model predicts the GDP for the United States in 2025 based on the available data.

## How to Run

1. Clone this repository to your local machine:
    ```
    git clone https://github.com/yourusername/yourrepository.git
    ```

2. Install the required libraries:
    ```
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. Run the Jupyter notebook `gdp_prediction_notebook.ipynb` to execute the analysis and predictions.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
