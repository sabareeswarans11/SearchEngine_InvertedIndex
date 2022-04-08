# SearchEngine with InvertedIndex TFIDF
SearchEngine_Inverted Index.ipyn: This is the source code file. Which has Four main processing tasks
1) Scraping text from 6 URL Websites and Store the Preprocessed Text data alone in text file for each HTML pages.
2) Creating Inverted index and document frequency with Posting locations.
3) Finding the similarity between 6 docs using CosineSimilarity metrics.
4) Implemented Inverted index as Simple Search Engine with information
retrieval. (Cross-platform Application software support with python -- Tkinter)

# Dataset Link
Wiki page 
1) https://en.wikipedia.org/wiki/Machine_learning
2) https://en.wikipedia.org/wiki/Engineering
3) http://my.clevelandclinic.org/research
4) https://en.wikipedia.org/wiki/Data_mining
5) https://en.wikipedia.org/wiki/Data_mining#Data_mining
6) http://cis.csuohio.edu/~sschung/

# Final Result and Conclusion
Computing Similarity between the documents using Cosine similarity metrics
Cosine similarity is a metric used to determine how similar the documents are irrespective of their size.

From the above results we can conclude that,

1) Doc 1 – Machine Learning,
2) Doc 2- Engineering, 
3) Doc 3 – research, 
4) Doc 4 – Data mining,
5) Doc 5 – Data mining # datamining
6) Doc 6- ss chung

Eliminating 1.0 cosine score, because comparing the same document (di,di) will give 1.0 which is useless for analysis.

Top matches sorted 

(Doc4, Doc5) -1 similar matches, content of Doc5 is the part of Doc4.
(Doc1, Doc4)-0.87 Similar matches Machine Learning vs Data mining
(Doc1, Doc2)- 0.82 Similar matches Machine Learning vs Engineering
(Doc2, Doc4)- 0.78 Similar matches Engineering vs Data mining
(Doc5, Doc6)-0.65 Similar matches
(Doc 1, Doc 6)-0.61 Similar matches
(Doc 1, Doc 3)-0.61 Similar matches
(Doc 2, Doc 3)-0.61 Similar matches
(Doc 3, Doc 4)-0.59 Similar matches
(Doc 3, Doc 5)-0.59 Similar matches
(Doc 2, Doc 6)-0.55 Similar matches



<img width="900" alt="image" src="https://user-images.githubusercontent.com/94094997/162354683-d17d30b0-36f7-42ae-aa99-13d1b89e93d2.png">
