# Sumeet-Sutar
Here, in this task, we made the raw dataset machine learning-ready. What we did is as follows:

Loaded the dataset
We loaded the CSV file with Pandas to play around with the data.

Explored the dataset
We inspected the shape, column types, missing values, and simple statistics.

Handled missing values

For number columns, we imputed missing data with the median.

For text columns, we imputed missing values with the most frequent value (mode).

Converted text to numbers
Because machine learning is based on numbers, we converted all categorical (text) data into numerical codes.

Normalized the data
We normalized all numeric columns into the range 0 to 1 with Min-Max normalization. This allows models to treat each feature the same way.

Visualized outliers
We plotted boxplots with Matplotlib to check whether there were values way outside the normal range.

Removed outliers
We eliminated extreme values that would impact the model using the IQR method (Interquartile Range).

Saved the cleaned data
Lastly, we saved the cleaned dataset into a new CSV file so it's available for use in machine learning.
