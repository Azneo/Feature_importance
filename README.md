# Car Price Prediction Analysis

## Overview

This project explores the key features influencing car prices using machine learning models and statistical analysis. The goal is to identify and quantify the factors that significantly impact a car's market value. The analysis includes various regression techniques such as Linear Regression, Logistic Regression, and Lasso Regression, and visualizes the importance of different features using various methods.

## Features Analyzed

- **Max Power**: The power of the car's engine, which has a significant impact on its price.
- **Year of Manufacture**: The year the car was produced, with older cars generally having a lower market value.
- **Kilometer Count**: The number of kilometers the car has been driven, which inversely affects its price.
- **Fuel Type, Transmission, and Location**: These categorical features are analyzed to understand regional and consumer preferences.

## Project Workflow

1. **Data Preprocessing**:
    - Categorical features are encoded using One-Hot Encoding.
    - Numerical features are standardized to ensure fair model performance.
    
2. **Model Training and Evaluation**:
    - Multiple regression models (Linear Regression, Logistic Regression, Lasso) are trained on the data.
    - R² scores are calculated for both training and test datasets to assess model performance.
    
3. **Feature Importance**:
    - Feature importances are extracted from the trained models and visualized in bar plots.
    - A deep dive into the correlations between features and price is provided, showing which features positively or negatively affect the car price.

4. **Results and Visualization**:
    - R² scores and feature importances are displayed with insights into which features contribute most to price prediction.
    - Color-coded plots indicate the positive or negative relationship of each feature with the price.

## Installation and Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Car-Price-Prediction.git
    ```

2. **Install the required dependencies**:
    You can install the necessary Python libraries using `pip`:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    After installing the dependencies, open the Jupyter Notebook to explore the analysis:
    ```bash
    jupyter notebook car_price_analysis.ipynb
    ```

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: 
    - pandas
    - numpy
    - scikit-learn
    - matplotlib

You can find the list of required packages in the `requirements.txt` file.

## Insights

The analysis shows that **Max Power** is the most influential factor in determining car price. Other factors such as **year of manufacture** and **kilometer count** have a negative impact on the price, while features like **fuel type** and **transmission** contribute to the model's predictive power depending on regional preferences.

## Conclusion

This project provides a solid foundation for understanding the key determinants of car pricing. By applying machine learning techniques to real-world data, we can make data-driven decisions in the automotive market. Future improvements could involve using more advanced algorithms or incorporating additional features for even better predictive accuracy.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- **Your Name** - [Your GitHub Profile](https://github.com/yourusername)
