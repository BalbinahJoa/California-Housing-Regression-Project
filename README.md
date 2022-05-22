# KNIME- PROJECT-1
 Business Understanding: To build a machine learning model that can predict the median housing price in any district, given all other attributes using the CRISP-DM framework in KNIME Analytics platform.
 The deployment file(output) can be fed into another machine learning system together with many other pieces of information and or models.
 Steps taken:
 1. Selecting a performance measure - Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) were used to show the performance of the model because they are both common for measuring accuracy of continous variables.
 2. Data Understanding - used data from the 1990 California census records.
 3. Explore Data - Used the CSV reader node to load and view the dataset in KNIME. The Data explorer node was also used to view the basic statistics of the data while the Scatterplot node was used to view the geographical data.
 4. Data Quality - Verified data quality using the Missing Value Column Filter node and 1% of the data was missing from one feature.
 5. Created metanodes to keep the workflow tidy and presentable and used annotations to highlight what steps were taken.
 Data preparation - Data was split into train(80%) and test(20%) sets, generated new features and scaled the new features.
 Data Cleaning - to handle the missing values.
 6. Modeling - three different models were trained: Linear regression model, Decision tree model and the Random forest model.
 7. Evaluation - the best model (Random Forest model) was evaluated on the test data set.

