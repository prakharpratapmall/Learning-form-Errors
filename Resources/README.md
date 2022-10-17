Welcome to "Learning from Errors" offered by BCS. We will be using discord to communicate, and you can use this channel to ask any queries or hold any discussion. @dhwanit  and I will be your mentors for this project. 

Through this project, we will be understanding how machines "learn from their errors" to make better decisions. Ultimately, we will learn the theory and implementation of various Reinforcement Learning techniques. But before that, we need to cover the basics. This week, we will be familiarising ourselves with python and its libraries. Here are the resources for the same:

Firstly, install Python3 on your system. Follow these links to install if you are facing issues: 
Ubuntu: https://phoenixnap.com/kb/how-to-install-python-3-ubuntu
Windows: https://phoenixnap.com/kb/how-to-install-python-3-windows
Mac: https://flaviocopes.com/python-installation-macos/

Next, go through these links. 
Basic Python tutorial: https://www.programiz.com/python-programming/tutorial

Jupyter Notebook tutorial: https://towardsdatascience.com/a-beginners-tutorial-to-jupyter-notebooks-1b2f8705888a

Numpy:-
https://numpy.org/devdocs/user/quickstart.html

Pandas:-
https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python

Matplotlib:-
https://towardsdatascience.com/matplotlib-tutorial-learn-basics-of-pythons-powerful-plotting-library-b5d1b8f67596

https://matplotlib.org/users/pyplot_tutorial.html (optional)

Try to go through these links by Thursday.  Note that you don't need to memorise the syntax, you just need to know what all you can do using the particular library.
Incase you face any difficulties, first try to Google. If that does not help, feel  ask your doubts here. All the best!

Hope you have gone through the material provided by us. Now it is time to implement these libraries to visualise data. Your first assignment is as follows:

1.Firstly, go to https://github.com/dhwanit75/Learning-form-Errors/tree/main/Assignment-1 and download the Hotel Booking dataset; "hotel_bookings.csv". 
2.In the same repo, you will find a Meta Data file ("MetaData.csv") that contains details about what each column represents. Read it carefully and make sure you have a good understanding of it. 
3.Next, import the dataset in a Jupyter Notebook (or Google Colab) using Pandas. 
4. Handle missing values 
5. Your main task is to perform data analysis and visualisation on the given dataset using the libraries that you have learnt about; matplotlib, numpy and pandas. Use these libraries to find answers to questions such as:
-> Using graphs, find out the time of the year when hotel bookings are at a peak.
->See if there is any association of price and what time of the year it is.
->Which type of room has the highest price?
->Which country has the highest number of bookings?
These are the questions that you MUST answer using visualisations. Apart from these, you also have to identify atleast FOUR other trends in a similar way. Of course, the more trends you identify, the better.

You have to submit the assignment by Sunday, 5 June 11:59pm. The details of how you have to submit the assignment will be shared later. Remember: Copying is strictly PROHIBITED. Feel free to ask any doubts on the channel. All the best!

Well done to those who submitted assignment 1 successfully. We will now be moving forward in the project. This week, we will be covering the basics of Machine Learning and also its implementation. The assignment will be released shortly. We will also inform you about a discussion session soon. Till then, go through these resources:

https://towardsdatascience.com/machine-learning-basics-part-1-a36d38c7916 Basic overview of what ML is

https://machinelearningmastery.com/what-is-deep-learning/ 
An introduction to deep learning

https://medium.com/towards-data-science/overfitting-vs-underfitting-a-conceptual-explanation-d94ee20ca7f9
Overfitting and Underfitting in more detail.

Then go through this playlist which explains the theory behind the most basic type of Machine Learning; Linear Regression:
https://youtube.com/playlist?list=PLJs7lEb1U5pYnrI0Wn4mzPmppVqwERL_4

Lastly, learn how to implement these ML algorithms using SciKit Learn
https://youtu.be/0B5eIE_1vpU

All the best and feel free to ask doubts!

Before finally moving on to reinforcement learning, here is assignment 2. In this assignment, you will be implementing what you learnt about machine learning using scikit learn. Here is your task:
1. Use the same dataset as last time. ("hotel_bookings.csv" at  https://github.com/dhwanit75/Learning-form-Errors/tree/main/Assignment-1 )
2. Separate the "adr" (Average Daily Rate) column from this dataset
3. Now using the rest of the 31 columns, you have to predict the Average Daily Rate for that booking. To do this, firstly you will have to preprocess the data using the various concepts you learnt last week, like handling categorical variables (In case you don't know how to, refer https://towardsdatascience.com/handling-categorical-data-the-right-way-9d1279956fc6 ), handling missing values, dropping columns, etc.
4. Split the data into test and training sets (use a ratio of 20-80)
5. Use any 5 (at least) machine learning algorithms (e.g Linear Regression, Random forest regression) to predict the ADR for each booking.
6. Evaluate each method using metrics such as MSE, R2 Score, etc. (You can learn more about these at https://towardsdatascience.com/ways-to-evaluate-regression-models-77a3ff45ba70 )

The deadline to submit this assignment is 14th June 11:59pm. Feel free to ask us any doubts regarding the material or the assignment. Good luck!

Finally we are done with the basics and now we will be moving on to Reinforcement Learning. Things will be getting a bit tougher now, so be careful that you understand the theory properly. Ask us any sort of doubts if you have any. Here are the resources for this week. Try going through these by Wednesday.

Read this article for an introduction: https://deepsense.ai/what-is-reinforcement-learning-the-complete-guide/ 

Watch these introductory videos on Object Oriented Programming as they will be helpful when we will be implementing this theory. Watch the first three videos of this playlist:

https://www.youtube.com/watch?v=ZDa-Z5JzLYM&list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc&index=1

And most importantly, here are the resources for reinforcement learning. Watch and read the text from the first 7 lessons from this website:

https://deeplizard.com/learn/video/nyjbcRQ-uQ8

Assignment 3 will be out soon. Go through these resources ASAP because it may take longer to understand. Good luck!

Hope you have been going through the RL material. So here is assignment 3. In this assignment you will be training an agent to play the Frozen Lake game (details in the notebook) using value iteration Q-Leaning. This is a fairly simple assignment,  just replace the "pass" with your code. Hints are provided in the text blocks and the comments. The deadline is 21st June EOD. 

https://colab.research.google.com/drive/1ijtG3OsO2UgBSiEvG2d_59oszZkkX9jf?usp=sharing

Feel free to ask doubts and all the best!