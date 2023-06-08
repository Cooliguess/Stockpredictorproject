# Stockpredictorproject

Installation steps:
  1. To clone the repository:
    git clone https://github.com/Cooliguess/Stockpredictorproject.git
  2. Install the required dependencies:
    pip install pandas scikit-learn xgboost yfinance ta
  3. Open the main.py file.
  4. Please replace my API key with your own Alpha Vantage API key in the API_KEY variable.
  5. You can change the stock variable to match the stock you care abt.

Run the script:
  python main.py
  
 
The script will make an API request to Alpha Vantage to retrieve the daily adjusted stock prices for the specified stock symbol. It will then perform feature engineering, splitting the data into training and testing sets, and training an XGBoost classifier. Finally, it will make predictions on the testing set and output a classification report.

Again, you can further process and use the Alpha Vantage data in the df DataFrame as per your requirements. 

Thanks

