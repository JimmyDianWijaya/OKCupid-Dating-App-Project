# OKCupid-Dating-App-Project
This repository contains the files related to OKCupid Dating App Project. 

This project contains sample data from a dating app known as 'Ok Cupid'.
The primary objective of this project is to explore and perform statistical analysis on the dataset.
Furthermore, I have also created a KNN algorithm to predict the user's horoscope sign based on a number of features.
The tool used in this project is Python in Jupyter Notebook. 

In this repository, you will find the dataset (59946 rows and 31 columns) with 2 different version:
1. The original dataset - profiles.csv - STATUS PENDING (file size is too big to be uploaded to GitHub)
2. The post-data cleaning dataset - cleansed_profiles.csv - STATUS PENDING (file size is too big to be uploaded to GitHub)

Furthermore, you will also find these files, OKCupid Cleansed Profile Data Analysis.ipynb, OKCupid Profile Data Cleansing.ipynb and Findings presentation in PowerPoint.

The dataset provided has the following columns of multiple-choice data:

- body_type
- diet
- drinks
- drugs
- education
- ethnicity
- height
- income
- job
- offspring
- orientation
- pets
- religion
- sex
- sign
- smokes
- speaks
- status

And a set of open short-answer responses to :

- essay0 - My self summary
- essay1 - What I’m doing with my life
- essay2 - I’m really good at
- essay3 - The first thing people usually notice about me
- essay4 - Favorite books, movies, show, music, and food
- essay5 - The six things I could never do without
- essay6 - I spend a lot of time thinking about
- essay7 - On a typical Friday night I am
- essay8 - The most private thing I am willing to admit
- essay9 - You should message me if…

During the data cleaning process, there were assumptions have to be made on null values.
For instance, 
1. In the body_type and diet columns, I assume the users who intentionally left this data out, would prefer not to say about his/her body type and diet.
2. In the drinks column, I also made the assumptions that the null values are the users who also drink socially.
3. In the drugs column, 'never' used drugs is used as an assumption. 

There are many more columns that I had to made a careful assumption.
 
Apart from making my own assumptions, there are also a few observation that had to be removed due to outliers and junk-content provided in the data. 
For example,
1. In the age column, there are users who input his/her age as 110 years old, 109 years old. 
2. In the income column, there are users who entered -1, which does not make sense. Therefore, I had to replace this value to 0.

Lastly, the features I chose to be used in the KNN Algorithm are as follows:
1. smoking behaviour
2. drinking behaviour
3. involvement of drugs
4. total words in their essay
5. the average word length in their essay
The feature scaling method I used is the StandardScaler.

Feel free to download these files to see how I approached this project.

Kind Regards,

Jimmy Wijaya
