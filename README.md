# <p align="center">Income Prediction Using TensorFlow</p>
My Summer Projects
<p align="center"><img src="Data/census_pics1.jpg"></p>

### Introduction
- This read me file is presented for the project **Income Prediction using TensorFlow**
- This project is for predicting the income range of every individual in the state of California based on various parameter of Census Data
- This project is classified into 2 parts
- The first part is to get the data from the website "**US Census Bureau**" and download the data in CSV file format 
- The downloaded data is then extrated to the program using Pandas library and converted to dataframe 
- The second part is to train the model using TensorFlow and predict the Income range on test data

### Project Description
- This project will provide the most efficient prediction on income range of the people and make it fall within two categories

  1.  Less than or equal to 50,000$
  2.  More than 50,000$

- Once the input data is cleaned and prepared, its is divided into two parts using Sklearn library. Here we are using **70%** for training the model and **30%** for testing the model
- Linear Classifier in TensorFlow is used as a machine learning algorithm to learn and predict the data 
- As a prat of this algorithm, we need to built two main parts which are **Feature columns** and **Input Function**
- Feature columns will provide the high significant parameters to the model and will be used to create the instance of the model
- Input Function will train the model like how much data can be used on batch size and epochs (one complete batch cycle) 
- Now the model is trained with 70% of data with both Independent and Dependent variables 
- Evaluating the model with the test data set and formating them into list for understanding the output

### Result of this Project 
- The predicted income range is converted to list and compared with the actual data
- The comparing is done using **Classification Report** from Sklearn 
- This provides an **efficiency of 85%**

<p align="center"><img src="Data/census_efficiency.png"></p>
