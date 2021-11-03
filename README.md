LINK : [https://whatsapp-chat-analysis-predict.herokuapp.com/]

# Introduction:

Hello there, thanks for review my notebook! So today we are going to analyse the whatsapp chat that we normally use everydays. In here we are going to use a chat group that is and in this group we normally will exchage knowleged that we learn by teaching one and others.

# Data Retrieval

First before any EDA to be done we must first understand how to get the data we need. Normally we can go to kaggle.com to start getting our dataset. But for this EDA we will use the whatsapp data that everyone can export in they own whatsapp group. Let me show how you are able to retrieval the data easily.

# Take note
I am export without media because if the media files is more than a certain value then not all the files are able to be exported

# Data Preparation and Cleaning
## Before we start our data preparation and cleaning there are so few item we need to take noted:

Business and data understand is the success key factor of a good analysis
Make sure all the row number is balance because we did now want to see outliner
Make sure the data are clean, such as you all need text not picture.

# Business & Data understanding
## Before we start any analysis we need to understand the Business and the data side

# Business understanding:

In any project we must understand what exactly we want to found out in this project?
Do this analysis help us to achieve business goal?

# Data Understanding

In here we can see there are 3 columns in the dataset
The dataset contains date, text and a NaN value
Using the info(), we are able to know the row of each object is not balance because there are 21k message but some of the columns only have 23k and 700
After knowing there is an unknown value in the dataset and inbalance row we now can clear the data

# Let get started on the Exploratory Data Analysis(EDA)
1. Which users have the most Chat/messages in the group?
2. Which emojis use the most by which users?
3. Most active hours?
4. Which month have the highest messages and also the busiest month?
5. Determine which word or text did the user use the most?


# Conclusion
## Data Retrieval

First we learn how to load data at whatsapp and understand the format as text file.Other than that we understand what kind format should we extract(eg "media" or "without media")

## Data Preparation and Cleaning

In the data preparation and cleaning we learn on how to convert text file into dataframe. Then we learn to add name to the colums and even on how to clean image file from the dataframe

## Business & Data understanding

Then we start understand the business needed and the data in the dataframe. In the business understand how us to understand what question should we need to ask that will lead to business succeed.

## Exploratory Data Analysis(EDA)

In the EDA we look at five important question to ask:
1. Which users have the most Chat/messages in the group?
2. Which emojis use the most by which users?
3. Most active hours?
4. Which month have the highest messages and also the busiest month?
5. Determine which word or text did the user use the most?


# Reference
https://www.drawingfromdata.com/setting-figure-size-using-seaborn-and-matplotlib

https://seaborn.pydata.org/examples/part_whole_bars.html

https://wellsr.com/python/seaborn-barplot-tutorial-for-python/
