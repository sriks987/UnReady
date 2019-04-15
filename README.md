# UnReady
## Main Tasks
* Referencing Flow of Conversation using Usernames
* Topic Clustering

### Ideas
1. Getting subject of a sentence - possibly LDA (https://towardsdatascience.com/nlp-extracting-the-main-topics-from-your-dataset-using-lda-in-minutes-21486f5aa925)
2. Likelihood of it being a reply is higher if pronoun is used
3. Message Gap = Particular reference to message -> Probability decreases exponentially
4. Context to map which message to reply to -> subject of the conversation - map it to the closest entity by default
    * Direct word matches give a higher probability
5. Single Word - Response to message
6. 1v1 Conversations - based on threshold - always same topic
7. Parallel Models - Word Similarity, Sentence Similarity and Reference Matching

### Columns of Dataset
1. Gap between messages
2. TimeStamp
3. Unread/Read
4. Username

### Preprocessing
1. Removal of Stopwords
    * Word Similarity - No Removal
    * Sentence Similarity - Removal Needed
    * Reference Matching - No Removal
2. Tokenisation and Lemmatisation
3. Extracting Whatsapp Messages

### Assumptions
1. Reply feature (used in common messaging applications) is not applicable
2. 
