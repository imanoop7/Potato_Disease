# Potato Disease Detection using TensorFlow, Keras, and CNN

!Potato Leaf

This repository contains a Jupyter Notebook (`Potato_Disease.ipynb`) that demonstrates how to build an image classification model for detecting potato leaf diseases. By analyzing leaf images, our automated solution enables early disease detection, reducing crop losses and aiding decision-making for farmers.

## Problem Statement

Farmers who grow potatoes suffer from serious financial losses each year due to diseases that affect potato plants. The two most frequent diseases are Early Blight (caused by fungus) and Late Blight (caused by specific microorganisms). Detecting these diseases early and applying appropriate treatment can save a lot of waste and prevent economic loss. Therefore, accurate identification of the disease type in potato plants is crucial.

## Approach

We'll use a Convolutional Neural Network (CNN) architecture to diagnose potato leaf diseases. The steps involved are as follows:

1. **Data Collection**: Collect potato leaf images. You can either use ready-made datasets or manually collect images from farmers and annotate them (healthy leaves, early blight, or late blight).

2. **Model Building**: Train a CNN model using TensorFlow and Keras. The model will learn to classify potato leaves into healthy or diseased categories.

3. **Deployment**: Deploy the model using Streamlit and host it on Heroku. This allows users to upload potato leaf images and receive predictions.

## Dependencies

Make sure you have the following Python libraries installed:

- `tensorflow`
- `keras`
- `numpy`
- `pandas`
- `matplotlib`

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Happy coding! 🌱🥔
