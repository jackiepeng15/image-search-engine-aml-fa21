# image-search-engine-aml-fa21
An image search engine that returns from a database of 2,000 images the top 20 relevant images given a natural language query.

# Information
Find in the .ipynb files a neural network, random forest, and ridge regression prediction model, respectively.

With the neural network, I was able to improve image selection accuracy by 90% from a baseline ridge regression model. Here, I trained a 3-layer neural network using Keras, processing text using a word2vec word embedding model, and tagging image vectors extracted using a pre-trained ResNet.
