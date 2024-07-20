# Image Caption Generator with CNN-LSTM Network

This project implements a model to generate captions for images using a combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks.

## Project Information

This project aims to predict captions describing the content of an image. The model is trained on the Flickr8k dataset, containing 8,000 images with 5 captions each.

## Dataset

* **Source:** Flickr8k ([https://www.kaggle.com/adityajn105/flickr8k](https://www.kaggle.com/adityajn105/flickr8k))
* **Size:** 8,000 images with 5 captions per image

## Model Architecture

* **Image Features:** Extracted using a pre-trained VGG16 CNN.
* **Text Features:** Extracted and processed using Natural Language Toolkit (NLTK).
* **Combined Features:** Concatenated image and text features for prediction.
* **Sequence Prediction:** LSTM network predicts the next word in the caption sequence.

## Libraries

* numpy
* matplotlib
* keras (with TensorFlow backend)
* nltk

## Next Steps

* Explore different hyperparameter configurations for potentially improved BLEU scores.
* Experiment with advanced image feature extraction techniques.
* Integrate the model into a real-world image captioning application.

**Feel free to explore the project code for further details!**
