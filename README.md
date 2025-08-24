# Intrusion-detection-in-5g-networks-using-LSTM
1)Project Overview-
This project focuses on building an Intrusion Detection System (IDS) for 5G networks using deep learning. With the rise of 5G, ensuring secure communication is critical. We used the NSL-KDD dataset to train models that detect and classify different types of network intrusions.

2)Objectives-
Detect malicious activities in 5G network traffic.
Classify attacks such as DoS, U2R, R2L, and probing.
Compare the performance of LSTM-based models for anomaly detection.
Evaluate the system using key metrics like accuracy, precision, recall, F1-score, and ROC.

3)Dataset
NSL-KDD dataset (a refined version of KDD Cup 99 dataset).
Contains normal traffic and multiple types of attacks.

4)Tools & Technologies-
Python,
TensorFlow / Keras,
NumPy, Pandas,
Matplotlib, Seaborn (for visualization)

5)Methodology-
Data Preprocessing → Normalization and preparation of NSL-KDD dataset.
Modeling → Implemented RNN-LSTM with Dense layers for anomaly detection.
Training & Testing → Split dataset and evaluated model performance.
Evaluation → Plotted graphs for accuracy, precision, recall, F1-score, and ROC.

6)Results-
Implemented and tested the IDS using the NSL-KDD dataset.
The LSTM model showed good performance in classifying normal and attack traffic.
Visualized results with accuracy, precision, recall, F1-score, and ROC curves.
Confirmed that sequence-based models like LSTM can be effectively applied to 5G intrusion detection.
