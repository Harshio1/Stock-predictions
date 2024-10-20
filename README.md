# Stock-predictions
This project is a machine learning model built using the Random Forest Regression algorithm to predict stock prices. It utilizes historical stock data, including previous closing prices, highs, lows, and trading volume. By leveraging these trends, the model generates future price predictions to help investors make informed decisions.
# Features
Random Forest Regression Model: Built using historical data to forecast future stock prices.
Adaptable for any company: By uploading different datasets, the model can predict stock prices for any company.
Visualization: The project visualizes both the actual and predicted stock prices over time.
# How to Use:
# Example with Tata Motors:
In the "source code" file, I have provided an example using Tata Motors. This will allow you to see how the project works with pre-existing input for a specific date and its corresponding output.
# Run the Code for Other Companies:
If you'd like to predict stock prices for other companies, download the relevant dataset and follow the upcoming steps. Open the "source code" file and enter the name of the csv file(that contains the datasets)in the 9th line of the code(data = pd.read_csv('.csv')). I have provided datasets for nifty50 in the "nifty50" file. You can upload the desired dataset and run the code by entering your desired date to see the output.

# Steps to Run the Projecct in Google Colab
1.Transfer the code from the source code file into a new Google Colab notebook.
2.Upload the dataset files to the Colab environment.
3.Ensure all necessary libraries are imported by running the first cell.
4.Execute the cells to run the code and make predictions.

# Steps to Run the Project in VS Code
1. Open the `source_code.py` file in VS Code.
2. Ensure you have the required packages installed.
3. Place the dataset files in the same directory as the script.
4. Run the script from the terminal.
5. 
# Steps to Run the Project in Jupyter Notebook
1. Open the Jupyter Notebook containing the code.
2. Ensure you have the required packages installed in your environment.
3. Upload the dataset files to the same directory as the notebook.
4. Run the cells in the notebook to execute the code.
