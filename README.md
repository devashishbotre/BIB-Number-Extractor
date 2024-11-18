# BIB-Number-Extractor
This project is made for automated race results by identifying unique BIB number given to each participant which helps in player tracking and time calculations. This project contains Yolov11 architecture for the detection of bib number and Keras-OCR for extracting numbers.
# Dataset Description
The dataset used in this project comprises three subsets:

Training Set:

Contains images and corresponding label files.
Label files provide bounding box coordinates and the single class ("BIB").
Validation Set:

A smaller portion of the dataset for evaluating model performance during training.
Test Set:

Contains unseen images used for testing the trained model.
