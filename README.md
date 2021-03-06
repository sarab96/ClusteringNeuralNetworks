# ClusteringNeuralNetworks
Unsupervised clustering of patients using CNN with Deep Learning

Patient Clustering with Neural Network: Unsupervised Machine Learning
Unsupervised clustering of patients using CNN with Deep Learning. Used different technique and CNN to explore clustering based on feature detection.

Traditional neural network clustering techniques use methods to create boundaries around groups within dataset based on distance from centroids or use PCA kind of dimension reduction.

Some of traditional neural network clustering algorithms are:

1) Vector Quantization (VQ) based on simple competitive learning

2) Self Organizing Map (SOM) Kohonen network

3) Neural Gas neural networks

4) Adaptive Resonance Theory (ART) networks

5) C-mean/K-mean Algorithms

We decide to use different technique. Recently CNN have been used even for NLP applications like sequence modelling. So we used convolutional neural network to capture local patterns and then using mean square distance error to map all data into clusters. 2D Embedding of the input data is generated by three final fully connected layers of the CNN in 2D for plotting of the clusters.

This techniques has below advantages: 1) Number of clusters not fixed at the start 2) Unsupervised learning. No labels required 3) Regular deep learning tools used with back propagation for feature learning 4) Slight modification of this technique can be used to do clustering for a particular goal. For example clustering to decide which group of people spend different number of days in hospital. In this distance can be minimized for number of days spent in hospital to create clusters.

Blow plot shows various clusters found by the CNN clustering.


10 years of patient clinical care dataset from 130 hospitals is used. Each record has 50 features. With total of 110K records. We used only five features for our study: 1) Race, 2) Gender, 3) Age, 4) Admission Type 5) Number of days spent in hospital

See below for more details:
https://www.linkedin.com/pulse/patient-clustering-neural-network-unsupervised-machine-singh
