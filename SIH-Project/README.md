# SIH-Project
A web app and an API hosted using Google Cloud for call transcription and analysis using AI/Ml and provide feedback to enhance customer care services and provide business insights.


Call recording: Utilizing Twilio API for VoIP call recording

Audio Transcription: Employing Whisper, Wav2Vec2 and Pyannote ML models for accurate call transcription and diarization

Translation of transcription: If the conversation took place in any vernacular or local language, then it will be translated into English with proper context using MBart50 for sentiment analysis

Sentiment & Emotion Analysis: Using DistilBERT to analyze sentiments and emotions in transcribed text.

Summarization & Recommendation: Utilizing Llama 2 for natural language summarization and generating personalized recommendations based on sentiment analysis.

Web portal: Building an interactive web-based dashboard for employees and admins to view sentiment analytics data and performance metrics. (Not completed)

Data Security:Transmitting transcribed and analyzed data to the database in an encrypted manner using the Cryptography library in Python (Not completed)
