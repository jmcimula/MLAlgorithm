#Deep learning for time series and sequence prediction

Time series prediction problems are difficult not least because of the hidden relationships between steps in the input data.

Traditional neural nets can tackle these types of sequence problems, but require a clumsy reframing of the problem with a fixed sliding window.

Alternately, you can use neural nets that have recurrent connections, allowing them to learn the inter-dependencies between the samples in the sequence. 

It is these types of recurrent neural networks that are achieving impressive results like:

- Automatically captioning images with text descriptions.
- Composing new jazz music learned from a corpus of examples.
- Reading and classifying sequences of text.

The most popular example of this type of network is called the Long Short-Term Memory network or LSTM. They do so well as a deep learning method because they can be stacked up like pancakes.