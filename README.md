# Predicting-Insurance-Claim-Amounts
Regression modeling of medical insurance charges using the Medical Cost Personal Dataset. Includes data exploration, visualizations (age, BMI, smoking status), linear regression training, and evaluation with MAE and RMSE to understand key factors influencing healthcare costs.

## Objective
Estimate medical insurance charges based on personal attributes such as age, BMI, and smoking status. This regression task helps understand how lifestyle and demographic factors influence healthcare costs.

## Dataset
The project uses the **Medical Cost Personal Dataset** (Kaggle).  
It contains individual records with features including:
- Age  
- Sex  
- BMI (Body Mass Index)  
- Children  
- Smoker status  
- Region  
- Charges (Target variable)

## Approach
1. **Data Loading & Inspection**
   - Loaded dataset using pandas
   - Inspected structure with `.head()`, `.shape`, and `.info()`

2. **Exploratory Data Analysis (EDA)**
   - Scatter plots to analyze age vs charges and BMI vs charges
   - Box plots to compare charges between smokers and non-smokers
   - Correlation analysis to identify key influencing factors

3. **Data Preparation**
   - Encoded categorical variables (sex, smoker, region) using one-hot encoding
   - Split dataset into training (80%) and testing (20%) sets

4. **Model Training**
   - Implemented Linear Regression to predict insurance charges

5. **Model Evaluation**
   - Evaluated performance using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE)

## Results & Insights
- **Smoking Status:** Strongest predictor of higher insurance charges  
- **BMI & Age:** Both positively correlated with charges
- *Model Performance:* Achieved reasonable accuracy with MAE ≈ 4181 and RMSE ≈ 5796 
- **Model Performance:** Achieved reasonable accuracy with MAE ≈ XXXX and RMSE ≈ XXXX (replace with your actual values)

or ye? ya isko or polish karoon?
