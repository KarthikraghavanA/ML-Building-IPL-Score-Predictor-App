# *Machine Learning - Building IPL Score Predictor App*

In this project, We will predict the IPL score between the teams given a few feature values.
We will deploy using flask.

----------------------------------------------------------------------------------------

# *Dataset Link*

* https://data.world/datasets/sports
* https://raw.githubusercontent.com/ghimiresunil/IPL-First-Innings-Score-Prediction-/master/ipl.csv

----------------------------------------------------------------------------------------

# *Machine Learning - Building IPL Score Predictor App*

## *Introduction*

Cricket is one of the most popular outdoor sports that has captured everyone’s heart. There are many series that are held, and the Indian Premier League (IPL) is one of them which has a long and illustrious tradition in the sports world. IPL is a professional Twenty20 (T20) league started in 2008 which was founded by the Board of Control for Cricket in India (BCCI). The IPL is a 20-over league, which means each team plays 20 overs from both sides. Every year, eight teams from eight Indian cities participate in this league. A cricket match is influenced by a variety of factors, and the factors that have a major impact on the outcome of a T20 cricket match are described in this project. This project takes several years of IPL data, including player information, match location information, team information, and ball to ball information, and analyzes it to draw different conclusions that help in the enhancement of player’s results. It focuses on calculating the results of IPL matches using data mining techniques on both balanced and imbalanced datasets. In T20 Cricket matches, the first innings score is currently estimated based on the existing run rate, which is measured as the number of runs scored per a number of overs bowled. It includes the following factors:

Number of wickets left
Number of balls left
On how much scores are the current batsman batting?
How much has the team scored in the last 5 years?
How much did the team have lost wickets in the last 5 overs?
The nature of the pitch
How strong is the batting and bowling team?

## *Steps Involved*


* Firstly, the data is trained. We will take 15-20% of the data from the data collection to train the model.
* We will take 15-20% of the data from the data collection to train the model.
* For the prediction, we will be using a Linear regression algorithm.
* The project is split into three separate Jupyter Notebooks: one to collect the IPL data, inspect it, and clean it; a second to further refine the features and fit the data to a Linear Regression model to train and evaluate our output.


## *Software Requirement*

The Code is written in Python 3.7 .If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of  pip . To install the required packages and libraries, run this command in the project directory:

>> pip install -r requirements.txt

    * Python
    * Pandas
    * Numpy
    * Matplotlib
    * Scikit Learn
    * Jupyter Notebook / Google Colab
    * Pycharm

## *Data Collection*

Dataset link --> https://raw.githubusercontent.com/ghimiresunil/IPL-First-Innings-Score-Prediction-/master/ipl.csv

Kaggle was used to collect the IPL score data, We took 80% of the data for the train set and the rest 20% for the test set.

Paramaters are:

    * Venue
    * Bat Team
    * Bowl Team
    * Batsman
    * Bowler
    * Runs
    * Wickets
    * Overs
    * Runs last 5
    * Striker
    * Non Striker
    * Total

## *Steps involved in Data Preprocessing*

    * Feature Selection
    * Normalization
    * Machine Learning (Linear Regression Algorithm is the ML algorithm used in our project)
    
## *Directory Tree*

![image](https://user-images.githubusercontent.com/112689649/212249231-d365b414-4df8-417e-b88d-6f2f5224df9a.png)

![image](https://user-images.githubusercontent.com/112689649/212249174-7fee9e16-c72a-439b-b237-5fefbcf1e301.png)

![image](https://user-images.githubusercontent.com/112689649/212249205-b4a33102-3e3e-4f12-9896-496ed0bf8a0e.png)


