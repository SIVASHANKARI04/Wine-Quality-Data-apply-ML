**WINE QUALITY DATA APPLY MACHINE LEARNING CONCEPT**



**Dataset Overview**


The dataset used in this project is the Car Resale Price Prediction Dataset, which includes information about used cars 

such as manufacturing year, brand, fuel type, transmission type, mileage, engine capacity, number of previous owners, and the selling price.

The dataset contains 6,000 rows and 10 columns, with both numerical and categorical variables. Key features include Year, Fuel_Type, 

Transmission, Owner, Kilometers_Driven, Engine, and the target variable Selling_Price.



**Data Preparation**


Several preprocessing steps were applied to clean and transform the dataset before feeding it into machine learning models:

Handling Missing Values: Missing values in columns like Engine and Mileage were imputed using median values.


**Feature Engineering:**

Created a new feature Car_Age by subtracting the manufacturing year from the current year.

Extracted numerical values from columns like Mileage and Engine which originally had units (e.g., "kmpl", "CC").


**Encoding Categorical Variables:**

Applied one-hot encoding to Fuel_Type, Transmission, and Seller_Type.

Outlier Detection and Removal: Used boxplots and IQR method to remove extreme outliers from Selling_Price and Kilometers_Driven.

Feature Scaling: Applied MinMaxScaler to numerical features to normalize them between 0 and 1.
