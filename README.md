# Water-Potability-Prediction
Access to clean drinking water is a fundamental human right and a critical component of public health. However, the quality of water from various sources can vary widely and can sometimes be contaminated with harmful substances. Traditional methods of testing water quality can be time-consuming and require significant resources. To address this challenge, we aim to develop a predictive model that can accurately assess the potability of water based on key water quality parameters. This model will leverage machine learning techniques to analyze historical water quality data and predict the likelihood that a given water sample is safe for consumption. The goal is to provide a quick, reliable, and cost-effective tool for monitoring water quality and ensuring access to safe drinking water.
## Columns Info
pH: Measures the acidity or alkalinity of water. A pH level of 7 is neutral, below 7 is acidic, and above 7 is alkaline.

Hardness: Indicates the concentration of calcium and magnesium ions in water. Hard water can cause scale buildup in pipes and reduce soap effectiveness.

TDS (Total Dissolved Solids): Refers to the total amount of dissolved substances in water, including minerals, salts, and organic matter. High TDS can affect the taste and safety of water.

Chlorine: Often added to water for disinfection purposes. Excessive chlorine can lead to health issues and unpleasant taste or odor.

Sulfate: Naturally occurring in water, but high levels can cause a bitter taste and have laxative effects.

Conductivity: Measures the water's ability to conduct electrical current, which correlates with the concentration of dissolved ions.

Organic Carbon: Represents the amount of carbon-based compounds in water. High levels can indicate contamination and affect water quality.

Trihalomethanes (THMs): Byproducts formed when chlorine reacts with organic matter. High levels of THMs are considered harmful and can increase cancer risks.

Turbidity: Refers to the cloudiness or haziness of water caused by suspended particles. High turbidity can harbor pathogens and reduce water quality.

Potability: Indicates whether water is safe to drink. This is determined by analyzing various parameters and ensuring they meet the safety standards.

## Exploratory Data Analysis
1. Studied meta-data & found number of records, null values & data types.
2. Detected outliers and skewness within the data.

## Data Cleaning & Preprocessing
1. Dropped the null values, handled skewness & imputed the outliers with median.
2. Normalized the data with the help of StandardScaler
3. Separated Features(X) and Target(Y).
4. Splitted the dataset into train set and test set.

## Model Building
Built the following models and attained 90%+ accuracy in every model:

| Model  | Accuracy |
| ------------- | ------------- |
| Logistic Regression  | 92.44%  |
| KNeighbors Classifier | 93.86%  |
| SVM Classifier  | 94.69%  |
| Decision Tree Classifier | 99.07%  |
| Random Forest Classifier | 99.25%  |
| XGBoost Classifier | 99.23%  |


