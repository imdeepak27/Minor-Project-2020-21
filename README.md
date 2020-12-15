# Minor-Project-2020-21
Deep Learning based project titled - Image Captioning . The Image Captioning Generator Model uses the combination of CNNs and RNNs(specifically LSTMs).
  Caption generation is a challenging artificial intelligence problem where a textual description must be generated for a given photograph.It requires both methods from computer vision to understand the content of the image and a language model from the field of natural language processing to turn the understanding of the image into words in the right order.
A “classic” image captioning system would encode the image, using a pre-trained Convolutional Neural Network(ENCODER) that would produce a hidden state h.
Then, it would decode this hidden state by using a LSTM(DECODER) and generate recursively each word of the caption.
Deep learning methods have demonstrated state-of-the-art results on caption generation problems. What is most impressive about these methods is a single end-to-end model can be defined to predict a caption, given a photo, instead of requiring sophisticated data preparation or a pipeline of specifically designed models.
