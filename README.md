[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/pininduwk/LipNet/blob/main/LipNet.ipynb)

# LipNet

The LipNet is a deep learning model for lip reading that was proposed by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas from the University of Oxford in 2016. The model uses spatiotemporal convolutional neural networks (CNNs) to learn features from videos of people speaking and then maps these features to corresponding words.

The model takes as input a sequence of 75 video frames of a person speaking and processes each frame using three consecutive convolutional layers. The resulting feature maps are then processed by a recurrent neural network (RNN) with long short-term memory (LSTM) cells. The output of the LSTM is passed through a softmax layer to predict the most likely word.

One unique aspect of LipNet is that it was trained on the GRID corpus, a dataset of 1000 videos of 34 speakers recorded in four different positions and under different lighting conditions. The model achieved an accuracy of 95.2% on the GRID corpus, outperforming previous state-of-the-art lip reading models.

Data:- "https://drive.google.com/uc?id=1YlvpDLix3S-U8fd-gqRwPcWXAXm8JwjL"
