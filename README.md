# CQhack25-Oral Disease Detection using Quantum Machine Learning Models

This experiment explores oral diseases identification using hybrid quantum-classical neural networks (HQCNN) and quantum convolutional neural networks (QCNN). We investigated the possibilities of quantum machine learning in processing complicated dental image data. A whole dataset of oral disease images was preprocessed to improve model generalization using data augmentation and class balancing methods, especially ADASYN. Incorporating principle component analysis (PCA) for dimensionality reduction and angle encoding for quantum state preparation, we created and compared HQCNN and QCNN architectures. Accuracy, F1-score, recall, precision, and AUROC were among the criteria used in the training and evaluation of the models. Our results show that with an accuracy of 88.73%, HQCNN exceeded QCNN in binary classification. With a top accuracy of 65.92% utilizing a 3-qubit architecture, HQCNN displayed decent performance for multi-class classification. This work opens the path by highlighting the possibility of quantum-enhanced machine learning for raising the accuracy and efficiency of oral disease diagnosis.

![Motivational Figure drawio](https://github.com/user-attachments/assets/4824b0db-c45f-4783-8149-7e6be1761a2d)

Figure 1: A QCNN model used for classifying dental images consists of several convolution and pooling layers that reduce the dimensionality of data to classify images either as tooth discoloration or dental caries.

<img width="572" height="311" alt="Structure of Layers HQCNN drawio" src="https://github.com/user-attachments/assets/d1187282-861c-44df-8bdc-0a0e9a5d2d23" />

Figure 2: Two Qubit HQCNN model

## Inspiration

More than 3.5 billion people around the world have oral diseases, but early diagnosis is still expensive, slow, and often wrong.

## What it does

Hybrid quantum-classical neural network (HQCNN) & Quantum Convolutional Neural Network (QCNN) to look at medical images and determine what kind of oral diseases the patient has.

## How we built it

We used Qiskit, PyTorch, and Google Colab to make HQCNN and QCNN models that can tell the difference between different kinds of oral diseases based on medical images.

## Challenges we ran into

We had trouble getting to quantum hardware, scaling qubits, and training for a long time on a free-tier cloud to test those models on a Real IBM Brisbane (QPU)

## Accomplishments that we're proud of

Using a hybrid quantum-classical model on real medical datasets, we could correctly classify 88.73% of the time.

## What we learned

We learned that hybrid quantum models can be more accurate, stable, and efficient at training than pure quantum models.

## What's next for Oral Disease Detection Using Quantum Machine Learning Models

Use real quantum hardware and improve real-time clinical diagnosis.

## Built With

* matplotlib
* numpy
* pandas
* pytorch
* qiskit
* scikit-learn
* tensorflow

## Try it out

* GitHub Repo
* [www.canva.com](http://www.canva.com)
* [https://youtu.be/amcMESB1q9s?si=iFcmxzW\_BPS1HlZn](https://youtu.be/amcMESB1q9s?si=iFcmxzW_BPS1HlZn)
