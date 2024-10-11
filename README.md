## Machine Learning Course Project
# Plant Disease Detection Using Machine Learning

## Overview

Plant diseases cause low agricultural productivity. Plant diseases  are challenging to control and identify by the majority of farmers. In  order  to reduce future losses, early disease diagnosis is necessary. This study presents a deep learning approach for detecting tomato leaf  diseases  using Convolutional Neural Networks (CNNs). The proposed method involves preprocessing the tomato leaf images, followed by training the CNN model to classify them into one of ten categories: healthy, yellow leaf curl virus (YLCV), bacterial spot (BS), early blight (EB), leaf mold (LM), Septoria leaf spot (SLS) target spot (TS), two spotted spider mite spot(TSSMS), mosaic virus(MV) and late blight (LB). The model was trained using a dataset of 16021 tomato leaf images. The training was conducted for 2 epochs, 5 epochs and the accuracy achieved was 64%, 89% respectively.  These results demonstrate the effectiveness of the proposed approach in detecting tomato leaf diseases, and the performance improves with increasing epochs. The automated approach can aid in the early detection and prevention  of tomato diseases, which can ultimately help in improving the yield and quality of tomato crops.


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Training the Model](#training-the-model)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)


## Features

- **Image Classification**: Classifies plant images into healthy or various diseased categories.
- **User-Friendly Interface**: Simple web or command-line interface for uploading images.
- **Real-Time Detection**: Quickly identifies diseases in plant images.
- **Extensible**: Easily add new diseases or improve existing models.

## Technologies Used

- Python
- TensorFlow/Keras or PyTorch
- OpenCV
- Flask or Streamlit (for web interface)
- Scikit-learn
- Jupyter Notebook (for development)

## Installation

To get started with the project, clone the repository and install the required dependencies.

```bash
git clone https://github.com/yourusername/Plant-Disease-Detection-using-ML.git
cd Plant-Disease-Detection-using-ML
pip install -r requirements.txt
```

## Usage

1. **Prepare Your Dataset**: Ensure your images are organized in folders based on their categories (healthy and various diseases).
2. **Train & Test the Model**: Run the training script to build your model.
3. **Upload Images**: Use the web interface to upload plant images for disease detection.

## Dataset

This project uses publicly available datasets for plant disease classification.

## Output
![Screenshot 2024-08-18 165549](https://github.com/user-attachments/assets/3887396f-43b4-4764-8c34-e2c7556959e2)
### Fig1. Upload Image file in jpg/jpeg Format to Predict disease

![Screenshot 2024-08-18 165625](https://github.com/user-attachments/assets/3620949f-22e3-4014-bdb5-b16d16291e16)
### Fig2. Predicting the accuracy and exact disease
