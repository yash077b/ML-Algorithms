🏠 House Price Prediction | Linear Regression
A foundational Machine Learning project demonstrating the end-to-end workflow of building a predictive model using Linear Regression in Python.
This project serves as a practical, hands-on application of core data science concepts, bridging the gap between raw data and actionable predictions. It covers data preprocessing, feature engineering, model training, and performance evaluation.

📌 Project Overview
This model estimates property values based on a comprehensive set of real estate features. The goal is to establish a strong baseline understanding of how various property attributes influence market prices.
Key Features Analyzed:
Dimensions: Area
Rooms: Bedrooms, Bathrooms, Guest room
Layout: Stories, Basement
Amenities: Air conditioning, Parking capacity
Location & Access: Main road access, Preferred neighborhood status

🧠 Algorithm
Linear Regression: Chosen as the baseline model. While housing markets often exhibit complex, non-linear behavior, Linear Regression provides excellent interpretability. It serves as the perfect starting point for understanding how individual features mathematically impact the final house price.
🛠 Tech Stack
Language: Python
Data Manipulation: Pandas, NumPy
Machine Learning: Scikit-learn
Data Visualization: Matplotlib

📂 Dataset Details
Source File: Housing.csv
Data Types: Contains a mix of continuous numerical data and categorical variables.
Preprocessing Applied: Categorical text values (e.g., "yes"/"no") were mapped to binary integers (1/0) through encoding, allowing the mathematical model to process them effectively.

⚙️ Pipeline & Methodology
Data Ingestion: Loaded the raw housing dataset into a Pandas DataFrame.
Data Cleaning: Inspected the data for missing values and handled structural inconsistencies.
Encoding: Transformed categorical variables into a machine-readable numerical format.
Feature Selection: Isolated the target variable (Price) from the independent predictor variables.
Data Splitting: Divided the dataset into training and testing subsets (e.g., 80/20 split) to ensure unbiased evaluation.
Model Training: Fit the Scikit-learn Linear Regression model to the training data.
Prediction & Evaluation: Generated predictions on the unseen test set and calculated performance metrics.

📊 Model Evaluation
Primary Metric: R² Score (Coefficient of Determination)
Result Interpretation: The model achieves moderate accuracy. This is a standard and expected outcome, highlighting the foundational nature of Linear Regression and setting the stage for future iterations using more complex, non-linear algorithms.

📈 Visualizations
The project includes an Actual vs. Predicted Prices Scatter Plot:
This graph visually represents the model's accuracy.
How to read it: The closer the data points cluster along the perfect diagonal line, the more accurate the predictions. Points scattered further away indicate variance that the linear model couldn't perfectly capture.

🚀 How to Run
1. Install Required Dependencies:
   # pip install pandas numpy matplotlib scikit-learn
