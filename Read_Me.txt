READ ME!!!!

The dataset contains 5 columns and 3706 records of GOld prices from previous years.
the data set includes daily gold price information including daily Open, High and Low prices and the final price of each day (Close).

Preprocessing the data:
Checking for Duplicate values
Checking for Missing Values

Vizualizing the data:
Plotting the high and lows of the check the range of values the Gold prices.
info of the dataframe contains 5 columns of Datetime and 4 float type columns.
Checking the corr through matrix and in the corr matrix we look at Close row as that is our Target values and rest are our features. All the features are high 0.99 indicating that target is highly dependent on the all the features.

Splitting into Training and Testing:

Breaking the datframe into traning and testing.
We are assuming Testing data which is present in year 2022.
And the rest as training data.

Normalizing the data
Using MinMaxScalar we are normalizing the data

Creating LSTM:
Why i choose LSTM as a Prediciton Model
LSTM (Long Short-Term Memory) is a type of recurrent neural network (RNN) architecture that is particularly well-suited for sequential data analysis and time series forecasting.

LSTM networks are designed to capture and remember long-term dependencies in the input sequences. This is crucial for analyzing time series data, as past observations often have a significant impact on future values.

LSTM networks can handle variable-length input sequences, which is beneficial for time series forecasting

Model Evalution:
Test Loss: 0.004019958432763815
Test MAPE: 0.05996951788276743
Test Accuracy: 0.9400304821172326

