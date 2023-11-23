Demo 2 – Chinese Word Segmentation
 

Part 1 – Transformers for Sequence Classification (7 points)
Here we want to compare how Transformers work when compared to other kinds of sequence to sequence networks, such as LSTMs. Follow the tutorial hereLinks to an external site. in order to implement a token classification model.

The tutorial uses DistilBERT, a smaller version of BERT designed to be used when we have less memory available. BERT itself is one of the most popular Transformer models both for sequence and for token classification.

 

Part 2 – Using BERT with Our Data (16 points)
The huggingface tutorial uses both an English dataset and a model pretrained in English. Change the code so that it can use the CONLL-U dataset from the demo notebook.

One of the major issues that you might find is that just changing the dataset will not yield the results we would expect. Because of that, you might also have to change the model you’re using. I wasn’t able to find a reasonably documented version of DistilBERT for Chinese, but HuggingFace has a Chinese BERTLinks to an external site. available.

Another thing to keep in mind is that BERT already segments the words as it things they should be segmented, so you will probably have to find a workaround in order to avoid the task being trivial (and to get a single label from each of your characters).

 

Part 3 – Performance Analysis (7 points)
Do a comparison between both models and how differently they perform. We are assuming that most of you don’t read Chinese, so we are not expecting much in the area of qualitative analysis.