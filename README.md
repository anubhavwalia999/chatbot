# 🤖 BlenderBot Chatbot

This project is a simple chatbot web app built using [Meta's BlenderBot-400M](https://huggingface.co/facebook/blenderbot-400M-distill) model and [Gradio](https://gradio.app/) for the user interface.

## 🔍 About

BlenderBot is a transformer-based conversational model by Meta, trained to have human-like interactions. This project demonstrates how to:

- Load and run a pretrained conversational model.
- Use Gradio's `ChatInterface` to build a modern chat UI.
- Maintain conversation history for more contextual responses.

## 🧪 Features

- Real-time chatbot UI
- Memory of past messages within a session
- Completely local (no external API usage)
- Deployable on Hugging Face Spaces or any Python web server

## 🚀 Try it Out

Upload this project to [Hugging Face Spaces](https://huggingface.co/spaces), select **Gradio** as the SDK, and you're ready to go!

## 🛠️ Requirements

See `requirements.txt` for Python dependencies.

## 📁 File Structure

.
├── app.py # Main chatbot application
├── requirements.txt # Python dependencies
└── README.md # Project summary and instructions
