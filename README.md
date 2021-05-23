This is a chatbot that will give answers to most of your corona related questions/FAQ. The chatbot will give you answers from the data given by WHO(https://www.who.int/). This will help those who need information or help to know more about this virus.

It uses a neural network with two hidden layers(enough for these QnA) that predicts which pattern matches with the user’s question and sends toward that node. More patterns can be added from user’s questions to train it for more improved results and add more info about coronavirus in the JSON file. The more you train this chatbot the more it gets precise. The advantage of using deep learning is that you don’t have to ask the same question as written in JSON file cause stemmed words from the pattern are matched with user question

Training data :
To feed the data to chatbot I have used json with possible question patterns and our desired answers.
The JSON file used for the project is WHO
For this project, I have named my JSON file as intents.json 
In the JSON file tag is the category in which all those responses fall.
patterns are used for listing all possible question patterns.
responses contains all the responses with respect to the patterned questions

Bag of Words:
As we know neural networks and machine learning algorithms require numerical input. So out list of strings won’t cut it. We need some way to represent our sentences with numbers and this is where a bag of words comes in.What we are going to do is represent each sentence with a list the length of the number of words in our model vocabulary. Each position in the list will represent a word from our vocabulary.f the position in the list is a 1 then that will mean that the word exists in our sentence, if it is a 0 then the word is nor present.
