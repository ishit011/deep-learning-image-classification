# Deep Learning Image Classification

## Project Overview
This project leverages deep learning techniques to classify images from the Stanford Dogs Dataset. A pre-trained ResNet-18 model is fine-tuned to achieve high accuracy in classifying 120 dog breeds.

## Dataset
The Stanford Dogs Dataset was used, containing over 20,000 images of 120 dog breeds. The dataset was split into training, validation, and test sets with an 80/10/10 ratio. Data preprocessing steps included resizing, normalizing, and applying various augmentation techniques.

## Model Architecture
We utilized a pre-trained ResNet-18 model, modifying the final layer to classify the 120 dog breeds. The architecture includes convolutional layers, batch normalization, ReLU activation functions, and fully connected layers.

## Training Process
The model was trained using the Adam optimizer with an appropriate learning rate. Early stopping and other regularization techniques were employed to prevent overfitting.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Results
- **Validation Accuracy**: Achieved a validation accuracy of xx% after 5 epochs.
- **Test Accuracy**: The final test accuracy is xx%.

## Installation
To run this project, you need to install the required dependencies. You can do this by running:
```bash
pip install -r requirements.txt
