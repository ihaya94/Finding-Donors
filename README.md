# Finding-Donors

Introduction to Machine Learning with TensorFlow Nanodegree Program
Project 1: Finding Donors for CharityML
Project Description
In this project, I used sklearn and supervised learning techniques on data collected for the U.S. census in 1994 to help a charity organization identify people most likely to donate.

First, I investigate the elements that influence the possibility of charitable donations. Then, I use a training and predicting pipeline to evaluate the accuracy and efficiency/speed of three supervised machine learning algorithms (GaussianNB, DecisionTree, Adaboost). I then proceed to tune the parameters of the algorithm that provides the highest accuracy in efficient time. Finally, I also explore the impact of reducing number of features in data.

Install
This project requires Python 2.7 and the following Python libraries installed:

NumPy
Pandas
matplotlib
scikit-learn
You will also need to have software installed to run and execute an iPython Notebook

Code
The main code for this project is located in the finding_donors.ipynb notebook file. 


Data
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", by Ron Kohavi. You may find this paper online, with the original dataset hosted on UCI.

Features
age: Age
workclass: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
education-num: Number of educational years completed
marital-status: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
occupation: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
relationship: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
race: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
sex: Sex (Female, Male)
capital-gain: Monetary Capital Gains
capital-loss: Monetary Capital Losses
hours-per-week: Average Hours Per Week Worked
native-country: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

Target Variable
income: Income Class (<=50K, >50K)
