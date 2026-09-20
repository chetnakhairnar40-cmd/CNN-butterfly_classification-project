# CNN-butterfly_classification-project
classification of butterfly using CNN
# Butterfly Image Classification Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to
classify butterfly images into different categories.

The model is developed using Python and TensorFlow/Keras.
It processes images, learns visual features, and predicts
the butterfly category of a given image.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Features
- Image preprocessing and normalization
- Image resizing to 64x64 pixels
- CNN model development
- Image classification using Softmax
- Training and validation
- Single image prediction
- Prediction confidence display

## CNN Model Architecture
- Convolutional Layer (32 filters, ReLU)
- Max Pooling Layer
- Convolutional Layer (32 filters, ReLU)
- Max Pooling Layer
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Output Layer (Softmax)

## Model Configuration
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Batch Size: 32
- Epochs: 10
- Image Size: 64x64

## Project Structure
CNN-Butterfly-Classification/
│
├── CNN project 3.ipynb
├── dataset/
│   ├── train/
│   ├── test/
│   ├── Training_set.csv
│   ├── Testing_set.csv
│   └── single_prediction/
│
├── README.md
├── LICENSE
└── .gitignore

## How to Run
1. Clone or download this repository.
2. Install the required libraries.
3. Ensure the dataset is organized as expected.
4. Open the notebook in Jupyter Notebook.
5. Run the cells to train the CNN model.
6. Test the model using a butterfly image.

## Learning Outcomes
- Understanding CNN architecture
- Image preprocessing and normalization
- Training an image classification model
- Making predictions using a trained CNN
- Gaining practical Deep Learning experience

## Author
Chetna Khairnar
