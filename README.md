 🧠 MentalAi
MentalAi is an AI-powered mental health chatbot designed to provide accessible, private, and immediate emotional support. The application combines Natural Language Processing (NLP) with a Feed Forward Neural Network to understand user messages, classify their intents, and provide appropriate responses.


———————————————————————————

🎯 Project Objective
The main goal of MentalAi is to connect Artificial Intelligence with mental health support by creating a simple digital environment that can respond to users and support their emotional well-being.


———————————————————————————
🤖 AI & Technologies
The chatbot uses:
• Python
• TensorFlow / Keras
• NLTK
• NumPy
• Scikit-learn
• Natural Language Processing (NLP)
• Feed Forward Neural Network
NLP Techniques
The text is processed using:
1. Tokenization
2. Lowercasing
3. Stemming
4. Bag of Words
5. Label Encoding

———————————————————————————
📊 Dataset
The project uses an intents.json dataset containing:
• 5 intents: Greeting, Goodbye, Thanks, Name, and Age
• 19 training sentences
• Patterns and responses for each intent
The JSON format was selected because it is lightweight, easy to modify, and suitable for intent-classification models.


———————————————————————————
⚙️ Model Training
The neural network was trained using:
• Optimizer: Adam
• Loss Function: Sparse Categorical Crossentropy
• Epochs: 200
• Activation: ReLU
• Dropout: Used to reduce overfitting
• Output: Softmax


———————————————————————————
📈 Results
The model achieved approximately 80–90% training accuracy, while validation accuracy remained around 20%.
This revealed a significant overfitting problem, mainly caused by the very small dataset. The model performs well on training examples but struggles with new sentences.


———————————————————————————
🚧 Challenges
• Very limited training data
• Simple model architecture
• Different user writing styles
• Slang, short forms, and emojis
• No sentiment analysis


———————————————————————————
🚀 Future Improvements
Future versions could improve the system by:
• Increasing the size and diversity of the dataset
• Adding sentiment analysis
• Supporting different writing styles
• Reducing overfitting
• Using advanced models such as LSTM, BiLSTM, or BERT


———————————————————————————
💡 Conclusion
MentalAi represents a first step toward combining artificial intelligence with mental health support. With more data and advanced techniques, the system could become smarter, more accurate, and more helpful in providing digital emotional support.
Note: MentalAi is a project for AI and mental health support and should not be considered a replacement for professional mental health care.



