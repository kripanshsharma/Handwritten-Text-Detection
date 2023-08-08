# Handwritten Text Recognition System
TensorFlow (TF)-based Handwritten Text Recognition (HTR) system developed, trained using IAM off-line HTR dataset. The model produces the recognized text after receiving input in the form of images of single words or text lines (many words). Character error rate is 10%, and 3/4 of the words in the validation-set are correctly identified.

What remains is the bare minimum to recognize text with an acceptable accuracy.

It consists of 5 CNN layers, 2 RNN (LSTM) layers and the CTC loss and decoding layer.
For more details see this [Medium article](https://towardsdatascience.com/2326a3487cd5).

## References
* [Build a Handwritten Text Recognition System using TensorFlow](https://towardsdatascience.com/2326a3487cd5)
* [Scheidl - Handwritten Text Recognition in Historical Documents](https://repositum.tuwien.ac.at/obvutwhs/download/pdf/2874742)
* [Scheidl - Word Beam Search: A Connectionist Temporal Classification Decoding Algorithm](https://repositum.tuwien.ac.at/obvutwoa/download/pdf/2774578)
