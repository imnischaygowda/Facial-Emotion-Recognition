# Face Emotion Recognition - DeepCNN Python
 
![Python](https://forthebadge.com/images/badges/made-with-python.svg)       <a href="https://medium.com/nerd-for-tech/face-emotion-recognition-deepcnn-python-a710b05f560"><img src="https://img.shields.io/badge/medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" height=35></a>



Emotion Recognition using Tensorflow, simple and easily understandable code.

## Introduction

  The most common application of CNN in Computer Vision technology is Image processing. Given the images as input, RGB or BW, we use underlying the pixel data to extract specific information, based on the given label. We then train a CNN network.

  If you are just getting started into Computer Vision, the simplest problem to work on would be, Cat and Dog classifier, which you study [here](https://medium.com/r/?url=https%3A%2F%2Ftowardsdatascience.com%2Fcnn-classification-a-cat-or-a-dog-568e6a135602).
  
---
 
## Problem statement
  
  The task at hand is to build a Face emotion recognition model, in simple terms an Emotion Classifier, from a given Image input. You can find more details of the Problem and the dataset [here](https://medium.com/r/?url=https%3A%2F%2Fwww.kaggle.com%2Fashishpatel26%2Ffacial-expression-recognitionferchallenge).

---

## Data Overview

The given data consists of, (35887, 3) datapoints rows and 3 column features.
1. **emotion** - numerical value to indicate the type of emotion, 0–2 being negative, 3–5 being positive and 6 indicates neutral emotion.

2. **Pixels** - represents the pixel coordinate point of the image.

3. **usage** - data split

emotion label - **'anger'**,  **'disgust'**, **'fear'**, **'happiness'**, **'sadness'**, **'surprise'**, and **'neutral'**.
