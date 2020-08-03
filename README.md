# HMMs-and-Viterbi-algorithm-for-POS-tagging
Building your own HMM-based POS tagger and implement the Viterbi algorithm using the Penn Treebank training corpus. 
the basic idea of the Viterbi algorithm is as follows - given a list of observations (words) 
O1,O2...On to be tagged, rather than computing the probabilities of all possible tag sequences, you assign tags sequentially, i.e. assign the most likely tag to each word using the previous tag. 
More formally, you assign the tag 
Tj to each word Oi
 such that it maximises the likelihood:

 

