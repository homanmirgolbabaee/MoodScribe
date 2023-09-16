📖 README: MoodScribe
🌟 Introduction
MoodScribe is a versatile application that offers a range of functionalities to enhance your content processing experience. Whether you want to transcribe a YouTube video, process articles, interact with a database, or chat with a bot, MoodScribe has got you covered!


🚀 Features
1️⃣ Youtube/Upload:
🎤 Input a YouTube video URL or upload an audio file to obtain a precise transcription of the content.

2️⃣ Article Processing:
📑 Use the transcription or your text for article processing.
📋 Obtain a summarized version of the content. Adjust word limits to suit your preference!
😊 Gauge the mood of your content.
🏷️ Classify or label the content.
💾 Seamlessly save the processed information to Weaviate database.
3️⃣ Observe Weaviate Database:
📊 Visualize the most frequent moods in the database with just a click!
📥 Download the transcriptions and database mood entries as a CSV for further use.
4️⃣ ChatBot:
💬 Dive into conversations with our HugChat bot instance.
🎥 The bot can even provide YouTube video URLs based on certain prompt formats.

📚 Libraries and Technologies Used
Core Technologies:
AssemblyAI: For accurate audio transcriptions.
Weaviate: Used as the database backbone.
Streamlit: Framework for the entire application.
Clarifai: For leveraging GPT, mood detections, and classification models.

Third-party Libraries:
Plotly: For stellar visualizations within Streamlit.
HugChat: Powers our interactive chatbot.


🔧 Key Functions
Here are some of the main functions that power MoodScribe:

save_mood_to_weaviate(mood, transcription)
get_all_moods_and_transcriptions_from_weaviate()
transcribe_audio(file)
transcribe_youtube(url)
get_mood_clarifai(sentence)
... (and many more!)
