# MNIST Continual Learning (CNN)

the other two implementations was mine befor with normal Neural network and CNN to see the difference 
with actually hand written generalized with my hand note of letter 6, the other one with
file name: /Mnist_cnn_continual.ipynb include my major task I have use locally permuted mnist dataset 
whcih made from my previous normal mnist dataset

the task demonstrates catastrophic forgetting on MNIST using a CNN and compares three strategies:
- No mitigation
- Rehearsal (replay buffer)
- Regularization (EWC-style penalty)

## Main notebook
- [CNN/Mnist_cnn_continual.ipynb](CNN/Mnist_cnn_continual.ipynb)

I used 2 method of metrics :
  - the 1st is Average accuracy which is (Accuracy Task A + Accuracy Task B) /2
  - the other is forgotting metrics which i show how much the model is forgetting the past
    Task A after trained on Task B
