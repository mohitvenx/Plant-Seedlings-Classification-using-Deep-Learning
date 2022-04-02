# Plant-Seedlings-Classification-using-Deep-Learning
# Final Project of Computer Vision with Deep Learning PESU-I/O
# Team Members

1. Mohit Venkatesh

2. Ashish A Iyer

3. Sujith Bonthala
 
We have taken a Plant Seedlings Classification dataset that classifies 12 different varieties of plant seedlings. They are as follows:

1. Black-grass
2. Charlock
3. Cleavers
4. Common Chickweed
5. Common Wheat
6. Fat Hen
7. Loose Silky-bent
8. Maize
9. Scentless Mayweed
10. Shepherds Purse
11. Small-flowered Cranesbill
12. Sugar Beet

# Applications of our model

Our model can be used by nature-friendly people who visit farms and nurseries, where they can figure out the plant species at its seedling stage by using our model. It can also be used by the cultivators to see if there is much difference between their plant seedlings and the actual plant seedlings of a particular class in our dataset by checking the accuracy and hence determining the quality of the plant seedlings.

# Architecture of our model
Our model uses a InceptionResNetV2 pretrained model in replacement for CNN. We have added a GlobalAveragePooling2D layer to reduce the dimensionality of the images, following which we have added 5 Dense layers, 4 of which have an activation of 'relu' and the other having 'softmax' activation'. The model is then compiled with optimizer to be 'adam' and loss function to be 'categorical_crossentropy'.

# Approach to increase accuracy
Our method of approach to increase accuracy was by using Data Augmentation and by increasing the number of layers in the neural network.

Current Training Accuracy	90.43%

Current Validation Accuracy 86.30%

Current Training Loss 0.2422	

Current Validation Loss 0.4068
# How to use our Model
To run the code and classify your image, copy the code from GUI.py and download Saved_Model folder from the Google Drive link at the end of this README.md file. Note that the python file and the Saved_Model folder must belong to the same directory.

Link to the Saved_Model folder - https://drive.google.com/drive/folders/1ddCXen9sAn-xsIUTgo0TjdOnzrYJEt1m?usp=sharing
