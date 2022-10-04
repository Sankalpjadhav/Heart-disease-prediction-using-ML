# Heart Disease Prediction using Machine Learning
This model is developed by taking available data-sets and trained the model accordingly to predict whether the patient has a positive response or negative response to heart disease.

# Machine learning algorithms are often categorized as follows
•	Supervised machine learning algorithms can apply what has been learned in the past to new data using labeled examples to predict future events. The system can provide targets for any new input after sufficient training. The learning algorithm can also compare its output with the correct, intended output and find errors to modify the model accordingly.

•	In contrast, unsupervised machine learning algorithms are used when the information used to train is neither classified nor labeled. Unsupervised learning studies how systems can infer a function to describe a hidden structure from unlabeled data. The system doesn't figure out the right output, but it explores the data and can draw inferences from datasets to describe hidden structures from unlabeled data.

•	Semi-supervised machine learning algorithms fall somewhere in between supervised and unsupervised learning, since they use both labeled and unlabeled data for training – typically a small amount of labeled data and a large amount of unlabeled data. The systems that use this method can considerably improve learning accuracy. 

•	Reinforcement machine learning algorithms are a learning method that interacts with its environment by producing actions and discovers errors or rewards. Trial and error search and delayed reward are the most relevant characteristics of reinforcement learning. This method allows machines and software agents to automatically determine the ideal behavior within a specific context to maximize its performance. Simple reward feedback is required for the agent to learn which action is best; this is known as the reinforcement signal.

# Various concepts of machine learning for development of project were used. 
Some of the Machine learning libraries used are:

# Matplotlib  
It is an amazing visualization library in Python for 2D plots of arrays. Matplotlib is a multi-platform data visualization library built on NumPy arrays and designed to work with the broader SciPy stack. It was introduced by John Hunter in the year 2002. One of the greatest benefits of visualization is that it allows visual access to a huge amount of data. Matplotlib consists of several plots like line, bar, scatter, histogram.

# NumPy 
It is a general-purpose array-processing package. It provides a high-performance multidimensional array object and tools for working with these arrays. It is the fundamental package for scientific computing with Python. NumPy can also be used as an efficient multi-dimensional container of generic data.
Pandas: It is the most popular Python library that is used for data analysis. It provides highly optimized performance with back-end source code which is purely written in C or Python.

# Tkinter
Python offers multiple options for developing GUI (Graphical User Interface). Out of all the GUI methods, Tkinter is the most commonly used method. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with Tkinter outputs the fastest and easiest way to create GUI applications. Creating a GUI using Tkinter is an easy task.

Machine learning supports various algorithms. Some of the algorithms used are:

# Linear regression 
It is a statistical approach for modelling the relationship between a dependent variable with a given set of independent variables. Simple linear regression is an approach for predicting a response using a single feature. It is assumed that the two variables are linearly related. Hence, a linear function that predicts the response value(y) as accurately as a possible function of the feature or independent variable(x) is found.

# Decision Tree classifier Algorithm 
A decision tree is a flowchart-like tree structure where an internal node represents feature (or attribute), the branch represents a decision rule and each leaf node represents the outcome. The topmost node in a decision tree is known as the root node. It learns to partition based on the attribute value. It partitions the tree in recursively manner call recursive partitioning. This flowchart-like structure helps in decision making. It visualizes like a flowchart diagram which easily mimics the human-level thinking. That is why decision trees are easy to understand and interpret.

All these concepts and algorithms helped to develop a project which predicts whether a person has heart disease or no.

# Firstly, 
It all started with downloading both training and testing datasets from the Kaggle website in the form of a CSV file, then finding the accuracy of the trained model. The detailed information like Blood pressure, Cholesterol level, Family history, Body mass index (BMI) and Age is taken to predict whether the patient has a heart disease or not. Histogram is used to show how each feature and label is distributed along different ranges, which further confirms the need for scaling. Next, wherever the discrete bars are seen, it means that each of these is a categorical variable. These categorical variables are handled before applying Machine Learning. The target labels have two classes, 0 for no disease and 1 for disease.

The project involves analysis of a heart disease using patient’s dataset with proper data processing. The use of different types of Machine Learning Techniques to predict the occurrence of heart disease has been summarized. Determined the prediction performance of each algorithm and applied the proposed system in appropriate areas. Used more relevant selection methods to improve the performance of the algorithms.

# In conclusion,
The belief is that only a marginal success is achieved in the creation of a predictive model of heart disease of a patient and hence there is a need for computational and more complex models to increase the accuracy of predicting the early onset of heart disease. In this project, the model has been trained as well as tested to get higher accuracy which will help in achieving success for the model that has been developed.
Many possible improvements could be explored to improve the scalability and accuracy of this prediction model and further thinking can make this model more flexible by training large amount of dataset so that accuracy of this model will be more relevant for the application.

# Taking Input for Prediction
![input](https://github.com/Sankalpjadhav/Heart-disease-prediction-using-ML/blob/master/input.PNG?raw=true "Optional Title")

# Positive response
![Positive response](https://github.com/Sankalpjadhav/Heart-disease-prediction-using-ML/blob/master/Positive%20response.png?raw=true "Optional Title")

# Negative response
![Negative response](https://github.com/Sankalpjadhav/Heart-disease-prediction-using-ML/blob/master/Negative%20response.png?raw=true "Optional Title")

# Patient's Age Graph
![Age plots](https://github.com/Sankalpjadhav/Heart-disease-prediction-using-ML/blob/master/AgePlots.png?raw=true "Optional Title")

# Patient's Blood pressure Graph
![Patient's Blood pressure Graph](https://github.com/Sankalpjadhav/Heart-disease-prediction-using-ML/blob/master/BloodPressurePlot.png?raw=true "Optional Title")

# Patient's Cholestrol Graph
![Patient's Cholestrol Graph](https://github.com/Sankalpjadhav/Heart-disease-prediction-using-ML/blob/master/CholestrolLevelsPlot.png?raw=true "Optional Title")


