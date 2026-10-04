# AI-Call-Summary-Generator
# AI Call Summary Generator

## 📌 Overview

The **AI Call Summary Generator** is an AI-powered application that converts recorded audio calls into text and automatically generates a short summary. It uses **OpenAI Whisper** for speech-to-text conversion and a **BART Transformer model** for summarization.

This project can help users quickly understand the important information from long conversations without reading the complete transcript.

## 🎯 Objectives

* Convert call audio into text automatically.
* Generate a concise summary of the conversation.
* Reduce the time required to review long calls.
* Provide a simple and interactive web interface.
* Demonstrate the use of Speech Recognition and Natural Language Processing.

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **OpenAI Whisper**
* **Hugging Face Transformers**
* **BART**
* **PyTorch**
* **Gradio**

## 🔄 How It Works

1. Upload or record a call audio file.
2. Whisper processes the audio.
3. The speech is converted into a text transcript.
4. The BART model analyzes the transcript.
5. A short call summary is generated.
6. The transcript, summary, and status are displayed.

## ✨ Features

* 🎤 Audio upload
* 🎙️ Microphone recording
* 📝 Automatic speech transcription
* 🤖 AI-generated call summaries
* 📊 Simple Gradio interface
* ⚡ Easy to run in Google Colab

## 📋 Example

**Call Transcript:**

> Customer contacted support regarding a delayed order. The support representative checked the order status and informed the customer that the package would arrive soon.

**Generated Summary:**

> Customer reported a delayed order. Support checked the status and provided an updated delivery estimate.

**Status:** Call analyzed successfully.

## ▶️ How to Run

1. Open **Google Colab**.
2. Create a new notebook.
3. Copy the project code into a cell.
4. Run the cell.
5. Wait for the AI models to load.
6. Upload or record an audio call.
7. Click **Generate Call Summary**.
8. View the transcript and generated summary.

## 📁 Project Structure

```text
AI-Call-Summary-Generator/
│
├── AI_Call_Summary_Generator.ipynb
└── README.md
```

