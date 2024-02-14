## Convolutional Neural Networks for Text Classification
### Introduction
I worked on Convolutional Neural Networks for sentence classification and reported the results on 3 datasets. CNNs are widely used for image vision and detection tasks. There are a number of techniques which are used for sentence classification prevalent of which are LSTMs and RNNs. Over the past years, CNNs have shown improved performance on various NLP tasks such as semantic parsing, sentence modelling, etc.

Recently, it was discovered that CNNs perform well and achieve good results on sentence classification tasks. Amazed by this idea and wondering how CNNs capture relationship between words and classify sentences, I wanted to explore more about this novel concept. We know how LSTMs are used to classify sentences, how word embeddings come into play for this task. I use these same concepts for using CNNs for sentence classification where I use GloVe and fastText word embeddings.

I perform sentence classification on three datasets,
<br/>
a) MR: Movie reviews with one sentence per review. Classification involves detecting positive and negative reviews.
<br/>
b) SST2: Stanford Sentiment Treebank, an extension of MR but with train/dev/test splits provided.
<br/>
c) Subj: Subjectivity dataset where the task is to classify a sentence as being subjective or objective.

### Learnings
Adapting CNNs, originally designed for image processing, to NLP tasks like sentence classification is possible through 1-D convolutions and kernels operat- ing on word embeddings.

Also, we can apply concepts from one domain (image processing) to another (NLP) learnt how these concepts can be adapted and optimized for different tasks.

Using pre-trained word embeddings like GloVe and fastText is beneficial, and fine-tuning these embeddings for specific tasks can significantly enhance model performance in sentence classification.

One interesting thing was how kernels capture general features by learning weights, as similar words have similar word embeddings.

Overall, I learnt that not only the technical aspects of CNNs for sentence clas- sification but also the adaptability and potential of applying these architectures across different domains within machine learning and artificial intelligence.
