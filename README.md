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
