# Weather-image-recognition
This is the repository showcasing the presentation for project "Weather Image Recognition". Please check the pdf file "Weather image recognition project.pdf" to see the experiment results.

# Team member:
- Yiheng Ye
- Scott He
- Debalina Chowdhury
# Problem:
How to train specialized CNN models on complex real-world weather image recognition  dataset and improve the prediction accuracy.  In other words, we want to make better CNN models that can be used under actual images that include other objects (cars, houses, trees, etc.) to classify the current weather in a given image. Furthermore, there are also some irrelevant elements in the image collected like watermark, and we want our model to work through those interferences as well.
# Data:
Weather Image Recognition:
https://www.kaggle.com/jehanbhathena/weather-dataset
# Proposed solution:
We try to improve the original VGG16 model by changing some of its layer structures. 
That is to say, we are going to modify the VGG16 model and add our own architectures. 
The methods we are going to try include changing the activation functions (ReLU) and 
adding average pooling layers similar to MeteCNN.
# Experiments:
We will work on only part of the images mentioned in the above data set to reduce our classification workload. We will use weather images of certain labels we selected to train and validate our models.
1.  Using simple CNN networks as baseline
2. Trying to run our datasets on VGG16 models
3. Running our datasets on MeteCNN models
4.  Running our datasets on the new CNN architectures 
5.  Tuning our models on different sets of hyperparameters.

# References:
[1] Haixia Xiao,Feng Zhang,Zhongping Shen,Kun Wu,Jinglin Zhang (2021) , Classification of  Weather Phenomenon From Images by Using Deep Convolutional Neural Network
https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2020EA001604

[2] Simonyan, K., & Zisserman, A. (2014). Very deep convolutional networks for large-scale image recognition. In Computer Vision and Pattern Recognition. arXiv preprint arXiv:1409.1556
