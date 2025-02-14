# Fuel Consumption Prediction Using Linear Regression

## Overview
This project involves the development of a **machine learning model** to predict **fuel consumption (Gallons per 100 miles)** based on various car attributes, such as **weight and horsepower**. The model uses **Linear Regression** to make predictions and analyze trends in fuel efficiency.

## Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - pandas (data manipulation)
  - matplotlib & seaborn (data visualization)
  - scikit-learn (machine learning model training & evaluation)
- **Tools:** Jupyter Notebook

## Dataset
- The dataset used is `AutoMPG.csv`, which contains car specifications and their corresponding fuel consumption.
- The dataset was cleaned to handle missing values and inconsistencies before model training.

## Steps in the Project
1. **Data Cleaning & Preprocessing**
   - Identified and handled missing values.
   - Standardized data for consistency.
2. **Exploratory Data Analysis (EDA)**
   - Visualized relationships between car attributes and fuel consumption.
   - Identified key factors influencing fuel efficiency.
3. **Feature Engineering**
   - Selected relevant features (e.g., weight, horsepower) for model training.
4. **Model Training & Evaluation**
   - Implemented **Linear Regression** using `scikit-learn`.
   - Evaluated model performance using:
     - **Mean Squared Error (MSE)**
     - **R² Score**


## Results
- The model successfully predicts fuel consumption based on car attributes.
- Visualizations help in understanding trends in fuel efficiency and how different features affect consumption.

## Future Improvements
- Experiment with more advanced regression models.
- Incorporate additional features for better prediction accuracy.
- Deploy the model as a web application.

## License
This project is open-source and available under the **MIT License**.

