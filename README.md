Aksara - README
Aksara is a project that uses Keras as its model, Mediapipe to identify joint movement, and OpenCV to show our image. This project has two directories:

dataset: In this directory, we store the images that we capture from the Mediapipe joint detection by pressing the 's' key to save new datasets. Currently, we only take three datasets, which are A, B, and C.

model: Here, we put our model that has been trained using Teachable Machine by Google.

To run this code, there are two files:

datacollection.py: This file is used to collect the dataset for our model. Press 's' after running the code, and then the image will be saved to the directory that is set on line 13.

Main.py: This file is where the model is being implemented.

To use this code, you can fork it to your Python editor. We recommend using PyCharm.

Steps to run this code:

Fork the code to your Python editor (PyCharm is recommended).

Run the datacollection.py file to collect the dataset for the model. Press the 's' key to save new datasets.

Run the Main.py file to implement the model.

We hope this project will be useful for those who want to learn about using Keras, Mediapipe, and OpenCV. If you have any questions, please contact us at [danishfitri131@gmail.com].
