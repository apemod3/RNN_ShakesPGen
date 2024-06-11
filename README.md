# RNN_ShakesPGen
This repository contains a Python script for generating text using a pre-trained recurrent neural network (RNN) model trained on Shakespearean text data. The script utilizes TensorFlow and Keras libraries for model creation, training, and text generation.

The script begins by loading Shakespeare's text data from an online source and preprocessing it to convert characters to lowercase and create dictionaries for character indexing. The data is then used to train an LSTM-based neural network model. However, the training section is commented out in the script, assuming that the model has been trained and saved previously.

After loading the pre-trained model, the script defines functions for generating text based on the learned patterns. The generate_text function takes parameters for the length of the generated text and a "temperature" parameter to control the randomness of the generated text.

Finally, the script provides examples of generating text with different temperature values, showcasing the variety and creativity of the generated text.

To use the script, ensure that TensorFlow and Keras libraries are installed, and a pre-trained model file named 'textgenerator.h5' is available in the repository.

Note: The commented-out training section suggests that the model training process may have been conducted separately and is not included in this script.
