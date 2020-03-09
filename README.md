# Natural-Language-Processing-Text-Mining-Functions
Operations in  Natural Language Processing(NLP) and Text Mining technique. 

#Text Minig or Text Analytics is the process of extract meaningful information from natural language text.

#Natural Language Processing is a part of Computer Science and Artificial Intelligence which deals with the interactions between computers and human(natural) languages.

@ Applications of NLP: 1.Sentiment Analysis  2.Chatbot  3.Speech Recognition 4.Machine Translation 

@Applications of NLP and Text Mining:1.Information Extraction 2.Spell Checking 3.Keyword Searching 4.Summarization 5.Advertisement Matching 6.Classification(Spam Filtering) 7.Question Answerning and others.....

@Tasks of Natural Language Processing: 1.Tokenization 2.Stemming 3.Lemmatization 4.Part of Speech (POS) Tagging
                                       5.Named Entity Recognition 6.Chunking
  
  *** when working with Text Mining that's time deal with "Stop Word Removal" step before the "Chunking" step.***

1.Tokenization:
  Tokenization(word segmentation) is the task of chopping it up into pieces(smaller meaningful elements) called tokens.Tokens can be words, numbers, or punctuation marks.This process is done by using a tokenization algorithm.
  
  Sentence Tokenization is the process of tokenizing a text into sentences.NLTK provides a method called sent_tokenize to perform sentence-level tokenization. 
  
  Word Tokenization is the process of tokenizing sentences or text into words and
punctuation.NLTK provides a method called word_tokenize ,which splits text using punctuation and non-
alphabetic characters.

Key points of the NLP tokenization,
Text into sentences tokenization
Sentences into words tokenization
Sentences using regular expressions tokenization.

2.Stemming:
Stemming is a process in which remove the end or the beginning of the word in hope of
achieving its base form.As example, Form: Studies, studying. where, Suffix: -es, -ing and here, Stem: Studi, Study. Also, jumped and jumps may be reduced to jump , while jumpiness may be reduced to jumpi.

NLTK provides,PorterStemmer , which is based on the Porter Stemming Algorithm.Other stemmers include SnowballStemmer and LancasterStemmer.

3.Lemmatization: Lemmatization is a process that uses vocabulary and morphological analysis of words to
remove the inflected endings to achieve its base form (dictionary form), which is known as
the lemma.
Examples of lemmatization:
-> rocks : rock
-> corpora : corpus
-> better : good

NLTK using WordNetLemmatizer for lemmatization.

4.POS Tagging:The POS tagging is to assign labels for each token (a word in this case) with its
respective grammatical component, parts of speech include nouns, verb, adverbs, adjectives, pronouns, conjunction and their sub-categories.

Most of the POS tagging falls under Rule Base POS tagging, Stochastic POS tagging and Transformation based tagging.NLTK provides a function called pos_tag , to perform POS tagging of sentences, but this requires the sentence to be tokenized first.

