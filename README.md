# Portfolio
Portfolio of projects I have completed for academic and other learning purposes.

# [Project 1: IBM Data Science Capstone](https://github.com/LoganCon44/IBM_Capstone_Repo)
The intent behind this project was to predict if the first stage of the Falcon 9 rocket would successfully land. With a successful landing, the launch costs SpaceX 62 million dollars compared to the competitor's 165 million dollar per launch cost. Being able to provide landing prediciton insight to our company in this project was vital as it allowed for the comapny to determine what overall costs of a launch would be. Knowing cost information enabled the company to then compete with SpaceX. To collect the data I used web scraping and a SpaceX API, then performed data wrangling and exploratory data analysis with SQL and visualization with matplotlib. I then created interactive visual analytics with Folium marking the launch sites, success/failed lanches, and calculated the distances between a launch site and its proximities. For the predictive models, I built Logistic Regression, Support Vector Machine, Decision Tree, and KNN using the best parameters with combinations of hyperparameters. The best model was the Decision Tree model with an accuracy of 88.75%.  

![](/Images/KSC_LC-39A_launch.jpg)
![](/Images/model_accuracy.jpg)

# [Project 2: IBM Machine Learning Project](https://github.com/LoganCon44/Portfolio/blob/main/code%20files/IBM_Machine_Learning_Project.ipynb)
The goal of this project was to build machine learning models to predict whether a loan case will be paid off or not. I loaded a dataset from previous loan applications, analyzed and cleaned the data, and applied different classification algorithms such as k-Nearest Neighbor, Decision Tree, Support Vector Machine, and Logistic Regression. When testing, I determined the accuracy of each model using Jaccard Index, F1 Score, and LogLoss.

![](/Images/KNN_Test.png)
![](/Images/Decision_Tree.png)
![](/Images/Accuracy_Report.png)

# [Project 3: Finite Difference Model in Python](https://github.com/LoganCon44/Portfolio/blob/main/code%20files/Finite_Differences_Python.ipynb)
In this project I used the implicit finite difference model to determine the option prices for a given stock. I then used the option prices retrieved during backward walk to formulate a graph of said prices.

![](/Images/Finite_Differences_Python_img.png)

# [Project 4: IBM Data Science Python Project](https://github.com/LoganCon44/Portfolio/blob/main/code%20files/IBM_Python_Project.ipynb)
This project was part of the IBM Data Science Professional Certificate where I used yfinance to extract stock data and webscraping to extract revenue data for Tesla and GameStop. I then analyzed the data and plotted the revenue and stock data of both companies.

![](/Images/Tesla_Plots.png)

# [Project 5: P&L Attribution in Excel](https://github.com/LoganCon44/Portfolio/blob/main/code%20files/P%26L_Attribution.xlsx)
The objective of this project was to construct a P&L attribution from COB Jan 27 and COB Jan 26 for 100,000 850-strike TSLA calls that expired on Feb 4, 2022. This was done using formulas for the Black-Scholes greeks to determine the change in price of the TSLA calls.

# [Project 6: Finite Difference Models in Excel](https://github.com/LoganCon44/Portfolio/blob/main/code%20files/Finite_Differences.xlsx)
For this project I used the stock and options of Apple to determine the price of european call and put options. Using the explicit finite differences algorithm, I determined the price of the call and put options. I then compared the results to the values I recieved from Black-Scholes and Binomial Lattice methods.

# [Project 7: Analysis of Bonds in Excel](https://github.com/LoganCon44/Portfolio/blob/main/code%20files/Bonds_Data.xlsx)
In the first part of this project I used a 10-year bullet bond with semi-annual coupon payments to determine DV01 using discounted cash flows. I then utilized DV01 to calculate the modified duration and the modified duration to calculate the macaulay duration and convexity. Next, I used this to estimate the effect of 25 basis points changes. The second part of the project consideres a sequence of zero-coupon prices for bonds maturing in 1-5 years, I used these prices to calculate zero coupon yields, implied forward 1-year rates, and par coupons. 
