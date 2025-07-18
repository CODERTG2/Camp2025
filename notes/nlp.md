# NLP

AI struggles with text
- misspelings
- slang
- emojis
- repetition
- incosistent casing

## Text Cleaning
lowercasing
remove poncutation
remove stopwords - "i am the best" into "best"
lemmatization - reduce words into simple parts - "running" into "run"
remove repeated letters

Stemming
- stemming just cuts of endings.
- fast but doesn't always ends with actual words

Lemmatization
- looks thru dictionary to reduce words into smaller words

Less clean data is better than more messy data!!!!!!!!!!!!!

## BOW
Explanation -- 
- Vocab of all diff words - n words
- our table's features will be n columns and the rows will be the different documents.
- we can also write it as a vector in n dimensions for each document.

Stregnths
- Simple
- can make a word cloud

Weaknesses
- compound words
- correlation between words
- words have diff meanings
- order

## Term Document Matrix
- their vectors in space are similar then the documents are similar

Cosine similarity
- the angle theta between the vectors

words show up in many books - and, the, etc.

TF-IDF
- the more often the word appears in the document the higher weight of the word
- TF increases the weight of the word, and idf will reduce it.
- weight = termfrequency * log(total num of docs/num of documents that have the word)
- the log being the idf
- the weight is used to alter the magnitude of the vectors while keeping the direction.

## stuff
Word2Vec
- runs a binary prediction? 
GloVe