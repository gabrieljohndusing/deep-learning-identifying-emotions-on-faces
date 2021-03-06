# GA-TOR-Jabberwocky-Capstone-Project

## Contents

- [Introduction](#introduction)
  - [Problem Description](#problem_description)
  - [Motivation](#motivation)
- [Tooling](#tooling)
  - [Links to Tools](#tooling_links)
- [Goals, Methodology, and Success Criteria](#goals)
- [Training Data](#training-data)

## [Introduction](#introduction)

This repository contains the notebooks and training data used to build the model used in the accompanying Flask application.
The repo for the actual application can be found [by following  this link](https://github.com/gabrieljohndusing/GA-TOR-Jabberwocky-Capstone-App).

### [Problem Description](#problem_description)

I built a model that classifies images of faces based on their displayed emotion.

### [Motivation](#motivation)

Some applications of emotion detection include:

- Helping people with visual impairment identify emotions
- Detecting alertness in drivers and pilots
- In market research, to identify consumer sentiment when engaging with a product

## [Tooling](#tooling)

For modeling, Keras and Tensorflow were used. Keras is a Python based, deep-learning API that runs with Tensorflow in the backend. Interactivity is provided through the [Flask application](https://github.com/gabrieljohndusing/GA-TOR-Jabberwocky-Capstone-App).
When the user uploads an image using the Flask app, the image is processed using OpenCV2.

### [Links to Tools](#tooling_links)
- [Keras](https://keras.io/about/)
- [Tensorflow](https://www.tensorflow.org/)
- [Flask](https://flask.palletsprojects.com/)
- [OpenCV](https://docs.opencv.org/master/d6/d00/tutorial_py_root.html)

## [Goals, Methodology, and Success Criteria](#goals)

The project is complete and successful when there is an application hosted on Heroku that:
- Takes an uploaded image containing a single face

- Returns probabilities of what emotions the face is portraying
  - The success of the project depends on how accurate the probabilities are.
  - i.e. The emotion with the highest probability corresponds to the actual emotion the face is portraying.
  
I intend to build a convolutional neural network for my model in Keras.

## [Training Data](#training-data)

Training data was obtained from Kaggle's "[Challenges in Representation Learning: Facial Expression Recognition Challenge](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/overview)"