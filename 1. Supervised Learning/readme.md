# Supervised Learning

![Alt Text](/images/supervised.JPG)

## 1. Classification 

**Dataset**</br>

https://archive.ics.uci.edu/ml/datasets/kdd+cup+1999+data </br>

Description - 

KDD99 (Knowledge Discovery and Data Mining Cup 1999) is a widely used dataset for network intrusion detection and is commonly used as a benchmark dataset for evaluating new intrusion detection systems. It contains a sample of network traffic data from an actual U.S. Air Force local area network that includes both normal and malicious traffic. The dataset was created as part of a competition aimed at developing intrusion detection algorithms to identify different types of attacks, including Denial of Service (DoS), User to Root (U2R), Remote to Local (R2L), and Probe attacks.

The KDD99 dataset has a total of 41 features, including basic network connection attributes such as protocol type, service, source and destination IPs, source and destination ports, and duration of the connection. Each connection is labeled as either normal or as one of the four attack types mentioned above. The dataset contains approximately 5 million connection records, with around 2% of the connections being labeled as attacks.

The goal of the classification problem using KDD99 dataset is to accurately classify network connections as either normal or attack.

**Models Used**

- Logistic Regression </br>
- Support Vector Machines </br>
- K-Nearest Neighbors </br>
- Gaussian Naive Bayes </br>
- Tensorflow Fully Connected Neural Networks</br>


## 2. Regression

**Dataset** </br>

https://www.kaggle.com/datasets/javagarm/fifa-19-complete-player-dataset </br>

FIFA19 dataset is a collection of data related to soccer players and teams in the FIFA 19 video game. It includes a comprehensive set of player attributes, such as skill ratings, physical traits, preferred positions, and more, as well as team and league data.

The dataset consists of two CSV files: "players_19.csv" and "teams_and_leagues.csv". The "players_19.csv" file contains information on individual players, such as their age, nationality, preferred foot, overall rating, potential rating, and more. The "teams_and_leagues.csv" file contains information on the teams and leagues in the game, such as team name, league, and team overall rating.

This dataset can be used for various purposes such as analyzing player performance, building machine learning models to predict player ratings, or exploring team dynamics and strategy. It is a useful resource for sports analysts, game developers, and soccer enthusiasts.

The goal of the regression problem using FIFA 19 dataset is to predict the overall value of a player.

**Models used**

- Linear Regression
- Logistic Regression
- K-Neighbors
- Random Forest
- Support Vector Machines


