# CO2 Emission by Car Project

This project aims to analyze and predict the CO2 emissions of cars based on various features such as engine size, number of cylinders, fuel consumption, and more. The dataset used for this project is a CSV file containing information about different car models and their respective CO2 emissions.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Project Steps](#project-steps)
- [Results](#results)
- [Conclusion](#conclusion)

## Installation

To run this project, you need to have Python installed along with the following libraries:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Dataset

The dataset used in this project is `co2.csv`, which contains the following columns:
- Make
- Model
- Vehicle Class
- Engine Size (L)
- Cylinders
- Transmission
- Fuel Type
- Fuel Consumption City (L/100 km)
- Fuel Consumption Hwy (L/100 km)
- Fuel Consumption Comb (L/100 km)
- Fuel Consumption Comb (mpg)
- CO2 Emissions (g/km)

## Project Steps

1. **Import Dependencies**: Import necessary libraries and modules.
2. **Load the Data**: Load the dataset from the CSV file into a pandas DataFrame.
3. **Display the First Few Rows**: Display the first few rows of the dataset to get an overview.
4. **Describe the Data**: Get a statistical summary of the dataset.
5. **Analyze Null Values**: Check for any missing values in the dataset.
6. **Drop Unnecessary Columns**: Drop the 'Make' and 'Model' columns as they are not important for prediction.
7. **Analyze Vehicle Class**: Analyze the distribution of the 'Vehicle Class' column.
8. **Encode Vehicle Class**: Convert the 'Vehicle Class' column from categorical to numerical using Ordinal Encoding.
9. **Analyze Engine Size**: Plot the distribution of the 'Engine Size (L)' column.
10. **Analyze Cylinders**: Plot the distribution of the 'Cylinders' column.
11. **Value Counts of Cylinders**: Display the value counts of the 'Cylinders' column.
12. **Analyze Transmission**: Analyze the distribution of the 'Transmission' column.
13. **Encode Transmission**: Convert the 'Transmission' column from categorical to numerical using Ordinal Encoding.
14. **Analyze Fuel Type**: Analyze the distribution of the 'Fuel Type' column.
15. **Encode Fuel Type**: Convert the 'Fuel Type' column from categorical to numerical using Ordinal Encoding.
16. **Analyze Fuel Consumption City**: Plot the distribution of the 'Fuel Consumption City (L/100 km)' column.
17. **Analyze Fuel Consumption Highway**: Plot the distribution of the 'Fuel Consumption Hwy (L/100 km)' column.
18. **Analyze Fuel Consumption Combined**: Plot the distribution of the 'Fuel Consumption Comb (L/100 km)' column.
19. **Analyze Fuel Consumption Combined (mpg)**: Plot the distribution of the 'Fuel Consumption Comb (mpg)' column.
20. **Analyze CO2 Emissions**: Plot the distribution of the 'CO2 Emissions (g/km)' column.
21. **Split the Data**: Split the dataset into training and testing sets.
22. **Model Selection**: Select the Linear Regression model for prediction.
23. **Train the Model**: Train the Linear Regression model using the training data.
24. **Predict Train Data**: Make predictions on the training data and calculate the R2 score.
25. **Predict Test Data**: Make predictions on the testing data and calculate the R2 score.
26. **Plot Results**: Plot the actual vs predicted CO2 emissions for the test data.
27. **Model Evaluation**: Evaluate the model by predicting the CO2 emission for a new data point.

## Results

The model was trained and tested using the Linear Regression algorithm. The R2 score for the training data and testing data was calculated to evaluate the model's performance. The actual vs predicted CO2 emissions were plotted to visualize the results.

## Conclusion

This project demonstrates how to analyze and predict CO2 emissions of cars using various features. The Linear Regression model was used for prediction, and the results were evaluated using the R2 score. The project provides insights into the factors affecting CO2 emissions and helps in understanding the relationship between different features and CO2 emissions.
