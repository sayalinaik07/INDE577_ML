# Supervised Learning

![Alt Text](./images/supervised.JPG)

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
- K-Nearest Neighbors
- Gaussian Naive Bayes
- Tensorflow Fully Connected Neural Networks
