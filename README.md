# DL- Developing a Neural Network Classification Model using Transfer Learning

## AIM
To develop an image classification model using transfer learning with VGG19 architecture for the given dataset.

## THEORY


## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 
Import required libraries and define image transforms.

### STEP 2: 
Load training and testing datasets using ImageFolder.


### STEP 3: 
Visualize sample images from the dataset.


### STEP 4: 
Load pre-trained VGG19, modify the final layer for binary classification, and freeze feature extractor layers.


### STEP 5: 
Define loss function (CrossEntropyLoss) and optimizer (Adam). Train the model and plot the loss curve.


### STEP 6: 
Evaluate the model with test accuracy, confusion matrix, classification report, and visualize predictions.




## PROGRAM

### Name: Saranya V

### Register Number: 212223040188

```python
# Load Pretrained Model and Modify for Transfer Learning



# Modify the final fully connected layer to match the dataset classes



# Include the Loss function and optimizer



# Train the model


```

### OUTPUT

## Training Loss, Validation Loss Vs Iteration Plot


<img width="793" height="663" alt="image" src="https://github.com/user-attachments/assets/936bf38e-b285-4ff3-aba1-dd9b7a6d94b6" />


## Confusion Matrix

<img width="740" height="685" alt="image" src="https://github.com/user-attachments/assets/bea0c729-2a51-42b3-b635-082e6b5702a9" />


## Classification Report

<img width="748" height="259" alt="image" src="https://github.com/user-attachments/assets/aae1e41f-86b1-4337-9dd1-fbcb64b2cdc8" />


### New Sample Data Prediction

<img width="406" height="450" alt="image" src="https://github.com/user-attachments/assets/bfeac4d9-b7af-498d-a71e-6f015fa29515" />

<img width="386" height="452" alt="image" src="https://github.com/user-attachments/assets/a50861b4-171b-4137-9464-6480e1507fe7" />


## RESULT
Developing a Neural Network Classification Model using Transfer Learning was successfully implemented.
