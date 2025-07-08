# Final Project: Stock Price Prediction using LSTM

## Objective
The goal of this project is to build a deep learning model using LSTMs to predict stock prices. The model will analyze historical stock data and predict the next 15 units of the stock's adjusted closing price. Additionally, the project will incorporate technical indicators to enhance prediction accuracy.

---

## Problem Statement
You are required to build a stock price prediction system using Long Short-Term Memory (LSTM) networks. <br>
The system should:

1. **Take user input** for:
   - Stock name (e.g., "AAPL" for Apple, "GOOGL" for Alphabet Inc.).
   - Start date and end date to define the data range.
   - Timeframe (e.g., daily, weekly, monthly).

2. **Fetch stock data** from the internet using the `yfinance` library, based on the user's input.

3. **Visualize the data** by plotting:
   - Adjusted closing price of the stock.
   - At least two technical indicators (e.g., MACD, RSI, Moving Averages, Bollinger Bands).

4. **Build and train an LSTM model** to:
   - Predict the next 15 units of stock data based on historical trends.
   - Use adjusted closing price and technical indicators (Minimum 2) as input features.

5. **Present results graphically**, including:
   - Historical data and predicted prices.
   - Comparisons between actual and predicted values.

6. **Calculate the R² score** to evaluate model performance:
   - $`
     R^2 = 1 - \frac{\sum w_i (y_i - \hat{y}_i)^2}{\sum w_i y_i^2}
     `$

     where $`y_i`$
 and $`\hat{y}_i`$
 are the true value and predicted value respectively; and w
 is the sample weight vector.

---

## Tasks and Deliverables

### Task 1: Data Collection
1. Prompt the user for stock name, start date, end date, and timeframe.
2. Use the `yfinance` library to fetch historical stock data based on user input.

### Task 2: Data Visualization
1. Plot the adjusted closing price of the stock over time.
2. Calculate and plot at least two technical indicators, such as:
   - Moving Average Convergence Divergence (MACD).
   - Relative Strength Index (RSI).
   - Simple/Exponential Moving Averages.
   - Bollinger Bands.

### Task 3: Data Preprocessing
1. Normalize the stock price and technical indicator data for use in the LSTM model.
2. Create sequences of data (e.g., sliding window of past 60 days) to use as input for the model.

### Task 4: Build the LSTM Model
1. Design an LSTM model using a deep learning framework such as TensorFlow or PyTorch.
2. Train the model using the prepared data.
3. Evaluate the model's performance and fine-tune as needed.

### Task 5: Prediction and Visualization
1. Predict the next 15 units of data using the trained LSTM model.
2. Visualize:
   - Predicted values vs. actual values for the training period.
   - Forecasted prices for the next 15 units.
3. Calculate the R² score using the formula provided above.

### Task 6: Submission
1. **Prepare the following for submission:**
   - Python script or Jupyter Notebook implementing the entire project.
   - A `README.md` file explaining the implementation and results.
   - Visualizations generated during the project.

2. **Submit the project on a GitHub repository**:
   - Create a new repository on GitHub.
   - Upload your project files, including the Python script/Notebook, `README.md`, and visualizations.
   - Include a clear project description in the repository's README file.

---
### Brief Guide to Upload on GitHub
1. Create a GitHub account if you don’t have one.
2. Navigate to [GitHub](https://github.com/) and click on "New" to create a repository.
3. Initialize the repository with a name and optional description.
4. Clone the repository to your local machine using:
   ```bash
   git clone <repository_url>
   ```
5. Add your project files to the repository folder.
6. Stage and commit the changes:
   ```bash
   git add .
   git commit -m "Initial commit"
   ```
7. Push the changes to GitHub:
   ```bash
   git push origin main
   ```

---

## Guidelines

1. **Programming Language and Tools**:
   - Use Python for implementation.
   - Recommended libraries include `yfinance`, `matplotlib`, `pandas`, `numpy`, `tensorflow`/`pytorch`, and `scikit-learn`.

2. **Technical Indicators**:
   - Choose two technical indicators relevant to your analysis. Briefly explain their significance in the README.

3. **Documentation**:
   - Comment your code for clarity.
   - Provide a `README.md` file with instructions on how to run the code and interpret the results.

---

## Resources

### Tutorials
1. [LSTM Time Series Forecasting with TensorFlow](https://www.tensorflow.org/tutorials/structured_data/time_series)
2. [Technical Analysis Indicators](https://www.investopedia.com/terms/t/technicalindicator.asp)

### Documentation of Python Libraries
1. [Pandas](https://pandas.pydata.org/docs/)
2. [Matplotlib](https://matplotlib.org/stable/index.html)
3. [Tensorflow](https://www.tensorflow.org/api_docs)
4. [Scikit-learn](https://scikit-learn.org/stable/)
5. [yfinance](https://pypi.org/project/yfinance/)

### Videos (DO NOT COPY-PASTE CODE FROM THESE VIDEOS)
1. [Stock Price Prediction with LSTMs](https://www.youtube.com/watch?v=QIUxPv5PJOY)
2. [RNN/LSTM Price Movement Predictions](https://youtu.be/hpfQE0bTeA4?si=Y5RMAC6vz1Xf5lb1)
3. [Mistakes while using LSTM](https://youtu.be/lhrCz6t7rmQ?si=Ufds96Ln9lQIMQ38)

---
## Submission Link
Submit your link to github repository [Here](https://forms.gle/NrdnbqLA6T9ZiUyg8) <br>
Good luck!!
