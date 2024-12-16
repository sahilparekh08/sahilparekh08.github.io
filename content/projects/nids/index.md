---
title: "An Approach to Reducing Uncertainty Problem in NIDS"
description: "Developed a machine learning-based Network Intrusion Detection System using Genetic Algorithms for feature selection, applying KDDCup99, NSL KDD datasets, and Wireshark-captured packets. The system utilized a random forest classifier to optimize accuracy and minimize false positives. Published in the 15th IEEE Conference on Industrial and Information Systems"
date: "2020-12-01"
---

Detecting malicious packets on the fly with minimal lag time is a very important feature of a Network Intrusion Detection System. With the use of machine learning algorithms, the detection becomes more robust as it aids the rules coded into the system and also helps in detecting packets which might be malicious for which rules have not been written yet.

The project's goal was to train the system on a variety of malicious and non-malicious packets and then build a model through which it can then predict and bucket the packet. The first layer of this project uses a Genetic Algorithm as a feature selection algorithm on a combination of KDDCup99 Dataset, NSL KDD data set and packets collected through Wireshark by simulating cyber attacks in a LAN. By using a fitness function on a random forest classifier which rewards a chromosome for high accuracy and low false positives and error rates, the data is run through multiple epochs of fitness, selection, crossover and mutation functions to determine the important features from a 43 feature dataset.

The resulting data was then passed through multiple classification algorithms for a comparitive study. This project was published as an [IEEE paper](https://ieeexplore.ieee.org/document/9342634) in the 15th IEEE Conference on Industrial and Information Systems.