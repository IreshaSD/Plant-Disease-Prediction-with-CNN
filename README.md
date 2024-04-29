# Plant-Disease-Prediction-with-CNN

This project utilizes Convolutional Neural Networks (CNNs) to predict plant diseases from images. It offers an end-to-end solution for detecting diseases in plant leaves, aiding farmers and agricultural experts in early disease detection and management.

### Features:

  1.  Data Curation: The project includes code for downloading and preprocessing a dataset of plant images using the Kaggle API. The dataset comprises images of various plant diseases and healthy plants.
  2.  Model Training: A CNN model is trained on the curated dataset using TensorFlow and Keras. The model learns to classify images into different classes corresponding to various plant diseases or healthy states.
  3.  Model Evaluation: The trained model's performance is evaluated using validation data to assess its accuracy and generalization ability.
  4.  Prediction System: Upon training and evaluation, the model is saved and integrated into a prediction system. This system allows users to input images of plant leaves and receive predictions about the presence 
  of diseases.

### Usage:

  1.  Training the Model: Run the provided code to train the CNN model on the dataset. Ensure proper configurations and dependencies are in place before starting the training process.
  2.  Model Evaluation: After training, evaluate the model's performance using the validation data. This step helps gauge the model's accuracy and identify potential areas for improvement.
  3.  Prediction System: Once the model is trained and evaluated, integrate it into the prediction system. Users can then utilize the system to predict plant diseases from input images.

### Dependencies:

  1.  Python 3.11.9
  2.  TensorFlow
  3.  Keras
  4.  Streamlit 
  5.  Pillow
  6.  Matplotlib

### Dataset:
The dataset used for training and evaluation is sourced from the PlantVillage Dataset on Kaggle. It consists of images of various plant diseases and healthy plants across multiple plant species.
