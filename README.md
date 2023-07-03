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

Once the data has been cleaned with regards to the null values, we continued the analysis by making correlation Data Frames; they indicate which attributes are mostly correlated with the SalePrice dependent variable. For comparison purposes, we use three cases so that we can assess the impact on the model's effectiveness at predicting house price:
1. Two Variables vs. SalePrice
2. Five Variables vs. SalePrice
3. Eight Variables vs. SalePrice

We then created a Linear Regression object to evaluate the score for each case above based on the actual data and the predicted data based on the linear model. The closer the score is to 1, the more accurate the model. We concluded that as we involved more variables in the linear model, we were more accurately predicting the house price due to an increase in the score value.

In other words, Case 3 with Eight Variables produced the most accurate model with a score of 0.85083, as shown below in Figure 2. 

| ![image](https://github.com/ukthanki/MIT_House_Price_Prediction_Project/assets/42117481/92c899be-f23b-4417-aea8-95e7864881a0)| 
|:--:| 
| **Figure 2.** Score values per case. |

Overall, this was an interesting project because it allowed me to explore a real-world dataset and understand the mathematical relationship between various home characteristics and the eventual selling price of a home.

**You can view the full Project in the "Module 7_Final_Project_Thanki.ipynb" file in the Repository.**
