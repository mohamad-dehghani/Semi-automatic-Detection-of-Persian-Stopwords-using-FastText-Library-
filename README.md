# Semi-automatic-Detection-of-Persian-Stopwords-using-FastText-Library

A stopword is a word that does not add much
semantic information to the text that despite of its very high
frequency. Stopwords include prepositions, conjunctions, and
pronouns. One of the steps in natural language processing is to
remove stopwords to reduce dataset size and process faster. In
this study, a semi-automatic method for collecting the Persian
language's stopwords is proposed. The proposed method lists the
stopwords of each text depending on its subject. For this purpose,
based on a corpus of news texts, the Inverse Document
Frequency (IDF) weight in the text is calculated for each word
and the stopwords candidates are determined. Then, using the
fastText library, the vector of each word is obtained. In the next
step, five neighbors are found for each vector. Next, by removing
duplicate words, the final list of stopwords (1014 stopwords) is
collected. The result of simulations show the accuracy of
detecting stopwords by the k-nearest neighbor method is 94.6%.
