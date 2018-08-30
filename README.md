# contento

## Keras
Why are we using Keras? Keras was developed to enable deep learning engineers to build and experiment with different models very quickly. Just as TensorFlow is a higher-level framework than Python, Keras is an even higher-level framework and provides additional abstractions. Being able to go from idea to result with the least possible delay is key to finding good models. However, Keras is more restrictive than the lower-level frameworks, so there are some very complex models that you can implement in TensorFlow but not (without more difficulty) in Keras. That being said, Keras will work fine for many common models.

## The Problem
For your next vacation, you decided to spend a week with five of your friends from school. It is a very convenient house with many things to do nearby. But the most important benefit is that everybody has commited to be happy when they are in the house. So anyone wanting to enter the house must prove their current state of happiness.

As a deep learning expert, to make sure the "Happy" rule is strictly applied, you are going to build an algorithm which that uses pictures from the front door camera to check if the person is happy or not. The door should open only if the person is happy.

You have gathered pictures of your friends and yourself, taken by the front-door camera. The dataset is labbeled.

![Happy house members](https://raw.githubusercontent.com/themousepotato/contento/master/images/house-members.png)

## The Pipeline
![Pipeline](https://raw.githubusercontent.com/themousepotato/contento/master/images/HappyModel.png)

## Model Summary
![Model Summary](https://raw.githubusercontent.com/themousepotato/contento/master/images/model-summary.png)

## Results
Our model gets around 95% test accuracy in 40 epochs (and 99% train accuracy) with a mini batch size of 16 and "adam" optimizer.
