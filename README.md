In this tutorial, I show how to estimate topic model by Latent Dirichlet Allocation (LDA) algorithm applied to the FOMC minutes. 
First, I show how to represent the text as a bag of words and carry out basic operations with text such as tokenization. Then I show how to prepare this data to extract meaningful information from the text. As such, I remove the words without information content - so called stopwords.  Also, I exclude the most common words in text which generate the noise in the data. Finally, I estimate topic model by LDA algorithm and provide with a time series of topic distribution throughout the period from 1995 to 2019.

For references please consult the paper Blei D. M., Ng A. Y., and Jordan M. I. , “Latent Dirichlet Allocation,”, Journal of Machine
Learning Research
