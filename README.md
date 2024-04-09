# sms_spam_detector
Module 21: Spam or Ham?
In this module I refactored code from an SMS text classification solution into a function that constructs a linear Suppor Vector Classification.
Once this model is created and trained, I  created a gradio app to host the application, enabling users to test whether the message is spam or not.

To begin, I first created a SMS Function that included a pipeline from TfidfVectorizer and Linear SVC to transform the test set and compare it to the training set.

I then created the SMS predicted function that includes conditionals that returns a message if it is "ham' or "spam"

Lastly, I created the gradio interface app to intake a message and an output to predict whether it is spam or not.

