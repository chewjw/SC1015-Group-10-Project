# SC1015-Group-10-Project
Group 10 members: Low Guang Shen, Zheng Rongtao, Chew Jun Wei
## Phone Price Analysis and Machine Learning

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on phone prices and specifications from [GSMArena Mobile Phone Devices](https://www.kaggle.com/datasets/msainani/gsmarena-mobile-devices). For detailed walkthrough, please view the source code in order from:

1. [Data Extraction & Cleaning](https://github.com/chewjw/SC1015-Group-10-Project/blob/main/Extraction%20and%20Cleaning.ipynb)
2. [Data Visualization](https://github.com/chewjw/SC1015-Group-10-Project/blob/main/Data%20Visualization.ipynb)
3. [Machine Learning](https://github.com/chewjw/SC1015-Group-10-Project/blob/main/Machine%20Learning.ipynb)

## Problem Definition

- What should mobile phone companies do to thrive in the market?
- Are we able to predict if a mobile phone price based on its specifications?
- Which model would be the best to predict it?

## Models Used

1. Linear Regression
2. Random Forest
3. XGBoost

## Conclusion

1. Platform cpu, platform gpu and platform chipset are the highest correlated variables with respect to price
2. Despite so, intangible factors like brand loyalty and user experience is paramount in affecting price
3. Amongst the 3 different machine learning models, XGBoost is the best suited model

## Lessons learnt

1. Usage of Power Query to aid in data cleaning process making it much more efficient
2. Usage of category encoders to find correlation for categorical variables with respect to price using a train test split
3. Usage of XGBoost as a Machine Learning technique to help predict price using a technique that consist of simpler and weaker models
4. Data can only show us a relationship to an extent, other intangible factors should also be considered, which in this case is brand loyalty and user experience
5. Collaborating using GitHub

