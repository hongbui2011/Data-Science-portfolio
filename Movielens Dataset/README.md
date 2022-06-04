# Portfolio Part 1 – Analysis of MovieLens Data
**Description:** 

This project includes the Exploratory Data Analysis technique using the MovieLens dataset collected by the GroupLens Research Project at the University of Minnesota. 

**Data Dictionary:**

| Columns      | Description                                         |
| -----------  | -----------                                         |
| userId       | the user's id                                       |
| age          | the user's age                                      |
| gender        | the user's gender                                  |
| occupation   | the user's occupation                               |
|movieId | the movie's id                                            |
|rating | the user's rating towards the movie                        |
| genre | the genre of the movie                                     |
| timestamp | the timestamp indicating when the user rated the movie |

**Analysis Tasks to be performed:**

•	Importing dataset in csv format

•	Detecting and removing any missing values

•	Explore the dataset using descriptive statistics and visualisation techniques

    o	User – Age - Gender distribution 
    o	User’s occupation distribution
    o	Top Genre by viewership rating
    
•	Detecting and removing any outliers that affect the analysis

# Portfolio Part 2 – Regression Model with MovieLens Dataset
**Description:** 

We used the same dataset as in Portfolio Part 1. However, this time the dataset had been cleaned before being imported into the Notebook. The goal of this portfolio is to is to train linear regression models to predict users' ratings towards movies. Besides, we also explored the impacts of feature selections and different sizes of training/testing data on the model performance.

**Analysis Workflow:**

•	Exploring data

•	Building regression models

•	Making predictions

•	Evaluating models using different evaluating metrics, including MSE and RMSE

# Portfolio Part 3 – Advanced Machine Learning with MovieLens Dataset
**Description:** 

In this Portfolio project, we continued to work with the MovieLens data collected by the University of Minnesota's GroupLens Research Project. The target variable in the dataset is changed from 'rating' to 'feedback'. The target 'feedback' has two values: 1 indicates that the user likes the video, while 0 indicates that the user dislikes it.

The goal of this project is to develop predictive Machine Learning Models using existing features, hence predict the value of the ‘feedback’ column. The project also involved in Feature Selection to figure out which features deliver the most accurate prediction.

**Analysis Workflow:**

•	Exploring data

•	Preparing data (Feature Engineering) 

•	Constructing two Machine Learning models: Regression and K-Nearest Neighbors

•	Performing Feature Selection

•	Evaluating models based on the accuracy score of each model
