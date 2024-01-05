# Text-Mining Project

This text mining project aims to perform named entity recognition. The project was carried out in collaboration with 3 university colleagues.

The dataset used in our project is “wikigold.conll.txt”, a manually annotated collection of Wikipedia text. The dataset follows the Conll-03 format, which serves as a reference for named entity recognition.

After conducting explanatory analysis to better understand the data we would be working with, we opted for a Neural Network approach. 
In the project, to achieve better results, we employed the concept of transfer learning.
Initially, we decided to employ recurrent neural network models, specifically LSTM and Bidirectional-LSTM. This choice was made because these models address the well-known issue of vanishing gradients that affects traditional recurrent neural network models. 
Since using these models requires word embedding, we chose to use pre-trained Glove embeddings. 

Subsequently, we decided to adopt a transformer-based approach, specifically BERT (BertForTokenClassification), loading it with the pretrained weights of bert-base-uncased.
