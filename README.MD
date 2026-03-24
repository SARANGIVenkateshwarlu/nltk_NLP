### NLP :NLTR, spaCy, FinBERT , HuggingFace models

The difference between NLTK and spacy are:
1.	NLTK supports various languages whereas spaCy have statistical models for 7 languages (English, German, Spanish, French, Portuguese, Italian, and Dutch). It also supports named entities for multi language.
2.	NLTK is a string processing library. It takes strings as input and returns strings or lists of strings as output. Whereas, spaCy uses object-oriented approach. When we parse a text, spaCy returns document object whose words and sentences are objects themselves.
3.	spaCy has support for word vectors whereas NLTK does not.
4.	As spaCy uses the latest and best algorithms, its performance is usually good as compared to NLTK. In word tokenization and POS-tagging spaCy performs better, but in sentence tokenization, NLTK outperforms spaCy. Its poor performance in sentence tokenization is a result of differing approaches: NLTK attempts to split the text into sentences. In contrast, spaCy constructs a syntactic tree for each sentence, a more robust method that yields much more information about the text.


5. word2vec 
6. spaCy
7. FinBERT
8. HuggingFace models
9. Transformers 