# What is Deep Learning?
is a branch of Machine Learning that focuses on using multi-layered artificial neural networks (Deep Neural Networks) to mimic how the human brain processes information and recognizes complex patterns.


# Features of Deep Learning:

 * It can learn complex representations directly from raw data (such as images, audio, text) without much human intervention in feature extraction.

 * Uses many layers (deep) of interconnected neurons that process information sequentially.

 * Applied in tasks like image recognition, machine translation, speech analysis, and autonomous driving.

![deep learning](../images/deeplearning.png)



## History Deep Learning

![deep learning](../images/history_deeplearning.png)



## Deep Learning Algorithm:

1-Images and Videos:

 * Usually, Convolutional Neural Networks (CNNs) are used because they are excellent at detecting patterns in images and videos.

 * Videos are considered sequences of images, so CNNs can be combined with temporal models to handle the time dimension.

2-Speech and Text:

 * For these, models that handle **sequential data** like Recurrent Neural Networks **(RNNs)**, especially LSTM, are used because they can manage long-term temporal relationships.

 * Also, Transformers have become very popular recently for analyzing text and speech.


![algorithm](../images/algorithm_dl.png)


## What is an ANN?

Imagine a large network of tiny cells (like brain cells).
Each tiny cell is called a "neuron."
These neurons are connected to each other in layers.




## What does Deep Learnig do?

First, it takes information or data (for example, an image or text).

Then, this data moves from one layer to another.

Each layer processes the data using numbers called weights and **BIAS** to understand parts of the data.

In the end, it produces a result (for example, it says whether the image contains a cat or a dog)



![ANN](../images/ANN.png)



## What RNN (Recurrent Neural Network)?

It is a type of neural network specifically designed to handle sequential or time-ordered data, such as text, speech, or time series.

One key feature of RNN is the feedback loop:
This loop allows the network to retain information from previous steps and use it when processing the current input, enabling the model to understand context and dependencies over time.



![RNN](../images/RNN_define.png)


## Types of RNN Architecture:
1. One-to-One
   * Simple type.

   * One input → One output.

   * Example: Image classification (not really an RNN case, but for comparison).


2. One-to-Many
   * One input → Multiple sequential outputs.

   * Example: Image captioning (generating a sequence of words from one image).


3. Many-to-One
   * Multiple sequential inputs → One output.

   * Example: Sentiment analysis (classifying a sentence as positive or negative).


4. Many-to-Many
   * Multiple sequential inputs → Multiple sequential outputs.

   * Example: Machine translation (translating a full sentence to another language).

![types RNN](../images/types_rnn.png)



## What is LSTM?

It’s a special type of Recurrent Neural Network (RNN) designed to better remember information over long sequences and avoid the problem of forgetting important details too quickly.


## Why is LSTM important?

Traditional RNNs struggle with vanishing gradients, making it hard to learn long-term dependencies.

LSTM uses gates (input, forget, and output gates) to control what information to keep, update, or forget.

This lets LSTM remember relevant information for longer periods and ignore irrelevant or old data.


## Where is it used?

Speech recognition

Language modeling and translation

Time series prediction

Any task involving sequential data with long-range dependencies


## What differance between RNN,LSTM?

   * RNN works well with short sequences but tends to forget quickly with long data.

   * LSTM not only retains important information for a long time but also removes repeated or unnecessary information using forget gates, making it better at handling long and complex sequences.


   
![Lstm](../images/working_LSTM.png)

