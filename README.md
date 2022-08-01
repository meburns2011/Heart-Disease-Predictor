# Using a health survey to predict heart disease or attack
The data set that I used was collected through a phone interview across the U.S. about health risks in 2015. 

Author: Mary Burns

# Data: Most of the questions are yes or no questions asking whether or not someone is physically active, has high blood pressure or has been asked by their doctor to check for high cholesterol. Some of the questions are scaled into groups such as age or how many days a month someone has poor mental health. Some of these questions require more detailed answers to get a better idea of what lifestyle the patients are living. 
Specifically there should be more detailed questions over smoking habits and physical acitvity. The survey only asked if a person had ever smoked 5 packs of cigarettes in their life which skews the data. This is because lungs can heal from smoking after 2 years of stopping and theoretically would lower that person's chance of heart disease. The survey also only asks whether the person has been physically active at all in 30 days. 1 day of physical acitvity is not the same as 24 days of physical activity. This also skews the data. 

# Data preparation
 Data preparation for me only included scaling the data. It had already been cleaned by another data science and posted to Kaggle. 

# Final Model
My final model predicts accuracy by 94%. However I do include a Kmeans cluster model to show the different types of people who were interviewed. I believe it is very important to not just use the model to predict heart attack or disease but to also understant the difference between the people who did have a heart attack from the people who didn't. This gives doctors the chance to look for indicators early and helping the patients change thier lifestyles to prevent heart disease instead of simply monitoring for it. 
