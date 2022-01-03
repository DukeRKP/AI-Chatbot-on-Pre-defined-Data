# AI-Chatbot-on-Pre-defined-Data

The AI based Chat Bot has a list of questions and answers which can be customised and trained. The trained data then can be used to predict the answers given to it according to a "Tag" system. 

The intent.json file contains the questions and answers followed by a "Tag". This chatbot uses the questions part of each Tag and checks for occurance of each key-words for each Tag. Next the chatbot pulls up the trained data and predicts the tag and one random element from the answers inside the predicted tag is displayed as a reply.

How to use:

First customise the intents.json file to suite your question and answers

Now run the training.py and wait for it to train for a total 1000 times, it will generate a data.pickle file to store the training data

now run the chatbot.py and start chatting with the bot
