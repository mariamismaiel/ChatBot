# ChatBot
🤖 Chatbot with TF-IDF Text Classification 
📚  This project implements a chatbot using TF-IDF text classification technique. 
The chatbot is trained on a set of pre-defined conversations stored in a JSON file. It uses cosine similarity to classify user input and provide appropriate responses. 

The project leverages the following technologies and tools:
- Python programming language
- NLTK (Natural Language Toolkit) library for text preprocessing
- Scikit-learn library for TF-IDF vectorization and cosine similarity calculation
  
Features:
- Preprocesses user input to remove stop words and non-alphanumeric characters
- Generates TF-IDF vectors for the preprocessed training data
- Uses cosine similarity to find the most similar pre-defined input and returns the corresponding response

To use the chatbot, simply run the Python script and start typing your messages. The chatbot will respond based on the patterns and information it has learned from the training data.

Feel free to customize the training data in the JSON file to improve or expand the chatbot's capabilities. You can also modify the code to enhance the chatbot's preprocessing or add new features.
