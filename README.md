# Board-Game-Review-Prediction
Reviews can make or break a product; as a result, many companies take drastic measures to ensure that their product receives good reviews.  When it comes to board games, reviews and word-of-mouth are everything. In this project, we will be using a linear regression model to predict the average review a board game will receive based on characteristics such as minimum and maximum number of players, playing time, complexity, etc. 

Before we get started, we will need to clone a GitHub repository that contains the data set we will be using. This can be accomplished by installing git, an incredibly useful tool, or by simply downloading the repository using the link provided. Git can be installed by issuing the following command in the terminal:

conda install -c anaconda git

1. Importing Libraries and Loading the Data

After the .csv file 'games.csv' has been copied to the current directory, we can import the data as a Pandas DataFrame. As a DataFrame, we will be able to easily explore the type, amount, and distribution of data.  Furthermore, using a correlation matrix, we can explore the relationships between parameters.  This is an important step in determining the type of machine learning algorithm to utilize. 

2. Linear Regression

In the following cells, we will deploy a simple linear regression model to predict the average review of each board game.  We will use the mean squared error as a performance metric.  Furthermore, we will compare and contrast these results with the performance of an ensemble method. 
