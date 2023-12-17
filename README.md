# DL_Project

# Model
InceptionNetV3 was used as an image encoder to encode the images which were then input in the model.
Keras embedding layer was used to generate word embeddings on the captions which were encoded earlier.
The embeddings were then passed into LSTM after which the image and text features were combined and sent to a decoder network to generate the next word.
