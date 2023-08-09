
# Calories-Burnt Prediction : ML Project
This is a Machine Learning (ML) project that predicts the amount of calories a user (male or female) burns during exercise. The ML model takes feaures such as the duration of exercise, average heart beat during the exercise, the body temperature, height and weight of the person.


## Workflow

![Workflow](https://github.com/Brafamous/Machine-Learning_Regression/blob/main/Machine-Learning-Project.jpg)


## Dataset:
The dataset for this project is avaialable at: (https://www.kaggle.com/datasets/aadhavvignesh/calories-burned-during-exercise-and-activities)


## Data Analysis
Here a heatmap for the data is generated to show how the features or the dependent variables are correlated to each other. A very hihg value (say 1) depicts that the features are positively or strongly correlated and a very low value shows a weak correlation. As shown below Weight and Height are positvely correlated whiles duration and height have a negative correlation. However, the diagonal correlation are excluded. Duration and heart rate have a correlation of 0.9 which indicates a positive correlation. This implies that, a person who exercise for a longer hours will have a faster heart rate than someoen who exercise for a short period of time.

![Heatmap](https://github.com/Brafamous/ML-Calories-Burnt-Prediction/blob/main/Heatmap.png)


## Prediction and Evaluation
The image below shows a demo simulation of the ML taking the user's height, gender, weight, heart rate during exercise among others to predict the amount of calories burnt during the exercise.

![Heatmap](https://github.com/Brafamous/ML-Calories-Burnt-Prediction/blob/main/Prediction_test.PNG)


## Notebook
<iframe src="https://github.com/Brafamous/ML-Calories-Burnt-Prediction/blob/main/Prediction_of_Calories_Burnt%20(1).ipynb" width="100%" height="600px"></iframe>



The predicted calories burnt is as shown below 

![Heatmap](https://github.com/Brafamous/ML-Calories-Burnt-Prediction/blob/main/Prediction_test2.PNG)

