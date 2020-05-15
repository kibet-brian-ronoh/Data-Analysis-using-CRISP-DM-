# Data-Analysis-using-CRISP-DM-
Exploratory Data Analysis of the Goodreads dataset publicly available in the Kaggle website. 
In this project we analyzed the Goodreads-books dataset from the Kaggle website using the CRISP DM methodology. 

# What is CRISP-DM?

CRISP-DM stands for Cross Industry Standard Process for Data Mining. It provides a structured approach to planning a data mining project. The process involves six main steps for data mining.

# Data

The data used in this project is publicly available on Kaggle’s website. It can also be found in the goodreads website: https://www.goodreads.com.com. The data provides not only a good list of books to read but also questions on books to test your knowledge of the content.

We have also attached the data in a csv file with this submission. 

# Installation and instructions to run the notebooks. 

The python notebook files in this repo should run with Anaconda distribution of Python versions 3.*.

To explore this project please download the attached dataset (books.csv) and the three python notebooks.

You can either upload the files using Jupyter notebook which will automatically place these files in the current working directory of your Python installation or place these files in the current working directory and then run the notebooks. 

# Queries to be answered by the data

To get more insights about the Goodreads-books dataset, we wanted to find answers to the following questions:

1.	Which authors wrote the most books (peek into the top 10)?

2.	Who are the top 10 highly rated and the bottom 5 poorly rated authors?

3.	Did the books with more text reviews receive higher ratings?

4.	Did the ratings for Harry Potter series follow a trend?

5.	How are books distributed across different languages?

# Jupyter Notebook File Descriptions

There are three python notebooks attached to this repo. Each of these notebooks explore the pragmatic steps of the CRISP-DM methodology to understand the dataset and infer useful insights from it.

# 1.	DataExploration.ipynb

o	This notebook explores the data to understand each features individually. We perform a univariate descriptive analysis on each feature to understand the data better. We then create plots like Histograms and Box-plots for the quantitative variables and look at the breakdown of unique values for the qualitative variables.

# 2.	DataAnalysis.ipynb

o	This notebook looks at each features and performs data mining analysis on the selected input variables (X's) to predict the average rating (Y) for a book. We have split the data into two subsets based on high and low user ratings for each books. We then trained and tested two models to predict average ratings on these two subset data. Finally, we understood the model quality based on the average prediction errors by looking at the Mean Absolute Error (MAE), Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

# 3.	Queries.ipynb

o	This notebook looks at the business related queries we wanted to ponder in the Queries section above. We did this by using break-down analysis and applying previous knowledge we gained about the data using the other two notebooks.

# Summary Results

The results of our data exploration involving a thorough understanding of all the features in the dataset are summarized in the DataExploration.ipynb notebook. We created two Linear Regression models and predicted the average rating of test set cases using the same. The model evaluation part is summarized in the DataAnalysis.ipynb notebook. Finally, we answered the important business questions by exploring the dataset further and finding more insights from it. This is documented in the last Python notebook Queries.ipynb.



