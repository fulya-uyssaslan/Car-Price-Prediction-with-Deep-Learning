Mercedes Benz Car Price Prediction with Deep Learning

This project aims to develop a deep learning model to predict the prices of used Mercedes cars sold in the UK between 1970 and 2020. The project includes data cleaning, preprocessing, model training, and evaluation steps.

Project Summary

The dataset contains 7 features: year, price, transmission, mileage, tax, mpg, engineSize.

There were a total of 13,119 records.

After cleaning outliers and inconsistencies, 12,987 reliable records were obtained.

The transmission column was removed because it contained non-numeric values.

Data Cleaning

Approximately 131 cars with very high prices (about 1% of the data) were removed.

The data for the year 1970 was excluded because it contained only one record.

This process ensured a clean and balanced dataset for the model.

Model Architecture and Training

The data was split into 70% training and 30% testing.

Features were scaled between 0 and 1 using MinMaxScaler.

The model consists of 4 hidden layers, each with 12 neurons and ReLU activation.

The output layer contains a single neuron (for regression).

The model was trained using the Adam optimizer and Mean Squared Error (MSE) loss function.

Training was performed over 300 epochs with a batch size of 250.

Results

Training and validation loss progressed very closely, indicating no overfitting.

The model showed high agreement between predicted and actual prices.

The average error rate was approximately 13%.

The learning process was fast and stable.
