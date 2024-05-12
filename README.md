# Convolutional Autoencoder for Image Denoising

## AIM

To develop a convolutional autoencoder for image denoising application.

## Problem Statement and Dataset

Using autoencoder, we are trying to remove the noise added in the encoder part and tent to get the output which should be same as the input with minimal loss. The dataset which is used is mnist dataset.
![image](https://github.com/obedotto/convolutional-denoising-autoencoder/assets/119390329/5bf609f9-4550-4992-a7a1-292ecacf83c4)

## Convolution Autoencoder Network Model

Include the neural network model diagram.

## DESIGN STEPS

### STEP 1:
Import the necessary libraries and dataset.

### STEP 2:
Load the dataset and scale the values for easier computation.

### STEP 3:
Add noise to the images randomly for both the train and test sets.

### Step 4:
Build the Neural Model using Convolutional, Pooling and Up Sampling layers. Make sure the input shape and output shape of the model are identical.

### Step 5:
Pass test data for validating manually.

### Step 6:
Plot the predictions for visualization.

## PROGRAM

Include your code here

## OUTPUT

### Training Loss, Validation Loss Vs Iteration Plot

Include your plot here

### Original vs Noisy Vs Reconstructed Image

Include a few sample images here.



## RESULT

Thus, a Convolutional Auto Encoder for Denoising was sucessfully implemented.
