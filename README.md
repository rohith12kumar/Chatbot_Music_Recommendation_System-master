🧠 Project Name: Chatbot Music Recommendation System
Description:
This project is a smart chatbot that recommends music to users based on their mood or input text. It uses Natural Language Processing (NLP) and machine learning to understand user messages and respond with appropriate music suggestions.

🔧 Technologies Used:
Python 3

Flask for the web application

NLTK for natural language processing

scikit-learn for training the machine learning model

HTML/CSS/JavaScript for frontend interface

Requests for handling HTTP calls

JSON to store chatbot intents and responses

📁 Key Files:
app.py – Main application script that runs the chatbot using Flask.

intents.json – Contains predefined intents (moods/emotions) and possible responses.

chatbot_model.pkl – Saved ML model after training.

templates/index.html – Web interface for interacting with the chatbot.

static/style.css – Stylesheet for customizing the frontend.

🚀 Features:
Chat interface for user interaction.

Text classification to identify user intent/mood.

Dynamic music suggestions based on emotional tone.

Flask-based web deployment for easy access.

Easily expandable by adding more intents in the intents.json file.

✅ How It Works:
User types a message.

The message is processed using NLP to identify intent.

The chatbot uses a trained model to classify the message.

A response is selected from the corresponding intent's list.

A music recommendation is shown to the user.
