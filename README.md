# NLP-Project- Simple Chatbot using NLTK

A chatbot  is a computer program or an artificial intelligence which conducts a conversation via auditory or textual methods.Some chatterbots use sophisticated natural language processing systems, but many simpler systems scan for keywords within the input, then pull a reply with the most matching keywords, or the most similar wording pattern, from a database

NLTK has a module, nltk.chat, which simplifies building these engines by providing a generic framework.

Chat: This is a class that has all the logic that es and its corresponding output values. It is an optional dictionary 
that you can use. You can also create your own dictionary in the same format as below and use it in your code.
is used by the chatbot.

Reflections: This is a dictionary that contains a set of input valu
The nltk.chat chatbots work on the regex of keywords present in your question. So you can add any number of questions in a proper format so that your chatbot doesn’t get confused in determining the regex.

Steps:

1. Importing Libraries: The first step is to import the necessary libraries from the NLTK module.
2. Creating the QA List: This list contains pairs of regular expressions and responses. Each question pattern is matched against user input, and the corresponding response is provided.
3. Defining the Welcome Message: A function welcome_message() is defined to greet the user and provide instructions on how to interact with the chatbot.
4. Creating an Instance of the Chat Class: An instance of the Chat class is created using the QA list and the reflections dictionary, which helps in handling pronouns.
5. Triggering the Conversation: The chat.converse() method is called to start the interaction with the user when the script is run.

This structure provides me with a simple but effective way to create a chatbot using the NLTK library, allowing for easy expansion and customization. I can add more patterns and responses to the QA list as needed.
