# EarlyWarnings
A repository containing exercises on data analysis and predictive modeling for early warning detection in crisis scenarios.

First, the script creates a dataset with 3 columns: Data, Return and Yield. 
Then, a new column column called "Crisis" is created, to identify crisis days of the market. It states if there has been a crisis (1) or not (0) in a certain day, considering the values of "Return" less than -0.05.

Then, the dataset is split into train and test, and some models are applied.
