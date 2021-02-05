# One_Class_Cyberattack_identification

This repository consists of code for various ML algorithms used to identify anomalies in a network by using One Class Classification.

One Class Classification (OCC):

OCC is a unary classification technique where the rare classes in our dataset are treated as anomalies. For example, in the case of network security, the ML training data consists mostly of more 'Benign' data samples and few 'Attack' samples. These attacks can be treated as outliers and identified using Unsupervised One Class Classification techniques. Such models are trained only on the majority class (Benign) in order to classify new samples as attack or benign.

Prerequisites:

Python >=3.6.0,  Keras = 2.2.4, Tensorflow >= 1.14.0

Network Security Dataset Used: CICIDS2017
