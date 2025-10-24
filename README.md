# AI Doctor App

## Overview

A multimodal AI-powered medical assistant that processes images, text, and voice to generate intelligent diagnostic responses. Built using state-of-the-art GenAI models and APIs, the app enables users to interact via uploaded images and natural speech, receiving both text and spoken feedback.

👉 **[Live Demo on Hugging Face Spaces](https://huggingface.co/spaces/imdanishakhtar7/ai-doctor-app)**


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
   git clone https://github.com/Danish137/ai-doctor-app.git
   cd ai-doctor-app
   
2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt

6. **Set your API keys**
   Create a .env file in the root directory with the following:
   ```bash
   OPENAI_API_KEY=your_openai_key
   ELEVENLABS_API_KEY=your_elevenlabs_key
   GROQ_API_KEY=your_groq_key

7. **Run the app**
   ```bash
   python app.py

## Usage

1. Open the app in your browser.
2. Input your symptoms and  Image in the provided field.
3. Click on the "Submit" button to receive potential diagnoses and health advice.


