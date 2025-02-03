**Deaf Sign Language Prediction** <br>
This project aims to predict the alphabet (A-Z) from American Sign Language (ASL) gestures by using image processing and machine learning. <br>

**How it Works**

The model takes an input image of a sign language gesture. <br>
It processes the image by converting it into a 28x28 grayscale format. <br>
The processed image is passed through a trained machine learning model, which outputs the corresponding alphabet letter (A-Z) based on the gesture. <br>

**Technologies Used**
1. Python
2. CNN
3. TensorFlow/Keras

**Process**

**Image Preprocessing**: Before feeding the image into the CNN, you resized it to 28x28 pixels and possibly converted it to grayscale to standardize the input size and reduce computational complexity. <br>

**Feature Extraction**: The convolutional layers in the CNN apply filters to detect features like edges, corners, and textures from the input image. <br>

**Classification**: After the feature extraction, the CNN passes the image through one or more fully connected layers, which help predict the letter corresponding to the hand gesture in the image.
