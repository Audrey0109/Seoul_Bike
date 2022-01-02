<h1 align="center">
  <br>
   <img src=https://user-images.githubusercontent.com/61688477/147778433-746a8785-ad30-4160-aed1-d74c87f22c05.jpg>
  <br>
  Analysis of Seoul Bike Demand
  <h2 align="center">
    CHMIEL Audrey & DONIER Marie  
    <br>
    ESILV | DIA 1
  </h2>
</h1> 

## Table of contents
  * [About the project](#about_the_project)
  * [Notebook](#notebook)
  * [Usage](#usage)
  * [Features](#features)
  * [Architecture](#architecture)

## About the project
### Introduction

*This project is the final project of ESILV course Python for Data Analysis* 
<br>
During this project, we had to study a CSV dataset for estimating Seoul Bike rental demand based on a panel of time and meteorological criteria. 

### Tasks achieved 

The project is organized in 3 main parts: 
<br><br>
•	  A data visualization part, where we studied the links between our target variable "Bike_rented" and the other variables, using elaborate graphics made via the Python matplotlib and seaborn libraries. Once this approach was carried out, we saw that the number of bikes rented depended a lot on the Temperature and Time variables (Day, Hour, Month...) and less on some meteorological features. <br> We then cleaned up our model by removing the insignificant variables, in order to make its prediction more efficient. We also adapted our categorical features into numerical variables to make them exploitable thanks to Pandas library functions.
<br><br>
•	  The second major part of this project was the realization of predictive models based on Machine Learning using supervised regression learning methods built thanks to  the Scikit Learn library. We have carried out numerous tests by swapping the hyperparameters in order to obtain the smallest error, and therefore the best possible precision. We even try to use a neural network model by using the tensor flow library Keras.
<br><br>
•  Finally the last part of our project was to transform our model into an API. We choose to do it with Flask
 
### Conclusion
By comparing Machine Learning models, we found that the Gradient Boosting model was the best algorithm to predict Seoul bike rental demand. 
<br>
For more informations on the project (observations/selection of features, model selection), please go to the notebook's section below. 
 
 ## Notebook
 [Go to the study](../main/Seoul_Bike_Data_Project_VRAI.ipynb)

 ## Usage
 The Flask API is in the last part of the notebook "7. Flask". 
 
 First, after opening the notebook, you need to put some files in the “content” folder :
  - You have to put the files index_accueil.html, model_grad_boosting_reg.pkl and df_bike2.pkl
  - You have to create a “static” folder. In the “static” folder, place the image bike.jpg, create a “css” folder in which you place the file style.css
  
  ![image](https://user-images.githubusercontent.com/95496652/147863425-66063d62-4d66-4be5-8715-fc2340f13ca2.png)

 
 Then after that, you must execute all cells in the section.
 When you run the application cell, three internet links will appear. Click on the second to access the API.
 
 ![tempsnip](https://user-images.githubusercontent.com/95496652/147863512-7b923101-a5f8-4fbf-b994-535484f5d57e.png)

![image](https://user-images.githubusercontent.com/95496652/147863518-c69a9ffe-b2ce-4b2f-8df4-61af57dd8caa.png)

 
 ## Features
 
 ## Architecture
 
 

-------------------------
