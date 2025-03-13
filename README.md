**AI-Medical Assistant**

*Overview*

This project was developed as part of our AI course by Me, Siddhant Madan, and Vineet. It is a Streamlit-based AI-powered medical assistant that transcribes doctor-patient conversations and provides prognosis, diagnosis, and treatment recommendations using Whisper for speech-to-text and Groq API (LLaMA 3) for medical analysis.


*Features*


Audio Transcription: Converts doctor-patient audio conversations into text using OpenAI's Whisper model.

Medical Analysis: Generates insights on possible diagnoses, prognoses, and treatment recommendations using Groq’s AI model.

Chat History: Maintains conversation history to enable follow-up queries related to previous analyses.

Multiple File Uploads: Supports multiple audio files for batch processing.



*Technologies Used*



Streamlit: For building the user interface

Whisper (OpenAI): For audio transcription

Groq API (LLaMA 3): For AI-driven medical analysis

Python: Core programming language



*Installation & Setup*


Prerequisites

Python 3.8+, Pip, Streamlit, Whisper, Groq API key


*Usage*


Upload an audio file containing a doctor-patient conversation.
The system will transcribe the audio into text using Whisper.

Groq’s AI model will analyze the conversation and provide:
A possible prognosis, A diagnosis, Treatment or medication recommendations. 

Users can interact with the chatbot to ask follow-up questions based on the analysis.



**Contributors**

Bala Manish Reddy
Siddhant Madan
Vineet Patnaik
