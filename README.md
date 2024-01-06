# Emotion Detection from Image using MobileNet

This machine-learning project focuses on detecting emotions in images using a pre-trained MobileNet model with Keras. Please note that the accuracy may not always be perfect.

## Overview:

1. **Model Choice:**
   - Utilized the MobileNet architecture, a pre-trained model available in Keras.

2. **Building the Model:**
   - Since the model comes pre-trained with its weights, the first step involves constructing the neural network.

3. **Data Preparation:**
   - Prepared training and validation datasets to prevent overfitting.
   - Leveraged the `ImageDataGenerator` function from Keras for reading image data.

4. **Implementation of Key Techniques:**
   - Implemented early stopping and best checkpoint strategies.
   - Early stopping avoids unnecessary resource usage by terminating training when accuracy plateaus.
   - The best checkpoint saves the model with the highest accuracy during training.

5. **Testing:**
   - After training, the model is ready for testing with any image.

## Running the Project:

1. **Setup:**
   - Run the `Emotion_detection_from_image.ipynb` file in Google Colab.
   - Make sure to provide the correct path for your input images.

2. **Execution:**
   - Execute the notebook in Colab, ensuring that the Colab environment is mounted.


