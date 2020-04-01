# Image-Captioner
It is a Image Captioning bot trained on flickr image dataset(https://www.kaggle.com/hsankesara/flickr-image-dataset)
which generates the best possible caption for a image describing it.

The model is trained on 2 neural networks, a ANN for training the images and a RNN for training the captions, and then joined by using the decoders.

The 'glove.6B.50d' was used for embedding the words
