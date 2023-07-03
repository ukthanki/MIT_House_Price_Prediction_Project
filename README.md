[Go to Back to Home Page](https://ukthanki.github.io/)

# MIT Data Engineering Professional Certification

## House Price Prediction Model

<p align="center">
    <img width="100%" src="https://github.com/ukthanki/MIT_House_Price_Prediction_Project/assets/42117481/29fc8ce1-f3c8-49df-b5f6-cd6c6b10eb12">
</p>

Up to this point in the course, we had learned the following topics:
1. NumPy
2. Pandas
3. SQL
4. Linear Regression

For the first project, we were tasked with analyzing housing data in order to build a predictive model that can be used to determine the price of a house with certain characteristics.

we started by loading the raw data from a csv file that was provided into a Pandas Data Frame. Since the project involved Linear Regression, I selected several fields that I believed would have an impact on house price as an initial hypothesis. However, several fields have significant number of null records, as shown in Figure 1 below. This necessitates that the data be cleaned before we begin the modeling process.

| ![image](https://github.com/ukthanki/MIT_House_Price_Prediction_Project/assets/42117481/809779b0-251f-41d9-bbee-21ad7f6c7746)| 
|:--:| 
| **Figure 1.** Null entry counts in each field in the original dataset. |

Once the data has been cleaned with regards to the null values, we continued the analysis by making correlations. Specifically, we use three cases so that we can assess the impact on the model's effectiveness at predicting house price:
1. Two Variables vs. SalePrice
2. Five Variables vs. SalePrice
3. Eight Variables vs. SalePrice

You can view the full Project in the "Module 7_Final_Project_Thanki.ipynb" file in the Repository.
