# Cervical Spine Fracture Detection Project
Contributors: Peter, CJ, Omar, Raph

Welcome to our project on Cervical Spine Fracture Detection, inspired by the RSNA 2022 Cervical Spine Fracture Detection competition 1st place subbmision on Kaggle. This project aims to leverage advanced machine learning models to accurately detect cervical spine fractures from CT scans.

## Project Goals

- **Objective:** Develop and validate models to identify fractures in CT scans of the cervical spine.
- **Datasets:** Utilize comprehensive datasets consisting of CT scans with and without cervical spine fractures, similar to the dataset provided in the RSNA competition.
- **Models:** Implement state-of-the-art deep learning models to achieve high accuracy in fracture detection.

## Data

The data for this project includes CT scans of the cervical spine. These scans are annotated to indicate the presence of fractures at both the individual vertebra and patient level. The original dataset from the RSNA competition consists of thousands of CT scans collected from multiple institutions.

## Methods

1. **Data Preprocessing:** Standardize and preprocess the CT scan images for input into the machine learning models.
2. **Model Training:** Train various convolutional neural networks (CNNs) and other deep learning architectures to detect fractures.
3. **Model Evaluation:** Evaluate the models using metrics such as accuracy and Intersection Over Unioun.

   ## Models Used

### MaNet
MaNet (Multiscale Attention Network) is a model designed to capture features at multiple scales using attention mechanisms. It enhances feature representation by focusing on relevant parts of the image, making it particularly useful for detecting subtle fractures in CT scans.

### ResNet
ResNet (Residual Network) is known for its deep architecture, which uses skip connections to prevent the vanishing gradient problem. This allows the network to be very deep (e.g., ResNet-50, ResNet-101) and effectively learn complex features from the images.

### VGG
VGG (Visual Geometry Group) networks are deep CNNs characterized by their simplicity and use of small (3x3) convolutional filters. VGG models, like VGG-16 and VGG-19, have been successful in various image recognition tasks and are used here to detect spinal fractures.

### YOLO (You Only Look Once)
Our new approach integrates YOLO, a state-of-the-art object detection model known for its speed and accuracy. YOLO divides the image into a grid and predicts bounding boxes and probabilities for each grid cell. This approach is particularly effective for real-time detection of fractures in CT scans.


## Challenges

- **Large File Sizes:** The models developed in this project exceed 100MB in size and therefore could not be uploaded directly to GitHub. Instead, we have hosted these models on Google Drive.

## Accessing the Models

The trained models can be accessed and downloaded from the following Google Drive link:

[Download Trained Models](https://drive.google.com/drive/folders/1dTxO27AQ2lnnRvcBz5E-hwhhwQ-mM300?usp=sharing)

## How to Run the Code

**Clone the Repository:**
   ```sh
   git clone https://github.com/CPD9/MALDASC.F2401.git
   cd MALDASC.F2401
