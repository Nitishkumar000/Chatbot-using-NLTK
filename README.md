# NLP-Project- Simple Chatbot using NLTK

A chatbot  is a computer program or an artificial intelligence which conducts a conversation via auditory or textual methods.Some chatterbots use sophisticated natural language processing systems, but many simpler systems scan for keywords within the input, then pull a reply with the most matching keywords, or the most similar wording pattern, from a database

NLTK has a module, nltk.chat, which simplifies building these engines by providing a generic framework.

Chat: This is a class that has all the logic that is used by the chatbot.

Reflections: This is a dictionary that contains a set of input values and its corresponding output values. It is an optional dictionary 
that you can use. You can also create your own dictionary in the same format as below and use it in your code.

The nltk.chat chatbots work on the regex of keywords present in your question. So you can add any number of questions in a proper format so that your chatbot doesn’t get confused in determining the regex.

Steps:

1) Import the necesrray libraries

2) Create a list of question & Answers.
      
      2.1) Use Regex for framing your questions

3) Define a function for a welcome message 

4) Create an instance of Chat class containing pairs(list of tuples containing set of question and answers) and reflections

5) To trigger the conversation invoke the chat.coverse()
