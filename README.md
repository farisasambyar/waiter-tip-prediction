🍽️ Waiter Tip Prediction

This project aims to predict the tip amount for waiters using restaurant transaction data and a Linear Regression model. The goal is to understand how different factors influence tipping behavior and to estimate tip values based on given inputs.

📊 Dataset
The dataset is loaded from Google Drive and contains the following columns:
- total_bill – total customer bill (USD)
- tip – tip amount (USD) (target variable)
- sex – customer gender
- smoker – smoking status
- day – day of the week
- time – lunch or dinner
- size – number of people at the table
No missing values were found in the dataset.

🛠️ Libraries Used
- pandas – data loading and processing
- numpy – numerical computation
- plotly – data visualization
- scikit-learn – data splitting and Linear Regression model

🔍 Project Workflow

1. Load and inspect the dataset
2. Check for missing values
3. Visualize relationships using scatter plots and pie charts
4. Encode categorical features into numeric values
5. Split data into training (80%) and testing (20%) sets
6. Train a Linear Regression model
7. Predict tip values based on input features

🧠 Model & Features

Algorithm: Linear Regression

Features used:
- total_bill
- sex
- smoker
- day
- time
- size
These features were selected because they can influence customer tipping behavior.

🔮 Example Prediction

Input:
[24.50, 1, 0, 0, 1, 4]

Output:
≈ 4.20 USD


This means the model predicts a tip of approximately $4.20 for the given conditions.

✅ Conclusion
The project shows that Linear Regression can be used to predict waiter tips and analyze factors affecting tipping behavior. This model can serve as a basic foundation for further improvements or more advanced machine learning approaches.
