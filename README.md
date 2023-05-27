# Action-Identifier
Developing a CNN and RNN based model to identify the action of a given video

## DataSet used

This model uses the UCF101 action recognition dataset. It contains realisitic action vidios from youtube of  101 action categories.
Due to limited computing power I have used a preprocessed dataset of UCF101 which contains half of the size of the original dataset. It also has limited the length of the videos to 64 frames and seperated them into frames.

**Credits** - Soomro, K., Zamir, A. R., & Shah, M. (2012). UCF101: A dataset of 101 human actions classes from videos in the wild. arXiv preprint arXiv:1212.0402

## Description
I use a combination of CNN(convolutional neural network) and RNN (recurrent neural networks) to recognize the action
CNN - the model uses CNN to extract meaningful features from videos frames. For this model I use a pre-trained CNN model. The pre-trained model I use is InceptionV# from keras library of tenserflow.

After we get the features we get a the output as 2D tensors.

RNN-  the model now uses RNN to process the above tensors and predict the action label.

## Implementation
Run the Breed **.ipynb** file. 
