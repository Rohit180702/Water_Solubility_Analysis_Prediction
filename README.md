# Water Solubility Analysis and Prediction

This project involves a comprehensive analysis of a water quality dataset to predict water solubility based on various attributes such as pH levels, chemical composition, and environmental factors. The primary objective is to extract insights from the data and build predictive models that can accurately forecast water solubility.

## Project Overview

The water quality dataset contains information on various parameters including water composition, sources, color, and a target variable indicating water solubility. The project is divided into several stages:

1. **Data Cleaning and Preprocessing**: Handling missing values, normalizing and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**: Visualizing data distributions, relationships, and patterns.
3. **Feature Engineering**: Transforming features to improve model performance.
4. **Modeling**: Building and evaluating multiple machine learning models to predict water solubility.
5. **Evaluation**: Comparing models based on accuracy, ROC curves, and AUC scores.

## Dataset

The dataset used in this project includes the following key features:

- **pH, Iron, Nitrate, Chloride, Lead, Zinc, Color, Turbidity, Fluoride, Copper, Odor, Sulfate, Conductivity, Chlorine, Manganese, Total Dissolved Solids**: Chemical and physical properties of water.
- **Source, Water Temperature, Air Temperature, Month, Day, Time of Day**: Environmental and temporal data.
- **Target**: Binary variable indicating water solubility.

## Exploratory Data Analysis (EDA)

- **Distribution Analysis**: Histograms and density plots were created for various features like pH levels, turbidity, odor, and others to understand their distributions.
- **Categorical Data Visualization**: Bar plots were used to analyze the frequency of different water colors and sources.
- **Time Series Analysis**: Visualizations of water temperature over time were plotted to identify trends.
- **Box Plots**: Used to compare pH distributions across different water sources.
- **Chemical Composition Analysis**: Bar charts showing the percentage composition of chemicals like Zinc, Lead, and Chlorine.

## Machine Learning Models

Several machine learning models were trained and evaluated:

1. **Logistic Regression**
   - **Accuracy**: 79.12%
2. **Decision Tree**
   - **Accuracy**: [To be included]
3. **Random Forest**
   - **Accuracy**: 88.79%
4. **XGBoost**
   - **Accuracy**: 85.51%

## Conclusion

The Random Forest model performed the best with an accuracy of 88.79%. The project successfully demonstrates how machine learning algorithms can be applied to predict water solubility based on various environmental and chemical factors.

## Installation

To run the project, install the required libraries:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

## Usage

Run the Jupyter notebook to execute the analysis and modeling steps. The code can be modified for different datasets or extended with additional models.

## Contributions

Feel free to fork the repository, make modifications, and submit a pull request. Contributions to improve the model accuracy or add new features are welcome!

## License

This project is licensed under the MIT License.

---

This README covers the major aspects of your project, including data analysis, modeling, and evaluation, while also making it easy for others to replicate or contribute to your work.
