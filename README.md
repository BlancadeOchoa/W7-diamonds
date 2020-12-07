# W7-diamonds

The **goal of thie project** is the prediction of the price of diamonds based on their characteristics (weight, color, quality of cut, etc.), **putting into practice all the machine learning techniques** we know.
I decided to divide my project the following way:

- Cleaning data

- Use : Supervised algorithms


![Getting Started](images/diamond.jpeg)



# Cleaning data:

I have created 4 independent files where I clean the data differently, this way I could test not only different algorithms but also datasets.
These files are stored in the folder called cleaning_data:

-  **0_understand_and_explore:** here I explored the data to try and understand it and see what type of variables we were dealing with as well as the important features and models I should use according to the datatype.
- **1_cleaning_data:** here I drop columns based n high colinearity and change de dtype of the columns using dummies.
- **2_cleaning_data:** I do the same as in 1_cleaning_data but I also replace the outliers with the mean value of their respective column.
-  **3_cleaning_data:** I drop columns based on high colinearity and manually change de dtype of the columns by replacing the  values with a rating scale.
- **4_cleaning_data:** I drop columns based on low colinearity and treat some columns to they are more relevant to use in the analysis


# Algorithms used:
I opted for the use of many algorithms in order to have a lot of possibilities of reducing the rmse value. This is why I have used 8 different ones on each of the different cleaned databases;
 **Linear regression, lasso, ridge, decision tree, random forest, k-nearest neighbour, bayesian ridge an elastic net**.


Of each of them I have extracted the following parameters:
- mean absolute error
- mean squared error
- r2 score
- root mean squared error


# Challenges faced

![Getting Started](images/overcome.jpg)

Many challenges were faced throughout the project, some of them where;

- Not being able to check the rmse calculated by kaggle was my main issue, because this meant I couldnt identify my mistakes.

- I couldn't see if I was training my model correctly because from what I saw from the first submission my calculated rmse was much lower than what later kaggle calculated which meant some algorithms I was using to fit the model were overfitted. But it was hard to fix because I had no way of checking if my changes were going in the right direction.

- The lack of time has been a problem as well, many of the functions I have used could be simplified, I have repeated so much code through the whole project that could have been avoided if I had automatized some processes.


