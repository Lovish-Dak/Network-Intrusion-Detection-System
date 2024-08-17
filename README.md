# Network-Intrusion-Detection-System

# Overview
This is my B.Tech Project, where I created a model which can detect network intrusions effectively. For the effective intrusion detection system, I used the Convolutional Neural Networks as they can capture both spatial and temporal patterns, and I used BiLSTM layers as well because LSTM generalizes well on time series or sequential data.

# Datasets Used
(i) NSL-KDD <br>
(ii) UNSW-NB15 

# Techniques Used
(i) Removing NULL and duplicate values <br>
(ii) Oversampling <br>
(iii) One-Hot Encoding <br>
(iv) Min-Max Normalization <br>
(v) Stratified K-Fold Cross Validation

# Model Architecture (Layers Used)
1. Conv-1D Layer <br>
2. Max Pooling Layer 
3. Batch Normalization Layer
4. BiLSTM Layer
5. Reshape Layer
6. Max Pooling Layer
7. Batch Normalization Layer
8. BiLSTM Layer
9. Dropout Layer
10. Dense Layer (Softmax Regression in case of Multi-Class Classification and Logistic Regression in case of Binary Classification)

PPT Link: https://www.canva.com/design/DAGNOmyvUU4/5tyNhD6c0KHF3Fx624fEnQ/view?utm_content=DAGNOmyvUU4&utm_campaign=designshare&utm_medium=link&utm_source=editor 
