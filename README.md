# SC1015 Data Science & AI project
### About
This is a project for SC1015 (Introduction to Data Science and Artificial Intelligence).
Our project focuses on a [Movies Dataset](https://www.kaggle.com/datasets/arsalanrehman/movies-dataset-from-piracy-website). The order of files are as follows:

1. [Data Extraction](https://github.com/bombaysus/DSAI-Project/blob/main/Data-Extraction.ipynb) 
    * Extracted the dataset and performed data cleaning 
2. [Exploratory Data Analysis](https://github.com/bombaysus/DSAI-Project/blob/main/Exploratory-Data-Analysis.ipynb)
    * Explored the dataset using graphs and plots to better understand the data 
3. [Data Resampling and Splitting](https://github.com/bombaysus/DSAI-Project/blob/main/Data-Resampling-and-Splitting.ipynb)
    * Performed various oversampling and undersampling methods 
4. [Linear Regression](https://github.com/bombaysus/DSAI-Project/blob/main/Linear-Regression.ipynb)
    * Used uni-variate and multi-variate linear regression models to predict ratings  
5. [Neural Network-LSTM](https://github.com/bombaysus/DSAI-Project/blob/main/Neural-Network-LSTM.ipynb)
    * Used the LSTM model to predict ratings
6. [Neural Network-MLP](https://github.com/bombaysus/DSAI-Project/blob/main/Neural-Network-MLP.ipynb)
    * Used the MLP model to predict ratings
7. [Random Forest Model](https://github.com/bombaysus/DSAI-Project/blob/main/Random-Forest.ipynb)
    * Used a random forest classifier to predict whether a movie is good 
8. [Slides](https://www.canva.com/design/DAFf9rcu6s8/_Z2kIJdfm5uJg5uSSkSJbA/watch?utm_content=DAFf9rcu6s8&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)
    * Summarises our project and our findings 
  

### Problem Defintion 
Are we able to predict which factors are the most influential in getting people to watch a movie?

Which model would make the best prediction?

### Models Used 
1. Linear Regression 
2. Neural Network - LSTM 
3. Neural Network - MLP 
4. Random Forest 

### Conclusion 
* Different models yield different accuracies in predicting ratings
* Amongst all the models used (linear regression, LSTM, MLP, random forest) the MLP algorithm provided us with the most accurate results
* From the MLP model, we discovered that the 'downloads' variable had the greatest influence on movie ratings 

### What we learnt from this project 
*  We learnt how to clean, process, take samples and run tests on the dataset
*  We learnt that different models are suitable for different cases. For example, Random Forest is more suitable for categorical variables
*  Various methods of undersampling and oversampling
*  The implementation and workings of neural networks and random forest models 
*  Checking the accuarcy and reliability of our results through data visualisation and metrics such as mean squared error 

### References 
* https://www.kaggle.com/datasets/arsalanrehman/movies-dataset-from-piracy-website
* https://www.educative.io/answers/how-to-install-tensorflow-in-jupyter-notebook
