# Guided Project: Object Localization Model with TensorFlow
## Main Objective:
The goal of this project is to create and train an object localization model with TensorFlow, using the Keras API. The model will focus on localizing and classifying emojis in images. Specifically, the task is to predict the position of the emoji in the image by determining the bounding box coordinates around the emoji
## Approach:
In this project, we will build a Convolutional Neural Network (CNN). The model will be capable of:

Classifying the emoji in the image.

Localizing the emoji by predicting its coordinates (bounding box position).

Localization refers to the model's ability to predict the position of the object in the image, which is crucial for the task of Object Localization.
## Comparison with Object Detection:
While Object Localization might seem similar to Object Detection, there is a key difference:

Object Detection: The model predicts multiple objects in an image and provides both the class (what it is) and the bounding box (where it is located) for each object.

Object Localization: In this task, it is assumed there is only one object in the image (in this case, the emoji), and the model must predict both the class (emoji) and the bounding box coordinates.
