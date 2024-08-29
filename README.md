# Oral_cancer_prediction
Oral Cancer Prediction Using Hybridized Neural Network Model
<br><br>

**About the Project**

This project aims to develop a hybridized neural network model integrating Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) for the accurate prediction and classification of oral cancer. By leveraging the spatial feature extraction capabilities of CNNs and the sequential pattern recognition strengths of RNNs, the model enhances the early detection and treatment outcomes for oral cancer, ultimately improving patient care.
<br><br>
**Features**

**Hybrid Model:** Combines CNNs for spatial feature extraction and RNNs for sequential pattern analysis to predict oral cancer from histopathological images.

**EfficientNet Backbone:** Utilizes EfficientNet as a pre-trained base model for feature extraction, followed by additional layers for robust prediction.

**Real-Time Prediction:** Capable of real-time prediction with a user-friendly interface for medical professionals.

**Data Management:** Securely stores patient data, including medical images, in a database with efficient retrieval and management capabilities.

<br><br>
**System Architecture**

**EfficientNetB3** Pre-trained Model: Used as the base model for feature extraction.

**LSTM Layer:** Processes sequences of features for temporal dependency capture.

**Fully Connected Layers:** Includes dense layers with dropout for regularization, optimized with Adam optimizer.

**Final Output:** Softmax activation function provides the probability distribution over the classes for classification.
![new](https://github.com/user-attachments/assets/6853644c-1da8-4d09-851e-9c9fe86ac968)


<br><br>
**Presentation**
The project is presented as part of a VI Semester Mini Project Evaluation in the Department of Computer Science and Engineering, focusing on the integration of advanced machine learning techniques for improving oral cancer detection.

[final_review_ppt[1]-Only.pptx](https://github.com/user-attachments/files/16803103/final_review_ppt.1.-Only.pptx)

<br><br>
**Getting Started**

**Prerequisites**

Python 3.7+

pip (Python package installer)

Required Python packages:

pandas

tensorflow

itertools

seaborn

numpy

cv2

pathlib

shutil


<br><br>
**Installation**

Clone the repository:git clone https://github.com/yourusername/oral-cancer-prediction.git

Navigate to the project directory:cd oral-cancer-prediction

Install the required packages

Run in google colab then u will get weights put that weights to particluar folder where u have cloned then use that to predict.

Run backend first using npm start (we have reat technology).

After that run the frontent using npm start.

<br><br>
**Usage**

**Data Input and Preprocessing:** Upload and preprocess histopathological images.

**Model Training:** Train the hybrid CNN-RNN model on the preprocessed data.

**Prediction**: Use the trained model to predict and classify new images in real-time.

**User Interface:** Access the web-based interface to upload images and view prediction results.

<br><br>
**Results**

The proposed hybrid model achieved an accuracy of 98.29% over 36 epochs, outperforming other models such as AlexNet-ELM, TBNet, and standalone CNN models. The project demonstrates the enhanced predictive capability of combining CNNs and RNNs, particularly for complex medical image analysis tasks.

![Picture1](https://github.com/user-attachments/assets/880436af-4f68-4668-ab33-90a19cdcb53f)
<br><br>

![nPicture2](https://github.com/user-attachments/assets/f63b5000-04eb-4bea-ae55-b568e04abb92)

![Picture2](https://github.com/user-attachments/assets/6c86e540-44b1-4233-a1ac-db7498b4bd6f)

