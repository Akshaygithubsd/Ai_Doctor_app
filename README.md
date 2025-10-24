---
title: AI Doctor App
emoji: 🏥
colorFrom: blue
colorTo: red
sdk: gradio
sdk_version: 5.17.1
app_file: app.py
pinned: false
license: mit
short_description: AI-powered medical assistant with vision and voice capabilities
---

# AI Doctor App

A multimodal AI-powered medical assistant that processes images, text, and voice to generate intelligent diagnostic responses. Built using state-of-the-art GenAI models and APIs, the app enables users to interact via uploaded images and natural speech, receiving both text and spoken feedback.

## 🚀 Features

- 🧠 Uses Meta llama-4-scout-17b-16e-instruct for image + text-based reasoning
- 🎤 Speech-to-text input with OpenAI Whisper
- 🔊 Realistic voice responses using ElevenLabs TTS
- 🌐 Clean Gradio interface for real-time interaction
- 🧩 Supports Hugging Face Spaces deployment

## 🛠️ Tech Stack

- **Python**
- **Gradio** (UI & interface)
- **Meta LLaMA 4 Scout 17b** via GROQ API
- **OpenAI Whisper** (STT)
- **ElevenLabs API** (TTS)
- **Hugging Face Spaces** (deployment)

## 📦 Requirements

- Python ≥ 3.8
- pip
- API keys for:
  - OpenAI
  - ElevenLabs
  - GROQ (for LLaMA model access)

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ai-doctor-app.git
   cd ai-doctor-app
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set your API keys**
   Create a .env file in the root directory with the following:
   ```bash
   OPENAI_API_KEY=your_openai_key
   ELEVENLABS_API_KEY=your_elevenlabs_key
   GROQ_API_KEY=your_groq_key
   ```

5. **Run the app**
   ```bash
   python app.py
   ```

## Usage

1. Open the app in your browser.
2. Input your symptoms and Image in the provided field.
3. Click on the "Submit" button to receive potential diagnoses and health advice.

## 🔧 Environment Variables

For Hugging Face Spaces deployment, you need to set the following environment variables in your Space settings:

- `OPENAI_API_KEY`: Your OpenAI API key for Whisper STT
- `ELEVENLABS_API_KEY`: Your ElevenLabs API key for TTS
- `GROQ_API_KEY`: Your GROQ API key for LLaMA model access

## ⚠️ Disclaimer

This application is for educational and learning purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare professionals for medical concerns.