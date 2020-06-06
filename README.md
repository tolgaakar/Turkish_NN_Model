# Turkish_NN_Model
## Neural Network Language Model and Sentiment Classifier For Turkish

The goal of this project was to build a neural network language model for Turkish, and, using the ULMfit approach, use that model to build a second model for Turkish sentiment classification. In order to achieve my goals, I followed the footsteps of Jeremy Howard and his video on NLP applications for Non-English languages.

In the first part, using the Sentence Piece Tokenizer (SPProcessor() in fast.ai library) since it is a better fit for Turkish, unlike space based tokenization techniques, I trained a RNN language model for Turkish.

And for the second part, firstly I fine-tuned the model with the new data. Although both Jeremy Howard and the state-of-the-art (Gezici and Yanıkoğlu, 2018) are using only the Turkish movie reviews data, I used another dataset as well, which is product reviews in 4 categories namely books, DVDs, electronics and kitchen. Here I achieved 88.5% accuracy, which over performs the state-of- the-art by far.
