# Word-Embedding implementation using Keras

#### Part of Assignment of Deep Learning Course (2IMM10) at TU/e 

## Objective

Build word embeddings with a Keras implementation where the embedding vector is of length 50, 150 and 300. Use the Alice in Wonderland text book (alice.txt) for training . Use a window size of 2 to train the embeddings (window size in the jupyter notebook).

> Build word embeddings of length 50, 150 and 300 using the Skipgram model
> Build word embeddings of length 50, 150 and 300 using CBOW model
> Analyze the different word embeddings:
>> Implement your own function to perform the analogy task as explained in [Efficient estimation of word representations in vector space](/reading/word_representations_in_vector_space.pdf). Use the same distance metric as in the paper without using use existing libraries for this task such as Gensim. Your function should be able to answer whether an analogy as in example provided below is true.
>>> A king is to a queen as a man is to a woman ![equation](https://latex.codecogs.com/gif.latex?e_{king}-e_{queen}&plus;e_{woman}\approx&space;e_{man}), where ```e_x``` denotes the embedding ```e``` of word ```x```. We want to find the word ```p``` in the vocabulary, where the embedding of ```p``` ```(e_p)``` is the closest to the predicted embedding (i.e. result of the formula). Then, we can check if ```p``` is the same word as the true word (```man``` in above example).
>> Give at least 5 different examples of analogies.
>> Compare the performance on the analogy tasks between the word embeddings and briefly discuss your results
