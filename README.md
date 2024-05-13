# Time Series Prediction using Python and ARIMA Model

This project involves time series prediction using the ARIMA (AutoRegressive Integrated Moving Average) model in Python. Specifically, the Microsoft stock's closing prices for the year 2021 were predicted.

## Technologies Used

- **JupyterLab (Notebook)**: JupyterLab was utilized as the development environment for writing and executing Python code in a notebook format.
- **pandas**: Used for data manipulation and analysis. pandas provided powerful data structures like DataFrame, which are essential for handling time series data.
- **numpy**: Utilized for numerical computations, especially for mathematical operations on arrays and matrices.
- **statsmodels**: Used for building the ARIMA model and performing statistical tests and analysis.
- **matplotlib**: Employed for data visualization. matplotlib was used to plot the time series data, model diagnostics, and forecasted results.
- **pmdarima**: Used to automatically select the optimal ARIMA model parameters, saving time and effort in model selection.
- **scikit-learn (sklearn)**: Although primarily known for machine learning, sklearn was used for data preprocessing, such as splitting the dataset into training and testing sets.

## Project Overview

In this project, historical Microsoft stock prices were used to build an ARIMA model to forecast future stock prices. The ARIMA model is a popular choice for time series forecasting due to its ability to capture trends and seasonal patterns in the data.

### Technical Details

- **Data Preparation**: The historical stock price data was loaded into a pandas DataFrame. Necessary preprocessing steps, such as converting date columns to datetime objects and setting them as the index, were performed.
- **Model Training**: The ARIMA model was trained on the training dataset using the statsmodels library. The model parameters (p, d, q) were either manually selected or automatically determined using pmdarima.
- **Model Evaluation**: The trained model's performance was evaluated on a separate validation dataset. Various metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) were calculated to assess the model's accuracy.
- **Forecasting**: Using the trained ARIMA model, future stock prices for the year 2021 were forecasted.
  
## How to Use

1. Ensure you have all the required libraries installed. You can install them using pip:

    ```
    pip install jupyterlab pandas numpy statsmodels matplotlib pmdarima scikit-learn
    ```

2. Open the JupyterLab notebook (`time series.ipynb`) to see the code and the prediction process step by step.

3. Follow the instructions within the notebook to execute the code cells and replicate the analysis.

## License

This project is licensed under the MIT License.
