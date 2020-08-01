# Gesture Classifier

This repository is a demo gesture classifier using fastai framework. It aims to determine if a gesture is positive or negative.

The dataset for train and validation was built using Google Images and the test dataset was made by me and the collaboration of some friends.

There are two classes:
THUMBSUP representing the positive gestures and THUMBSDOWN representing negative gestures.

The model used is the ResNet152. A complex model for a complex dataset.

# Usage:

I assume that you will use Google Colab to run the classifier.
So, for that there are some simple steps:

1) Download the Datasets "Data.rar" and "testData" and then, upload it to your Google Drive inside 'My Drive'.
2) Open the notebook on Google Colab. There is a link on the file "GesturesCalssification.ipynb" that will redirect to there.
3) Connect to a Runtime and set the notebook for GPU usage: RunTime >> Change Runtime type >> and on Hardware Accelerator, select GPU.
4) Follow the steps explained on the notebook to run training and prediction processes
