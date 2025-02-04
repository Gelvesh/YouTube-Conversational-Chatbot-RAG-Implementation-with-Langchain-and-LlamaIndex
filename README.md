# YouTube Conversational Chatbot (RAG Implementation with Langchain and LlamaIndex)

## Project Overview

This project implements a **RAG (Retrieval-Augmented Generation)** Q&A chatbot for content fetched from YouTube videos. The chatbot leverages **LlamaIndex** (formerly known as GPT Index) and **Langchain** to extract and generate responses based on the content of YouTube videos. The content is specifically fetched using the **LlamaIndex YoutubeTranscriptReader**.

## Features

- **Retrieval-Augmented Generation**: Utilizes LlamaIndex and Langchain for question-answering based on YouTube video transcripts.
- **YouTube Video Integration**: Fetches transcripts from YouTube videos for chatbot-based interactions.
- **Customizable**: The chatbot can be modified to work with any YouTube video transcript for personalized Q&A.
- **Real-time Responses**: Provides dynamic responses based on the content of the video.

## Requirements

- Python 3.7+
- Dependencies:
  - Langchain
  - LlamaIndex
  - youtube-transcript-api
  - OpenAI (for API access)

Run the code:
streamlit run you-tube-chat.py
