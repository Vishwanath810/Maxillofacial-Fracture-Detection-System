# Transfer Learning for an Automated Detection System of Fractures in Patients with Maxillofacial Trauma

## Overview

This project presents an AI-powered fracture detection system designed to identify maxillofacial fractures from CT scan images using Deep Learning and Transfer Learning techniques. The system assists radiologists by providing fast and accurate fracture classification, helping reduce manual effort and diagnostic errors.

The model uses a pre-trained ResNet50 Convolutional Neural Network (CNN) architecture for feature extraction and classification. The system classifies CT scan images into two categories:

* Fracture
* No Fracture

---

## Features

* Automated fracture detection from CT scan images
* Transfer Learning using ResNet50
* Image preprocessing and normalization
* High accuracy fracture classification
* Real-time prediction support
* User-friendly GUI using Tkinter
* Accuracy graphs and confusion matrix visualization

---

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn
* Tkinter

---

## System Architecture

1. CT scan images are collected as input data.
2. Images are preprocessed using resizing and normalization.
3. ResNet50 extracts deep features from images.
4. Transfer Learning is applied to train the model.
5. The trained model classifies images as Fracture or No Fracture.
6. Results are displayed through a graphical interface.

---

## Dataset

The dataset consists of labeled CT scan images categorized into:

* Fracture
* No Fracture

The images are preprocessed before training to improve model performance and accuracy.

---

## Model Used

### ResNet50

ResNet50 is a pre-trained deep learning model widely used for image classification tasks. It uses residual learning to improve training performance and avoid vanishing gradient problems.

Why ResNet50?

* High accuracy in image classification
* Efficient feature extraction
* Faster training using transfer learning
* Performs well with limited medical datasets

---

## Results

The proposed system achieved high accuracy in detecting maxillofacial fractures from CT scan images. Performance evaluation was carried out using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Project Workflow

* Upload Dataset
* Preprocess Images
* Train ResNet50 CNN Model
* Evaluate Model Performance
* Predict Fracture from Test Image

---

## Future Enhancements

* Improve dataset size for better generalization
* Deploy as a web-based application
* Add support for other fracture types
* Integrate real-time hospital diagnostic support
* Improve prediction accuracy using advanced architectures

---


## Conclusion

This project demonstrates the effectiveness of Transfer Learning and Deep Learning in medical image analysis. The proposed automated fracture detection system helps improve diagnostic accuracy, reduce radiologist workload, and support faster clinical decision-making.

---

## Authors


Shaik Fasi,
N. Sai Vishwanath Reddy,
P. Poojitha,
K. Vivek Raju

---

## License

This project is developed for academic and educational purposes.
