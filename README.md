# Face-recognition-using-covolutional neural network

# Abstract
Convolutional Neural Networks has been playing a significant role in many applications including surveillance, object detection, object tracking, etc. Extensive research is recorded for face recognition using CNNs, which is a key aspect of surveillance applications. In most recent times, the Face Recognition technique is widely used in University automation systems, Smart Entry management systems, etc. In this paper, a novel CNN architecture for face recognition system is proposed including the process of collecting face data of students. Experimentally it is shown that the proposed CNN architecture provides 99% accuracy. Further, the proposed CNN framework is used to develop a “Smart Attendance Management System (SAMS)“, which is a web-based application, to provide attendance of students using face recognition, in realtime. The proposed application is easy to deploy and maintain.

# Project Description
The application gives a complete description regarding dataset creation i.e, collection of images and creating of CSV files as well as exploratory analysis of the generated data including development of a custom CNN model using convolutional layers, maxpooling, dropout and dense layers by hyperparameter tuning resulting the increase in accuracy.

Firstly, coming to the dataset creation, the current repository contains a folder namely:

Dataset_Creation consisting of two python scripts Create_Dataset.py used to capture images, convert_to_csv.py used to generate the dataset i.e, a csv file.
By executing the Create_Dataset.py file, it prompts the user for his/her desired label, number of images to be captured and then starts capturing the required number of images and stores them into a folder with the name previously prompted for. Then by executing the convert_to_csv.py file those collected images can be converted into a CSV file.
